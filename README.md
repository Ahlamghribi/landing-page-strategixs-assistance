<div align="center">

```
███████╗████████╗██████╗  █████╗ ████████╗███████╗ ██████╗ ██╗██╗  ██╗
██╔════╝╚══██╔══╝██╔══██╗██╔══██╗╚══██╔══╝██╔════╝██╔════╝ ██║╚██╗██╔╝
███████╗   ██║   ██████╔╝███████║   ██║   █████╗  ██║  ███╗██║ ╚███╔╝ 
╚════██║   ██║   ██╔══██╗██╔══██║   ██║   ██╔══╝  ██║   ██║██║ ██╔██╗ 
███████║   ██║   ██║  ██║██║  ██║   ██║   ███████╗╚██████╔╝██║██╔╝ ██╗
╚══════╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝   ╚══════╝ ╚═════╝ ╚═╝╚═╝  ╚═╝
```

**`ASSISTANCE · FRANCE`**

<br/>

*Two landing pages. Two identities. One brand.*

<br/>

![HTML](https://img.shields.io/badge/HTML5-pure-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-animated-1572B6?style=flat-square&logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-3D-000000?style=flat-square&logo=three.js&logoColor=white)
![Status](https://img.shields.io/badge/status-production_ready-00C8FF?style=flat-square)
![France](https://img.shields.io/badge/France-🇫🇷-blue?style=flat-square)

</div>

---

## `// WHO IS STRATEGIX`

**Strategix Assistance** est une entreprise française spécialisée dans le **déblocage administratif**. Face à un système préfectoral opaque, des délais d'instruction interminables et une plateforme ANEF souvent défaillante, Strategix intervient comme tiers de confiance pour des milliers de personnes en France.

L'entreprise opère à deux niveaux :

- **Cabinet d'assistance administrative** — accompagnement direct des personnes bloquées dans leurs démarches préfectorales, ANEF, Démarches Simplifiées et recours juridiques
- **Entité de conseil stratégique** — positionnement premium auprès de fondateurs, dirigeants et entreprises en croissance qui ont besoin d'une vision et d'une exécution sans compromis

Ces deux réalités coexistent. Ces deux pages les incarnent.

---

## `// THE WORK`

Ce repository contient **deux landing pages** conçues de zéro — sans framework, sans CMS, sans template. Chaque ligne de code a été écrite avec une intention précise : convertir, impressionner, et incarner l'identité de Strategix.

<br/>

### `[ PAGE 01 ]` — Strategix Assistance
**`page 1.html`**

```
IDENTITÉ  →  Cabinet administratif · Aide aux personnes bloquées
PALETTE   →  Cyber Blue  #1A2EFF · Neon Cyan #00C8FF · Deep Dark #04060F
TYPO      →  Poppins 300–900 · Hiérarchie brutale · Lisibilité maximale
MOOD      →  SaaS Dashboard · Interface outil · Confiance institutionnelle
```

Une page construite pour **convaincre en 8 secondes**. L'utilisateur qui arrive ici est stressé, bloqué, à bout. Le design absorbe cette urgence et la transforme en clarté : *"vous êtes au bon endroit, voici comment on règle ça."*

**Ce qui la rend différente :**
- Carte 3D interactive en hero avec **parallax réactif à la souris**
- Particules connectées en canvas — toile de fond vivante
- Dashboard ANEF simulé avec barres de progression animées
- Timeline de traitement dossier animée en temps réel
- Accordion FAQ avec transitions fluides
- Compteurs qui s'incrémentent au scroll (`95%` · `1500+` · `<30j`)
- Anneaux pulsants en CTA final — tension visuelle calculée

<br/>

### `[ PAGE 02 ]` — Strategix
**`page2 .html`**

```
IDENTITÉ  →  Consulting premium · Dirigeants · Croissance ambitieuse
PALETTE   →  Deep Black #070707 · Liquid Gold #C9A84C · Ivory #F0ECE3
TYPO      →  Syne 800 · Instrument Serif italic · Space Mono — trio signature
MOOD      →  Luxury Editorial · Dark Futurism · McKinsey × Maison de couture
```

Une page qui ne cherche pas à plaire à tout le monde — elle cherche à **arrêter les bonnes personnes**. Ceux qui la voient et ressentent *"c'est exactement où je veux être"*.

**Ce qui la rend différente :**
- **Scène 3D hero** — icosaèdre en wireframe doré, 4 anneaux orbitaux, octaèdres flottants, champ de particules. Tout réagit à la position de la souris en temps réel
- **Scène 3D showcase** — cube métallique avec inner cube contra-rotatif, 7 sphères en orbite, grille 3D animée, rayons de coins
- Curseur personnalisé doré avec lag physique et expand au hover
- Loading screen avec barre de progression
- Marquee ticker — rythme éditorial
- Titre hero avec animation slide-up décalée par mot
- Révélations au scroll avec easing cubic-bezier précis

---

## `// TECHNICAL PHILOSOPHY`

```
Zéro framework.  Zéro dépendance npm.  Zéro build step.
```

Tout est écrit en **HTML · CSS · JS vanilla** avec Three.js chargé via CDN. Ce choix n'est pas une contrainte — c'est une décision architecturale.

- **Performance** : pas de bundle, pas d'overhead. Le navigateur charge une seule ressource.
- **Maintenabilité** : n'importe quel développeur ouvre le fichier et comprend immédiatement.
- **Portabilité** : double-clic → le site tourne. Partout. Toujours.
- **Contrôle total** : chaque pixel, chaque milliseconde d'animation, chaque courbe de Bézier est explicitement définie.

---

## `// DESIGN SYSTEM`

Les deux pages partagent des principes de design communs tout en ayant des identités visuelles radicalement opposées — c'est voulu.

```
┌─────────────────────────────────────────────────────────────┐
│                    SHARED PRINCIPLES                        │
│                                                             │
│  • Curseur personnalisé sur les deux pages                  │
│  • Scroll reveal avec IntersectionObserver                  │
│  • Animations CSS cubic-bezier — pas de librairie           │
│  • Variables CSS — cohérence et thémabilité                 │
│  • Canvas interactif — fond vivant réactif                  │
│  • Responsive mobile-first — breakpoints chirurgicaux       │
│                                                             │
└─────────────────────────────────────────────────────────────┘

┌──────────────────────────┐  ┌──────────────────────────────┐
│      PAGE 1 — BLUE       │  │       PAGE 2 — GOLD          │
│                          │  │                              │
│  Poppins — sans-serif    │  │  Syne — geometric display    │
│  Grids utilitaires       │  │  Layouts asymétriques        │
│  Glassmorphism cards     │  │  Clip-path polygonaux        │
│  Neon glow effects       │  │  Grain texture overlay       │
│  Dashboard UI language   │  │  Editorial white space       │
│  Bleu → confiance légale │  │  Or → excellence rare        │
└──────────────────────────┘  └──────────────────────────────┘
```

---

## `// PROJECT STRUCTURE`

```
landing-page-strategixs-assistance/
│
├── page 1.html          ← Strategix Assistance — Cabinet administratif
│   ├── Particules canvas connectées
│   ├── Carte 3D hero parallax
│   ├── Sections features avec dashboards
│   ├── Grilles services + témoignages + FAQ
│   └── CTA final avec anneaux pulsants
│
├── page2 .html          ← Strategix — Consulting premium
│   ├── Three.js Hero Scene (icosaèdre + anneaux + particules)
│   ├── Three.js Showcase Scene (cube + orbites + grille)
│   ├── Loader animé
│   ├── Stats + Services + Process + Testimonial
│   └── CTA + Footer
│
└── README.md            ← You are here
```

---

## `// RUN LOCALLY`

```bash
git clone https://github.com/Ahlamghribi/landing-page-strategixs-assistance.git
cd landing-page-strategixs-assistance

# C'est tout. Ouvrir dans le navigateur.
open "page 1.html"      # macOS
start "page 1.html"     # Windows
xdg-open "page 1.html"  # Linux
```

Aucune installation. Aucun `npm install`. Aucun serveur.

---

## `// BROWSER COMPATIBILITY`

```
Chrome  ✓   Firefox  ✓   Safari  ✓   Edge  ✓
WebGL required for Three.js 3D scenes (page 2)
```

---

<div align="center">

---

```
Fait pour Strategix Assistance · France · 2026
Chaque ligne écrite avec intention.
```

</div>
