# 🚀 Intégration Continue avec GitHub Actions

Ce projet met en place une **pipeline CI** (Intégration Continue) avec **GitHub Actions** pour automatiser les tests et la vérification du code à chaque modification.

---

## 📌 Objectif

- Exécuter automatiquement les tests unitaires avec `pytest`
- Vérifier la qualité du code avec `flake8`
- Déclencher la pipeline à chaque `push` ou `pull_request` sur `master`

---

## 🗂️ Structure du projet

- `main.py` : fichier principal
- `test_main.py` : tests unitaires
- `.github/workflows/ci.yml` : configuration de la pipeline

---

## ⚙️ Contenu de la pipeline CI

1. **Déclenchement automatique** (push/pull_request sur `master`)
2. **Installation de Python**
3. **Installation des dépendances** (`pytest`, `flake8`)
4. **Analyse du code** avec `flake8`
5. **Exécution des tests** avec `pytest`

---

## ✅ Prérequis

- Compte GitHub
- Git installé localement
- Projet Python structuré

---

## 📌 Utilisation

1. Cloner le dépôt
2. Ajouter ton code dans `main.py`
3. Ajouter tes tests dans `test_main.py`
4. Pousser sur GitHub
5. Consulter l’onglet **Actions** pour voir la pipeline s'exécuter

