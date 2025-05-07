# cff

## Screenshots

<img src="./ss/1.png" width=300> <img src="./ss/2.png" width=300>

##  Installation
Clone this repository in your chrome folder:

```sh
git clone https://github.com/mistekko/cff
```

Then import the style sheets somewhere in your `userChrome.css`:
```css
@import url("cff/bookmarks.css");
@import url("cff/menus.css");
@import url("cff/tabs.css");
@import url("cff/urlbar.css");
```

You may also want to set a different font:

```css
* {
    font-size: 14px !important;
    font-family: monospace !important;
}
```

## The future
This theme is still rather rough. Expect many improvements, but don't expect them to come quickly.

Here's a list of things I want to make more consistent or prettier:

* context menu colour palette (needs to match rest of application)
* bookmark edit menu (needs to look a fair bit better)
* "playing audio icon" (needs to be flush)
* space between menus (see screenshot 1)
* icons in menu and their padding (need consistency)

If there's anything I've neglected, feel free to [make an issue](https://github.com/mistekko/cff/issues/new/choose)



