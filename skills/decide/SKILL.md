---
name: decide
description: "Transformă dovezile și comparația într-o recomandare argumentată, cu incertitudini explicite."
metadata:
  version: "1.0.0"
---

# decide

## Activare și limite
Folosește la `$decide`, la convenția conversațională `/DECIDE` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
decizie, opțiuni și dovezi; opțional criterii și constrângeri. Parametrii pot fi exprimați în limbaj natural.

## Flux
Recomandă alegerea susținută de dovezi și obiectiv. Explică de ce este preferabilă, compromisurile, riscurile rămase și informația nouă care ar schimba recomandarea. Dacă datele nu permit o alegere, dă o recomandare condiționată sau propune obținerea informației decisive. Nu prezenta incertitudinea ca certitudine și nu confunda recomandarea cu autorizarea executării.

## Outputuri
recomandare, motivare și condiții de revizuire. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$decide A costă 100, B 150, bugetul este 120. Recomandă o variantă.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
