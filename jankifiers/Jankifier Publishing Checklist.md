# Jankifier Publishing Checklist

To be published here, jankifiers should have the items in the instructions below.

You can edit your jankifier file by hand. Or, you can copy the following instructions and text snippets into your favorite LLM and attach your jankifier HTML file, and your LLM may be able to edit the file for you.

Remember to change the things that are in ALL CAPS. Note that you need to change YOUR NAME in two places.

You can leave number 5 the way it is, or to make it easier for the LLM to get it right, you can add a sentence or two describing your jankifier and how to use it.

## Instructions

Read these instructions and text snippets. Make the following changes to the attached HTML file. Let me download the updated HTML file.

1. Confirm that `<!DOCTYPE html>` is the first line. Delete blank lines before it.
2. Add the "copyright notice in an HTML comment" directly after that.
3. Make sure `<title>` and `<h1>` have the name and version given in the text snippets. Start with "v1.0.0" (which is from [semantic versioning](https://semver.org/)). Add the `<h1></h1>` directly after `<body>`, if it's not already there.
4. Right after the `<h1>`, there should be a paragraph `<p></p>` with a link to the Jankifiers page on the web.
5. Right after that, there should be a paragraph `<p></p>` with a short description of how to work this jankifier, and what it does.
6. Right before `</body>`, there should be a copyright notice in HTML (not a comment). Use `<div class="footer">`.
7. Along with the copyright, optional but nice to have, an open source dedication. The "MIT License" is a good choice. Just use the verbiage in the text snippets.

## Text Snippets

Copyright notice in an HTML comment (for number 2):

```html
<!-- 
    Copyright © 2024 YOUR NAME
    Licensed under the MIT License
    https://ai101.peterkaminski.wiki/jankifiers
    https://github.com/peterkaminski/ai101-peterkaminski-wiki/jankifiers/
-->
```

Name and version: JANKIFIER v1.0.0

Paragraph with a link to the Jankifiers page on the web: `<p>Read more <a href="https://ai101.peterkaminski.wiki/jankifiers" target="_blank">About Jankifiers.</a></p>`

Copyright notice in HTML (for number 6):

```html

    <div class="footer">
        <p>&copy; 2024 YOUR NAME</p>
        <p>Open source, licensed under the <a href="https://opensource.org/licenses/MIT" target="_blank">MIT License</a></p>
    </div>


```
