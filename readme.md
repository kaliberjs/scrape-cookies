# Scrape cookies
This library scrapes cookies with all the necessary information for display on a cookie policy page.

## Motivation
Collecting cookies is annoying, lets automate it.

## Installation

```
yarn add @kaliber/scrape-cookies
```

## Usage
Short example. If your library has multiple ways to use it, show the most used one and refer to `/example` for further examples.

```jsx
const scrapeCookies = require('@kaliber/scrape-cookies')

const cookieJson = await scrapeCookies('http://localhost:8000', { 
  userAgent: 'KaliberEvidenceCollector'
})

console.log(cookieJson)
```

![](https://media.giphy.com/media/l1EsZ3evUEy7eLg76/giphy.gif)

## Disclaimer
This library is intended for internal use, we provide __no__ support, use at your own risk. 

This library is not transpiled.
