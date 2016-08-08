This repo holds the sources for the [Pointer Events](https://w3c.github.io/pointerevents/) spec.

Implementation status:
- EdgeHTML: [Shipped](https://developer.microsoft.com/en-us/microsoft-edge/platform/status/pointerevents)
- Suggested polyfill: [jQuery PEP](https://github.com/jquery/PEP)
- Blink: [Behind a flag & dev-channel experiment](https://www.chromestatus.com/features/4504699138998272)
- Gecko: [In development](https://platform-status.mozilla.org/#pointer-events)
- WebKit: [Opposition](https://lists.webkit.org/pipermail/webkit-dev/2012-December/023050.html)

The [reduce-hit-tests branch](https://github.com/w3c/pointerevents/tree/reduce-hit-tests) contains a [proposal](https://rawgit.com/w3c/pointerevents/reduce-hit-tests/index.html#implicit-pointer-capture) with a [few changes](https://github.com/w3c/pointerevents/compare/gh-pages...reduce-hit-tests) changes to address a [performance concern raised by the Chrome team](https://github.com/w3c/pointerevents/issues/8). 
   

