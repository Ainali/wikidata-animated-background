# Wikidata Animated Background

This repository contains a sample html and css setup to create a webpage that has the Wikidata logo animated in the background.

## Preview

[![Preview](screenshot.gif)](https://ainali.github.io/wikidata-animated-background/)

**[View Live Preview](https://ainali.github.io/wikidata-animated-background/)**

## Download and Installation

To begin using this template, choose one of the following options to get started:

- Clone the repo: `git clone https://github.com/ainali/wikidata-animated-background.git`
- [Fork, Clone, or Download on GitHub](https://github.com/ainali/wikidata-animated-background)

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files to fit your purpose.
These are the only files you need to worry about, you can ignore everything else!
To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Settings to possibly change

Besides adapting the html to whatever you want, there are a number of things that you might want to adjust in the ccs.
Here are some of those you may want to adapt first.

#### .background-container::before

Here you can experiment with `width`, `height` and `background-size` to get the pattern you like.
If you change these, `transform: translateX(-30%)` may also need to be adjusted so the pattern covers the entire view.
Note that you may also do adjuments in the media query for smaller screen sizes.

In `animation` you can change the time, or the speed, of the animation.
A higher value than the default 30s will make it move slower.

Finally, you can change the `opacity`.
Default it is set to 1, which may be to saturated for text to be readable, so changing it to 0.5 or even lower might make it a bit more subtle.

#### @keyframes

By changing the 100% and 0 between the first and second line of `background-position` you will make the animation swith direction.

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/ainali/wikidata-animated-background/issues) here on GitHub.

## About

This background was created as a birthday gift at [Wikidata's 12th birthday](https://www.wikidata.org/wiki/Wikidata:Twelfth_Birthday).

## Copyright and License

Code released under [CC 0](https://github.com/ainali/wikidata-animated-background/main/LICENSE) license.
