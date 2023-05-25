---
title: "design und quellcode"
---

Alle Entwürfe und der Quellcode der Software befinden sich in unseren selbst
gehosteten Git-Repositories unter [git.qcode.ch/nakamochi/](https://git.qcode.ch/nakamochi/).
Wir spiegeln sie auch auf GitHub unter [github.com/nakamochi/](https://github.com/nakamochi/),
um die Redundanz zu erhöhen, den Bekanntheitsgrad zu steigern und Beiträge
zu erleichtern.

Unsere selbst gehosteten Git-Repositories akzeptieren Themen und Code-Änderungen
nur von bestehenden Konten. Die Funktion zum Erstellen neuer Konten ist deaktiviert:
Wir möchten potenziellen Missbrauch vermeiden. Nichtsdestotrotz nehmen wir gerne
alle Vorschläge von GitHub auf.

Folgend sind die wichtigsten Repositories, in denen die Entwicklung stattfindet.

## NDG

Nakamochi Daemon und GUI, der Hauptteil der Software. Diese besteht aus zwei Schichten:
einem Hintergrund-Daemon und einer touchfähigen GUI-Schnittstelle.

- Repository: [git.qcode.ch/nakamochi/ndg](https://git.qcode.ch/nakamochi/ndg)
- Spiegel: [github.com/nakamochi/ndg](https://github.com/nakamochi/ndg)

{{ screenshot(src="/assets/ngui-screenshot.png", caption="nakamochi touchscreen GUI screenshot") }}

## 3D

CAD-Designs von Gehäusen und anderen zugehörigen mechanischen Teilen.

- Repository: [git.qcode.ch/nakamochi/3d](https://git.qcode.ch/nakamochi/3d)
- Spiegel: [github.com/nakamochi/3d](https://github.com/nakamochi/3d)

{{ screenshot(src="/assets/git-3d-screenshot.png", caption="nakamochi touchscreen GUI screenshot") }}

## sysupdates

Optimierungen des Betriebssystems und automatische Aktualisierungen.
Alle Nodes holen und installieren Updates aus diesem Repository.

- Repository: [git.qcode.ch/nakamochi/sysupdates](https://git.qcode.ch/nakamochi/sysupdates)
- Spiegel: [github.com/nakamochi/sysupdates](https://github.com/nakamochi/sysupdates)

## PCB

<div class="text-media-card">
  <div class="card-text">

Benutzerdefinierte Hardware-Designs für die PRO-Version. Dieser Teil ist noch nicht
abgeschlossen. Wir werden hier Links hinzufügen, sobald das Repository live ist.

  </div>
  <figure class="card-media">
    <img src="/assets/pro-question-mark.png" alt="PRO version in progress">
  </figure>
</div>
