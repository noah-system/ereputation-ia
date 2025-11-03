# 🌟 E-RÉPUTATION IA

**E-RÉPUTATION IA** est un service automatisé de gestion des avis clients.  
Il permet aux commerçants et entreprises de **surveiller, analyser et répondre à leurs avis Google** grâce à l’intelligence artificielle.

---

## 🚀 Objectif du projet

- Centraliser les avis Google dans un tableau de bord unique.  
- Automatiser les réponses personnalisées grâce à l’IA (modèle GPT).  
- Générer un QR code à partager avec les clients pour simplifier la collecte d’avis.  
- Fournir des rapports mensuels sur la note moyenne, le volume d’avis et la satisfaction.

---

## 🧠 Architecture

Projet propulsé par **NOAH SYSTEM CORE**, hébergé sur **GitHub Pages**.

**Structure des fichiers :**
/ereputation-ia
│
├── assets/ → Images, icônes et logo
│ ├── logo.png
│ ├── phone.png
│ ├── icon-ia.svg
│ ├── icon-detect.svg
│ └── icon-report.svg
│
├── index.html → Page de présentation (accueil)
├── offre.html → Page tarif / abonnement
├── contact.html → Page de contact
├── style.css → Feuille de style principale
└── README.md → Présentation du projet

---

## 🎨 Design

- **Template maître :** `business_template_K1`
- **Charte couleur :**
  - Bleu principal : `#1A73E8`
  - Gris clair : `#F9FAFB`
  - Texte principal : `#202124`
- **Typographie :** [Inter](https://fonts.google.com/specimen/Inter)
- **Style visuel :** inspiré de la charte Google – épuré, moderne, responsive.

---

## ⚙️ Fonctionnement

Le site est composé de 3 pages statiques :

| Page | Description |
|------|--------------|
| **index.html** | Présentation du service et fonctionnement |
| **offre.html** | Abonnement unique : 9,99 €/mois sans engagement |
| **contact.html** | Formulaire de contact (email, téléphone, adresse) |

Le site est **entièrement responsive** et optimisé pour les Core Web Vitals.

---

## 🛠️ Déploiement

**Hébergement :** GitHub Pages  
**Branche :** `main`  
**URL publique :** [https://noah-system.github.io/ereputation-ia/](https://noah-system.github.io/ereputation-ia/)

Pour republier après modification :
1. Commit des fichiers (`index.html`, `style.css`, etc.)
2. Vérifie que la source de déploiement est `main / root`
3. Attends 1-2 minutes, la page se met à jour automatiquement.

---

## 🔄 Intégration NOAH

Ce projet est généré via **NOAH Builder**, module de production web automatisée.  
Les données sont injectées dans le template maître K1 à partir du JSON suivant :

```json
{
  "project_id": "ereputation-ia",
  "project_type": "b2b_service",
  "template": "business_template_K1.html",
  "theme_color": "#1A73E8",
  "subscription_price": "9.99",
  "contact_email": "contact@ereputation-ia.fr"
}
| Élément              | Statut              |
| -------------------- | ------------------- |
| Design K1            | ✅ Validé            |
| Pages HTML           | ✅ En ligne          |
| Assets / icônes      | ✅ Uploadés          |
| Connexion Stripe     | ⏳ À intégrer        |
| Dashboard IA         | 🧩 En développement |
| Synchronisation NOAH | 🟢 Active           |
Support technique : contact@ereputation-ia.fr

Téléphone : +33 7 49 66 86 54
Adresse : 5 Rue des Moulins, 68700 Cernay, France



