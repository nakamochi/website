---
title: "design and code sources"
---

All the designs and software source code are located on our self-hosted
git repositories at [git.qcode.ch/nakamochi/](https://git.qcode.ch/nakamochi/).
We also mirror them on GitHub at [github.com/nakamochi/](https://github.com/nakamochi/)
for redundancy, broader awareness and to ease contributions.

Our self-hosted git repositories accept issues and code changes only from
existing accounts, and creating new accounts feature is disabled: we'd like
to avoid potential abuse. Nonetheless, we will happily take in any suggestions
on the GitHub mirrors.

The following are the main repositories where the development is done.

## NDG

Nakamochi daemon and GUI, the main software part. It is composed of two layers:
a background daemon and a touch-capable GUI interface.

- repository: [git.qcode.ch/nakamochi/ndg](https://git.qcode.ch/nakamochi/ndg)
- mirror: [github.com/nakamochi/ndg](https://github.com/nakamochi/ndg)

{{ screenshot(src="/assets/ngui-screenshot.png", caption="l'interfaccia grafica del touchscreen") }}

## 3D

CAD designs of enclosures and other related mechanical parts.

- repository: [git.qcode.ch/nakamochi/3d](https://git.qcode.ch/nakamochi/3d)
- mirror: [github.com/nakamochi/3d](https://github.com/nakamochi/3d)

{{ screenshot(src="/assets/git-3d-repo.png", caption="i disegni CAD delle parti meccaniche") }}

## sysupdates

Operating system tweaks and automated updates. All nodes fetch and install updates
from this repository.

- repository: [git.qcode.ch/nakamochi/sysupdates](https://git.qcode.ch/nakamochi/sysupdates)
- mirror: [github.com/nakamochi/sysupdates](https://github.com/nakamochi/sysupdates)

## PCB

<div class="text-media-card">
  <div class="card-text">

KAFI version custom board hardware designs. This is still upcoming. We will add links here
as soon as the repository is live.

  </div>
  <figure class="card-media">
    <img src="/assets/kafi-question-mark.png" alt="versione KAFI è ancora in fase di elaborazione">
  </figure>
</div>
