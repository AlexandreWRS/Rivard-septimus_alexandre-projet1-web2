DOCUMENTATION.md
# Démarche

Pour ce projet, j’ai commencé par analyser la maquette Figma avec le Dev Mode afin de comprendre :

les espacements
les tailles
les couleurs
les règles d’auto-layout (Flexbox)

Ensuite, j’ai planifié :

la structure HTML
les composants réutilisables
la nomenclature CSS (BEM)
le système de variables CSS

L’objectif était de produire un code clair, structuré et maintenable.

# Architecture HTML

Le site est structuré en sections principales :

Header (navigation)
Hero
Programmation
Horaire
Artistes
Billets
Partenaires
Témoignages
Contact
Footer

Chaque section est divisée en composants pour faciliter la réutilisation.

# Composants réutilisables

Les composants identifiés sont :

1. Navigation (nav)
2. Hero
3. Program-card
4. schedule-item
5. Artist
6. Ticket
7. Partner
8. Témoignage
9. Formulaire

Ces composants sont réutilisables et modulaires.

## Nomenclature CSS (BEM)

J’ai utilisé la méthode BEM :

1. Block : .artist, .schedule
2. Element : .artist__name
3. Modifier : .artist--featured
4. Pourquoi :
5. structure claire
6. meilleure lisibilité
7. maintenance facile
8.évite les conflits CSS
9. Variables CSS (Design tokens)

## Les variables sont définies dans :root.

Types :
- Couleurs
- Espacements
- Typographie
- Bordures
Exemple :
--color-primary
--spacing-md
--font-size-lg
  
 Pourquoi :
cela permet de créer de la cohérence visuelle et c'est facile à modifier

### Flexbox a été utilisé pour :

- navigation
- grilles (artists, tickets)
- alignement (schedule)

Pourquoi :correspond à Figma Auto Layout , alignement facile , responsive simplifié


# Défis rencontrés
1. Centrage des éléments (icône + lettre)

Solution :

position: relative (parent)
position: absolute (lettre)

2. Espacements

Solution :

utilisation de padding + gap
variables CSS
3. Organisation du CSS

Solution :

utilisation de BEM
regroupement des styles

# Utilisation de l’IA

Outil : ChatGPT (OpenAI)
Version : GPT-5.3
Date : Mars 2026

Utilisation :
J'ai utilisé l'IA pour comprendre comment mettre une lettre dans un calendrier SVG ( je n'ai meme pas recu a le centrer).
De même pour le Form je n'arrivais pas à rappetisser le dernier bloc.


### Le projet était assez dur surtout pour que ca soit identique à la maquette , comme les  petits détails par exemple de centre les titres et les sous-titres et qu'il soit vis à vis 
(J'AI FAIS ÉNORMÉMENT DE ESSAIE ERREUR DONC C'ÉTAIT LOONG)

### Mais je suis content de ce que j'ai fais
code structuré
utilisation de BEM
variables CSS
Flexbox

Le résultat est un site maintenable et fidèle à la maquette.
