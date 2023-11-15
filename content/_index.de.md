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

Die folgenden Versionen sind in der Reihenfolge zunehmender Benutzerfreundlichkeit
aufgeführt. Es ist immer ein Kompromiss zwischen den Kosten und dem Aufwand,
den man selbst betreiben muss, und dem Vertrauen in das Fertigungsunternehmen
und seine Lieferkette.

<div class="text-media-card">
  <div class="card-text">

Alle Versionen haben etwas gemeinsam: die Touchscreen-Benutzeroberfläche und
automatische System-Updates. Selbst bei einem hohen Mass an Misstrauen kann
man immer noch von der Open-Source-Software und, was ebenso wichtig ist,
von den System-Updates profitieren.

  </div>
  <figure class="card-media screenshot">
    <img src="/assets/ngui-screenshot.png" alt="nakamochi touchscreen GUI screenshot">
    <figcaption>nakamochi touchscreen GUI screenshot</figcaption>
  </figure>
</div>

### DIY

<div class="text-media-card">
  <div class="card-text">

Für die [DIY-Version](https://git.qcode.ch/nakamochi/3d#diy-version-fff) werden
nur handelsübliche Hardwarekomponenten und 3D-gedruckte Teile verwendet. Es handelt
sich um ein lauffähiges System; du kannst die Hardware selber beziehen und sogar
ersetzen. Alles ist Open Source und für jeden frei zugänglich. Du kannst
natürlich auch das gesamte Kit bei uns günstiger kaufen, um das Sourcing zu vereinfachen.
Viel Spass beim Ausprobieren des Quellcodes, der CAD-Entwürfe und der Schaltpläne.
Du kannst hier frei darauf losbasteln. Stelle einfach sicher, dass das Gerät danach
noch funktioniert.

  </div>
  <figure class="card-media bogen">
    <img src="/assets/diy-assembly.png" alt="DIY version assembly">
    <figcaption>DIY version assembly</figcaption>
  </figure>
</div>

### DIY+

<div class="text-media-card">
  <div class="card-text">

Wenn du von einer Produktentwicklung profitieren möchtest, aber trotzdem
handelsübliche Komponenten verwenden möchtest, empfehlen wir die DIY+-Version.
Wie der Name schon sagt, verbessert das "Plus" in dieser Version einige
Eigenschaften des Geräts. Diese Version verbessert die Wärmeableitung, wobei
das Gerät völlig geräuschlos und ohne Lüfter bleibt. Allerdings erfordert
diese Ausgabe immer noch minimale technische Kenntnisse in der CNC-Bearbeitung
und 3D-Druck.

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

Wenn du vor allem an der Freiheit des Bitcoin-Standards interessiert bist, dem
Bitcoin-Netzwerk helfen willst dezentralisiert zu bleiben, und ein Gerät willst,
das ohne ein DIY-ähnliches technisches Wissen in Hardware-Design und
Software-Engineering einfach funktioniert, ist die PRO-Edition die Richtige für dich.

Wir nehmen das gesamte Wissen aus den DIY-Versionen und entwerfen die meisten
Teile selbst: von den mechanischen Teilen, über das Gehäuse bis hin zu den Leiterplatten.
All dies für eine optimale Gerätelösung, bei der Hardware und Software sehr gut
zusammenarbeiten. Diese Arbeit bleibt natürlich Open Source.

Die PRO-Version befindet sich noch in der Entwicklung.

  </div>
  <figure class="card-media bogen">
    <img src="/assets/pro-question-mark.png" alt="PRO version in progress">
    <figcaption>PRO version in progress</figcaption>
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
