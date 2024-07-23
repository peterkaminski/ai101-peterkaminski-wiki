# Jankifiers

_New! [[Jankifier Betterification Project]]_

Jankifiers are small tools written in HTML and JavaScript (often by an LLM like ChatGPT, with guidance from a human).

The first jankifiers we've written are used to create and modify ("jankify") prompts for AI, especially AI image generators.

The first versions look janky but do the job. Play with these! Write your own! Send comments or new jankifiers to [Pete](mailto:kaminski@istori.com)!

To make your own, put a prompt like this into ChatGPT or another chatbot (replace the ALL CAPS phrases):

> Write a single html file with javascript. Let the user enter some text. When the user presses the "YOUR BUTTON NAME HERE" button, WHAT YOU WANT TO HAPPEN. Display the output and copy it to the clipboard. Don't show an alert. Let me download the html file.

To publish your jankifier on the web, either on your website or this one, you should add a copyright notice for attribution, a version number so people know if the copy they might have is out of date, and an open source dedication if you're okay with that.

Check out the [[Jankifier Publishing Checklist]] for detailed instructions. Do "view source" on any of the jankifiers below to see live examples.

Jankifiers were introduced on the [[Learn and Do with Peter, 2024-03-24]] call and we did a detailed walkthrough on [[Learn and Do with Peter, 2024-03-29]].

## Usable Image Generator Jankifiers

- [[Adjective Adder.html]] - adds random outlandish adjectives before each noun
- [[Adverbifier.html]] - adds some random adverbs
- [[Catifier.html]] - catifies your text
- [[Chopper.html]] - removes every nth character from your input
- [[Commifier.html]] - adds commas randomly
- [[Essifier-es.html]] - adds "es" suffix to each word
- [[Essifier.html]] - adds "s" suffix to each word (not very interesting)
- [[Frankifier.html]] - adds hotdog atmosphere to your input
- [[Froggifier.html]] - froggifies your text
- [[Interleaver.html]] - interleaves two prompts word-by-word (like cars doing a zipper merge)
- [[Janky Rhymifier.html]] - changes some words into janky rhymes of the original word
- [[JunglefyJankifier.html]] - add some jungle atmosphere to your input
- [[Letterrific.html]] - add a random letter between each existing character, good with small prompts
- [[Lexiconstructor.html]] - generates random strings of words
- [[Numberfier.html]] - changes random words into numbers
- [[Raccoonify.html]] - raccoonifies your text
- [[Random Letter Generator.html]] - v1 - generates random letters
- [[RandomJourney.html]] - randomizes the stylize, chaos, and weird values of your Midjourney prompt
- [[Reverse Text.html]] - reverses the input text character by character
- [[Reverse-Jankifier.html]] - swaps pairs of words
- [[Sortor.html]] - Alphabetically sorts the letters in each word
- [[Text Bots Assemble.html]] - adds a prefix and suffix to multiple lines of text
- [[WikiWords.html]] - pulls two random sentences from a random Wikipedia article
- [[WorldArt Text Modifier.html]] - modifies your text to include world art-related terms

## Utility Jankifiers

- [[Fast Hours Monthly Targetifier.html]] - calculate how you're doing on your Midjourney Fast Hours "budget" this month
- [[Zoom_Transcript_Cleaner_v1_0_0.html]] - transforms Zoom transcripts into easy-to-read text

## Pre-release Jankifiers

These are not ready for primetime, but may still be interesting.

- [[Dallefier.html]] - v0.0.1 - accepts a text prompt, sends it to OpenAI / DALL-E 3 to generate an image. NOTE: no progress indicator (it will look like nothing is happening for a while while the image is being generated), download is broken (you can still use "Save As" in your browser to save the image), image parameter inputs aren't provided.

## About Jankifiers

Each of these rough tools was created by ChatGPT by giving it a short prompt (see example below). The idea is to democratize the creation of little utilities like this, and with a good LLM, you can do it even if you're not a programmer!

We'll continue to add, improve, or perhaps even retire particular jankifiers without notice, except for posting them here.

Each single, self-contained HTML file can be used on the web, or saved to your computer or smartphone and used from there. We'll add more explanation later, but to start, you can just click on one of the links above, then do what the web page tells you -- add some text somewhere, click a button, copy the resulting text, then go over to your image generator and paste the text. The processing all happens on your computer, and for simple functions, nothing is sent to the cloud. (Jankifiers that use web APIs -- for image generation or text generation, for example -- will send data to the web, and we'll clearly note that on the jankifiers that do.)

The authors (Peter Kaminski and/or others)  of these jankifiers can't help you with your image generator, and are not responsible for your use or misuse of the jankifiers, including problems caused by the text you copy and paste. What you do with these is your responsibility. Read the included and linked [MIT License](https://opensource.org/license/MIT) for more information.

## Sample Jankifier Creation Prompts

## Letteriffic

_A slightly cleaner prompt than the Interleaver prompt below. Also includes version number and copyright info, which makes this prompt a little harder to read. Forgot to include the link to the Jankifier page._

Write a single HTML file that includes JavaScript. Use the title "Letteriffic v1.0.0".

Accept a text input. When the user presses the "Letterify" button, add a random letter between all the existing letters. Display the result in an output area, and copy the result to the clipboard. Provide a separate button "Copy to Clipboard" which copies the result to the clipboard.

Add this text to the top of the file:

<!--   
    Copyright © 2024 Peter Kaminski  
    Licensed under the MIT License  
    https://ai101.peterkaminski.wiki/jankifiers  
    https://github.com/peterkaminski/ai101-peterkaminski-wiki/jankifiers/  
-->  

Add a sentence of instructions to the page before the input areas.

Add this text at the bottom of the page:

```
    <div class="footer">
        <p>&copy; 2024 Peter Kaminski</p>
        <p>Open source, licensed under the <a href="https://opensource.org/licenses/MIT" target="_blank">MIT License</a></p>
    </div>
```

Before you write the HTML file, do you have any clarifying questions for me?

## Interleaver

_This is an example prompt for GPT-4, which generated the original Interleaver. Copy and modify it, then give it to ChatGPT or other LLM to make your own jankifier! Send your jankifiers to [Pete](mailto:kaminski@istori.com) if you'd like to have them listed here._

> Using JavaScript, HTML, and CSS, create one HTML file that acts as an app called "Interleaver" that displays a web page if not given any input. The web page will show some simple instructions, two text boxes for input ("Text 1" and "Text 2"), a text output area, and a button labeled "Interleave". When the form data is submitted, Interleaver will interleave Text 1 and Text 2 word by word, and display it in the text output area.
> 
>  Before you write the app, do you have any clarifying questions for me?

(ChatGPT returned the HTML page.)

> Great! Now, add a button to copy the result text to the user's clipboard, and clear the textareas after interleaving.
