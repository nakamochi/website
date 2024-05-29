---
title: "design and code sources"
---

All the designs and software source code are located on GitHub
at [github.com/nakamochi/](https://github.com/nakamochi/).

The following are the main repositories where the development is done.

## NDG

Nakamochi daemon and GUI, the main software part. It is composed of two layers:
a background daemon and a touch-capable GUI interface.

[github.com/nakamochi/ndg](https://github.com/nakamochi/ndg)

{{ screenshot(src="/assets/ngui-screenshot.png", caption="nakamochi touchscreen GUI screenshot") }}

## 3D

CAD designs of enclosures and other related mechanical parts.

[github.com/nakamochi/3d](https://github.com/nakamochi/3d)

{{ screenshot(src="/assets/git-3d-repo.png", caption="CAD designs of mechanical parts") }}

## sysupdates

Operating system tweaks and automated updates. All nodes fetch and install updates
from this repository.

[github.com/nakamochi/sysupdates](https://github.com/nakamochi/sysupdates)

## PCB

<div class="text-media-card">
  <div class="card-text">

KAFI version custom board electronics designs. This is still upcoming. We will add links here
as soon as the repository is live.

  </div>
  <figure class="card-media">
    <img src="/assets/kafi-question-mark.png" alt="KAFI version in progress">
  </figure>
</div>
