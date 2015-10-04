# AMP HTML Extended Components

Extended components must be explicitly included
into the document as custom elements.

For example, to include a youtube video in your page
include the following script in the `<head>`:

    <script custom-element="amp-youtube" src="https:///cdn.ampproject.org/amphtml/v0/amp-youtube-0.1.js" async></script>

Current list of extended components:

| Component                                     | Description                                                                                 |
| --------------------------------------------- | ------------------------------------------------------------------------------------------- |
| [`amp-anim`](amp-anim.md)                     | Runtime-managed animated image, most typically a GIF.                                       |
| [`amp-audio`](amp-audio)                      | Replacement for the HTML5 `audio` tag.                                                      |
| [`amp-carousel`](amp-carousel)                | Generic carousel for displaying multiple similar pieces of content along a horizontal axis. |
| [`amp-fit-text`](amp-fit-text)                | Expand or shrink font size to fit the content within the space given.                       |
| [`amp-iframe`](amp-iframe.md)                 | Displays an iframe.                                                                         |
| [`amp-image-lightbox`](amp-image-lightbox.md) | Allows for a “image lightbox” or similar experience.                                        |
| [`amp-instagram`](amp-instagram.md)           | Displays an instagram embed.                                                                |
| [`amp-lightbox`](amp-lightbox.md)             | Allows for a “lightbox” or similar experience.                                              |
| [`amp-twitter`](amp-twitter.md)               | Displays a Twitter Tweet.                                                                   |
| [`amp-youtube`](amp-youtube.md)               | Displays a Youtube video.                                                                   |