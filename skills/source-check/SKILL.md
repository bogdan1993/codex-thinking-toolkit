---
name: source-check
description: "Evaluează credibilitatea și independența surselor unui material sau ale unei cercetări."
metadata:
  version: "1.0.0"
---

# source-check

## Activare și limite
Folosește la `$source-check`, la convenția conversațională `/SOURCE-CHECK` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
surse, linkuri sau afirmații cu surse; opțional scop și perioadă. Parametrii pot fi exprimați în limbaj natural.

## Flux
Inspectează autorul, proveniența, metoda, competența relevantă, data și legătura cu afirmația. Preferă sursa primară disponibilă. Caută interese financiare/instituționale și dependențe între surse: republicarea aceluiași comunicat nu este confirmare independentă. Semnalează sursele secundare slabe și afirmațiile fără suport. Popularitatea nu dovedește validitatea. Nu acuza conflicte de interese fără dovezi; distinge conflict documentat de posibilitate.

## Outputuri
evaluare pe sursă și impact asupra concluziei. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$source-check Evaluează dacă aceste trei articole oferă dovezi independente.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
