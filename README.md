# Modélisation du Risque de Crédit & Analyse Prédictive

Ce dépôt contient un projet complet de **Data Science appliquée au risque de crédit**, réalisé dans le cadre d’un **stage en Data Science à la Banque de Tunisie**. Le projet couvre l’analyse exploratoire, la modélisation stochastique (chaînes de Markov), l’analyse de survie, ainsi que des modèles de machine learning pour la prédiction du risque.

---

## 📌 Contexte du projet

- **Auteur :** Emna Turki  
- **Période :** 1 juillet 2025 – 31 août 2025  
- **Département :** Gestion des Risques & Analyse de Données  
- **Objectif principal :** Modéliser et analyser le risque de crédit afin d’estimer les transitions de défaut, la perte de crédit attendue (ECL) et les comportements d’écoulement des soldes, tout en intégrant des approches prédictives.

---

## 🧠 Objectifs analytiques

- Analyser la distribution et l’évolution temporelle des **stages de crédit**
- Construire des **chaînes de Markov** et matrices de transition
- Valider statistiquement les transitions (test du Chi‑carré)
- Calculer la **Perte de Crédit Attendue (ECL)**
- Étudier les durées d’écoulement et d’annulation des soldes
- Appliquer des techniques d’**analyse de survie** (Kaplan‑Meier, modèles paramétriques, Weibull AFT)
- Estimer le risque via la **Value at Risk (VaR)**
- Développer des **modèles de Machine Learning** pour la prédiction du risque

---

## 📂 Contenu du dépôt

```
├── Projet_BT_COMPLET_FINAL.ipynb   # Notebook principal du projet
├── README.md                      # Documentation du projet
```

Le notebook contient l’intégralité du pipeline :
1. Chargement et préparation des données  
2. Analyse exploratoire (EDA)  
3. Modélisation du risque de crédit (Markov, ECL)  
4. Analyse de survie et modèles paramétriques  
5. Modélisation prédictive (Machine Learning)

---

## 📊 Sources de données

Le projet repose sur deux grandes sources de données internes (anonymisées) :

1. **Données de Risque de Crédit**  
   - Stages de crédit
   - Historique des transitions

2. **Données d’Écoulement**  
   - Soldes initiaux (`encours_debut_modif`)
   - Débits et crédits
   - Identifiants clients et périodes temporelles

---

## ⚙️ Méthodologies utilisées

- **Statistiques & Finance :**
  - Chaînes de Markov
  - Perte de Crédit Attendue (ECL)
  - Value at Risk (VaR)

- **Analyse de survie :**
  - Kaplan‑Meier
  - Modèles paramétriques
  - Weibull AFT (Accelerated Failure Time)

- **Machine Learning :**
  - Préparation des datasets
  - Entraînement et comparaison de plusieurs modèles prédictifs

---

## 🛠️ Technologies & librairies

- Python  
- pandas, numpy  
- matplotlib, seaborn  
- scikit‑learn  
- lifelines  
- scipy

*(La liste exacte des dépendances peut être déduite du notebook.)*

---

## ▶️ Exécution du projet

1. Cloner le dépôt :
```bash
git clone https://github.com/votre-utilisateur/votre-repo.git
```

2. Ouvrir le notebook :
```bash
jupyter notebook Projet_BT_COMPLET_FINAL.ipynb
```

3. Exécuter les cellules dans l’ordre pour reproduire l’analyse.

---

## 📈 Résultats clés

- Estimation robuste des probabilités de transition entre stages de crédit
- Calcul de l’ECL basé sur des approches stochastiques
- Analyse approfondie des comportements d’écoulement via l’analyse de survie
- Modèles prédictifs permettant une meilleure anticipation du risque

---

## ⚠️ Avertissement

Les données utilisées sont **confidentielles et anonymisées**. Ce dépôt est destiné à un usage **académique et démonstratif** uniquement.

---

## 📬 Contact

Pour toute question ou suggestion :

**Emna Turki**  
*Data Science – Risk Analytics*

