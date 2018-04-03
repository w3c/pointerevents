# Introduction
This repo holds the sources for the [Pointer Events](https://w3c.github.io/pointerevents/) spec. The [extension doc](https://w3c.github.io/pointerevents/extension.html) contains proposals for adding new functionalities to future versions of the spec.

# Editing process
- **Edit first, review later**: Editors land changes at their discretion, but a change should be reverted if it turns out the change does not reflect the rough consensus of the working group.
- **Test driven**: Normative spec changes are generally expected to have a corresponing [pull request](https://github.com/w3c/web-platform-tests/pulls?utf8=%E2%9C%93&q=is%3Apr%20is%3Aopen%20label%3Apointerevents%20) in  [web-platform-test/pointerevents](https://github.com/w3c/web-platform-tests/tree/master/pointerevents).  Outstanding test work is tracked via issues in this repository and issues generally remain open until both spec and test changes land.

# Test results
- Tests can be run manually [here](http://w3c-test.org/pointerevents/)
- The latest generated test results (currently quite old) is [here](https://w3c.github.io/test-results/pointerevents/all.html).
- TODO: we want a live link to current test results!  This is currently hard :-(

# Implementation status:
- EdgeHTML: [Shipped](https://developer.microsoft.com/en-us/microsoft-edge/platform/status/pointerevents)
- Blink: [Shipped](https://www.chromestatus.com/feature/4504699138998272)
- Suggested polyfill: [jQuery PEP](https://github.com/jquery/PEP)
- Gecko: [In development](https://platform-status.mozilla.org/#pointer-events) (though enabled on desktop in Firefox 59)
- WebKit: [Opposition](https://lists.webkit.org/pipermail/webkit-dev/2012-December/023050.html)
