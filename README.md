# ANNAROZ Design — page de liens

Micro-site public utilisé comme hub de liens pour les biographies de réseaux sociaux et les points de contact ANNAROZ Design.

> **Dépôt actuellement public.** Son code, son historique et ses assets sont visibles par tous. Aucun secret, document client, fichier commercial nominatif ni source privée ne doit y être ajouté.

## État vérifié au 22 juillet 2026

- Dépôt : `Janeanrz/annaroz-liens`
- Visibilité GitHub : publique
- Branche publiée : `main`
- Technologie : HTML/CSS statiques
- Build : aucun build requis
- Hébergement configuré : GitHub Pages
- Déploiement : automatique à chaque push sur `main`
- Domaine déclaré : `liens.annarozdesign.com`
- Titre : `Annaroz Design · Liens`

## Rôle

Cette page centralise des liens publics tels que :

- prise de contact ;
- réseaux professionnels et inspiration ;
- adresse e-mail publique ;
- futurs points d’entrée validés vers les offres, le site ou l’application.

Elle ne remplace ni le site vitrine, ni l’application client, ni un CRM. Elle ne collecte et ne stocke aucune donnée dans le dépôt.

## Structure

```text
annaroz-liens/
├── index.html                  # page unique
├── CNAME                        # sous-domaine GitHub Pages
├── assets/                      # avatar, polices et icônes
├── favicon.ico
├── apple-touch-icon.png
├── .github/workflows/pages.yml  # publication automatique
└── README.md
```

## Prévisualisation locale

Aucune dépendance Node n’est nécessaire.

```bash
python -m http.server 8080
```

Sous Windows :

```powershell
py -m http.server 8080
```

Ouvrir ensuite `http://localhost:8080`.

## Déploiement

Le workflow GitHub Pages publie directement la racine du dépôt lors d’un push sur `main`.

Procédure :

1. créer une branche ;
2. ouvrir la page en local ;
3. tester chaque lien ;
4. vérifier l’affichage mobile ;
5. ouvrir une pull request ;
6. confirmer qu’aucune information non publique n’a été ajoutée ;
7. fusionner dans `main` ;
8. suivre l’Action GitHub Pages ;
9. contrôler le sous-domaine et HTTPS.

## Contrôles avant publication

- identité, avatar et couleurs conformes au canon ANNAROZ Design ;
- textes courts et lisibles sur mobile ;
- liens réellement actifs ;
- coordonnées publiques cohérentes avec le site et les pages légales ;
- aucun lien interne, temporaire ou propre à un assistant IA ;
- aucune campagne expirée laissée comme CTA principal ;
- aucun secret dans l’URL ou le code ;
- cibles tactiles confortables ;
- contraste et focus clavier suffisants ;
- page légère et rapide sur réseau mobile.

## Domaine

Le fichier `CNAME` déclare :

```text
liens.annarozdesign.com
```

Le domaine a été ajouté, retiré puis recréé dans l’historique. Avant toute nouvelle modification :

- confirmer la cible DNS actuelle ;
- vérifier les paramètres GitHub Pages ;
- contrôler le certificat HTTPS ;
- préparer un retour arrière ;
- éviter tout conflit avec le site principal ou d’autres sous-domaines.

## Visibilité publique

La visibilité publique est compatible avec une page GitHub Pages destinée au public, mais elle doit rester volontaire.

Avant chaque ajout, vérifier :

- droits sur les images et polices ;
- absence de données personnelles non destinées à la publication ;
- absence de brouillons stratégiques ;
- absence de fichiers de travail ou d’exports ;
- absence de token, clé, mot de passe ou paramètre sensible.

## Reprise depuis le portable

1. Installer Git et GitHub CLI.
2. Cloner le dépôt.
3. lancer un serveur local ;
4. modifier sur une branche ;
5. tester les liens ;
6. fusionner par pull request ;
7. vérifier GitHub Pages et le domaine.

Le PC fixe n’est pas nécessaire pour maintenir cette page.

## Gouvernance

Le positionnement, les offres et la voix de marque de référence sont versionnés dans le dépôt privé `Janeanrz/annaroz-foundation`. La page de liens doit rester une exécution courte et cohérente de ce canon.
