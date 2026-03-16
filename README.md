# 🏴‍☠️ Coding Pirates Denmark — Repository Naming Guidelines

Velkommen til **Coding Pirates Denmark – Repository Naming Guidelines**.  

Dette dokument beskriver, hvordan repositories skal navngives i vores GitHub-organisation, så vi kan skabe en struktur, der er **overskuelig**, **genkendelig** og **nem at arbejde med** for både nye og erfarne frivillige.

Målet er, at alle projekter – uanset teknologi, hold, afdeling eller frivillig – følger en fælles standard, der gør det nemt at finde, søge og vedligeholde materialer.

---

# 📚 Table of Contents

1. [🧭 Formål](#-formål)
2. [⚡ Quick Start](#-quick-start)
3. [🏗️ Navngivningsprincipper](#️-navngivningsprincipper)
   1. [🟦 Kategoripræfikser](#-kategoripræfikser)
   2. [🟩 Underemner](#-underemner)
   3. [🟨 Projektnavn](#-projektnavn)
4. [🏷️ Topics](#️-topics)
5. [🧩 Eksempler på korrekte repo-navne](#-eksempler-på-korrekte-repo-navne)
6. [📝 Tjekliste inden du opretter et repo](#-tjekliste-inden-du-opretter-et-repo)
7. [📨 Forslag til nye kategorier?](#-forslag-til-nye-kategorier)
8. [🏁 Tak!](#-tak!) 

---

## 🧭 Formål

- Sikre en klar og ensartet repo-struktur  
- Gøre det lettere for frivillige at finde relevant materiale  
- Understøtte samarbejde på tværs af afdelinger  
- Skabe et professionelt og genkendeligt udtryk for hele organisationen  

---

## ⚡ Quick Start
Repos **skal** følge dette format, og tilføjes GitHub Topics:

- **Navngiv repoet efter formatet:**  
   `<kategori>-<underemne>-<projektnavn>`  
   _Eksempel: `games-pygame-platformer`_


Så vil du oprette et nyt repository? Så følg disse 4 hurtige trin:

1. **Brug et kategoripræfiks for emnet:**  
   _Eksempler: `games-`, `hardware-`, `web-`, `ai-`, `robotics-`, `resources-`, `templates-`, `admin-`, `org-`_

2. **Brug et underemne for teknologi eller platform:**  
   _Eksempler: `microbit-`, `pygame-`, `react-`, `arduino-`, `python-`_

3. **Brug et (kort) projektnavn**:
   _Eksempler: `streetfighter`, `platformer`, `sensor-kit`, `space-shooter`_

4. **Tilføj GitHub Topics:**  
   Mindst: `coding-pirates` + `<kategori>`  
   _Eksempel: `coding-pirates, games, pygame, python`_

👉 Detaljerede regler og eksempler finder du nedenfor.

---

# 🏗️ Navngivningsprincipper

Alle repositories skal følge denne struktur:

Hvor:

- **kategori**: overordnet fagområde  
- **underemne** (valgfrit): teknologi, sprog eller platform  
- **projekt**: titel eller formål  

Der bruges **små bogstaver**, **engelske ord** og **bindestreger** (`-`).  
Specialtegn, mellemrum og `/` må **ikke** bruges.

---

## 🟦 Kategoripræfikser

Hvert repo starter med et præfiks, der angiver emnet.

| Kategori | Præfiks | Typiske projekter |
|---------|---------|-------------------|
| Spiludvikling | `games-` | Pygame, Kaplay, Godot, Unity |
| Hardware & elektronik | `hardware-` | Micro:bit, Raspberry Pi, Arduino |
| Webudvikling | `web-` | HTML/CSS, JS, React |
| Robotter | `robotics-` | LEGO Mindstorms, robotarme |
| Kunstig intelligens | `ai-` | Python ML, ml5.js, vision |
| Undervisningsmaterialer | `resources-` | Slides, øvelser |
| Skabeloner | `templates-` | Standardprojekter |
| Organisationsdokumenter | `admin-` | Regler, struktur, guidelines |
| Organisation (fælles regler) | `org-` | Denne type repos |

> Kategorien **bestemmer ikke** permissions — kun navnet.

---

## 🟩 Underemner

Underemnet beskriver teknologien eller platformen.

Eksempler:

- `pygame`
- `kaplay`
- `godot`
- `microbit`
- `raspberrypi`
- `arduino`
- `htmlcss`
- `python`
- `js`
- `react`

Underemnet er **valgfrit**, men anbefales hvis det gør repoet lettere at forstå.

---

## 🟨 Projektnavn

Projektdelen beskriver projektets titel, fx:

- `streetfighter`
- `platformer`
- `space-shooter`
- `sensor-kit`
- `basic-site`
- `imageclassifier`

Hold det kort, klart og uden specialtegn.

---

# 🏷️ Topics

Når du opretter et nyt repository, skal du tilføje relevante **GitHub Topics**.  
Topics gør det nemmere for frivillige at:

- søge efter projekter inden for samme emne  
- filtrere materiale efter teknologi eller kategori  
- opdage relaterede undervisningsforløb  
- navigere i store mængder undervisningsmateriale  

Topics fungerer som metadata og skaber struktur *uden at være en del af repo-navnet*.

---

## 🎯 Obligatoriske Topics

Alle repos i Coding Pirates Denmark skal have følgende topics:

- `coding-pirates`
- `<kategori>` (fx `games`, `hardware`, `web`, `ai`, `robotics`, `resources`, `templates`, `admin`, `org`)

---

## 🎨 Valgfrie Topics

Du kan tilføje så mange relevante topics du vil, fx:

### Teknologier
- `python`
- `pygame`
- `kaplay`
- `godot`
- `unity`
- `javascript`
- `html`
- `css`
- `react`
- `microbit`
- `raspberry-pi`
- `arduino`
- `ml5js`

### Undervisningsniveau
- `beginner-friendly`
- `intermediate`
- `advanced`

### Indholdstype
- `lesson`
- `template`
- `example`
- `project`
- `exercise`
- `workshop`

---

## 🧪 Eksempler

### Eksempel 1: Pygame projekt
**Repo-navn:**  
`games-pygame-platformer`

**Topics:**

`coding-pirates`, `games`, `pygame`, `python`, `beginner-friendly`

### Eksempel 2: Micro:bit projekt
**Repo-navn:**  
`hardware-microbit-ledgame`

**Topics:**

`coding-pirates`, `hardware`, `microbit`, `lesson`, `beginner-friendly`

### Eksempel 3: React website
**Repo-navn:**  
`web-react-clicker-game`

**Topics:**
`coding-pirates`, `web`, `react`, `javascript`, `project`

---

# 🧩 Eksempler på korrekte repo-navne

### 🎮 Spiludvikling

```
games-kaplay-streetfighter
games-pygame-platformer-template
games-godot-space-shooter
```

### 🔌 Hardware

```
hardware-microbit-intro
hardware-raspberrypi-sensor-kit
hardware-arduino-robotarm
```

### 🌐 Web

```
web-htmlcss-beginners
web-js-dom-intro
web-react-clicker-game
```

### 🤖 AI

```
ai-python-imageclassifier
ai-ml5js-vision-demo
```

### 📚 Ressourcer

```
resources-lesson-templates
resources-teacher-guide
```

### 🛠️ Organisation & skabeloner

```
org-repo-naming
admin-organization-handbook
templates-project
```

---

# 📝 Tjekliste inden du opretter et repo

1. Har du valgt korrekt **kategori-præfiks**?
2. Har du valgt et relevant **underemne**?
3. Er **projektnavnet** kort og klart?
4. Er navnet **kun med små bogstaver og bindestreger**?
5. Kan man se repoets formål ud fra navnet alene?
6. Har du tilføjet relevante **Topics**?

---

# 📨 Forslag til nye kategorier?

Hvis du mener, der mangler en kategori eller et navngivningsmønster, så:

1. Opret et Issue i dette repo  
2. Brug skabelonen **"New Naming Category Proposal"**  
3. Beskriv hvorfor kategorien bør tilføjes  

Vi udvikler strukturen i fællesskab — på ægte Coding Pirates-manér! 🏴‍☠️

---

# 🏁 Tak!

Spørgsmål eller forslag?  
Opret et Issue — eller fang os på Slack i kanalen kaldet `github-organisation` afhængigt af din lokale afdeling.


