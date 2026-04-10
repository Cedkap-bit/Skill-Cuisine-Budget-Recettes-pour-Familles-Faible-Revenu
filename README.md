# 🍲 Cuisine Budget — Recettes pour Familles à Faible Revenu

> Réinterpréter les plats traditionnels haïtiens, congolais, caribéens et africains avec un budget serré, sans perdre la richesse culturelle ni la valeur nutritive.

![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-actif-brightgreen)
![Budget](https://img.shields.io/badge/budget-3%20%C3%A0%2010%20CAD%2Frepas-blue)

---

## 🎯 Mission

Ce projet est un **skill d’assistant culinaire** conçu pour :

- Proposer des recettes nourrissantes avec **moins de 10$ CAD / 6€ / 500 HTG** pour 4 personnes.
- Adapter les plats traditionnels aux ingrédients locaux et de saison.
- Indiquer **où acheter** au meilleur prix, selon la région de l’utilisateur.
- Créer des plats **fusion** et des recettes d’**urgence budget**.

> 💡 **Philosophie** : Un petit budget n’est pas une honte, c’est une force créative.

---

## 🧠 Fonctionnement (Workflow)

L’assistant suit toujours ces 4 étapes :

### 1️⃣ Identifier le contexte
- Région / ville de l’utilisateur
- Budget disponible (sinon, valeurs par défaut)
- Type de plat souhaité : haïtien, congolais, caribéen, africain, fusion ou libre

### 2️⃣ Proposer la recette revisitée
Avec structure standardisée :

- 🍽️ Nom du plat — Version Budget
- 📍 Région, 💰 Coût estimé, ⏱️ Temps
- Origine culturelle
- Tableau des ingrédients (quantité, prix estimé, alternative)
- Préparation pas à pas
- Astuce budget 💡
- Valeur nutritive simplifiée

### 3️⃣ Indiquer où acheter
Selon la région, l’assistant donne :

- Marchés locaux recommandés
- Épiceries ethniques / caribéennes / africaines
- Supermarchés économiques
- Conseil saisonnier 🌱

### 4️⃣ Proposer variantes et nouveaux plats
- Plat fusion (ex : haïtien + légumes québécois)
- Variante encore moins chère
- Plat “d’urgence budget” (3-4 ingrédients)

---

## 📚 Bibliothèque de recettes de base

| Plat traditionnel | Version budget |
|------------------|----------------|
| Riz collé haïtien | Lentilles + riz, épices douces |
| Legim haïtien | Chou, carottes, sardines |
| Griot (porc) | Cuisses de poulet ou abats |
| Saka-saka (feuilles de manioc) | Épinards + arachides |
| Pondu congolais | Feuilles de patate douce |
| Fufu / Ugali | Farine de maïs + eau |
| Bouillon haïtien | Version végétarienne ou aux œufs |
| Maïs moulu (maïs ak pwa) | Haricots rouges + maïs |

---

## 🔁 Règles de substitution d’ingrédients

| Original | Alternative économique | Économie |
|----------|------------------------|----------|
| Bœuf / cabri | Cuisses de poulet, sardines | -50 à -70% |
| Crevettes | Poisson fumé, harengs | -60% |
| Légumes rares | Épinards, chou, carottes | -40% |
| Épices en sachet | Épices vrac (épicerie ethnique) | -30 à -60% |
| Noix de coco fraîche | Lait de coco en conserve | variable |
| Plantains mûrs | Bananes bien mûres | -30% |
| Igname | Pomme de terre / patate douce | -40% |

---

## 🧪 Nouveaux plats fusion budget

| Plat | Inspiration | Budget pour 4 |
|------|-------------|----------------|
| Riz collé aux lentilles | Haïtien + méditerranéen | <3$ CAD |
| Poulet DG simplifié | Cameroun + légumes de saison | ~5€ |
| Bouyon légume (végétarien) | Haïtien + marché local | ~2$ CAD |
| Mataba aux sardines | Saka-saka express + sardines | ~1.50€ |
| Akasan enrichi | Bouillie de maïs + protéines | ~1.80$ CAD |

---

## 🛒 Références régionales intégrées

### 🇨🇦 Québec / Canada
- **Montréal** : Jean-Talon, Atwater, Maxi, Super C, épiceries CDN/Saint-Michel
- **Québec Ville** : Marché Sainte-Foy, Maxi, Super C, Limoilou
- **Laval** : Marché 440, Maxi Laval, Super C
- **Régions rurales (Beauce, Saint-Elzéar)** : IGA, Metro, Maxi.ca, marchés saisonniers

### 🇫🇷 France
- **Paris** : Marché d’Aligre, Barbès, Château Rouge, Lidl, Aldi
- **Lyon, Marseille, Bordeaux** : marchés centraux + quartiers diaspora africaine/caribéenne

### 🇭🇹 Haïti
- **Port-au-Prince** : Croix-des-Bossales, Hyppolite, Pétion-Ville
- **Zones rurales** : marchés hebdomadaires, jardins vivriers

### 🇨🇩 RDC / Congo
- **Kinshasa** : Marché Central, Matongé, Lemba
- **Prix repères** : feuilles de manioc (500-1000 FC), poisson fumé (2000-5000 FC/kg)

> 🔍 Si une région n’est pas dans la base, l’assistant utilise une **recherche web** pour trouver marchés, prix et épiceries locales.

---

## 💬 Exemples de prompts d’utilisation

### 🇭🇹 Haïtien
> *“Je veux faire un repas haïtien pour 4 personnes avec seulement 6$ à Montréal.”*

> *“Comment faire un legim haïtien pas cher avec du chou, des carottes et des sardines ?”*

### 🇨🇩 Congolais
> *“Recette de pondu économique à Paris. Où trouver des feuilles de manioc pas chères ?”*

> *“Fufu et mafé pour 5 personnes avec moins de 8€ à Lyon.”*

### 💰 Budget extrême
> *“J’ai 3$ pour nourrir ma famille ce soir.”*

> *“Repas complet avec riz, haricots, oignon, ail.”*

### 🔀 Fusion
> *“Invente un plat entre Haïti et les légumes québécois bon marché.”*

### 📍 Recherche de lieux
> *“Où acheter plantains et épices créoles pas chers à Ottawa ?”*

> *“Épiceries africaines à Sherbrooke ?”*

---

## 🧠 Conseils systématiques intégrés

- Acheter légumineuses en gros → économies 30-50%
- Congeler plantains en promotion
- Faire tremper légumineuses → moins d’énergie de cuisson
- Cuisiner en grosses portions et congeler
- Bouillons maison avec épluchures
- Remplacer viande par légumineuses 2-3x/semaine

---

## 🎙️ Ton et style de communication

- **Chaleureux et encourageant** — jamais condescendant
- **Pratique et concret** — prix et lieux réels
- **Culturellement respectueux** — valorisation des cuisines traditionnelles
- **Quelques mots en créole ou lingala** — *“Bon manje!”*, *“Sép bon!”*
- **Accessible à tous les niveaux de revenus**

---

## 🤝 Contribution

Les recettes, références régionales et substitutions sont ouvertes aux contributions.

Tu peux :
- Ajouter une région avec ses marchés et prix repères
- Proposer une nouvelle recette fusion
- Améliorer une règle de substitution

→ `fork`, `pull request`, ou discussion dans *Issues*

---

## 📄 Licence

MIT — utilisation libre pour l’aide alimentaire communautaire, cuisines collectives et projets sociaux.

---

## 🙏 Remerciements

Aux cuisinières et cuisiniers de la diaspora haïtienne, congolaise, caribéenne et africaine qui transmettent la richesse culinaire avec très peu.

> *“Avec rien, on fait quelque chose. Avec quelque chose, on fait un festin.”*

