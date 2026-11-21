# Assets, sources and attributions

## Photography

Event imagery is requested from `images.unsplash.com` using curated Unsplash photo IDs contained in `events.js`. The app does **not** package or redistribute image files. Unsplash photos are used under the [Unsplash License](https://unsplash.com/license); Unsplash attribution is encouraged but not required by the standard license. For photographer attribution, resolve each photo ID on Unsplash and credit its actual contributor if you replace the sample imagery. All events themselves are fictional and do not claim to depict a real booked event.

If a remote image fails or there is no internet connection, `app.js` renders an original gradient SVG event poster instead.

## Icons

- [Font Awesome Free](https://fontawesome.com/license/free) 6.7.2 icon geometry is used for a subset of icons under the **CC BY 4.0** license. Copyright © Fonticons, Inc. The icon paths are carried as SVG vector geometry in `icons.js` (no font files).
- Additional original minimalist SVG line icons are included as fallbacks in `icons.js`.

## Fonts

The site references **Outfit** and **DM Sans** via Google Fonts, with system-font fallbacks.

## Frameworks and code

HTML, CSS and vanilla JavaScript. The optional Django API references the [Django framework](https://www.djangoproject.com/), a BSD-licensed project. See Django's licence for details.
