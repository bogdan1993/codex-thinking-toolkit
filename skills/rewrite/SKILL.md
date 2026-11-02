---
name: rewrite
description: "Rescrie un material existent după obiectiv, ton și public, păstrând sensul și datele corecte."
metadata:
  version: "1.0.0"
---

# rewrite

## Activare și limite
Folosește la `$rewrite`, la convenția conversațională `/REWRITE` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
text existent; opțional obiectiv, ton, public, lungime și limbă. Parametrii pot fi exprimați în limbaj natural.

## Flux
Păstrează sensul și informațiile corecte. Adaptează structura și formularea la scop, ton și public. Nu introduce modificări factuale nejustificate; semnalează ambiguitățile care schimbă sensul. Dacă originalul lipsește, cere-l. La cereri de voce personală folosește mostrele sau profilul de autor disponibil; nu presupune existența unui skill extern anume.

## Outputuri
text rescris utilizabil direct. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$rewrite Rescrie acest email într-un ton cald și concis: [text].`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
