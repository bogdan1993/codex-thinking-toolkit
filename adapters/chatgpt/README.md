# Utilizare în ChatGPT Cloud Projects

1. Creează sau deschide un Project în ChatGPT.
2. Copiază conținutul PROJECT_INSTRUCTIONS.md în instrucțiunile proiectului. Simpla încărcare a acestui fișier nu configurează instrucțiunile.
3. Adaugă COMMANDS.md în Sources/fișierele proiectului.
4. Deschide un chat nou în proiect și încearcă `/VERIFY Verifică dacă o creștere de la 80 la 100 înseamnă 25%.`.
5. Cere un rezultat cu date reale. Dacă biblioteca nu poate fi recuperată, atașează direct secțiunea necesară.

Poți folosi și un chat obișnuit: lipește instrucțiunile și atașează biblioteca pentru conversația respectivă. Pachetul nu instalează un plugin, nu înregistrează slash commands și nu modifică personalizarea globală. Nu rula instalatorul Python pentru adaptarea cloud. Capabilitățile contului și politicile workspace-ului determină accesul la web, analiză și crearea fișierelor. Workflow-urile nu oferă instrumente ori permisiuni noi.

Nu sunt incluse corpus personal sau credențiale. Păstrează și reconciliază instrucțiunile relevante deja existente ale proiectului. Alege o singură ediție lingvistică pentru același proiect.

Bază oficială de configurare, verificată la 2026-11-02: [ChatGPT Projects](https://learn.chatgpt.com/docs/projects). Instrucțiunile proiectului configurează comportamentul; biblioteca încărcată oferă workflow-urile. Adaptarea a fost instalată și testată într-un Project ChatGPT real la 2 noiembrie 2026. Accesul la bibliotecă și scenariile reprezentative au fost verificate în cont. Testele automate ale pachetului nu demonstrează calitatea generală a raționamentului sau funcționarea fiecărui workflow.

## Scopul testului live — 2 noiembrie 2026

Instrucțiunile proiectului au fost salvate și COMMANDS.md a fost încărcat în Sources. VERIFY, COMPARE și DECIDE au fost testate pe date fictive; REWRITE a cerut originalul când acesta lipsea. Acesta nu este un test individual al tuturor celor 20 de moduri. Adaptarea Claude rămâne netestată într-un cont Claude real.
