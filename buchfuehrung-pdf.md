---
context-lang: @(Projekt.contextlang)
title: @(Projekt.title)
subtitle: @(Projekt.subtitle)
cover: @(Projekt.cover)
date: @(Monat[heute.month].MMMM) @(heute.year)
git: @(GetShortGITHash "")
author: @(Autor.name)
---

# Einleitung<!--{**-->
@include "einleitung.md"
<!--**}-->

# System und Technik der Buchführung<!--{**-->
@include "inventur.md"
<!--**}-->

# Organisation der Buchführung<!--{**-->

## Buchführungspflicht


## Ordnungsmäßige Buchführung


## Bücherarten


## Belegorganisation
<!--**}-->

# Laufende Geschäftsfälle<!--{**-->

## Die Umsatzsteuer bei Ein- und Verkauf


## Buchungen im Warenverkehr



## Buchungen im Personalbereich
@include "personal.md"
<!--**}-->
