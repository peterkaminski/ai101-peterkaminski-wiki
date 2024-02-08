# How to use exiftool to retrieve the image prompt from a Midjourney PNG file

_Up to topic: [[Midjourney]]_

## Overview

Did you know that Midjourney saves the prompt used for an image inside the image file itself?

This doesn't work for files downloaded from Discord, only for files downloaded from the Midjourney web site.

## Using exiftool

Using an open source command line tool called `exiftool`, you can retrieve the prompt, like this:

```shell
exiftool -Description peterkaminski_example_--ar_21_--stylize_80_--v_6_a7421d2f-b262-44f9-977c-ac23e9c7d3e3_2.png
```

Result:

```
Description                     : example --ar 2:1 --stylize 80 --v 6 Job ID: a7421d2f-b262-44f9-977c-ac23e9c7d3e3
```

You can see that the prompt I used was "example --ar 2:1 --stylize 80 --v 6"

You can also retrieve the username of the person who generated it:

```shell
exiftool -Author peterkaminski_example_--ar_21_--stylize_80_--v_6_a7421d2f-b262-44f9-977c-ac23e9c7d3e3_2.png
```

Result:

```
Author                          : peterkaminski
```

My Midjourney username is "peterkaminski".

## Some Details

This will still work if the file is renamed, and the information will be retained when it is processed by some image tools, but some image tools might remove it.

`exiftool` can be used to retrieve many kinds of metadata from image files. It's typically used in photography, but it works for some other kinds of images, too, as we've seen above.

## Resources

- [[Bulk downloading images from Midjourney]]
- [[How to use the command line]]
- [[How to install exiftool]] (hint: on Mac, use Homebrew)
- [exiftool official website](https://exiftool.org/) (external website)
- A similar tool is [exiv2](https://exiv2.org/) (external website)
