---
name: checklist
description: "Transformă cerințe în elemente verificabile cu criterii clare de finalizare."
metadata:
  version: "1.0.0"
---

# checklist

## Activare și limite
Folosește la `$checklist`, la convenția conversațională `/CHECKLIST` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
cerințe sau proces; opțional etapă, responsabil și dovezi. Parametrii pot fi exprimați în limbaj natural.

## Flux
Extrage cerințele fără a adăuga obligații necerute. Formulează fiecare element astfel încât un evaluator să poată decide realizat/nerealizat și să știe dovada necesară. Separă condițiile opționale de cele obligatorii. Nu bifa elemente fără dovezi și nu confunda existența unui fișier cu acceptarea rezultatului.

## Outputuri
listă verificabilă cu criteriu pentru fiecare element. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$checklist Creează lista de acceptare pentru un PDF cu diacritice și tabele.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
