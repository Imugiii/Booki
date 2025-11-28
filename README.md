# Booki

Plateforme de réservation de logements en ligne permettant aux utilisateurs de rechercher et réserver des hébergements pour leurs vacances.

## Description

Booki est un site web de réservation d'hébergements qui permet aux utilisateurs de :
- Rechercher des hébergements par destination
- Filtrer les résultats selon différents critères (économique, familiale, romantique, pépites)
- Consulter les hébergements disponibles à Marseille
- Découvrir les hébergements les plus populaires
- Explorer les activités disponibles dans la région

## Structure du projet

```
Booki/
├── index.html      # Structure HTML principale
├── style.css       # Feuille de style CSS
├── image/          # Dossier contenant les images et logos
└── README.md       # Documentation du projet
```

## Référence CSS

### Classes CSS

| Classe | Description |
|--------|-------------|
| `search` | Barre de recherche de destination en haut de la section principale |
| `filter` | Conteneur des différents filtres sous la barre de recherche |
| `info-filter` | Section d'information sur le nombre de logements disponibles |
| `main-container` | Conteneur principal regroupant les sections hébergements et populaire |
| `places` | Section affichant la grille des hébergements disponibles |
| `resume-hotel` | Carte de résumé pour chaque hôtel dans la section hébergements |
| `popular` | Section aside affichant les hébergements les plus populaires |
| `popular-header` | En-tête de la section populaire avec titre et icône |
| `resume-popular` | Carte de résumé pour chaque hôtel dans la section populaire |
| `activitys` | Section affichant les activités disponibles |

### IDs CSS

| ID | Description |
|----|-------------|
| `search-bar` | Section globale contenant la barre de recherche et son titre |
| `filter` | Conteneur des filtres de recherche (identique à la classe) |
| `resume-hotel` | Carte de résumé d'hôtel (identique à la classe) |
| `resume-popular` | Carte de résumé d'hôtel populaire (identique à la classe) |
| `activitys` | Section des activités disponibles (identique à la classe) |

## Technologies utilisées

- HTML5
- CSS3
- Font Awesome (icônes)
- Google Fonts (Raleway)

## Notes de développement

- Le projet utilise une approche mobile-first avec une largeur maximale de 1440px
- La police de caractères utilisée est Raleway
- Les couleurs principales sont le bleu (#007bff) et le gris (#F2F2F2)
