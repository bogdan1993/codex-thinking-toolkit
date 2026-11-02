# rewrite


## Inputuri
text existent; opțional obiectiv, ton, public, lungime și limbă. Parametrii pot fi exprimați în limbaj natural.

## Flux
Păstrează sensul și informațiile corecte. Adaptează structura și formularea la scop, ton și public. Nu introduce modificări factuale nejustificate; semnalează ambiguitățile care schimbă sensul. Dacă originalul lipsește, cere-l. La cereri de voce personală folosește mostrele sau profilul de autor disponibil; nu presupune existența unui skill extern anume.

## Outputuri
text rescris utilizabil direct. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/REWRITE Rescrie acest email într-un ton cald și concis: [text].`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
