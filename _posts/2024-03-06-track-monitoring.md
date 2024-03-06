---
layout: post
title: Was bedeutet eigentlich Track Monitoring?
date: 2024-03-06 14:27 +0100
author: lei
toc: false
---

Betreiber von Eisenbahninfrastruktur (EIU) müssen regelmäßig den Zustand ihrer Infrastruktur überprüfen, um die Sicherheit und Zuverlässigkeit des Bahnsystems sicherstellen zu können. Aufgrund der Komplexität des Bahnsystems gibt es viele Dinge, die zu überwachen sind (Oberleitung, Sicherungstechnik, Fahrweg, ...). Der Aufwand die Eisenbahninfrastruktur zu überwachen ist dementsprechend hoch und daher personal- und kostenintensiv. Es bedarf daher neue Lösungen, welche mit Hilfe von Sensortechnik den Inspektionsprozess so weit wie möglich automatisieren, so dass ein Instandhalter Maßnahmen rechtzeitig planen kann, ohne dafür explizit die Infrastruktur begehen oder Messzüge lossschicken zu müssen. Solche Lösungen werder daher gemeinhin auch als **Track Monitoring** Lösungen bezeichnet.

Im Rahmen von Smart.TRAM wird eine Track Monitoring Lösung entwickelt, mit welcher sich der Zustand via Smartphone überwachen lässt. Dabei kommen die im Smartphone verbauten Sensoren zum Einsatz (u.A. Beschleunigungsaufnehmer und GNSS). Das Smartphone wird im Fahrerstand platziert und nimmt kontiniuierlich Daten auf, welche in einer Cloud-Plattform verarbeitet werden. Ziel ist es Fehler im Fahrweg über die Zeit aufzunehmen und bewerten zu können. Abbildung 1 zeigt wie ein Fehler in einem Streckenabschnitt typischerweise über die Zeit anwachsen kann. Werden Schwellwerte erreicht, müssen Instandhaltungsmaßnahmen eingeplant werden. Der stetige Einblick in dieses Fehlerwachstum erlaubt dem Instandhalter den Zeitpunkt kostenoptimal zu wählen. 

![monitoring](/assets/img/monitoring.png){: w="500" h="400" }
_Abb. 1: Beobachtung des Fehlerwachstums über die Zeit_

Über mehrere Jahre hinweg kann der Fahrwegzustand wie in Abb. 2 gezeigt dargestellt werden. Nach jeder Instandhaltungsmaßnahme ist der Fahrweg in der Regel wieder in seinem optimal Zustand.
Je nach Art des Oberbaus kann allerdings nach mehreren Zyklen der Optimalzustand nicht wieder hergestellt werden und umfangreiche Erneuerung des Fahrwegs ist erforderlich. Zum Beispiel durch einen kompletten Schotter und Schienentausch.
![instandhaltungszyklus](/assets/img/instandhaltung.png){: w="500" h="400" }
_Abb. 2: Zyklischer Prozess des Fehlerwachstums unter Einbezug von Instandhaltungsmaßnahmen_
Im Vorhaben Smart.TRAM soll dieser Zyklus durch die Messdaten kontinuierlich sichtbar gemacht werden. Idealerweise so, dass wie in Abb. 3 gezeigt auch eine Prognose des Fehlerwachtstums erfolgen kann. Mit Hilfe der Prognose sollen Maßnahmen frühzeitig geplant werden können. Außerdem erlaubt sie die rechtzeitige Abschätzung von notwendigen Investionen in die Infrastruktur.

![instandhaltungszyklus](/assets/img/prognose.png){: w="500" h="400" }
_Abb. 3: Fehlerwachstum mit Prognose_
