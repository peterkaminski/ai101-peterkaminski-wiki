# Jankifiers

Jankifiers are small, self-contained HTML files that help you create and modify ("jankify") prompts for AI, especially AI image generators. The first versions look dorky but do the job. Play with these! Write your own! Send comments or new jankifiers to [Pete](mailto:kaminski@istori.com)!

- [[commifier.html]] - v1.0.1 - adds commas randomly
- [[essifier-es.html]] - v1.0.1 - adds "es" suffix to each word
- [[essifier.html]] - v1.0.1 - adds "s" suffix to each word (not very interesting)
- [[interleaver.html]] - v1.0.1 - interleaves two prompts word-by-word (like cars doing a zipper merge)
- [[reverse-jankifier.html]] - v1.0.1 - swaps pairs of words

Each of these rough versions was created by ChatGPT by giving it a short prompt (see example below). The idea is to democratize the creation of little utilities like this, and with a good LLM, you can do it even if you're not a programmer!

We'll continue to add, improve, or perhaps even retire particular jankifiers without notice, except for posting them here.

Each single, self-contained HTML file can be used on the web, or saved to your computer or smartphone and used from there. We'll add more explanation later, but to start, you can just click on one of the links above, then do what the web page tells you -- add some text somewhere, click a button, copy the resulting text, then go over to your image generator and paste the text.

The authors (Peter Kaminski and/or others)  of these jankifiers can't help you with your image generator, and are not responsible for your use or misuse of the jankifiers, including problems caused by the text you copy and paste. What you do with these is your responsibility. Read the included and linked [MIT License](https://opensource.org/license/MIT) for more information.

## Interleaver Prompt

_This is an example prompt for GPT-4, which generated the original Interleaver. Copy and modify it, then give it to ChatGPT or other LLM to make your own jankifier! Send your jankifiers to [Pete](mailto:kaminski@istori.com) if you'd like to have them listed here._

> Using JavaScript, HTML, and CSS, create one HTML file that acts as an app called "Interleaver" that displays a web page if not given any input. The web page will show some simple instructions, two text boxes for input ("Text 1" and "Text 2"), a text output area, and a button labeled "Interleave". When the form data is submitted, Interleaver will interleave Text 1 and Text 2 word by word, and display it in the text output area.
> 
>  Before you write the app, do you have any clarifying questions for me?

(ChatGPT returned the HTML page.)

> Great! Now, add a button to copy the result text to the user's clipboard, and clear the textareas after interleaving.
