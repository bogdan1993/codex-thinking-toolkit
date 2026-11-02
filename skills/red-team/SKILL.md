---
name: red-team
description: "Testează adversarial ipoteze și soluții pentru scenarii de eșec, limite și efecte nedorite."
metadata:
  version: "1.0.0"
---

# red-team

## Activare și limite
Folosește la `$red-team`, la convenția conversațională `/RED-TEAM` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
soluție sau ipoteză; opțional domeniu, limite și resurse. Parametrii pot fi exprimați în limbaj natural.

## Flux
Caută scenarii plauzibile de eșec, vulnerabilități, riscuri ascunse, situații-limită și efecte nedorite. Explică mecanismul și condițiile în care recomandarea devine invalidă. Separă riscul demonstrat de scenariul ipotetic. Propune reducerea riscului, semnale timpurii și riscul rezidual. O analiză adversarială nu autorizează teste intruzive sau acțiuni externe.

## Outputuri
scenarii, condiții de invalidare și măsuri. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$red-team Testează planul dacă furnizorul principal devine indisponibil.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
