---
name: research
description: "Realizează cercetare aprofundată cu dovezi, surse citite și concluzii comparate; pentru întrebări care cer investigare."
metadata:
  version: "1.0.0"
---

# research

## Activare și limite
Folosește la `$research`, la convenția conversațională `/RESEARCH` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
întrebare; opțional domeniu, perioadă, surse, profunzime. Parametrii pot fi exprimați în limbaj natural.

## Flux
Delimitează întrebarea și ce dovezi ar schimba concluzia. Caută în materialele furnizate și în sursele relevante; folosește web când actualitatea sau cererea o impune. Citește sursele înainte de a le cita. Compară dovezile independente și explică dezacordurile. Separă rezultatele documentate de interpretări, ipoteze și estimări. O sursă indisponibilă sau un rezultat de căutare necitit nu este dovadă. Nu inventa surse, citate sau investigații.

## Outputuri
concluzii susținute prin trimiteri, incertitudini și goluri de dovezi. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$research Compară dovezile din cele două rapoarte atașate.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
