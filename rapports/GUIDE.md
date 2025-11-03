# Memoire de Master sur CVaR

## 📋 Description

Ce projet contient les fichiers sources LaTeX pour une thèse de master portant sur la Conditional Value at Risk (CVaR). Le document est rédigé en français et utilise une structure modulaire pour faciliter la maintenance et la collaboration.

## 📁 Structure du Projet

```
rapports/
├── main.tex                    # Fichier principal du document
├── preamble.tex                # Preamble avec les modifications
├── logoGSU.png                 # Non-Modified Used in tex/figures
├── references.bib              # Non-Modified Used in tex/references
├── tex/                        # Dossier contenant tous les fichiers sources
│   ├── config/                 # Configurations et pages préliminaires
│   │   ├── preamble.tex       # Préambule avec tous les packages
│   │   ├── titlepage.tex      # Page de titre
│   │   ├── resume.tex         # Résumé en français
│   │   ├── abstract.tex       # Résumé en anglais
│   │   └── abreviations.tex   # Liste des abréviations
│   ├── chapitres/             # Chapitres du document
│   │   ├── introduction.tex
│   │   ├── chapitre1.tex
│   │   ├── chapitre2.tex
│   │   └── chapitre3.tex
│   ├── annexes/               # Annexes
│   │   └── annexeA.tex
│   ├── figures/               # Images et graphiques
│   └── references/            # Fichiers bibliographiques
│       └── references.bib
├── output/                     # Dossier pour les fichiers de sortie
└── README.md                   # Ce fichier
```
## 🚀 Compilation

### Méthode recommandée (avec latexmk)
```bash
latexmk -lualatex -outdir=output main.tex
```

## 📦 Prérequis

### Distribution LaTeX
- **Windows** : TeX Live (recommandé) ou MiKTeX
- **macOS** : MacTeX
- **Linux** : TeX Live

**Important** : Ce projet utilise **LuaLaTeX** pour le support natif UTF-8 et les polices OpenType via `fontspec`.

### Moteur de Compilation
- **LuaLaTeX** (utilisé par défaut)
- Alternative : XeLaTeX également compatible

