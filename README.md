# 🛍️ AXEL STORE — Site E-commerce

**AXEL STORE** est une boutique en ligne moderne, élégante et responsive, développée avec HTML5, CSS3 et JavaScript.

Le projet propose une expérience d'achat simple, intuitive et accessible sur ordinateur, tablette et smartphone.

## 🎨 Design et identité visuelle

L'interface s'inspire du logo AXEL avec une identité graphique classique et professionnelle :

- **Blanc (`#FFFFFF`)** : couleur de fond principale.
- **Noir (`#151515`)** : textes et éléments de navigation.
- **Rouge (`#C91F32`)** : touches visuelles, boutons et accents.
- Design épuré, animations discrètes et navigation intuitive.
- Adaptation aux écrans Android, iPhone, tablettes et ordinateurs.

## 🚀 Fonctionnalités

### Catalogue de produits
- Affichage dynamique des articles avec JavaScript.
- Présentation des images, noms et prix en FCFA.
- Filtrage par catégories : Mode, Accessoires et Lifestyle.
- Recherche instantanée de produits.
- Tri par prix croissant, décroissant ou ordre alphabétique.

### Panier interactif
- Ajout et suppression de produits.
- Modification des quantités.
- Calcul automatique du montant total.
- Panneau latéral de consultation du panier.
- Conservation locale du panier si activée dans JavaScript.

### Favoris
- Ajout et retrait d'articles favoris.
- Consultation des produits préférés.
- Compteur de favoris.

### Commandes WhatsApp
Les clients peuvent préparer leur commande directement sur WhatsApp.

Le message contient :
- Le nom des articles sélectionnés.
- Les quantités commandées.
- Les prix de chaque article.
- Le montant total de la commande.

**Numéro WhatsApp :** +225 01 52 34 84 58

Le message est automatiquement préparé, mais le client doit confirmer son envoi dans WhatsApp.

## 🛠️ Technologies utilisées

| Technologie | Utilisation |
|---|---|
| HTML5 | Structure du site |
| CSS3 | Design et responsive |
| JavaScript | Interactions et fonctionnalités |
| LocalStorage | Stockage local du panier et des favoris |
| WhatsApp | Préparation des commandes |

## 📁 Structure du projet

```text
AXEL-STORE/
│
├── index.html
├── styleAXEL.css
├── Axel.js
├── AXELlogo.jpeg
├── README.md
│
└── assets/
    └── images-produits/
```

Le dossier `assets` est facultatif et peut contenir les images des produits.

## 💻 Installation

**1. Cloner le dépôt GitHub**

```bash
git clone https://github.com/VOTRE-UTILISATEUR/AXEL-STORE.git
```

Remplacer `VOTRE-UTILISATEUR` par le nom du compte GitHub hébergeant le projet.

**2. Ouvrir le projet**

Ouvrir le dossier `AXEL-STORE` dans Visual Studio Code.

**3. Lancer le site**

Ouvrir `index.html` avec l'extension Live Server ou directement dans un navigateur.

Aucune installation de dépendances npm n'est nécessaire.

## ⚙️ Personnalisation

### Modifier les produits

Les produits sont définis dans le fichier `Axel.js`.

Pour ajouter un produit, renseigner ses informations dans le tableau JavaScript utilisé par le catalogue : identifiant, nom, prix, catégorie et image.

### Modifier le numéro WhatsApp

Dans `Axel.js`, configurer :

```javascript
const WHATSAPP_NUMBER = "2250152348458";
```

Utiliser le numéro au format international sans espaces ni signe `+`.

### Modifier le design

Le fichier `styleAXEL.css` permet de personnaliser les couleurs, les espacements, les boutons, les cartes produits et les adaptations mobiles.

## 📱 Compatibilité

AXEL STORE est conçu pour s'adapter aux principaux formats :

- Ordinateurs Windows, macOS et Linux.
- Smartphones Android.
- iPhone et navigateurs iOS.
- Tablettes Android et iPad.
- Écrans mobiles de petite taille.

Des tests sur appareils réels sont recommandés avant la mise en production.

## 🔐 Limites actuelles

Cette version fonctionne principalement côté navigateur.

Elle ne comprend pas encore de backend, de base de données centralisée, de paiement en ligne intégré ou de gestion automatique des stocks.

## 🔮 Améliorations futures

- Développement d'un espace administrateur.
- Ajout et modification des produits sans toucher au code.
- Intégration de Node.js et Express.
- Connexion à une base de données MySQL.
- Gestion des comptes clients et des commandes.
- Intégration de paiements Mobile Money.
- Suivi des livraisons.
- Hébergement avec un nom de domaine personnalisé.

## 🌐 Déploiement

Le site peut être hébergé sur GitHub Pages, Netlify ou Vercel dans sa version statique.

Avant publication, vérifier les liens, les images, le fonctionnement du panier et le numéro WhatsApp.

## 👨‍💻 Développement

**Développeur :** Maewen'Steve

**Spécialité :** Développement web Front-end & Back-end

**Portfolio :** [www.maewens.com](https://www.maewens.com)

## 📄 Licence et droits

© 2026 AXEL STORE — Tous droits réservés.

Le code, les contenus et les éléments graphiques sont soumis aux droits de leurs propriétaires respectifs.

---

**AXEL STORE — L'essentiel du style. Sans compromis.**
