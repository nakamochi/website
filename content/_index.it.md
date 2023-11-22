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

Siamo focalizzati su due edizioni. Una è orientata agli smanettoni e le persone
con cononscenze tecniche. L'altra è "plug-and-play", come una macchinetta del caffè.

<div class="text-media-card">
  <div class="card-text">

Le edizioni hanno in comune l'interfaccia grafica touchscreen e gli aggiornamenti
del sistema. Naturalmente, tutto è open source, comprese le parti elettroniche
e meccaniche che abbiamo sviluppato noi in casa.

  </div>
  <figure class="card-media screenshot">
    <img src="/assets/ngui-screenshot.png" alt="nakamochi touchscreen GUI screenshot">
    <figcaption>screenshot dell'interfaccia grafica sul touchscreen</figcaption>
  </figure>
</div>

### NERD

<div class="text-media-card">
  <div class="card-text">

La versione NERD è stata progettata utilizzando solo componenti elettronici standard,
parti meccaniche stampate in 3D e fresate a CNC. È un sistema completamente funzionante
ed è possibile persino sostituire l'hardware. Tutto è open source e liberamente
accessibile. Qui si approfitta delle nostre conoscenze nel product engineering.
Ad esempio, migliora la dissipazione del calore permettendo l'apparecchio completamente
silenzioso, senza ventole.

Sarà possibile acquistare presso di noi l'intero kit fai-da-te oppure la versione
preassemblata. Naturalmente, uno può procurarsi tutti i compomenti incluso le parti
CNC e stampata 3D autonomamente.

Divertiti a revisionare il codice sorgente, i disegni CAD e le schematiche.
Smanetta senza limiti. Assicurati solo che poi l'apparecchio funzioni ancora.

  </div>
  <div class="card-media">
    <figure class="bogen">
      <img src="/assets/nerd-assembly.png" alt="assemblaggio versione NERD">
      <figcaption>assemblaggio versione NERD</figcaption>
    </figure>
    <figure>
      <img src="/assets/ir1166.jpg" alt="dissipazione del calore durante l'IBD (initial block download)">
      <figcaption>dissipazione del calore durante l'IBD (initial block download)</figcaption>
    </figure>
  </div>
</div>

### KAFI

<div class="text-media-card">
  <div class="card-text">

Se sei principalmente interessato agli aspetti di libertà e l'indipendenza,
al vivere nel mondo del "Bitcoin Standard", aiutando la rete Bitcoin a rimanere
decentralizzata, e desideri un dispositivo che funzioni senza conoscenze tecniche
fai-da-te nella progettazione l'hardware e nell'ingegneria del software, la versione
KAFI è quella che fa per te.

Stiamo utilizzando tutte le conoscenze apprese durante lo sviluppo della edizione
NERD al fine di costruire la maggior parte dei componenti noi in casa:
dalle parti meccaniche alle schede PCB per ottenere una soluzione
ottimale, in cui l'hardware ed il software funzionano perfettamente insieme.
Tutto il lavoro è naturalmente 100% open source.

L'edizione KAFI è ancora in lavorazione.

  </div>
  <figure class="card-media bogen">
    <img src="/assets/kafi-question-mark.png" alt="versione KAFI ancora in lavorazione">
    <figcaption>versione KAFI ancora in lavorazione</figcaption>
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
