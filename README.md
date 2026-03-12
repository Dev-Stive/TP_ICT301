# Cahier de Texte Digital - Projet ICT301 - Groupe G7

## 📋 Vue d'ensemble

Ce projet constitue une **Analyse et Conception Logicielle** complète d'un **Cahier de Texte Digital** pour les établissements scolaires. Le livrable est un rapport technique en LaTeX permettant aux développeurs de commencer le codage immédiatement.

## 👥 Composition de l'Équipe

| # | Nom et Prénom | Matricule | Rôle |
|---|---|---|---|
| 1 | NANA TCHOFFO STEVE JUNIOR | 23U2402 | **Chef de Groupe** - Infrastructure & Introduction |
| 2 | DINA KAMENI JOYCE CARELLE | 23U2293 | **Analyste Fonctionnel** - Cas d'utilisation |
| 3 | MOUTENG REBECCA ESTHER | 25G2079 | **Responsable Qualité** - Besoins non-fonctionnels |
| 4 | MONDJO NZUKAM VANELLE SANDRA | 25I2283 | **Architecte Données** - Modèle de données |
| 5 | FEUDJIO TSAGUE LAETICIA | 25I2170 | **Architecte Composants** - Architecture logicielle |
| 6 | NANYOU GILLES RAYMOND | 232351 | **Architecte Comportement** - Diagrammes de séquence + Conclusion |

## 📁 Structure des Fichiers

```
Project/
├── main.tex                          # Fichier racine (compilez CECI)
├── 00_Couverture/
│   ├── page_garde.tex               # Page de garde premium
│   └── membres_contributions.tex     # Tableau des rôles et contributions
├── NANA/
│   ├── task.tex                     # Instructions détaillées pour NANA
│   ├── intro.tex                    # À COMPLÉTER : Introduction
│   ├── existant.tex                 # À COMPLÉTER : Étude existant
│   └── infrastructure.tex           # À COMPLÉTER : Architecture technique
├── DINA/
│   ├── task.tex                     # Instructions détaillées pour DINA
│   └── analyse_fonctionnelle.tex    # À COMPLÉTER : Cas d'utilisation
├── MOUTENG/
│   ├── task.tex                     # Instructions détaillées pour MOUTENG
│   └── besoins_non_fonctionnels.tex # À COMPLÉTER : Attributs de qualité
├── MONDJO/
│   ├── task.tex                     # Instructions détaillées pour MONDJO
│   └── conception_structurelle.tex  # À COMPLÉTER : Modèle de données
├── FEUDJIO/
│   ├── task.tex                     # Instructions détaillées pour FEUDJIO
│   └── conception_architecturale.tex # À COMPLÉTER : Architecture composants
├── NANYOU/
│   ├── task.tex                     # Instructions détaillées pour NANYOU
│   ├── conception_comportementale.tex # À COMPLÉTER : Diagrammes séquence
│   └── conclusion.tex               # À COMPLÉTER : Conclusion générale
└── README.md                         # Ce fichier

```

## 🎯 Étapes pour Chaque Membre

### Pour NANA TCHOFFO STEVE JUNIOR (Chef)
1. Lisez attentivement `/NANA/task.tex` - contient **toutes les ressources** pour vos 3 fichiers
2. Complétez les fichiers :
   - `intro.tex` - Introduction au projet
   - `existant.tex` - Étude critique du système papier
   - `infrastructure.tex` - Architecture technique 3-tiers
3. Utilisez **TikZ** pour les diagrammes (voir exemples dans task.tex)
4. Vérifiez que tout compile sans erreur

### Pour DINA KAMENI JOYCE CARELLE (Analyse Fonctionnelle)
1. Lisez attentivement `/DINA/task.tex` - guide complet avec ressources
2. Complétez `/DINA/analyse_fonctionnelle.tex` :
   - Acteurs identifiés
   - Cas d'utilisation (UC-1 à UC-30)
   - Diagramme UML de cas d'utilisation
   - Scénarios critiques
3. Format : Suivez les exemples dans task.tex (très détaillés)

### Pour MOUTENG REBECCA ESTHER (Qualité)
1. Lisez attentivement `/MOUTENG/task.tex` - exigences non-fonctionnelles
2. Complétez `/MOUTENG/besoins_non_fonctionnels.tex` :
   - Attributs de qualité (Sécurité, Disponibilité, Performance, etc.)
   - Tableau récapitulatif avec métriques
   - Contraintes (technologiques, réglementaires)
   - Trade-offs et résolutions

### Pour MONDJO NZUKAM VANELLE SANDRA (Données)
1. Lisez attentivement `/MONDJO/task.tex` - modèle de données complet
2. Complétez `/MONDJO/conception_structurelle.tex` :
   - Description de chaque entité (Utilisateur, Classe, Matière, Séance, Devoir, Absence)
   - Tableau des relations et cardinalités
   - Diagramme E-R (entité-relation) avec TikZ
   - Schéma relationnel formel
   - Justification de la normalisation (3NF)

### Pour FEUDJIO TSAGUE LAETICIA (Composants)
1. Lisez attentivement `/FEUDJIO/task.tex` - architecture modulaire
2. Complétez `/FEUDJIO/conception_architecturale.tex` :
   - 10 composants identifiés (Auth, Users, Structure, Cahier, Devoirs, Absences, Rapports, Persistance, Audit, Notifications)
   - Pour chaque : responsabilités, interfaces (fournies/requises)
   - Diagramme de composants UML avec TikZ
   - Matrice de dépendances
   - Patterns architecturaux (Repository, Service Layer, etc.)

### Pour NANYOU GILLES RAYMOND (Comportement + Conclusion)
1. Lisez attentivement `/NANYOU/task.tex` - diagrammes et conclusion
2. Complétez `/NANYOU/conception_comportementale.tex` :
   - 5 scénarios critiques (saisie séance, consultation, validation, absences, rapports)
   - Diagrammes de séquence UML avec TikZ
   - Chronologies détaillées (happy path + alternatives)
   - Gestion des erreurs
3. Complétez `/NANYOU/conclusion.tex` :
   - Synthèse complète du projet
   - Récapitulatif de l'architecture
   - Avantages de la solution
   - Recommandations pour le développement (phases, risques, métriques)
   - Extensions futures

## 📝 Format à Respecter

### Structure LaTeX Standard
Chaque fichier doit utiliser la structure suivante :
```latex
\chapter{Titre du Chapitre}

\section{Section Principale}
Texte...

\subsection{Sous-section}
Texte...

\subsubsection{Sous-sous-section}
Texte...
```

### Diagrammes avec TikZ
Les diagrammes doivent être créés avec TikZ directement dans LaTeX (voir exemples dans `/NANA/infrastructure.tex`).

### Tableaux
Utilisez `tabularx` ou `xltabular` pour les tableaux (voir exemples dans les fichiers existants).

## 🔧 Comment Compiler

### Prérequis
- LaTeX complet (TeXLive, MiKTeX, ou MacTeX)
- Compilateur : `pdflatex` ou `xelatex`

### Compilation Simple
```bash
cd Project/
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex  # 2 fois pour TOC
```

### Résultat
Génère un fichier `main.pdf` - c'est votre **livrable final** à soumettre.

## ✅ Checklist avant Soumission

- [ ] Tous les fichiers `task.tex` sont remplis (guides complets pour chaque membre)
- [ ] Tous les fichiers contenu (`intro.tex`, `analyse_fonctionnelle.tex`, etc.) sont complétés
- [ ] Le document compile sans erreur (zéro erreur pdflatex)
- [ ] Table des matières correcte (page i, ii, iii...)
- [ ] Tous les diagrammes sont visibles et clairs (TikZ fonctionne)
- [ ] Page de garde affiche correctement les noms et matricules
- [ ] Pas de texte « À COMPLÉTER » en italique (sauf dans les task.tex)
- [ ] Principes SOLID respectés dans les conceptions (SRP, DIP, etc.)
- [ ] Architecture « quoi faire » vs « comment faire » - spécifications uniquement, pas de code
- [ ] Bibliographie remplie avec références cours (Bass, Clements, Kazman, etc.)

## 🎨 Principes de Rédaction

1. **Clarté** : Expliquez chaque concept sans jargon excessif
2. **Complétude** : Ne laissez rien de vague, spécifiez
3. **Pas de code** : Aucune ligne de code (C#, SQL, HTML, etc.) - uniquement spécifications
4. **Diagrammes** : Utilisez UML standard (cas d'utilisation, classes, composants, séquence, déploiement)
5. **Justification** : Justifiez chaque décision architecturale
6. **Cohérence** : Terminologie uniforme dans tout le document

## 📚 Ressources Fournies

Chaque dossier contient un fichier `task.tex` avec :
- ✅ Objectifs clairs
- ✅ Description détaillée de ce qui doit être fait
- ✅ **TOUTES les ressources complètes** (données, entités, cas d'utilisation, etc.)
- ✅ Format attendu
- ✅ Principes SOLID à respecter
- ✅ Recommandations pour la qualité

**Lisez attentivement votre task.tex - tout ce dont vous avez besoin y est déjà !**

## 🏁 Date de Remise

**13 Mars 2025** - Préparez votre document PDF (`main.pdf`) pour soumission.

## 💡 Conseils Finaux

1. **Commencez tôt** - 3 jours c'est juste pour un travail de qualité
2. **Séparez les tâches** - Chacun travaille en parallèle
3. **Testez la compilation** - Compilez régulièrement pour détecter les erreurs
4. **Relisez** - Orthographe, grammaire, clarté
5. **Coordonnez** - Utilisez une terminologie commune (ex: toujours « séance », pas « cours »)
6. **Ne codez pas** - Vous documentez une architecture, pas une application

---

**Bon courage au Groupe G7 ! 🚀**

Pour questions sur la structure ou les ressources, consultez le fichier `task.tex` de votre rôle.