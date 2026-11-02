---
name: critique
description: "Evaluează critic materiale, planuri și argumente, păstrând elementele care funcționează."
metadata:
  version: "1.0.0"
---

# critique

## Activare și limite
Folosește la `$critique`, la convenția conversațională `/CRITIQUE` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
material existent; opțional scop, public, criterii. Parametrii pot fi exprimați în limbaj natural.

## Flux
Evaluează față de scop, nu față de preferințe arbitrare. Identifică slăbiciuni, erori, inconsistențe, omisiuni și probleme de claritate; indică locul și consecința. Păstrează explicit elementele eficiente. Prioritizează îmbunătățiri concrete și proporționale. Nu inventa defecte pentru a umple o listă.

## Outputuri
constatări prioritizate și îmbunătățiri. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$critique Evaluează planul atașat față de obiectivul declarat.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
