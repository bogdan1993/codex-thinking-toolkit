---
name: fresh
description: "Verifică actualitatea informațiilor și diferența dintre data publicării, actualizării și evenimentului."
metadata:
  version: "1.0.0"
---

# fresh

## Activare și limite
Folosește la `$fresh`, la convenția conversațională `/FRESH` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
afirmații sau material; opțional data de referință, interval, domeniu. Parametrii pot fi exprimați în limbaj natural.

## Flux
Stabilește data de referință din contextul utilizatorului. Identifică afirmațiile susceptibile schimbării. Verifică versiunea și sursa actuală, distingând publicare, actualizare, eveniment și accesare. Nu presupune că o pagină recent actualizată descrie un eveniment recent. Marchează informația învechită, fără a o elimina dacă are valoare istorică. Dacă accesul lipsește, spune ce actualitate nu poate fi verificată.

## Outputuri
informații actualizate, date relevante și limite. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$fresh Verifică dacă prețurile din acest material mai sunt actuale.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
