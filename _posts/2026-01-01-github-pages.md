---
layout: post
title:  "GitHub Pages"
date:   2026-01-01 17:06:44 +0100
categories: jekyll update
---

Dank [GitHub Pages](http://pages.github.com/) ist es mir jetzt möglich, eine Website für `cryzze.net` und `www.cryzze.net` zur Verfügung zu stellen, ohne dabei zusätzlichen öffentlichen Traffic von der Hauptdomain an meinen Diensten zu riskieren oder Kosten für weitere Ressourcen in Kauf zu nehmen. GitHub Pages schien mir nun eine einfache, kostenfreie, seriöse und werbefreie Möglichkeit zu sein, auf der sonst ungenutzten Hauptdomain wenigstens keine Fehlermeldungen mehr zu präsentieren. Die Domain an sich nutze ich schon länger, die Website gibt es aus den genannten Gründen aber erst jetzt.

In losen Abständen veröffentliche ich hier (vielleicht) auch weitere Informationen über einige meiner Dienste im Allgemeinen oder anderer privater Projekte aus der Elektronik- oder Softwarekiste.

Wir werden sehen, Zeit ist gewöhnlich ein Faktor.

## Jekyll und minima

Diese Website wird aktuell mit [Jekyll](https://jekyllrb.com) und [minima](https://github.com/jekyll/minima) erzeugt. 

Jekyll ist ein statischer Website‑Generator, der Inhalte wie Markdown‑Dateien, Konfigurationsparameter und Templates verarbeitet und daraus eine statische HTML‑Struktur erzeugt. Grundlage dafür sind Front‑Matter‑Metadaten, Liquid‑Templates und ein festes Ordnungsmodell für Seiten, Beiträge und Collections. Jekyll definiert damit die technischen Abläufe, durch die Inhalte interpretiert, kombiniert und in endgültige Ausgabedateien überführt werden.

Das Theme minima ergänzt diese technische Basis um eine Präsentationsschicht. Es stellt Layouts, Includes, CSS‑Strukturen und typografische Vorgaben bereit, die Jekyll beim Rendern der Inhalte verwendet. minima liefert also die gestalterischen und strukturellen Elemente, während Jekyll die Verarbeitung und Zusammenführung übernimmt. Beide Komponenten greifen über das Template‑System ineinander: Jekyll füllt die von minima bereitgestellten Layouts mit Inhalten und erzeugt daraus die fertigen HTML‑Seiten.

GitHub Pages bildet die Ausführungs‑ und Hostingumgebung für dieses Zusammenspiel. Die Plattform führt Jekyll automatisch aus, sobald Änderungen im Repository vorgenommen werden, und verwendet dabei eine festgelegte Jekyll‑Version sowie eine definierte Auswahl unterstützter Plugins. Dadurch entsteht eine reproduzierbare Build‑Umgebung, die auf Stabilität und Sicherheit ausgelegt ist. Nach dem Build stellt GitHub Pages die erzeugten statischen Dateien öffentlich bereit und übernimmt deren Auslieferung über eine feste URL und ein globales CDN.

Grundlegend können alle in irgendeiner Weise (ggf. automatisiert) erstellten statischen Websites mit GitHub Pages dargestellt werden. In automatisierten Umgebungen findet der Build-Prozess im Unterschied zu Jekyll dann nicht bei GitHub statt, sondern muss in einer eigenen Build-Umgebung (lokal oder entfernt) ausgeführt werden.