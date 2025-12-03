# 🕌 Oumra Prestige - Site Web

Bienvenue sur le projet **Oumra Prestige**, un site web élégant et professionnel pour une agence de voyage spécialisée dans l'organisation de voyages spirituels (Oumra) vers La Mecque.

## 📋 Description

Oumra Prestige est un site web moderne et responsive conçu avec HTML et Tailwind CSS. Il offre une expérience utilisateur fluide et spirituelle, avec un design minimaliste inspiré par les couleurs dorées, blanches, beiges et vertes.

## 🎨 Design

Le site utilise une palette de couleurs apaisante et prestigieuse :
- **Jaune doré** (#F59E0B) : Représente la lumière et la spiritualité
- **Blanc** : Symbolise la pureté
- **Beige/Crème** : Évoque le sable du désert
- **Vert** : Couleur de l'Islam et de l'espoir
- **Gris foncé** : Pour les textes et contrastes

## 📁 Structure du projet

```
oumra-prestige/
│
├── index.html          # Page d'accueil
├── about.html          # Page À propos
├── signup.html         # Page d'inscription
├── login.html          # Page de connexion
├── reservation.html    # Page de réservation
├── contact.html        # Page de contact
└── README.md          # Ce fichier
```

## 🚀 Installation et utilisation

### Méthode 1 : Utilisation locale simple

1. **Téléchargez tous les fichiers** dans un dossier nommé `oumra-prestige/`

2. **Ouvrez le fichier `index.html`** dans votre navigateur web préféré :
   - Double-cliquez sur le fichier
   - Ou faites clic droit → "Ouvrir avec" → Choisissez votre navigateur

3. **Navigation** : Utilisez le menu de navigation pour accéder aux différentes pages

### Méthode 2 : Serveur local (recommandé pour le développement)

Si vous avez Python installé :

```bash
# Python 3
python -m http.server 8000

# Puis ouvrez votre navigateur à l'adresse :
# http://localhost:8000
```

Si vous avez Node.js installé :

```bash
# Installez le serveur http simple
npm install -g http-server

# Lancez le serveur
http-server

# Ouvrez votre navigateur à l'adresse indiquée
```

### Méthode 3 : Extension VS Code

Si vous utilisez Visual Studio Code :

1. Installez l'extension **"Live Server"**
2. Faites clic droit sur `index.html`
3. Sélectionnez "Open with Live Server"

## 📄 Pages du site

### 🏠 1. Accueil (`index.html`)
- Hero section avec image de La Mecque
- Présentation des services
- Témoignages de pèlerins
- Appel à l'action "Réserver maintenant"

### ℹ️ 2. À propos (`about.html`)
- Mission de l'agence
- Valeurs fondamentales (6 valeurs)
- Statistiques (années d'expérience, clients satisfaits, etc.)
- Appel à l'action

### ✍️ 3. Inscription (`signup.html`)
- Formulaire d'inscription complet
- Champs : Nom, Prénom, Email, Téléphone, Mot de passe
- Validation des données
- Acceptation des conditions

### 🔐 4. Connexion (`login.html`)
- Formulaire de connexion simple
- Email et mot de passe
- Option "Se souvenir de moi"
- Connexion via réseaux sociaux (Google, Facebook)

### 📅 5. Réservation (`reservation.html`)
- Formulaire complet en 3 étapes
- Informations personnelles
- Détails du voyage (dates, formule, nombre de personnes)
- Options supplémentaires (visa, assurance, guide privé)
- Calcul automatique du prix total

### 📧 6. Contact (`contact.html`)
- Formulaire de contact
- Coordonnées complètes de l'agence
- FAQ rapide
- Carte de localisation

## 🎯 Fonctionnalités

### Navigation
- Menu responsive avec hamburger sur mobile
- Logo cliquable "Oumra Prestige"
- Navigation cohérente sur toutes les pages

### Formulaires
- Validation des champs obligatoires
- Messages d'erreur clairs
- Confirmation d'envoi avec alertes
- Design uniforme et accessible

### Design responsive
- Adaptation automatique aux mobiles, tablettes et desktop
- Grid system de Tailwind CSS
- Images optimisées avec Unsplash

### Interactivité
- Hover effects sur les boutons et liens
- Animations douces (fade-in)
- Calcul dynamique des prix (page réservation)
- Menu mobile interactif

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique
- **Tailwind CSS** (CDN) : Framework CSS utility-first
- **JavaScript** : Fonctionnalités interactives (validation, calculs)
- **Google Fonts** : Polices Playfair Display et Lato
- **Unsplash** : Images haute qualité

## 🎨 Personnalisation

### Modifier les couleurs

Les couleurs principales sont définies dans les classes Tailwind :
- `yellow-600` / `yellow-500` : Couleur principale (doré)
- `gray-800` / `gray-900` : Textes et footer
- `green-600` : Accents verts

Pour changer la palette, remplacez ces classes dans tous les fichiers.

### Modifier les images

Les images proviennent d'Unsplash. Pour les remplacer :

1. Trouvez une image sur [Unsplash](https://unsplash.com)
2. Copiez l'URL de l'image
3. Remplacez l'URL dans le code HTML

Exemple dans `index.html` :
```html
<!-- Ancienne image -->
background: url('https://images.unsplash.com/photo-...');

<!-- Nouvelle image -->
background: url('VOTRE_NOUVELLE_URL');
```

### Modifier les contenus

Tous les textes sont directement dans les fichiers HTML. Utilisez la recherche (Ctrl+F) pour trouver et remplacer les contenus.

## 📱 Compatibilité

Le site est compatible avec :
- ✅ Chrome (dernière version)
- ✅ Firefox (dernière version)
- ✅ Safari (dernière version)
- ✅ Edge (dernière version)
- ✅ Appareils mobiles (iOS, Android)

## ⚠️ Notes importantes

### Fonctionnalités simulées

Ce site est une **maquette front-end**. Les fonctionnalités suivantes sont simulées :

- ❌ Les formulaires n'envoient pas réellement de données
- ❌ Pas de base de données
- ❌ Pas d'authentification réelle
- ❌ Pas de système de paiement

Pour un site en production, vous aurez besoin de :
- Un backend (PHP, Node.js, Python, etc.)
- Une base de données (MySQL, PostgreSQL, MongoDB)
- Un système d'authentification sécurisé
- Une passerelle de paiement (Stripe, PayPal, etc.)

### Images

Les images proviennent d'Unsplash (licence libre). Pour un usage commercial, vérifiez les conditions d'utilisation ou utilisez vos propres images.

## 🔧 Développement futur

Pour transformer ce site en une application complète :

1. **Backend** :
   - Créer une API REST ou GraphQL
   - Gérer l'authentification (JWT, OAuth)
   - Connecter une base de données

2. **Paiement** :
   - Intégrer Stripe ou PayPal
   - Sécuriser les transactions

3. **Emails** :
   - Automatiser les confirmations de réservation
   - Envoyer des newsletters

4. **Administration** :
   - Créer un tableau de bord admin
   - Gérer les réservations
   - Analyser les statistiques

5. **SEO** :
   - Optimiser les balises meta
   - Ajouter un sitemap.xml
   - Créer un blog

## 📞 Support

Pour toute question ou suggestion concernant ce projet :

- 📧 Email : contact@oumraprestige.fr (exemple fictif)
- 🌐 Site web : www.oumraprestige.fr (exemple fictif)

## 📜 Licence

Ce projet est un exemple éducatif. Vous êtes libre de l'utiliser et de le modifier pour vos propres projets.

## 👥 Crédits

- **Design** : Inspiré des meilleures pratiques web modernes
- **Images** : [Unsplash](https://unsplash.com)
- **Icônes** : Heroicons (via Tailwind CSS)
- **Polices** : Google Fonts (Playfair Display, Lato)

---

**Développé avec ❤️ pour Oumra Prestige**

*Que votre voyage spirituel soit béni et paisible* 🕋