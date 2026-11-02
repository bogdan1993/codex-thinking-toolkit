# Thinking Toolkit — command library

Citește numai secțiunile necesare cererii. Workflow-urile sunt activate de instrucțiunile proiectului, nu prin executarea aliasurilor.

# /MASTER

# master


## Inputuri
obiectiv, livrabil; opțional constrângeri, termen, resurse, skill-uri cerute. Parametrii pot fi exprimați în limbaj natural.

## Flux
Identifică rezultatul și criteriile de acceptare. Selectează etapele necesare și dependențele; nu rula toate comenzile automat. Citește modurile relevante din această bibliotecă, o singură dată per sarcină. Ordonează cercetare → verificare → analiză/comparație → decizie → implementare numai unde sunt necesare. Nu copia instrucțiunile subskill-urilor și nu reinvoca master prin ele. Reutilizează aceleași dovezi. Semnalează cerințele incompatibile. Livrează rezultatul cerut, dovezile executării și limitele.

## Outputuri
livrabilul cerut, decizii motivate și starea verificărilor. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/MASTER /ANALYZE Pregătește o decizie pe baza datelor atașate, fără cercetare externă.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /RESEARCH

# research


## Inputuri
întrebare; opțional domeniu, perioadă, surse, profunzime. Parametrii pot fi exprimați în limbaj natural.

## Flux
Delimitează întrebarea și ce dovezi ar schimba concluzia. Caută în materialele furnizate și în sursele relevante; folosește web când actualitatea sau cererea o impune. Citește sursele înainte de a le cita. Compară dovezile independente și explică dezacordurile. Separă rezultatele documentate de interpretări, ipoteze și estimări. O sursă indisponibilă sau un rezultat de căutare necitit nu este dovadă. Nu inventa surse, citate sau investigații.

## Outputuri
concluzii susținute prin trimiteri, incertitudini și goluri de dovezi. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/RESEARCH Compară dovezile din cele două rapoarte atașate.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /FRESH

# fresh


## Inputuri
afirmații sau material; opțional data de referință, interval, domeniu. Parametrii pot fi exprimați în limbaj natural.

## Flux
Stabilește data de referință din contextul utilizatorului. Identifică afirmațiile susceptibile schimbării. Verifică versiunea și sursa actuală, distingând publicare, actualizare, eveniment și accesare. Nu presupune că o pagină recent actualizată descrie un eveniment recent. Marchează informația învechită, fără a o elimina dacă are valoare istorică. Dacă accesul lipsește, spune ce actualitate nu poate fi verificată.

## Outputuri
informații actualizate, date relevante și limite. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/FRESH Verifică dacă prețurile din acest material mai sunt actuale.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /VERIFY

# verify


## Inputuri
afirmație, calcul sau material; opțional dovezi, data de referință. Parametrii pot fi exprimați în limbaj natural.

## Flux
Descompune afirmațiile verificabile. Recalculează valorile cu instrumente când este util; verifică unități, numitori și rotunjiri. Pentru fiecare afirmație folosește exact una dintre clasificări: CONFIRMAT, PARȚIAL CONFIRMAT, NECONFIRMAT, FALS, IMPOSIBIL DE VERIFICAT. NECONFIRMAT înseamnă dovezi insuficiente; FALS cere contradicție demonstrabilă; IMPOSIBIL DE VERIFICAT indică o limită concretă de acces/metodă. Explică dovezile, sursele și limitele; nu confunda absența dovezii cu falsitatea.

## Outputuri
afirmații, verdict, justificare și limite. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/VERIFY Verifică afirmația: o creștere de la 80 la 100 reprezintă 25%.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /SOURCE-CHECK

# source-check


## Inputuri
surse, linkuri sau afirmații cu surse; opțional scop și perioadă. Parametrii pot fi exprimați în limbaj natural.

## Flux
Inspectează autorul, proveniența, metoda, competența relevantă, data și legătura cu afirmația. Preferă sursa primară disponibilă. Caută interese financiare/instituționale și dependențe între surse: republicarea aceluiași comunicat nu este confirmare independentă. Semnalează sursele secundare slabe și afirmațiile fără suport. Popularitatea nu dovedește validitatea. Nu acuza conflicte de interese fără dovezi; distinge conflict documentat de posibilitate.

## Outputuri
evaluare pe sursă și impact asupra concluziei. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/SOURCE-CHECK Evaluează dacă aceste trei articole oferă dovezi independente.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /EXPERT-LENS

# expert-lens


## Inputuri
problemă; opțional discipline, scop, context. Parametrii pot fi exprimați în limbaj natural.

## Flux
Selectează numai specializările care schimbă înțelegerea problemei. Aplică întrebările și criteriile fiecărei discipline, apoi arată convergențele, diferențele și consecințele practice. Prezintă perspective analitice, fără a pretinde consultarea unor specialiști reali. Marchează unde lipsa expertizei sau a dovezilor limitează concluzia.

## Outputuri
perspective distincte și sinteză. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/EXPERT-LENS Analizează adoptarea AI din perspectiva organizațională și tehnică.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /ANALYZE

# analyze


## Inputuri
problemă, material sau date; opțional obiectiv, ipoteze. Parametrii pot fi exprimați în limbaj natural.

## Flux
Separă observațiile verificabile de interpretări. Descompune problema, urmărește relații și posibile mecanisme, identifică tipare și anomalii. Tratează cauzele ca posibile până când dovezile permit mai mult; corelația singură nu stabilește cauzalitate. Construiește concluzii proporționale cu datele și explică incertitudinile importante.

## Outputuri
analiză structurată și implicații susținute. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/ANALYZE Explică ce se poate deduce din aceste date de retenție.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /ASSUMPTIONS

# assumptions


## Inputuri
plan, argument sau problemă; opțional dovezi și constrângeri. Parametrii pot fi exprimați în limbaj natural.

## Flux
Identifică presupunerile explicite și implicite. Clasifică informațiile: Fapte confirmate, Ipoteze, Estimări, Necunoscute, Condiții care trebuie validate. Arată pentru fiecare presupunere importantă influența asupra concluziei și o modalitate proporțională de validare. Nu transforma o estimare plauzibilă în fapt.

## Outputuri
registru de presupuneri cu impact și validare. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/ASSUMPTIONS Identifică ipotezele acestui buget.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /COMPARE

# compare


## Inputuri
alternative; opțional criterii, ponderi, date și constrângeri. Parametrii pot fi exprimați în limbaj natural.

## Flux
Stabilește criterii comune potrivite obiectivului și folosește aceleași unități și perioade. Prezintă avantaje, dezavantaje, compromisuri, riscuri și diferențe materiale. Un tabel este util dacă simplifică comparația. Nu inventa date și ponderi; marchează valorile lipsă și sensibilitatea rezultatului. Nu favoriza arbitrar o alternativă.

## Outputuri
comparație echitabilă și limite. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/COMPARE Compară A la 100 lei și B la 150 lei, pentru un buget maxim de 120 lei.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /CRITIQUE

# critique


## Inputuri
material existent; opțional scop, public, criterii. Parametrii pot fi exprimați în limbaj natural.

## Flux
Evaluează față de scop, nu față de preferințe arbitrare. Identifică slăbiciuni, erori, inconsistențe, omisiuni și probleme de claritate; indică locul și consecința. Păstrează explicit elementele eficiente. Prioritizează îmbunătățiri concrete și proporționale. Nu inventa defecte pentru a umple o listă.

## Outputuri
constatări prioritizate și îmbunătățiri. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/CRITIQUE Evaluează planul atașat față de obiectivul declarat.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /RED-TEAM

# red-team


## Inputuri
soluție sau ipoteză; opțional domeniu, limite și resurse. Parametrii pot fi exprimați în limbaj natural.

## Flux
Caută scenarii plauzibile de eșec, vulnerabilități, riscuri ascunse, situații-limită și efecte nedorite. Explică mecanismul și condițiile în care recomandarea devine invalidă. Separă riscul demonstrat de scenariul ipotetic. Propune reducerea riscului, semnale timpurii și riscul rezidual. O analiză adversarială nu autorizează teste intruzive sau acțiuni externe.

## Outputuri
scenarii, condiții de invalidare și măsuri. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/RED-TEAM Testează planul dacă furnizorul principal devine indisponibil.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /DECIDE

# decide


## Inputuri
decizie, opțiuni și dovezi; opțional criterii și constrângeri. Parametrii pot fi exprimați în limbaj natural.

## Flux
Recomandă alegerea susținută de dovezi și obiectiv. Explică de ce este preferabilă, compromisurile, riscurile rămase și informația nouă care ar schimba recomandarea. Dacă datele nu permit o alegere, dă o recomandare condiționată sau propune obținerea informației decisive. Nu prezenta incertitudinea ca certitudine și nu confunda recomandarea cu autorizarea executării.

## Outputuri
recomandare, motivare și condiții de revizuire. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/DECIDE A costă 100, B 150, bugetul este 120. Recomandă o variantă.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /PLAN

# plan


## Inputuri
obiectiv; opțional termen, resurse, responsabilități, constrângeri. Parametrii pot fi exprimați în limbaj natural.

## Flux
Definește etape, dependențe, resurse, priorități, criterii de acceptare și riscuri. Folosește estimări marcate ca estimări; nu inventa disponibilitatea persoanelor. Arată ce poate începe acum și ce depinde de o decizie sau resursă. Nu transforma o cerere de plan în autorizare pentru implementare.

## Outputuri
plan executabil proporțional cu sarcina. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/PLAN Planifică un workshop de două ore pentru 12 manageri.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /NEXT

# next


## Inputuri
obiectiv și stare curentă; opțional blocaje, termen și resurse. Parametrii pot fi exprimați în limbaj natural.

## Flux
Alege acțiuni realizabile, prioritizate după impact, urgență, dependențe și efort. Formulează fiecare acțiune cu obiect concret și rezultat observabil. Dacă lipsește contextul, cere numai informația care schimbă prima acțiune sau indică o ipoteză explicită. Evită sfaturile generice și nu reface inutil un plan complet.

## Outputuri
următoarele acțiuni în ordine utilă. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/NEXT Avem sala, dar nu avem încă agenda sau invitațiile. Ce urmează?`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /CHECKLIST

# checklist


## Inputuri
cerințe sau proces; opțional etapă, responsabil și dovezi. Parametrii pot fi exprimați în limbaj natural.

## Flux
Extrage cerințele fără a adăuga obligații necerute. Formulează fiecare element astfel încât un evaluator să poată decide realizat/nerealizat și să știe dovada necesară. Separă condițiile opționale de cele obligatorii. Nu bifa elemente fără dovezi și nu confunda existența unui fișier cu acceptarea rezultatului.

## Outputuri
listă verificabilă cu criteriu pentru fiecare element. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/CHECKLIST Creează lista de acceptare pentru un PDF cu diacritice și tabele.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /OPTIMIZE

# optimize


## Inputuri
material sau sistem EXISTENT; opțional obiectiv, metrici și constrângeri. Parametrii pot fi exprimați în limbaj natural.

## Flux
Inspectează baza existentă și identifică ce funcționează. Îmbunătățește structura, claritatea, eficiența, persuasiunea sau experiența în funcție de obiectiv. Evită reconstruirea inutilă și modificările gratuite. Nu adăuga fapte neverificate. Explică modificările principale și efectul urmărit; un beneficiu anticipat nu este un rezultat măsurat. Dacă baza lipsește, cere-o; nu inventa un original.

## Outputuri
versiune îmbunătățită și modificări motivate. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/OPTIMIZE Simplifică textul atașat, păstrând mesajul și datele.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /AUDIENCE

# audience


## Inputuri
conținut sau strategie și public; opțional scop, context, obiecții. Parametrii pot fi exprimați în limbaj natural.

## Flux
Identifică nevoile, experiența, limbajul, contextul și obiecțiile publicului. Adaptează nivelul explicațiilor, exemplele și structura. Dacă publicul nu este definit, cere informația relevantă sau declară ipoteza folosită. Nu modifica faptele pentru atractivitate și nu trata stereotipuri drept caracteristici dovedite.

## Outputuri
adaptare potrivită publicului și ipoteze relevante. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/AUDIENCE Explică autentificarea cu doi factori unui public fără experiență tehnică.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /REWRITE

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

# /CONTENT-SUITE

# content-suite


## Inputuri
idee sau material; opțional canale, scop, public, brand, lungimi. Parametrii pot fi exprimați în limbaj natural.

## Flux
Stabilește mesajul comun și rolul fiecărui canal. Adaptează distinct unghiul, structura, hook-ul, lungimea, tonul, CTA-ul și formatul; CTA poate fi omis când scopul o cere. Nu multiplica mecanic același text. Nu inventa experiențe sau date pentru variație. Dacă lipsesc canalele, propune o selecție explicită și proporțională. Când este cerută vocea personală, folosește mostrele sau profilul de autor disponibil.

## Outputuri
pachet pe canale cu coerență editorială. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/CONTENT-SUITE Creează o postare LinkedIn și un Reel despre feedback.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.

# /BRAND

# brand


## Inputuri
material și documentație de brand; opțional canal, public și scop. Parametrii pot fi exprimați în limbaj natural.

## Flux
Identifică documentația oficială disponibilă și versiunea sa, folosind sursele furnizate. Aplică regulile vizuale, verbale și strategice relevante și verifică consecvența. Nu inventa culori, fonturi, logo-uri sau reguli oficiale. Distinge valori extrase, reguli explicite și propuneri. Dacă lipsesc sursele, cere-le sau livrează o propunere etichetată, fără a o numi identitate oficială. Pentru livrabile specializate precum PDF, folosește un workflow adecvat disponibil. Când este cerută vocea personală, folosește profilul sau mostrele furnizate și semnalează contradicțiile materiale cu cerințele brandului.

## Outputuri
material consecvent și abateri/limite documentate. Respectă formatul și limba cerute; implicit română dacă nu există alt context.

## Informații incomplete și compunere
Cere doar informația lipsă care schimbă material rezultatul; continuă partea independentă și marchează ipotezele. Nu declara acțiuni, acces, verificări sau rezultate neefectuate. Combină skill-urile în ordinea logică a sarcinii, reutilizează dovezile și nu iniția bucle. Cercetarea externă se face numai când este necesară sau cerută. Nu trimite, publica, instala ori modifica resurse externe pe baza simplei activări a acestui skill; respectă autorizarea sarcinii.

## Exemplu
`/BRAND Aplică ghidul atașat prezentării, păstrând datele.`

## Acceptare
Outputul îndeplinește fluxul de mai sus, păstrează restricțiile și distinge faptele, interpretările, estimările și recomandările unde sunt relevante. Verifică rezultatul, nu doar existența unui fișier.
