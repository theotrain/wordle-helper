# Wordle Helper Browser Extension

This extension can help you get unstuck from a tricky Wordle puzzle.  It provides a sidebar you can open to see a list of valid guesses based on the current state of the puzzle.  When the list is short, it will give you letter-by-letter hints to avoid revealing the answer too easily.

## Install as a Chrome Extension

1) Near the top of this page, expand the green "Code" dropdown, and choose "Download ZIP"

2) Unzip the file

3) In Chrome, visit this URL: chrome://extensions/

4) Click the "Load Unpacked" button, and select the directory of the unzipped files.

## Install as a Firefox add-on

1) Download the [XPI FIle](https://theotrain.github.io/images/wordle_helper-1.0.0-fx.xpi)

2) Follow [these instructions](https://support.mozilla.org/en-US/kb/unable-install-add-ons-extensions-or-themes?redirectslug=Unable+to+install+add-ons&redirectlocale=en-US#w_you-are-asked-to-download-the-add-on-rather-than-installing-it) for installing an add-on from a file.

## How to use

After installation, you will see a small arrow inside a circle whenever you visit the Wordle page.  Click it to run Wordle Helper.

![open Wordle Helper](https://theotrain.github.io/images/wordle-helper-open.jpg)

If there are many possible valid guesses, Wordle Helper will show you a complete list.

![Wordle Helper list](https://theotrain.github.io/images/wordle-helper-list.jpg)

If there are only a few possible valid guesses, Wordle Helper will show you how many valid words remain, along with links to reveal information about individual letters.  In the below image the user has clicked on "letter 5", revealing that of the remaining words, 20% end with W, 20% end with N and 60% end with R.

![Wordle Helper letter clues](https://theotrain.github.io/images/wordle-helper-clues.jpg)

### Customize

By default, if there are more than 12 words remaining, you will see the words listed. If fewer, you will see links to individual letter statistics.  You can change this threshold by changing the variable "hintThreshold" in "wordle-helper.js"

### Video

There's a [youtube video](https://youtu.be/iL4ZigGiN1E ) for this project.  It shows you how to write a regular expression for a Wordle puzzle, and gets you started with the Javascript. 