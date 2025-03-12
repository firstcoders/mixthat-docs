---
title: "Embedding a Player"
description: "Downloading a high quality mix"
summary: ""
date: 2025-03-01T16:13:18+02:00
lastmod: 2025-03-01T16:13:18+02:00
draft: false
weight: 5
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

A player can be embedded in any website using our [Mix That Player webcomponent](https://github.com/firstcoders/mixthat-player).

This is an open source webcomponent, built using [stemplayer-js](https://www.stemplayer-js.com) and can therefore be modified.

The player can also be styled using css-variables to match the colour scheme of your website.

Embedding does not use an iframe but the web-component standard, which ensures a superior integration.

In order to embed press the embed button.

then simply paste the embed code, for example

```js
<!-- paste the below just before the </head> tag -->
<script type="module" src="https://cdn.jsdelivr.net/npm/@firstcoders/mixthat-player@^4.0.0-beta.0"></script>
<style>
:root {
  --stemplayer-js-controls-background-color: #232323;
}
</style>
<!-- Paste the below in the HTML document where you would like the player to appear -->
<mixthat-player controls="" src="https://app.mixthat.co/api/v1/tracks/jgaYB9"></mixthat-player>
```

in the appropriate place in your website.

## Package Managers (NPM | Yarn)

If you prefer not to import the player script via a CDN you can use NPM instead to pull in the dependency into your platform.

Simply run `npm i @firstcoders/mixthat-player`

See [here for more information](https://github.com/firstcoders/mixthat-player).

## Customization

See the [stemplayer-js documentation](https://github.com/stemplayer-js/stemplayer-js/blob/main/docs/stemplayer-js.md) for more information on configuration, such as styling.
