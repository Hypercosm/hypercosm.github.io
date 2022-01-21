---
title: "Hypercosm Roundup 1/21/22: Let's Get Scripting!"
tags: Meta ProgressUpdate
author: LemmaEOF
---

A lot has happened this week in Hypercosm development, bringing us to the precipice of being Alpha-ready! Let's take a
look at what folks have gotten done.

<!--more-->

### Hypercosm IDL

**aDot** has been doing a lot of work on HIDL, a custom Interface Definition Language for Hypercosm! There's an
[implementation in Rust](https://github.com/Hypercosm/HIDL) which can generate both a JSON format and docs from the
`.hidl` spec we've sketched out. Now that we have a reference implementation, we can move on to systems for generating
networking code from HIDL so Node implementations won't have to roll everything themselves!

### Runtime Environment

**Daeken**'s big project for the week has been implementing the combined lua/WASM runtime for her Browser! While the
API surfaces haven't been written yet, the ability to run WASM and lua together is going to be crucial for Cosms to use
scripts to their full potential. She's also done a test compilation of [cimgui](https://github.com/cimgui/cimgui) to
WASM in order to use it for 2D interfaces within Cosms.

### Path to Alpha

Right now, we have four requirements for what we consider *mandatory* for an alpha protocol release.

- [x] Specifying the Core Protocol.
- [x] Specifying the Asset Delivery extension.
- [x] Specifying the World extension.
- [ ] Specifying the initial Scripting extension.

As soon as the scripting extension has been specified, Hypercosm will be ready for experimental Alpha use! 
**There will still be breaking changes from Alpha to release**, but it'll be the first point at which we feel things
are ready enough to open our projects up for testing and feedback! We'll keep giving you updates as development
progresses, so look forward to that! See y'all next time!~