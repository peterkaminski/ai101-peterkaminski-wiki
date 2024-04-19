# Jankifier Publishing Checklist

To be published here, jankifiers should have the following.

You can edit your jankifier file by hand. Or, if you copy the following instructions and example text into your favorite LLM and attach your jankifier HTML file, your LLM may be able to edit the file for you.

Remember to change the things that are in ALL CAPS. Note that you change YOUR NAME in two places.

You can leave number 5 the way it is, or you can add a sentence or two describing your jankifier and how to use it, to make it easier for the LLM to get it right.

Remember to ask to let you download the new HTML file.

---

Please make the following changes to the attached HTML file:

1. Confirm that `<!DOCTYPE html>` is the first line. Delete blank lines before it.
2. Copyright notice in an HTML comment directly after that.
3. `<title>` and `<h1>` with the name and version, start with "v1.0.0" (and use [semantic versioning](https://semver.org/)). Add the `<h1></h1>` directly after `<body>` if it's not already there.
4. Right after the `<h1>`, a paragraph `<p></p>` with a link to the Jankifiers page on the web.
5. Right after that, a paragraph `<p></p>` with a short description of how to work this jankifier, and what it does.
6. Right before `</body>`, a copyright notice in HTML (not a comment). Use `<div class="footer">`.
7. Along with the copyright, optional but nice to have, an open source dedication. The "MIT License" is a good choice.

Here is the text to use for some of the elements mentioned above (change the things that are in ALL CAPS):

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
