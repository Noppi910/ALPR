# 🥾 Inscriptions aux randonnées ALPR

Application web permettant aux adhérents de l'association de randonnées **ALPR** de consulter les sorties à venir et de s'y inscrire en quelques clics.

<!-- Ajoutez ici une capture d'écran : ![Aperçu de l'application](docs/apercu.png) -->

## Sommaire

- [Fonctionnalités](#fonctionnalités)
- [Technologies utilisées](#technologies-utilisées)
- [Installation](#installation)
- [Configuration](#configuration)
- [Utilisation](#utilisation)
- [Structure du projet](#structure-du-projet)
- [Contribuer](#contribuer)
- [Licence](#licence)
- [Contact](#contact)

## Fonctionnalités

- Consulter la liste des randonnées à venir (date, lieu, niveau, distance, dénivelé)
- S'inscrire ou se désinscrire d'une randonnée
- Voir le nombre de places restantes
- [Recevoir une confirmation d'inscription par e-mail]
- [Espace organisateur : créer, modifier et annuler des sorties]
- [Export de la liste des participants]

## Technologies utilisées

- **Front-end** : [ex. HTML/CSS/JavaScript, React, Vue…]
- **Back-end** : [ex. Node.js, PHP, Python…]
- **Base de données** : [ex. MySQL, PostgreSQL, SQLite…]

## Installation

### Prérequis

- [ex. Node.js 20 ou supérieur]
- [ex. Git]

### Étapes

```bash
# 1. Cloner le dépôt
git clone https://github.com/votre-nom/nom-du-depot.git
cd nom-du-depot

# 2. Installer les dépendances
npm install

# 3. Lancer l'application en local
npm start
```

L'application est ensuite accessible sur [http://localhost:3000](http://localhost:3000).

## Configuration

Copiez le fichier d'exemple puis renseignez vos valeurs :

```bash
cp .env.example .env
```

| Variable | Description |
|----------|-------------|
| `DATABASE_URL` | Adresse de connexion à la base de données |
| `MAIL_HOST` | Serveur d'envoi des e-mails |
| `SECRET_KEY` | Clé secrète de l'application |

> ⚠️ Ne publiez jamais le fichier `.env` sur GitHub. Ajoutez-le à votre `.gitignore`.

## Utilisation

**Pour un adhérent :**
1. Ouvrir l'application et consulter le calendrier des randonnées.
2. Cliquer sur une sortie pour voir le détail.
3. Remplir le formulaire d'inscription et valider.

**Pour un organisateur :**
1. Se connecter à l'espace d'administration.
2. Créer une nouvelle randonnée avec ses informations et le nombre de places.
3. Suivre les inscriptions en temps réel.

## Structure du projet

```
.
├── src/            # Code source de l'application
├── public/         # Fichiers statiques (images, styles)
├── docs/           # Documentation et captures d'écran
├── .env.example    # Modèle de configuration
└── README.md
```

## Contribuer

Les contributions sont les bienvenues !

1. Faites un *fork* du projet
2. Créez une branche : `git checkout -b ma-fonctionnalite`
3. Commitez vos modifications : `git commit -m "Ajout de ma fonctionnalité"`
4. Poussez la branche : `git push origin ma-fonctionnalite`
5. Ouvrez une *pull request*

Pour signaler un bug ou proposer une idée, ouvrez une [issue](../../issues).

## Licence

Ce projet est distribué sous licence [MIT](LICENSE). *(À adapter selon votre choix.)*

## Contact

Association ALPR : [adresse e-mail ou site web de l'association]
