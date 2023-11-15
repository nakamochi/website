---
template: "home.html"
title: "nakamochi"
extra:
  landing: true
  tagline: "un nodo per privacy completa e autonomia finanziaria, basato su bitcoin e lightning"
---
## Perché nakamochi

Ad oggi esistono molte applicazioni web e mobili che forniscono funzionalità
di portafogli bitcoin e lightning. Sono anche noti come [SPV], Simplified
Payment Verification client, perché si collegano ad un [nodo bitcoin] collocato
da qualche parte. Anche gli [hardware wallet] richiedono un'applicazione con cui
interfacciarsi, che a sua volta si connette a un nodo bitcoin gestito da qualcun altro.

Storicamente, i nodi di bitcoin - e soprattutto quelli lightning - sono stati gestiti
da organizzazioni e persone con conoscenze nei campi di crittografia, reti
ed ingegneria del software.

Nakamochi sfida lo status quo e prova a rendere questi nodi utilizzabili da un
pubblico più ampio. Proprio come una macchina del caffè o un microonde,
crediamo che chiunque deva poter essere in grado di gestire un nodo bitcoin
e lightning a casa propria, e raggiungere il 100% di privacy e indipendenza.
Installare un proprio full node a casa aiuta anche la rete Bitcoin a rimanere
decentralizzata.

[SPV]: https://developer.bitcoin.org/devguide/operating_modes.html#simplified-payment-verification-spv
[nodo bitcoin]: https://bitcoin.org/en/full-node#what-is-a-full-node
[hardware wallet]: https://bitcoin.org/it/wallets/hardware/

## Il nome

Il nome "nakamochi" deriva da due componenti, unite inseme: [Satoshi Nakamoto],
l'inventore di Bitcoin, ed un famoso
[animale domestico digitale giapponese](https://en.wikipedia.org/wiki/Tamagotchi).
Con questo nome vogliamo porre l'accento sul self-hosting vero proprio, a casa.

[Satoshi Nakamoto]: https://en.bitcoin.it/wiki/Satoshi_Nakamoto

## Le versioni

Le edizioni sotto elencate sono in ordine crescente per facilità d'uso.
Si tratta sempre di un compromesso tra costi, lavoro necessario da parte
dell'utente, e fiducia nell'azienda produttrice e la sua supply chain.

<div class="text-media-card">
  <div class="card-text">

Tutte le versioni hanno delle parti in comune: l'interfaccia utente touch screen
e gli aggiornamenti automatici del sistema. Anche con un livello di fiducia basso
è comunque possibile trarre benefici dall'utilizzo del software open source e,
cosa altrettanto importante, dagli aggiornamenti del sistema.

  </div>
  <figure class="card-media screenshot">
    <img src="/assets/ngui-screenshot.png" alt="nakamochi touchscreen GUI screenshot">
    <figcaption>nakamochi touchscreen GUI screenshot</figcaption>
  </figure>
</div>

### DIY

<div class="text-media-card">
  <div class="card-text">

La [versione fai-da-te](https://git.qcode.ch/nakamochi/3d#diy-version-fff) è stata
progettata utilizzando solo componenti hardware standard e  parti stampabili in 3D.
È un sistema completamente funzionante, ed è possibile reperire e persino sostituire
l'hardware. Tutto è open source e liberamente accessibile. Naturalmente è possibile
acquistare l'intero kit presso di noi per rendere le cose più facili.
Puoi divertirti a revisionare il codice sorgente, i disegni CAD e le schematiche.
Smanetta senza limiti. Assicurati solo che poi l'apparecchio funzioni ancora :)

  </div>
  <figure class="card-media bogen">
    <img src="/assets/diy-assembly.png" alt="DIY version assembly">
    <figcaption>DIY version assembly</figcaption>
  </figure>
</div>

### DIY+

<div class="text-media-card">
  <div class="card-text">

Se vuoi approfittare della nostra conoscenza, ma desideri comunque utilizzare
componenti standard, ti consigliamo la versione **DIY+**. Come dice il nome,
il "plus" in questa versione migliora alcune caratteristiche del dispositivo.

Ad esempio, la precedente versione fai-da-te può riscaldarsi, raggiungendo
temperature abbastanza elevate in determinate condizioni. Questa edizione
migliora la dissipazione del calore mantenendo l'apparecchio completamente
silenzioso, senza ventole.

Tuttavia, questa edizione richiede ancora alcune conoscenze tecniche nel campo
della lavorazione CNC e delle stampe 3D.

  </div>
  <div class="card-media">
    <figure class="bogen">
      <img src="/assets/diyplus-assembly.png" alt="DIY+ version assembly">
      <figcaption>DIY+ version assembly</figcaption>
    </figure>
    <figure>
      <img src="/assets/ir1166.jpg" alt="DIY+ heat dissipation">
      <figcaption>DIY+ heat dissipation during initial block download</figcaption>
    </figure>
  </div>
</div>

### PRO

<div class="text-media-card">
  <div class="card-text">

Se sei principalmente interessato agli aspetti di libertà e l'indipendenza,
al vivere nel mondo del "Bitcoin Standard", aiutando la rete Bitcoin a rimanere
decentralizzata, e desideri un dispositivo che funzioni senza conoscenze tecniche
fai-da-te nella progettazione l'hardware e nell'ingegneria del software, la versione
PRO è quella che fa per te.

Stiamo utilizzando tutte le conoscenze apprese durante lo sviluppo delle edizioni
DIY e DIY+, al fine di costruire la maggior parte dei componenti all'interno della
nostra azienda: dalle parti meccaniche alle schede PCB per ottenere una soluzione
ottimale, in cui l'hardware ed il software funzionano perfettamente insieme.
Tutto il lavoro è naturalmente 100% open source.

L'edizione PRO è ancora in progettazione.

  </div>
  <figure class="card-media bogen">
    <img src="/assets/pro-question-mark.png" alt="PRO version in progress">
    <figcaption>PRO version in progress</figcaption>
  </figure>
</div>

## Newsletter

Iscriviti alla newsletter per ricevere gli aggiornamenti sullo stato del progetto.

<form method="post" action="https://listmonk.nakamochi.io/subscription/form" class="listmonk-form">
  <input type="hidden" name="nonce">
  <input type="hidden" name="l" value="3c3bf41a-cda3-43b6-af42-452424b022df">
  <p><input type="email" name="email" placeholder="e-mail" required></p>
  <p><input type="submit" value="iscriversi" /></p>
</form>
