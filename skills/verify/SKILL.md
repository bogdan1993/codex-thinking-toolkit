---
name: verify
description: "Verifică afirmații, calcule și concluzii, atribuind un verdict explicit pe baza dovezilor."
metadata:
  version: "1.0.0"
---

# verify

## Activare și limite
Folosește la `$verify`, la convenția conversațională `/VERIFY` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
afirmație, calcul sau material; opțional dovezi, data de referință. Parametrii pot fi exprimați în limbaj natural.

## Flux
Descompune afirmațiile verificabile. Recalculează valorile cu instrumente când este util; verifică unități, numitori și rotunjiri. Pentru fiecare afirmație folosește exact una dintre clasificări: CONFIRMAT, PARȚIAL CONFIRMAT, NECONFIRMAT, FALS, IMPOSIBIL DE VERIFICAT. NECONFIRMAT înseamnă dovezi insuficiente; FALS cere contradicție demonstrabilă; IMPOSIBIL DE VERIFICAT indică o limită concretă de acces/metodă. Explică dovezile, sursele și limitele; nu confunda absența dovezii cu falsitatea.

## Outputuri
afirmații, verdict, justificare și limite. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$verify Verifică afirmația: o creștere de la 80 la 100 reprezintă 25%.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
