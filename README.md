# Codex Thinking Toolkit — Română

## Testat în ChatGPT Cloud

Instalat și testat într-un cont ChatGPT real la **2 noiembrie 2026**, cu instrucțiuni de Project și biblioteca de comenzi încărcată. Au trecut verificările reprezentative: acces la surse, cele cinci verdicte VERIFY, creșterea 80 → 100 = 25%, NECONFIRMAT pentru o afirmație fără dovezi, comparație și recomandare condiționată în limitele bugetului, plus REWRITE fără original, care a cerut textul lipsă.

Acesta este un test real al unor workflow-uri selectate, nu un benchmark al tuturor celor 20 de moduri. Adaptarea Claude nu a fost testată într-un cont Claude real. Vezi [scopul testelor](docs/CLOUD_TESTS.md).

## Variante cloud: Claude și ChatGPT

| Platformă | Configurare | Pachet de încărcat |
|---|---|---|
| Claude cloud / Claude Code | [Ghid Claude](adapters/claude/README.md) | [thinking-toolkit-ro.zip](https://github.com/bogdan1993/codex-thinking-toolkit/raw/refs/heads/main/adapters/claude/thinking-toolkit-ro.zip) |
| ChatGPT Cloud Projects | [Ghid ChatGPT](adapters/chatgpt/README.md) | [Pachet ChatGPT](https://github.com/bogdan1993/codex-thinking-toolkit/raw/refs/heads/main/adapters/chatgpt/thinking-toolkit-ro-chatgpt.zip) |

În Claude ai un skill cu 20 de moduri documentate. În ChatGPT ai instrucțiuni de proiect și biblioteca de comenzi încărcată. Pachetele cloud sunt separate de instalatorul local Codex. Citește ghidul înainte de upload; încărcarea întregului repository nu înseamnă instalare. Adaptarea ChatGPT a fost testată într-un cont real; pentru Claude, testarea live rămâne neefectuată.

**20 de skill-uri combinabile pentru cercetare, gândire critică, decizii, planificare și comunicare.** Fiecare comandă poate fi folosită separat sau împreună cu cele relevante pentru sarcină.

[Ediția în engleză](https://github.com/bogdan1993/codex-thinking-toolkit-en). Creat de **Bogdan Pădurariu împreună cu Codex**. Licență MIT. Proiect independent, fără afiliere oficială cu OpenAI.

## Instalare

Necesită Codex cu acces la fișiere locale și **Python 3.10+** pentru instalator. Instalatorul și testele folosesc doar biblioteca standard Python. Cercetarea, navigarea și producerea artefactelor folosesc instrumentele disponibile în sesiunea Codex.

```bash
git clone https://github.com/bogdan1993/codex-thinking-toolkit.git
cd codex-thinking-toolkit
python3 install.py --check
python3 install.py
```

Destinația implicită este `$CODEX_HOME/skills`, cu fallback la `~/.codex/skills`. Poți alege altă locație suportată:

```bash
python3 install.py --dest /cale/absoluta/skills --check
python3 install.py --dest /cale/absoluta/skills
```

`--check` nu scrie nimic. Instalatorul compară fișierele cu manifestul SHA-256, verifică toate destinațiile înainte de copiere, păstrează instalările identice și refuză suprascrierea skill-urilor diferite. Dacă o copiere eșuează, elimină numai directoarele nou create. Hash-urile detectează modificări accidentale; nu reprezintă semnături ale autorului.

După instalare, începe un chat nou sau reîmprospătează descoperirea skill-urilor dacă este necesar. Folosește `$analyze`, `$verify` etc. Aliasurile `/ANALYZE` sunt text conversațional; instalatorul nu înregistrează comenzi slash native.

**Alege o singură ediție pentru aceeași locație de instalare.** Ambele folosesc aceleași 20 de nume. Instalatorul semnalează conflictul dacă există o altă ediție sau un skill modificat. Păstrează o copie ori mută tu directoarele vechi înainte de schimbare; nu există suprascriere forțată. Pentru o selecție individuală, poți copia manual doar directoarele dorite din `skills/`.

## Comenzi

| Invocare | Scop | Exemplu |
|---|---|---|
| `$master` | Coordonează etapele necesare | Coordonează analiza și decizia pe baza datelor atașate. |
| `$research` | Cercetează cu surse citite | Compară dovezile din două rapoarte. |
| `$fresh` | Verifică actualitatea și datele | Verifică dacă informațiile despre această versiune mai sunt actuale. |
| `$verify` | Verifică afirmații și calcule | Verifică dacă o creștere de la 80 la 100 înseamnă 25%. |
| `$source-check` | Evaluează credibilitatea și independența | Verifică dacă trei articole repetă același comunicat. |
| `$expert-lens` | Aplică perspective disciplinare | Analizează adoptarea AI tehnic și organizațional. |
| `$analyze` | Identifică relații și implicații | Analizează retenția fără a presupune cauzalitate. |
| `$assumptions` | Expune ipotezele și necunoscutele | Identifică ipotezele care pot schimba bugetul. |
| `$compare` | Compară după criterii comune | Compară alternativele cu bugetul și datele disponibile. |
| `$critique` | Evaluează critic și păstrează ce funcționează | Evaluează planul față de obiectivul declarat. |
| `$red-team` | Caută eșecuri plauzibile și măsuri | Testează planul dacă furnizorul devine indisponibil. |
| `$decide` | Formulează recomandarea argumentată | Alege dintre opțiuni respectând bugetul. |
| `$plan` | Stabilește etape, dependențe și acceptare | Planifică un workshop de două ore pentru 12 oameni. |
| `$next` | Prioritizează acțiunile următoare | Avem sala. Ce facem în continuare? |
| `$checklist` | Transformă cerințele în verificări | Creează lista de acceptare pentru un raport cu tabele. |
| `$optimize` | Îmbunătățește baza existentă | Simplifică procesul păstrând pașii eficienți. |
| `$audience` | Adaptează la public | Explică autentificarea cu doi factori începătorilor. |
| `$rewrite` | Rescrie păstrând sensul | Rescrie emailul cald, fără angajamente noi. |
| `$content-suite` | Adaptează mesajul pentru mai multe canale | Creează o postare LinkedIn și un script scurt din aceeași idee. |
| `$brand` | Aplică identitatea documentată | Aplică ghidul de brand fără a inventa reguli. |

## Combinare

```text
$research $source-check Compară rapoartele și evaluează independența surselor.
$analyze $assumptions Explică rezultatul și ipotezele care îl pot schimba.
$compare $decide Compară opțiunile și recomandă una în limitele bugetului.
$plan $checklist Planifică workshopul și criteriile observabile de acceptare.
$rewrite $audience Adaptează emailul existent pentru un public fără experiență tehnică.
```

Folosește `$master` când coordonarea ajută; nu rulează automat toate cele 20 de skill-uri. Descrie rezultatul și constrângerile în limbaj obișnuit. Limba implicită este româna, dacă cererea sau contextul nu indică alta. Pachetul nu conține chei API, conturi sau corpus personal. Vocea și identitatea de brand pot fi furnizate ca inputuri, fără dependență de un skill extern anume.

## Verificare și limite

```bash
python3 -B -m unittest discover -s tests -v
python3 install.py --check --dest /cale/absoluta/skills-test
```

Testele automate acoperă instalarea, idempotenta, conflictele, revenirea după eșec, copierea Unicode, căile și integritatea surselor. [Scenariile de evaluare](docs/EVALUATION.md) descriu comportamentul de verificat într-o sesiune Codex reală. Validarea fișierelor nu demonstrează calitatea raționamentului. Workflow-urile nu garantează corectitudinea cercetării și nu oferă acces la surse indisponibile. Un plan sau o recomandare nu autorizează singure implementarea.

Pentru dezinstalare, salvează modificările și elimină doar directoarele instalate dorite. Instalatorul nu modifică configurația globală Codex. Instalează toate cele 20 de skill-uri și nu înlocuiește tacit nume existente.

## Structură și proveniență

- `skills/`: 20 de directoare independente cu instrucțiuni și licență.
- `manifest.json`: ediție, versiune, numele skill-urilor și hash-uri.
- `install.py`: instalator cu biblioteca standard.
- `tests/`: verificări automate ale instalării.
- `docs/EVALUATION.md`: scenarii comportamentale și limitele verificării release-ului.

Pachet extras din catalogul personal de comenzi al autorului și adaptat pentru utilizare independentă de proiect. Mostrele de voce, datele clienților și căile proiectelor private sunt excluse.
