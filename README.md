# 🛍️ SAP FICO Vision 360 - Monoprix France

**Projet réalisé pour le cours ERP & BI à l'Esprit School of Engineering**  
Optimisation des opérations financières de Monoprix France en utilisant SAP FICO, Power BI, Talend et des modèles d'IA — en mettant l'accent sur la gestion fournisseurs, l'optimisation comptable et l'aide à la décision stratégique.

---

## 🌟 Présentation du Projet

Développement d'un système intelligent de gestion financière 360° en intégrant les données SAP FICO avec de l'analytics avancé :

- 💰 **Analyse Fournisseurs et Clients** (Retards, détection d'anomalies)
- 🧾 **Performance des Comptes Généraux** (Suivi en temps réel de la santé financière)
- 🧠 **Modèles Prédictifs** (Prédiction des retards de paiement, scoring de risque)
- 📊 **Dashboards Dynamiques BI** (Visualisation des KPIs, reporting financier)

> 📄 La documentation complète sera bientôt disponible.

---

## 📊 Principaux Indicateurs Clés (KPIs)

| KPI | Formule | Objectif |
|:---|:---|:---|
| 📈 **DPO** (Days Payable Outstanding) | (Dettes fournisseurs / Coût des ventes) × Nombre de jours | ≤ 60 jours |
| 📉 **DSO** (Days Sales Outstanding) | (Créances clients / Chiffre d'affaires) × Nombre de jours | ≤ 45 jours |
| 🔍 **Taux de Résolution de Litiges** | (Litiges Résolus / Total Litiges) × 100 | ≥ 80% |
| 🔐 **Financial Risk Score** | Modèle IA de scoring risque | ≥ 85% |
| 📦 **Paid Ratio** | (Litiges Payés / Total Litiges) | ≥ 0.8 |

---

## 🛠️ Technologies Utilisées

### 🔌 Intégration Principale

- **Talend** – Outil ETL pour extraction SAP FICO
- **Flask** – API pour modèles prédictifs
- **SQL Server** – Data Warehouse centralisé
- **Angular** – Frontend pour visualisation
- **Python** – Modélisation de données et prédictions IA

### 📂 Sources de Données

├── Extractions SAP FICO (Vendors, Comptes Généraux, Documents de Paiement) ├── Rapports Financiers (PDF) ├── Fichiers Fournisseurs (CSV) ├── Résultats des Modèles Prédictifs (Python)


---

## 📈 Aperçu des Dashboards

- **Suivi des Litiges**  
  Évolution mensuelle des litiges, taux de résolution.

- **Visualisation du Scoring Financier**  
  Segmentation des fournisseurs : MinRisk, MaxRisk, Cible.

- **Analyse de la Liquidité vs Dettes**  
  Comparaison des liquidités et dettes à court terme.

- **Comparaison Budget vs Réalisé**  
  Suivi annuel et trimestriel par cluster de fournisseurs.

- **Suivi du Chiffre d'Affaires**  
  Variation mensuelle du CA.

- **Mapping de la Performance Fournisseurs**  
  Catégorisation par fiabilité et durabilité.

---

## 🎯 Objectifs Business

- 📉 **Réduction des Retards de Paiement** : Optimiser le processus fournisseur.
- 🔒 **Amélioration du Contrôle Financier** : Suivi en temps réel des KPIs.
- 📈 **Amélioration de l'Efficacité Opérationnelle** : Détection précoce des anomalies.

---

## 🏛️ Architecture du Projet

SAP FICO → Talend ETL → SQL Server → Flask API → Dashboards Power BI → Frontend Angular


- Mises à jour temps réel
- Couche prédictive intégrée
- Interface utilisateur moderne et interactive

---

## 📄 Cahier des Charges

### 1. Contexte et Objectifs
Développer un système Business Intelligence (BI) intelligent basé sur l'Intelligence Artificielle (IA) pour renforcer la gestion fournisseurs et optimiser les processus financiers/comptables de Monoprix France.

### 2. Périmètre Fonctionnel
- **Gestion des Paiements Fournisseurs** (SAP FI - Comptes Fournisseurs)
- **Suivi de la Performance des Comptes Généraux** (SAP FI - General Ledger)
- **Analyse des Comptes Auxiliaires** (Fournisseurs et Clients)

### 3. Objectifs Fonctionnels
- Améliorer l'efficacité opérationnelle (réduction des délais de paiement, meilleure gestion fournisseur).
- Renforcer le contrôle financier (suivi DPO, DSO, ratios financiers).
- Supporter la prise de décision stratégique (KPIs consolidés, dashboards dynamiques).

### 4. Livrables
- Dashboard BI interactif de suivi des KPIs
- Modèles prédictifs IA (retards de paiement, scoring de risque)
- Documentation technique et fonctionnelle complète

### 5. Contraintes & Exigences
- **Sources de données** : Extractions SAP FICO, fichiers PDF, CSV
- **ETL** : Talend
- **Stockage** : SQL Server
- **Visualisation** : Power BI
- **Programmation** : Python
- **Frontend** : Angular
- **Backend** : Flask

---

## 🔗 Liens Utiles

- 📖 [Présentation du module SAP FICO](https://www.rapidviews.io/blog/sap-fi-co/presentation-module-sap-fi-co)
- 📚 [Cahier des Charges - Vision 360 Monoprix France](#)

---

> **Empowering financial intelligence for Monoprix France with SAP FICO, Talend, and Power BI.** 🚀
