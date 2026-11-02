---
name: analyze
description: "Descompune probleme și date pentru a identifica relații, tipare, anomalii și implicații."
metadata:
  version: "1.0.0"
---

# analyze

## Activare și limite
Folosește la `$analyze`, la convenția conversațională `/ANALYZE` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
problemă, material sau date; opțional obiectiv, ipoteze. Parametrii pot fi exprimați în limbaj natural.

## Flux
Separă observațiile verificabile de interpretări. Descompune problema, urmărește relații și posibile mecanisme, identifică tipare și anomalii. Tratează cauzele ca posibile până când dovezile permit mai mult; corelația singură nu stabilește cauzalitate. Construiește concluzii proporționale cu datele și explică incertitudinile importante.

## Outputuri
analiză structurată și implicații susținute. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$analyze Explică ce se poate deduce din aceste date de retenție.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
