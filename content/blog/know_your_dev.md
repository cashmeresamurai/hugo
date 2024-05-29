+++
title = 'Know your developer (KYD)'
date = 2024-05-29T15:11:45Z
draft = true
+++

# Know your developer

Wie bei einem Know your Customer Verfahren (kurz KYC), gibt es hier ein kurzes Know your developer (KYD)
Ich möchte hier kurz darauf eingehen, was ich aktuell für ein Techstack verwende und was ich hier in dem Blog hauptsächlich thematisieren möchte.

## About me

Ich bin 23 Jahre alt und studiere aktuell in Hamburg Computer Science mit Nebenschwerpunkt Digitale Forensik/Cyber Security.
Ich war schon von klein auf immer technisch versiert, jedoch kam das Interesse an der Informatik erst durch das Studium.
Das Themenfeld, was mich aber die ganze Zeit begleitet hat, war schon immer die Automatisierung.
Ich fande es immer sehr spannend wie man alltägliche routine Aufgaben so optimieren kann, dass sie komplett von alleine stattfinden können. Am besten noch Parallel.

## Tech Stack

Ich programmiere meine Projekte hauptsächlich in Rust und Python. Für Frontend nutze ich aktuell Tauri als Frontend mit Vanilla Javascript/Typescript, HTML und PicoCSS.

## Deployment und Hosting

Deployment und Hosting tue ich es meist selbst durch auf gemietete Linux VPS und Docker.
Das hat den Vorteil, dass ich Kosten sparen kann, direkten Zugriff auf die Maschine habe, falls intensivere Änderungen nötig sind und ich lerne dabei über die verschiedensten Projekte von Aufsetzung bis zur Bereitstellung

## Programmierumgebung

Ich programmiere am Liebsten auf Linux. Im Endeffekt kann man überall programmieren, aber mir persönlich gefällt die Nutzung des Terminals dort am Besten.
Wenn für die Entwicklung Windows benötigt wird, nutze ich meist die Developer Version von Windows 11 in einer virtuellen Maschine (wird direkt von Microsoft bereitgestellt)

### Werdegang durch die verschiedene Programmiersprachen

Durch mein Studium, habe ich mit Python angefangen.
Ich empfand Python wie ein Freizeitpark für die verschiedensten Bereiche.
Von Automatisierung, API's, Web Development, bishin zu künstlicher Intelligenz kann man fast schon alles damit machen.
Ich dachte mehr als Python würde ich nicht brauchen. Dennoch hatte ich immer im Hinterkopf, dass es auch andere Programmiersprachen gibt und diese auch ihre Daseinsberechtigung haben.
So entschloss ich mich erstmal die nächsten Monate sehr tiefgründig mit Python zu arbeiten, sämtliche Projekte ausprobieren (wenn möglich auch fertigstellen^^), und die Stärken und Schwächen kennenlernen.

#### Pythons Stärken und Schwächen

Die Stärken von Python habe ich ja bereits aufgezählt.

- einfach und schnell zu erlenende Syntax
- Eine riesengroße Community mit unzähligen Libraries
- Sehr gut um sehr schnell was zu _skripten_

Die Schwächen von Python

- Code zu Binary zu compilen nicht möglich
- Finden von logischen Fehlern erst bei Runtime
- Das Deployen von Code erfordert immer die Installation von Python

Das waren meine persönlichen Punkte, warum ich Python sehr wertschätze, ich aber eine Programmiersprache lernen wollte, die aber vor allem compiled werden kann.
Vieler meiner Codes deploye ich auf Linux VPS und die Installation von Python, eine virtuelle Umgebung zu kreieren, die Pakete zu installieren etc. machens dann oft sehr mühselig damit zu arbeiten.
Vor allem ist das Senden eines Programms für meine Kunden, die ein run and go Prinzip haben möchten, mit Python nicht zu erreichen.
Bash oder .bat Skripte, ist meiner Meinung nach auch keine Lösung. Falls es zu Fehlern kommen sollte (von seitens Python aus), wissen sie oft nicht was zu machen ist.

### Willkommen zu Rust

Rust ist das gefühlte Gegenteil von Python. Darauf werde ich auch noch in den kommenden Blogeinträgen näher eingehen.
So viel soll aber dazu gesagt sein. Ja, es ist eine static Low Level Language, die länger braucht zum programmieren als z.B. Python oder Javascript.
Das schöne und tolle ist jedoch, wenn einmal das Programm compiled wurde, läuft es auch.
Man kann es für wirklich fast alle Betriebssystem compilen.
Frontends durch Tauri, sind auch möglich, sehen sehr gut aus und die Binaries bleiben dennoch klein.
Es werden viel weniger Ressourcen verschwendet als bei Python und die Type Safety sind die Gründe für mich, warum ich aktuell meine nächsten Projekte in Rust schreiben werde.

Was ich schade finde ist, dass Rust einen Ruf hat um gefühlt nur Betriebssysteme oder Programme für Embedded Systems damit schreiben zu sollen.
Dabei Kann es wirklich weitaus mehr.
Klar die Bibliotheken sind nicht umfangreich, wie Javascript oder Python, aber alles was ich bis jetzt benötigt hatte, habe ich auch in einer Form finden können (auch wenn in einer Lite Version :D)

### Meine Zukunft mit der Programmierung

Auch wenn ich viel in der Backend- und Softwareentwicklung sehe, ist ein grundlegendes Know How für GUI's und Frontend dennoch wichtig.
Durch HTML, CSS und Javascript (ich bevorzuge Typescript) ist das entwickeln von Frontends für Cross Plattform einfacher geworden.
Das solle man sich auch als Entwickler nicht entgehen.

## Ciao Abhängigkeit von Cloud Computing, Hallo Linux und Docker!
