# Claude — RO

## Claude cloud

Activează execuția de cod/crearea fișierelor dacă sunt necesare în cont. Deschide Customize > Skills, adaugă/creează un skill, alege Upload a skill și încarcă **thinking-toolkit-ro.zip** din acest director. Activează skill-ul. Nu încărca arhiva întregului repository. Cere: „Folosește thinking-toolkit-ro, modul verify: o creștere de la 80 la 100 este 25%?” Toate cele 20 de workflow-uri sunt într-un skill cu referințe; nu apar 20 de comenzi cloud separate.

## Claude Code (local, opțional)

Copiază folderul **thinking-toolkit-ro** în `~/.claude/skills/` (personal) sau în `.claude/skills/` din proiect. Păstrează directoarele existente diferite și salvează o copie înainte de a înlocui o ediție veche. Invocă `/thinking-toolkit-ro verify ...` sau alt mod. Numele distinct al toolkitului evită coliziunea cu comenzile native precum /plan. Această copiere nu instalează skill-ul în sesiunile cloud; pentru cloud folosește încărcarea în cont.

## Sources and verification

Checked 2026-11-02: [Use Skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude), [Create custom skills](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills), [Claude Code skills](https://code.claude.com/docs/en/skills).

The ZIP contains one skill folder at its root, with SKILL.md, all 20 references and LICENSE. Local packaging checks verify content, reference links and reproducibility. Account upload, invocation and model behavior have not been tested live. Tool availability and organization policy can affect use.
