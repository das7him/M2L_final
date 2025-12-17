# 🏅 Portail Web - Maison des Ligues (M2L)

> **Mission 2 :** Uniformisation du réseau et création du portail Web.

Ce dépôt héberge la version statique du portail web de la Maison des Ligues de Lorraine. [cite_start]Le projet a été développé dans le respect des standards W3C pour assurer l'interopérabilité et l'accessibilité des informations concernant les ligues sportives régionales[cite: 550, 556].

## 📋 Contexte du Projet

La Maison des Ligues (M2L) est une structure financée par le Conseil Régional de Lorraine, dont la gestion est déléguée au CROSL. [cite_start]Sa mission est de fournir des espaces et services aux ligues sportives[cite: 75, 78, 81].

[cite_start]Ce site répond à l'appel d'offre "Volet n°2" visant à développer un portail web offrant divers services aux utilisateurs et aux ligues[cite: 554].

## ✨ Fonctionnalités

Conformément au cahier des charges et au code implémenté, le site propose :

* [cite_start]**Accueil & Présentation :** Informations sur la M2L, missions et actualités (matchs récents)[cite: 73, 170].
* [cite_start]**Annuaire des Ligues (`explore.html`) :** Liste détaillée des ligues (Athlétisme, Aviron, Basket, Football, etc.) avec présentation des présidents et informations de contact[cite: 249, 318, 566].
* [cite_start]**Détails des Sports (`details.html`) :** Pages d'informations pratiques incluant les horaires d'ouverture, les coordonnées des cadres techniques et la localisation des bureaux[cite: 54, 519, 567].
* [cite_start]**Contact (`create.html`) :** Formulaire permettant aux utilisateurs de contacter la M2L (Sujet, email, message)[cite: 55, 541].
* [cite_start]**Organigramme :** Présentation des membres honoraires, du bureau et des salariés de la structure[cite: 454, 466, 504].

## 🛠️ Stack Technique

Le projet est un site statique respectant les contraintes suivantes :

| Technologie             | Détails                                       | Source                |
| :---------------------- | :-------------------------------------------- | :-------------------- |
| **Langage**             | [cite_start]HTML5, CSS3, JavaScript           | [cite: 556]           |
| **Framework**           | [cite_start]Bootstrap 5                       | [cite: 12]            |
| **Template**            | [cite_start]*Liberty Market* (TemplateMo 577) | [cite: 20, 572]       |
| **Icônes**              | [cite_start]FontAwesome                       | [cite: 14, 576]       |
| [cite_start]**Scripts** | jQuery, Owl Carousel, Isotope                 | [cite: 241, 243, 244] |

## 📂 Structure du Projet

```text
/
├── index.html          # Page d'accueil (Présentation & Derniers matchs)
├── explore.html        # Annuaire des ligues et Membres
├── details.html        # Informations détaillées par sport (Horaires, Staff)
├── create.html         # Formulaire de contact
├── assets/
│   ├── css/            # Feuilles de style (fontawesome, templatemo, etc.)
│   ├── images/         # Logos, photos des membres et illustrations
│   └── js/             # Scripts (custom.js, popup.js, tabs.js)
└── vendor/
    ├── bootstrap/      # Librairie Bootstrap
    └── jquery/         # Librairie jQuery