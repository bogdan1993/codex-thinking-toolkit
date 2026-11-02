---
name: expert-lens
description: "Analizează o problemă prin discipline relevante și explică acordurile și tensiunile dintre perspective."
metadata:
  version: "1.0.0"
---

# expert-lens

## Activare și limite
Folosește la `$expert-lens`, la convenția conversațională `/EXPERT-LENS` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
problemă; opțional discipline, scop, context. Parametrii pot fi exprimați în limbaj natural.

## Flux
Selectează numai specializările care schimbă înțelegerea problemei. Aplică întrebările și criteriile fiecărei discipline, apoi arată convergențele, diferențele și consecințele practice. Prezintă perspective analitice, fără a pretinde consultarea unor specialiști reali. Marchează unde lipsa expertizei sau a dovezilor limitează concluzia.

## Outputuri
perspective distincte și sinteză. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$expert-lens Analizează adoptarea AI din perspectiva organizațională și tehnică.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
