---
layout: post
title: Umsetzung
subtitle: Wie wurde der digitale Escape Room umgesetzt?
thumbnail-img: /assets/img/er_architecture_v3.png
tags: [implementation, framework]
---

In unserem Fall ist die Lerntechnologie der digitale Escape Room. Und dieser wiederum hat die Förderung der Kenntnisse zur Erstellung von Programmen mit der Programmiersprache Java zum Ziel. Der Digital Escape Room wurde von uns programmiert und umfasst folgende Komponenten:

![Framework](/assets/img/er_architecture_v3.png){: .mx-auto.d-block :}

## Frontend Applikation

Dabei handelt es sich um eine Java-basierte graphische Anwendung, die die Studierenden durch den Escape Room geleitet und in der auch die Rätsel und Programmieraufgaben gelöst werden müssen. Das Grundgerüst dieser Applikation wurde den Studierenden via Download zur Verfügung gestellt.

## Backend Applikation 
Die Frontend Applikation wird via Backend Services mit Daten (Texte, Bilder, Hinweise) versorgt und registriert und verwaltet den Fortschritt der einzelnen Teams. Damit wird auch sichergestellt, dass einzelne Tasks nicht übersprungen werden können.

## Leaderboard
In einer Single Page Application, die ebenfalls auf die Backend Services zurückgreift, werden den Studierenden laufend die besten Teams präsentiert, wobei die Teams nicht wissen wer in welchem Team (außer dem eigenen) ist. Somit wird der kompetitive Charakter des Escape Rooms in den Vordergrund gerückt und die Motivation der Studierende erhöht. Zusätzlich wurden die fünf besten Teams mit Preisen gekürt.
