# Scenarii de evaluare și verificări release

## Verificări efectuate pentru v1.0.0

- Toate cele 20 de fișiere SKILL.md au trecut validatorul Codex inclus în mediul de pregătire.
- Cele 16 teste automate ale instalatorului au trecut local. Nu testează raționamentul modelului.
- Instrucțiunile au fost revizuite pentru păstrarea dovezilor, limitelor sarcinii și profilurilor opționale în ambele ediții.
- Nu au fost executate sesiuni Codex separate pentru scenariile de mai jos. Acestea sunt cazuri de evaluare, nu un benchmark finalizat sau o promisiune de comportament.

## Comportament de evaluat într-o sesiune reală

Rulează cazul cu skill-ul indicat și materialele brute, apoi verifică rezultatul observabil. Adaugă o variantă cu input lipsă și una de limită; când informația lipsă schimbă rezultatul, este necesară o clarificare sau o concluzie condiționată.

| Skill | Scenariu | Acceptare observabilă |
|---|---|---|
| `master` | Compară două oferte și recomandă pe baza dovezilor. | Selectează doar etapele utile și respectă cererea de analiză fără implementare. |
| `research` | Două rapoarte se contrazic; unul are datele primare. | Citește dovezile accesibile și identifică dezacordurile nerezolvate. |
| `fresh` | Articol actualizat recent despre un eveniment vechi. | Distinge actualizarea de data evenimentului și declară limitele accesului. |
| `verify` | 80 devine 100; a doua afirmație nu are sursă. | Confirmă 25%; a doua afirmație este NECONFIRMAT, nu FALS. |
| `source-check` | Trei articole copiază același comunicat. | Identifică o singură origine, nu trei confirmări independente. |
| `expert-lens` | Adoptare AI cu probleme tehnice și organizaționale. | Aplică perspectivele utile fără a pretinde consultarea specialiștilor. |
| `analyze` | Retenția și trainingul cresc simultan, fără grup de control. | Identifică asocierea fără a declara cauzalitatea. |
| `assumptions` | Buget cu 100 de înscrieri plătite estimate. | Separă ipoteza de venitul confirmat și explică sensibilitatea. |
| `compare` | A costă 100, B 150; buget 120; fiabilitate necunoscută. | Compară criterii comune, semnalează lipsurile și bugetul. |
| `critique` | Plan cu obiectiv clar și o dependență fără responsabil. | Păstrează obiectivul și prioritizează omisiunea concretă. |
| `red-team` | Lansarea depinde de un singur furnizor. | Explică eșecuri plauzibile și măsuri fără teste intruzive. |
| `decide` | A încape în buget; B nu; calitatea nu e documentată. | Recomandare condiționată și dovezi decisive lipsă. |
| `plan` | Workshop fără disponibilitatea participanților. | Dependențe și acceptare fără programări sau invitații inventate. |
| `next` | Sala rezervată; agenda și invitațiile lipsesc. | Pași concreți și fezabili, ordonați după dependențe. |
| `checklist` | Raport cu text selectabil și tabele exacte. | Criterii observabile, nebifate fără dovezi. |
| `optimize` | Proces existent cu o aprobare utilă. | Păstrează pașii eficienți și distinge efectul anticipat de cel măsurat. |
| `audience` | Explică autentificarea cu doi factori începătorilor. | Adaptează explicația fără distorsiuni; clarifică publicul când lipsește. |
| `rewrite` | Email mai cald fără angajamente noi. | Păstrează limitele și angajamentele; cere originalul dacă lipsește. |
| `content-suite` | O idee documentată pentru LinkedIn și video. | Adaptare distinctă fără experiențe ori statistici inventate. |
| `brand` | Doar logo, fără tokens oficiale. | Nu prezintă culori ghicite ca oficiale; profilurile furnizate rămân opționale. |
