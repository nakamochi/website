---
template: "home.html"
title: "nakamochi"
extra:
  landing: true
  tagline: "a device for complete privacy and financial independence leveraging bitcoin and lightning networks"
---
## Motivation

Nowadays, there are many web and mobile apps providing bitcoin and lightning wallets
functionality. They are mostly known as [SPV], Simplified Payment Verification clients
which connect to a [full node]. Likewise, [hardware wallets] also typically require
a companion app which in turn connects to a full node run by someone else.

Historically, bitcoin - and especially lightning - nodes have been run by
organizations and people with knowledge in cryptography, system networks and
software engineering.

Nakamochi takes on the challenge to make such nodes usable to a broader audience.
Just like a coffee maker or a microwave oven, we believe anyone should be able
to run a node at home and reach 100% privacy and independence. Running one's own
full node also helps the whole Bitcoin network to remain decentralized.

[SPV]: https://developer.bitcoin.org/devguide/operating_modes.html#simplified-payment-verification-spv
[full node]: https://bitcoin.org/en/full-node#what-is-a-full-node
[hardware wallets]: https://bitcoin.org/en/wallets/hardware/

## The name

The name "nakamochi" comes from putting together [Satoshi Nakamoto], the founder
of Bitcoin, and a
[famous Japanese handheld digital pet](https://en.wikipedia.org/wiki/Tamagotchi)
to emphasize personal, self-hosting.

[Satoshi Nakamoto]: https://en.bitcoin.it/wiki/Satoshi_Nakamoto

## Editions

We are focusing on two editions. One for tinkeres and people with
technical knowledge. The other is a "plug-and-play" device, like a
coffee maker.

<div class="text-media-card">
  <div class="card-text">

The editions have something in common: the touch screen user interface
and system updates. Naturally, everything is open source, including
electronics and mechanical parts we designed ourselves.

  </div>
  <figure class="card-media screenshot">
    <img src="/assets/ngui-screenshot.png" alt="nakamochi touchscreen GUI screenshot">
    <figcaption>nakamochi touchscreen GUI screenshot</figcaption>
  </figure>
</div>

### NERD

<div class="text-media-card">
  <div class="card-text">

The NERD edition is designed using only off-the-shelf electronics components,
3D-printed and CNC-milled mechanical parts. It is a running system and you can
source and even replace the hardware. Everything is open source and freely
accessible for everyone. Here you profit from some product engineering.
It improves heat dissipation while keeping the device completely silent, fanless.

You can of course buy the whole kit from us to make things easier,
or source CNC and 3D printed material yourself. We will be offering it
in the preassembled and kit form.

Enjoy checking out the source code, CAD designs and schematics.
You can tinker here, just be sure that the device still works after that.

  </div>
  <div class="card-media">
    <figure class="bogen">
      <img src="/assets/nerd-assembly.png" alt="NERD version assembly">
      <figcaption>NERD assembly</figcaption>
    </figure>
    <figure>
      <img src="/assets/ir1166.jpg" alt="NERD heat dissipation">
      <figcaption>heat dissipation during initial block download</figcaption>
    </figure>
  </div>
</div>

### KAFI

<div class="text-media-card">
  <div class="card-text">

If you are mostly interested in the freedom of the Bitcoin Standard,
helping the Bitcoin network to remain decentralized, and want a device
that just works without a NERD-like technical knowledge in hardware
design and software engineering, the KAFI edition is the one for you.

We are taking all the knowledge and learnings from the NERD edition and
designing most of the parts ourselves here: from mechanical parts and
enclosure to PCBs for an optimal device solution where hardware and
software function well together. All of the work is open
source.

The KAFI edition is still work-in-progress and will be available soon.

  </div>
  <figure class="card-media bogen">
    <img src="/assets/kafi-question-mark.png" alt="KAFI version in progress">
    <figcaption>KAFI version in progress</figcaption>
  </figure>
</div>

## Newsletter

Sign up to receive news and updates about nakamochi.

<form method="post" action="https://listmonk.nakamochi.io/subscription/form" class="listmonk-form">
  <input type="hidden" name="nonce">
  <input type="hidden" name="l" value="3c3bf41a-cda3-43b6-af42-452424b022df">
  <p><input type="email" name="email" placeholder="e-mail" required></p>
  <p><input type="submit" value="subscribe" /></p>
</form>
