---
name: next
description: "Identifică și prioritizează următoarele acțiuni concrete pornind de la starea curentă."
metadata:
  version: "1.0.0"
---

# next

## Activare și limite
Folosește la `$next`, la convenția conversațională `/NEXT` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
obiectiv și stare curentă; opțional blocaje, termen și resurse. Parametrii pot fi exprimați în limbaj natural.

## Flux
Alege acțiuni realizabile, prioritizate după impact, urgență, dependențe și efort. Formulează fiecare acțiune cu obiect concret și rezultat observabil. Dacă lipsește contextul, cere numai informația care schimbă prima acțiune sau indică o ipoteză explicită. Evită sfaturile generice și nu reface inutil un plan complet.

## Outputuri
următoarele acțiuni în ordine utilă. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$next Avem sala, dar nu avem încă agenda sau invitațiile. Ce urmează?`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
