# Image Hosting With Real Web Addresses

Sometimes you have need to post an image file to the web for inclusion in web pages or other web-accessible databases, and you need to have a real web address (URL) for the image, not a link to a page it's on or a share link from a cloud drive service, etc.

(Note: if you want to have video hosted, it's more complicated because video needs a player application on the server. Consider using YouTube, Vimeo, or <https://bunny.net/> for video.)

Tradeoffs for choosing a service to host your images include:

- cost / advertising
- simplicity of upload / download
- file size limits
- simplicity of account creation and account management
- simplicity of file deletion years later, perhaps by you or someone cleaning up after you

Some services to consider:

- Backblaze B2
- Amazon AWS S3
- Imgur

As of 2024-08, I (Pete) recommend Backblaze for most people. The other services above, and even more, may be good choices as well, but Backblaze is a very good, easy choice for most people.

## Backblaze B2

Backblaze is a company that offers bulk data storage. They have a good track record and have been around for a while. Ask an LLM or do some web searches to get an idea of who they are and why they're good.

Backblaze B2 is their offering which is similar to AWS S3, but ~4x cheaper, and since all Backblaze does is storage, account setup and bucket management is much easier than for AWS.

Check current pricing: <https://www.backblaze.com/cloud-storage/pricing>. As of 2024-08, it's US $6/TB/month. That works out to about US $0.60/GB/month.

Here's a quick overview to start storing images that have real web addresses. Please [[contact Peter Kaminski]] with any problems or suggestions to expand this overview.

- Sign up for Backblaze B2: <https://www.backblaze.com/sign-up/cloud-storage>
- The first time you set up B2, you need to create a "bucket", which is like a folder inside the B2 service. It should have a name that is unique around the world, so not "images", but something like "peterkaminski-images". After this first setup, you can continue to use the same bucket for all your images.
- To keep things organized, you can optionally make a bucket for one kind of use, or for each project, for each year of upload, etc. Another thing to consider, if you want to delete a bunch of files to clean up, you can delete a whole bucket at once.
- When you're signed into Backblaze, on the left under "B2 Cloud Storage", click "Buckets".
- Click "Create a Bucket" and follow the instructions. Suggested settings for this use:
  - Files in Bucket are: Private
  - Default Encryption: Disable
  - Object Lock: Disable
- After the bucket is created, find it in your list of buckets, and click "Upload/Download".
- Click the "Upload" button, and upload an image or a folder.
- After the image is uploaded, click the circle-I "information" icon. You will find "Friendly URL" and "S3 URL". Use either of those as your image's real web address. If you don't know which one to use, pick the "S3" URL, as it has a standardized format.
- If you ever want to delete a bucket, click "Buckets" to get to the list of buckets. Click "Bucket Settings", then "Delete Bucket". Of course, all images in that bucket will no longer be available on the web if you delete the bucket.

There are a number of third-party free and paid applications which allow you to copy files from your computer to B2. These may be easier for bulk copies, but you'll have to figure out how to know what your files' real web addresses are. This isn't too hard, but it's currently not covered in this short overview.

