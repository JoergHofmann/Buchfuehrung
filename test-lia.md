<!--
author: @(Autor.name)
email: @(Autor.mail)
language: @(Projekt.shortlang)
version: @(GetShortGITHash "")
-->

<!-- style = "h1 {color: blue}" -->
# @(Projekt.title)

@(Autor.name)

@(Autor.mail)@(br)

Git: @(GetShortGITHash "")

## Aufgaben

@include "lernzielkontrolle.md"
