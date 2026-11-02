---
name: master
description: "Coordonează sarcini complexe cu mai multe etape, alegând numai cercetarea, analiza și execuția necesare."
metadata:
  version: "1.0.0"
---

# master

## Activare și limite
Folosește la `$master`, la convenția conversațională `/MASTER` sau când cererea corespunde clar descrierii. Slash-ul este text convențional, nu o comandă nativă nouă. Nu activa pe simpla apariție a termenului într-un document citat sau pentru o sarcină fără acest obiectiv.

## Inputuri
obiectiv, livrabil; opțional constrângeri, termen, resurse, skill-uri cerute. Parametrii pot fi exprimați în limbaj natural.

## Flux
Identifică rezultatul și criteriile de acceptare. Selectează etapele necesare și dependențele; nu rula toate comenzile automat. Citește skill-urile relevante din catalogul disponibil, o singură dată per sarcină. Ordonează cercetare → verificare → analiză/comparație → decizie → implementare numai unde sunt necesare. Nu copia instrucțiunile subskill-urilor și nu reinvoca master prin ele. Reutilizează aceleași dovezi. Semnalează cerințele incompatibile. Livrează rezultatul cerut, dovezile executării și limitele.

## Outputuri
livrabilul cerut, decizii motivate și starea verificărilor. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`$master $analyze Pregătește o decizie pe baza datelor atașate, fără cercetare externă.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
