# Image Hosting With Real Web Addresses

## Introduction

Sometimes you need to post an image file to the web for inclusion in web pages or other web-accessible databases. In these cases, you need a real web address (URL) for the image, not a link to a page it's on or a share link from a cloud drive service.

> **Note:** For video hosting, consider using YouTube, Vimeo, or [bunny.net](https://bunny.net/). Video hosting is more complex due to the need for a player application on the server.

## Choosing a Service

When selecting an image hosting service, consider these factors:

- Cost / Advertising
- Ease of upload / download
- File size limits
- Simplicity of account creation and management
- Ease of file deletion in the future

## Recommended Services

As of August 2024, here are some services to consider:

1. Backblaze B2 (Recommended for most people)
2. Amazon AWS S3
3. Imgur

## Backblaze B2: An Overview

Backblaze is a reputable company offering bulk data storage. Their B2 service is similar to AWS S3 but approximately 4 times cheaper, and much easier to set up.

### Pricing

Check current pricing at [Backblaze Cloud Storage Pricing](https://www.backblaze.com/cloud-storage/pricing). As of August 2024, it's US $6/TB/month (approximately US $0.60/GB/month).

### Getting Started with Backblaze B2

1. **Sign up**: Visit [Backblaze B2 Sign Up](https://www.backblaze.com/sign-up/cloud-storage)

2. **Create a bucket**:
   - Sign in to Backblaze
   - Under "B2 Cloud Storage", click "Buckets"
   - Click "Create a Bucket"
   - Choose a unique name (e.g., "yourusername-images")
   - Recommended settings:
     - Files in Bucket: Private
     - Default Encryption: Disable
     - Object Lock: Disable

3. **Upload files**:
   - Find your bucket in the list and click "Upload/Download"
   - Click the "Upload" button
   - Select an image or folder to upload
   - Do the same thing to upload as many files as you need to

4. **Get the image URL**:
   - After uploading, click the circle-I "information" icon
   - Use either the "Friendly URL" or "S3 URL" (prefer S3 URL if you're not sure)

### Managing Your Buckets

- **Create multiple buckets**: Optionally, consider creating separate buckets for organizing different projects, years, or usage types
- **Delete a bucket**: 
  1. Click "Buckets" to see the list
  2. Click "Bucket Settings"
  3. Click "Delete Bucket"

> **Warning:** Deleting a bucket removes all images within it from the web

### Advanced Usage

For bulk file transfers, consider using third-party applications (free or paid) that can copy files from your computer to B2. Note that you'll need to determine how to find your files' web addresses when using these tools.

This page mentions some applications: [Making Cloud Storage Easy: Backing Up From Desktop to the Cloud](https://www.backblaze.com/blog/cloud-storage-made-easy/)

Rclone is Pete's favorite, but it's a command-line tool, which may be too advanced for your purposes.
## Conclusion

This guide primarily focuses on Backblaze B2 as a recommended solution for most users. However, explore other options like Amazon AWS S3 or Imgur if they better suit your needs.

For any questions or suggestions to improve this guide, please [[contact Peter Kaminski]].
