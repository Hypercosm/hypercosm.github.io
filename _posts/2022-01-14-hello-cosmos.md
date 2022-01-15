---
title: Hello, Cosmos!
tags: Meta ProgressUpdate
author: LemmaEOF
article_header:
    type: cover
    image:
        src: /content/hypermosaic.png
---

Welcome to the Hypercosm dev blog! We'll be using this to host progress updates, showcases, and more as we continue to
develop the Hypercosm protocol, Cosm servers, and Browsers! Because the website is only just being created, let's
summarize everything that's been done so far.

<!--more-->

### Specs and Visions

The vision for Hypercosm has already been well-defined after discussions within the community. The results of those
discussions have been put into a [doc](https://docs.google.com/document/d/1Aq3u7ZFCBSSxrgXGH-Zel4uAkfoHA-d8xGpzzvmfmIg/),
and will be copied onto the website once we've determined them to be properly finalized. The same will happen with the
[core protocol spec](https://docs.google.com/document/d/1nydSDA7hdUWqpoBTlXBliOccDINq8l1Fuw2biFmrvic/edit) once it has
been updated to the 1.0 version.

### Implementations

While the Hypercosm project will not host any official implementations of Cosms or Browsers, multiple community members
have already created Hypercosm-compliant software and frameworks:

- **Daeken** has published [TestCosm](https://github.com/daeken/TestCosm) and
[HyperMosaic](https://github.com/daeken/HyperMosaic), the first proof-of-concept Cosm and Browser compliant with the
protocol! Both use Daeken's NetLib (included in the TestCosm repo) written in C#, and HyperMosaic is built in Unity.
- **aDot** is creating [nemicosm](https://gitea.treehouse.systems/aDot/nemicosm), a Browser implementation written in
Rust!
- **Retr0id** is working on a Python implementation of the Hypercosm spec!
- **nicolas17** is writing a Wireshark extension for Hypercosm packets!

### Community Showcase

Daeken's posted a video showing off HyperMosaic connecting to a test Cosm! You can check that out here:

{% twitter https://twitter.com/daeken/status/1482046423030026240 %}

nicolas17 has also shared a screenshot of the Hypercosm WireShark plugin:

![A screenshot of WireShark decoding Hypercosm packets.](/content/wireshark.png)

### Moving Forward

The core protocol and spec for asset delivery have now been fully specified with working test implementations! In order
to fully prepare the Alpha spec, we still need to define scripting, Worlds, and 2D UI. We're keeping track of version
requirements in a [Goals](https://docs.google.com/document/d/1l5nxZY7xuflq8h4BTJLCTQR_JlcEOpfIOdNm9XbBbAI/edit) doc,
and we'll keep posting regular updates here as they're implemented! If you want to give your feedback and ideas on
these specs, don't hesitate to join us in the [Discord](https://discord.gg/pvgemuz9wb)! Thank you very much for
reading, and we'll see you next time!~