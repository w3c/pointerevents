# Introduction
This repo holds the sources for the [Pointer Events](https://www.w3.org/TR/pointerevents/upcoming/) spec of the [Pointer Events Working Group](https://www.w3.org/groups/wg/pointer-events).

# Editing process
- **Edit first, review later**: Editors land changes at their discretion, but a change should be reverted if it turns out the change does not reflect the rough consensus of the working group.
- **Test driven**: Normative spec changes are generally expected to have a corresponding [pull request](https://github.com/web-platform-tests/wpt/pulls?utf8=%E2%9C%93&q=is%3Apr%20is%3Aopen%20label%3Apointerevents%20) in  [web-platform-test/pointerevents](https://github.com/web-platform-tests/wpt/tree/master/pointerevents).  Outstanding test work is tracked via issues in this repository and issues generally remain open until both spec and test changes land.

# Test
- Some of the [specification issues are test related](https://github.com/w3c/pointerevents/issues?q=is%3Aissue+is%3Aopen+label%3Atest)
- Tests can be [run manually](http://wpt.live/pointerevents/)
- WPT has a list of the [latest generated test results](https://wpt.fyi/results/pointerevents)

# Implementation status:
- Blink: [Shipped](https://www.chromestatus.com/feature/4504699138998272)
- Gecko: [Partially shipped](https://platform-status.mozilla.org/#pointer-events)
- WebKit: [Partially shipped](https://webkit.org/status/#specification-pointer-events-level-2)
