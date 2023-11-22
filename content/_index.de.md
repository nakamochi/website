---
template: "home.html"
title: "nakamochi"
extra:
  landing: true
  tagline: "ein Gerät, aus dem Bitcoin und Lightning Netzwerk, für vollständige Privatsphäre und finanzielle Unabhängigkeit"
---
## Motivation

Heutzutage gibt es viele Web- und Handy-Apps, welche die Funktionalität von
Bitcoin- und Lightning-Wallets bieten. Sie sind meist als [SPV]
(Simplified Payment Verification)-Clients bekannt, die sich mit einem [Full Node]
verbinden. Auch für [Hardware-Wallets] ist in der Regel eine Begleit-App erforderlich,
die wiederum eine Verbindung zu einem Full Node herstellt, der von jemand anderem
betrieben wird.

In der Vergangenheit wurden Bitcoin- und insbesondere Lightning-Nodes von Organisationen
und Personen mit Kenntnissen in Kryptografie, Systemnetzwerken und Softwaretechnik betrieben.

Nakamochi stellt sich der Herausforderung, solche Nodes für ein breiteres Publikum
nutzbar zu machen. Genau wie eine Kaffeemaschine oder eine Mikrowelle sollte jeder
in der Lage sein, einen Full-Node Zuhause zu betreiben und 100%ige Privatsphäre
und Unabhängigkeit zu erreichen. Der Betrieb eines eigenen Full-Nodes hilft auch
dem gesamten Bitcoin-Netzwerk, stabil und dezentral zu bleiben.

[SPV]: https://developer.bitcoin.org/devguide/operating_modes.html#simplified-payment-verification-spv
[Full Node]: https://bitcoin.org/en/full-node#what-is-a-full-node
[Hardware-Wallets]: https://bitcoin.org/de/wallets/hardware/

## Der Name

Der Name "nakamochi" setzt sich aus [Satoshi Nakamoto], dem Gründer von Bitcoin,
und einem [berühmten japanischen digitalen Haustier](https://de.wikipedia.org/wiki/Tamagotchi)
zusammen, um die persönliche, selbstverwaltete Nutzung zu betonen.

[Satoshi Nakamoto]: https://en.bitcoin.it/wiki/Satoshi_Nakamoto

## Versionen

Wir konzentrieren uns auf zwei Editionen. Eine für Tüftler und Menschen
mit technischem Wissen. Die andere ist ein "Plug-and-Play"-Gerät, eine
Kaffeemaschine.

<div class="text-media-card">
  <div class="card-text">

Die Editionen haben das wichtigste gemeinsam: die
Touchscreen-Benutzeroberfläche und System-Updates. Natürlich ist alles
Open Source, einschließlich der Elektronik und der mechanischen Teile,
die wir selbst entwickelt haben.

  </div>
  <figure class="card-media screenshot">
    <img src="/assets/ngui-screenshot.png" alt="nakamochi touchscreen GUI screenshot">
    <figcaption>nakamochi touchscreen GUI screenshot</figcaption>
  </figure>
</div>

### NERD

<div class="text-media-card">
  <div class="card-text">

Die NERD Edition wurde ausschließlich aus frei
verfügbaren/handelsüblichen elektronischen Komponenten, 3D-gedruckten
und CNC-gefrästen mechanischen Teilen entwickelt. Es handelt sich um ein
funktionierendes System, Sie können die Hardware sogar selbst beziehen
und ersetzen. Alles ist Open Source und für jeden frei zugänglich. Hier
profitierst du bereits von einer gewissen Produktentwicklung: Eine
verbesserte Wärmeableitung, während das Gerät völlig geräuschlos und
lüfterlos bleibt.

Für den NERD kannst du natürlich den ganzen Bausatz von uns kaufen, um
die Dinge einfacher zu machen, oder CNC- und 3D-gedrucktes Material
selbst beschaffen. Es wird in vormontierter und Kit Form verkauft.

Viel Spaß beim Ausprobieren des Quellcodes, der CAD-Entwürfe und der
Schaltpläne. Du kannst hier basteln, sei einfach sicher, dass das Gerät
danach noch funktioniert.

  </div>
  <div class="card-media">
    <figure class="bogen">
      <img src="/assets/nerd-assembly.png" alt="NERD version assembly">
      <figcaption>NERD version assembly</figcaption>
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

Wenn du vor allem an der Freiheit des Bitcoin-Standards interessiert
bist, dem Bitcoin-Netzwerk helfen willst dezentralisiert zu bleiben, und
ein Gerät willst, das einfach funktioniert, ohne ein NERD-ähnliches
technisches Wissen in Hardware-Design und Software-Engineering, dann ist
die KAFI-Edition das Richtige für Sie.

Wir nehmen all das Wissen und die Lehren aus der NERD-Version und
entwickeln die meisten Teile selbst: von den mechanischen Teilen über
das Gehäuse bis hin zu den Platinen für eine optimale Gerätelösung, bei
der Hardware und Software sehr gut zusammenarbeiten. Die gesamte Arbeit
ist Open Source. Die KAFI-Version ist noch in Arbeit und wird bald
verfügbar sein.

  </div>
  <figure class="card-media bogen">
    <img src="/assets/kafi-question-mark.png" alt="KAFI version in progress">
    <figcaption>KAFI version in progress</figcaption>
  </figure>
</div>

## Newsletter

Melde dich an um die Neuigkeiten und Updates über nakamochi zu erhalten.

<form method="post" action="https://listmonk.nakamochi.io/subscription/form" class="listmonk-form">
  <input type="hidden" name="nonce">
  <input type="hidden" name="l" value="3c3bf41a-cda3-43b6-af42-452424b022df">
  <p><input type="email" name="email" placeholder="e-mail" required></p>
  <p><input type="submit" value="Anmelden" /></p>
</form>
