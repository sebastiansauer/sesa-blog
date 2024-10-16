---
title: 'Streaming aus den Hörsaal, ein einfacher Ansatz'
author: Sebastian Sauer
date: 2022-03-23

tags: [teaching]
categories: [reaching]


draft: FALSE

output:
  blogdown::html_page:
    toc: true
    keep_md: yes
    number_sections: true
---







# Hintergrund


Aktuell setzt sich an vielen Hochschulen wieder Präsenzlehre durch oder ist zumindest angesagtes Gebot der Stunde. Allerdings gibt es eine mitunter substanzielle Zahl an Studis, die Online-Unterricht vorziehen, also nicht in den Präsenzunterricht kommen wollen. Der Grund ist zumeist, meine Vermutung, dass es bequemer ist, dem Unterricht online zu folgen, weniger Aufwand also. Man muss nicht extra an die Hochschule fahren etc. Einige Studentis wohnen coronabedingt gar nicht mehr am Ort der Hochschule, so dass die Barriere des "Reinkommens" hoch ist. Jedenfalls gibt es trotz einer "Präsenzempfehlung" viele Online-Studentis, so meine Erfahrung zumindest.

Daher kommt *Streaming* zupass: Gleichzeitig Präsenz- und Online-Unterricht anzubieten, hört sich nach der Besten-beider-Welten-Lösung an. Natürlich hat Streaming auch Nachteile (dazu später), aber eben auch den auf der Hand liegenden Vorteil, gleichzeitig beide Gruppen, die Studis zuhause und die Studis vor Ort, anzusprechen.

Einige Streaming-Lösungen sind aufwändig: Kameramann mit Profi-Equipment inklusive Beleuchtung. Datenschutz nicht zu vergessen. Wie alles hat so eine Profi-Lösung Vor- und Nachteile.

Hier stelle ich eine einfach Lösung, fast nur mit Bordmitteln, vor. Natürlich ist die auch nicht perfekt.
Aber gerade als Einstieg zum Ausprobieren oder als schnell umsetzbare Lösung kann so eine  einfache Lösung geeignet sein.

In diesem Post stelle ich meinen Ansatz vor, worum mich jemand gebeten hat. Vielleicht nutzt es ja einigen Kollegis.

# Warnung

Ich bin kein Audio-Experte! Ich kenne mich nicht aus mit Audio-Technik! Ich habe nur ein Setup gefunden, das für mich gut funktioniert. Ich beanspruche nicht, eine allgemein gute Lösung gefunden zu haben.

Wie gesagt, für mich funktioniert es gut. Vielleicht hilft es anderen Dozentis, 
deshalb stelle ich es hier vor.


# Ausrüstung

Ich nutze folgende Ausrüstung:


1. Laptop (MacBook Pro)

2. Sender-Empfänger-System [Rode Wireless Go](https://www.thomann.de/de/rode_wireless_go.htm)

3. [3,5mm Klinke Adapter zum Anschluss des Rode Receivers and das MacBook Pro](https://www.amazon.de/gp/product/B07N7JN76W/ref=ppx_yo_dt_b_asin_title_o05_s00?ie=UTF8&psc=1)

3. [Lavalier Mikro](https://www.amazon.de/gp/product/B01F84YMZQ/ref=ppx_yo_dt_b_asin_title_o08_s01?ie=UTF8&psc=1)

4. [Lavalier Mikro „Windjammer"](https://www.amazon.de/gp/product/B008EUH59W/ref=ppx_yo_dt_b_asin_title_o08_s00?ie=UTF8&psc=1)



# Aufbau

Das *Rode-Funksystem* ersetzt ein Kabel, sogar ein ziemlich langes. Auch in großen Hörsälen kann ich in jede Ecke gehen, ohne das die Verbindung leidet. Das Funksystem besteht aus zwei Teilen: Einen Sender (sendet Ihren Ton, also die Stimme) und einen Empfänger, der Ihren Ton "auffängt" und dann an den Computer (über den Audio-Eingang) weitergibt.

Zwar hat das Rode-Funksystme ein eingebautes Mikro, aber man kann noch ein Mikro (3,5mm Buchse) anstecken. Meine Erfahrung ist, dass ein Mikro, das nahe am Mund ist, für einen guten Ton sehr hilfreich ist. Dazu nutze ich ein günstiges *Lavalier-Mikro*, das ich an den Hemdkragen anknipse.

Um das Audiosignal in das Macbook zu leiten, braucht man noch ein *Adapterkabel*, ich nutze eines der Firma Heldenklang. Das MacBook hat nur eine Audio-Eingang, genau wie ein Smartphone, in dem Eingang (Mikro) und Ausgang (Kopfhörer) kombiniert sind. Hat man ein Mikro mit "Nur-Mikro-Ausgang", muss man auf den "Smartphone-Stecker" "umspannen". 
Das sind totale Laien-Erklärungen!

Den *Windschutz* ("Windjammer") habe ich zwar, setze ich aber eigentlich nicht ein.



# Streaming-Einsatz im Hörsaal

Das, was ich im Hörsaal am Beamer (an der Wand) zeige, übertrage ich via *Zoom* an die Studentis nach Hause (online). Meine Stimme übertrage ich an die Online-Studentis mit dem oben beschriebenen Audio-Setup. 
Ein Mikro für die Studentis vor Ort nutze ich nicht.


# Keine Kamera

Beim Streaming benutze ich keine externe Kamera. Warum nicht? Ist einfacher ohne. Keine Datenschutz-Probleme. Die Studis wissen ja, wie ich aussehe. Muss nix aufbauen, muss nicht auf einen Kameramenschen warten.

Hin und wieder mache ich meine Laptop-Kamera an, etwa zur Begrüßung und Verabschiedung. Hin und wieder sitze ich in der Vorlesung vor dem Rechner, dann mache ich sie auch an. Oder ich lasse sie einfach laufen, aber meistens renne ich im Hörsaal rum, dann nimmt die Kamera einfach die Wand hinter mir auf.


# Ablauf


Zum Beginn der Vorlesung baue ich meine Gerätschaften auf:

1. Rechner starten
2. Zoom starten zur Übertragung des Bildes wie Folien und den Ton für die Online-Studentis
3. Rode-Empfänger in Laptop einstöpseln
4. Mikrofon an Hemdkragen knipsen und an Rode-Sender anschließen
5. In Zoom "externes Mikrophon" bei den Mikro-Einstellungen auswählen
6. Beim MacBook in der Audio-Ausgabe das Macbook auswählen (nicht den "Kopfhörer" von dem der Macbook fälschlich im Standard ausgeht)
5. Sonstiges (wie Beamer starten)


# Probleme und Lösungen


## Es kommt kein Ton

Steckt man den Rode-Empfänger via Heldenklang-Kabel in den Mac, dann denkt der Mac, man möchte darüber (über die Audio-Buchse) den Sound ausgeben.
Macht in dem Fall keinen Sinn. Ist an sich kein Problem, 
in den Sound-Einstellungen am Macbook kann man das mit einem Klick ändern.
Man muss nur daran denken. Also: Hört man keinen Sound, wenn man das Mikro einsteckt, liegt es (vermutlich) daran, dass der Mac automatisch den Sound über einen (nicht vorhandenen) "Kopfhöhrer" (also über die Audio-Buchse) ausgeben möchte.


## Akku leer

Laut Werbung hält der Akku des Rode-Funksystems bis zu sieben Stunden.
Bei mir ist das deutlich weniger, vielleicht 4-5 Stunden, dann muss man laden. Die Rode-Teile (Empfänger und Sender) haben einen USB-C-Eingang,
über den ich sie mit meinem Händy-Ladegerät lade.

Den Empfänger kann man während des laufenden Betriebs laden, technisch kein Problem. Praktisch auch nicht, das Gerät liegt ja neben dem Laptop.
Der Sender ist nicht während des Betriebs zu laden, weil ich laufe ja herum. 

Hat man keinen langen Vorlesungstag ist die ganze Sache kein Problem.
Man muss nur ans Laden denken, z.B. am Abend nach der Vorlesung (nervt etwas). Bei einem langen Vorlesungstag mache ich Folgendes:
Den Empfänger lade ich einfach im laufenden Betrieb. 
Den Sender lade ich entweder während der Mittagspause.
Oder ich mache mal eine Vorlesung mit einer längeren Arbeitsphase,
wo ich nicht viel sagen muss, da kann ich dann über das MacBook-Mikro sprechen, so lange der Sender lädt. Natürlich muss ich dann in der Nähe des Laptops bleiben.


## Die Online-Studis hören nicht, was die Präsenz-Studis sagen

Hauptproblem für mich ist, die Online- und die Präsenz-Studis gleichmäßig in den Unterricht einzubinden. Wie schafft man es, dass die Online-Studis hören, wenn die Präsenz-Studis was sagen?
Das Problem ist, wenn die Präsenz-Studis kein Mikro haben, dann werden sie von den Online-Studis nicht gehört, es sei denn, sie sind nahe an meinem (Dozenten-)Mikro, was meistens nicht funktioniert.

Einfachste Lösung: Als Dozent wiederholt man, was ei Präsenz-Studi gerade gesagt hat, so dass die Online-Studis es mitkriegen. Keine tolle Lösung,
klappt aber einigermaßen, solange man wenig wiederholen muss.

Schöner wäre vermutlich ein Teilnehmer-Mikro, 
das auch mit Zoom verbunden ist.
Das werde ich demnächst mal ausprobieren.



Hat ei Präsenz-Studi einen längeren Redebeitrag, etwa um das Ergebnis einer Arbeitsgruppe vorzustellen, so mache ich das via Zoom. 
Die oder der betreffende Studi wählt sich bei Zoom ein und spricht dann über das Laptop-Mikro, so dass es alle Online-Studie mitkriegen.
Beim Präsentieren kann der/die Studie den Bildschirm teilen, so dass  die Online-Studis den geteilten Inhalt sehen.
Gleichzeitig zeige ich meinen Laptop-Bildschirm mit Zoom über den Beamer,
so dass auch die Präsenz-Studis den geteilten Inhalt sehen.



## Echo

Die oben beschriebene Lösung kann zu einem unschönen Problem führen: Echo.
Das Echo entsteht (glaube ich), wenn der Ton (z.B. aus einem Laptop-Lautsprecher) in ein Mikro kommt, von meinem Laptop oder über den Laptop eines Studis, sofern diese Person in die Zoom-Session eingeloggt ist.
Unschön! Was zu tun?

Eine einfache, aber nicht perfekte Lösung ist, einfach alle Lautsprecher der mit Zoom verbundenen Laptops auszuschalten (und die zugehörigen Mikros).
Dann gibt es kein Echo.

Hier wäre wieder das Teilnehmer-Mikro eine gute Sache.    

## An die Tafel schreiben geht nicht


Anstelle eines Tafelanschriebs kritzel ich auf mein iPad (mit dem Apple Pen),
das kann man einfach in Zoom teilen. 
Über den Beamer sieht man meinen Zoom-Bildschirm,
der die Kritzel-App zeigt.
Ich nutze zum Kritzeln Apps (am iPad) wie GoodNotes, Mac Notizen oder Miro.

Miro hat den Vorteil, 
dass man den Inhalt einfach über einen Link teilen kann,
ohne dass man etwas hochladen/einstellen muss,
was umständlicher wäre.

Ich hatte auch mal ein einfaches [Intuos-Grafik-Tablett von Wacom](https://www.wacom.com/de-de/products/pen-tablets/wacom-intuos) (S) benutzt,
das hat zwar auch was,
aber mit dem blind malen kam ich nicht so gut zurecht;
das Intuos-Pad hat kein Display,
sondern nur eine rezeptive Fläche, auf der man mit dem Stift schreibt. Das Pad erfasst den Stift genau, das ist gut (und das Pad ist günstig), aber wie gesagt,
blind malen ist nicht einfach (angeblich lernt man es schnell, aber hat bei mir nur bedingt geklappt).

Gut wiederum am Intuos-Pad ist, dass es technisch gesehen für den Computer einfach eine Art Maus ist. Sprich: Man kann es gut am Computer nutzen bzw. an den Apps am Computer wie Miro oder ConceptBoard.

Und wenn man das iPad nutzt, muss man es auch dabei haben bzw. mitschleppen. Und hat ein weiteres Gerät (gefühlt das hundertste), das man nach der Vorlesung nicht vergessen darf, einzupacken.

Aber insgesamt nutze ich das iPad lieber, zumindest aktuell.


# Fazit

Das Streaming ist aktuell für viele Module eine wichtige Sache,
und es gibt verschiedene Möglichkeiten zur Umsetzung.
Was ich hier vorgestellt habe, ist eine der einfachsten Wege,
 sicherlich nicht perfekt, aber praktikabel.
 







