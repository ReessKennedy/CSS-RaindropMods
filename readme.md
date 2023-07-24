Remote link: 

## Why? 
---
Raindrop's UI is generally great, except where it's not. 

Notes: 
Raindrop's newish note feature is great but I want my notes to stand out more on the page when scanning them on the web interface. They currently get lost in all the other text. 

Tags: 
Too much line height here.

## Process
---
I use a Chrome extension to insert CSS modifications. There are a few that do this but I use User Javscript and CSS since it allows you to insert both in one extension. Here it is: https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld

## Code
---

### Note CSS
I use the dark theme and this adds a white background and changes the font family so my notes really stand out. 
```css
[class*="note"] {
  /* Your styles here */
  font-size: 14px !important;
  font-family: Courier;
  background: #fff;
  color: #333;
  padding: 5px;
  line-height: 120%;
}
```

