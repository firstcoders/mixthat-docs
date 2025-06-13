---
title: "Embedding a Player"
description: "How to embed the Mix That Player web component in your website, with customization and integration tips."
summary: "A step-by-step guide to embedding and customizing the Mix That Player on your site."
date: 2025-03-01T16:13:18+02:00
lastmod: 2025-06-12T00:00:00+02:00
draft: false
weight: 102
toc: true
seo:
  title: "Embed the Mix That Player | Mix That"
  description: "Learn how to embed and customize the Mix That Player web component in your website, with code examples and integration tips."
  canonical: "/docs/guides/embedding-a-player/"
  robots: "index, follow"
---

You can easily embed the Mix That Player in any website using our open source [Mix That Player web component](https://www.npmjs.com/package/@firstcoders/mixthat-player), built on [stemplayer-js](https://www.stemplayer-js.com). This approach ensures seamless integration and full control over styling, without the limitations of an iframe.

### Why Web Components Instead of Iframes?

Embedding the Mix That Player as a web component offers several advantages over traditional iframes:

- **Seamless Integration:** Web components allow the player to blend naturally with your site's layout and design, without the visual and functional limitations of an iframe.
- **Full Customization:** You can style the player using CSS variables and adapt it to your branding, which is not possible with iframe-embedded content.
- **Better Performance:** Web components are lighter and more efficient, reducing load times and resource usage compared to iframes.
- **Improved Accessibility:** The player can interact directly with your site's DOM, making it easier to ensure accessibility and responsive design.
- **Enhanced Functionality:** Web components can communicate with your site's JavaScript, enabling advanced integrations and interactivity that iframes cannot provide.

This approach gives you greater control, flexibility, and a better user experience when embedding audio on your website.

### How to Embed the Player

1. Click the embed button in the Mix That app to generate your embed code.
2. Copy and paste the provided code into your website:

```html
<!-- Add this just before the </head> tag -->
<script type="module" src="https://cdn.jsdelivr.net/npm/@firstcoders/mixthat-player@^4.0.0-beta.0"></script>
<style>
  :root {
    --stemplayer-js-controls-background-color: #232323;
  }
</style>
<!-- Place this where you want the player to appear -->
<mixthat-player controls src="https://app.mixthat.co/api/v1/tracks/jgaYB9"></mixthat-player>
```

### Using Package Managers (NPM / Yarn)

Prefer not to use a CDN? Install the player via NPM:

```sh
npm i @firstcoders/mixthat-player
```

See the [GitHub repository](https://github.com/firstcoders/mixthat-player) for advanced usage and integration details.

### Customization

You can fully customize the player using CSS variables to match your site's color scheme and branding. For example, you can adjust colors, fonts, and other visual elements to ensure the player fits seamlessly into your website's design.

The Mix That Player is open source and released under the MIT license, so you are free to further customize or extend its functionality to suit your needs. You can contribute to its development or adapt it for your own projects.

For more configuration and styling options, refer to the [stemplayer-js documentation](https://github.com/stemplayer-js/stemplayer-js/blob/main/docs/stemplayer-js.md).

### Browser Support

The Mix That Player works in any modern browser that supports the Web Audio API and Custom Elements (including recent versions of Chrome, Firefox, Safari, and Edge).

If you have questions or need help with embedding, feel free to [contact support](/docs/general/support/).
