![Booki Icon](/public/assets/logo/Booki@3x.png)

## Transformer une maquette en site web avec HTML5/CSS3 - Booki

### P2 - OpenClassrooms "Développeur Web"

#### Contexte du projet

Vous avez trouvé votre premier stage en tant que développeur web chez Booki, une petite entreprise proposant un outil de planification de vacances ! Son site permet aux usagers de trouver des hébergements et des activités dans la ville de leur choix. Les hébergements peuvent également être triés par thématique, par exemple leur budget ou leur ambiance. Un nouveau design basé sur les principes du Material Design vient d’être réalisé par Loïc, designer UI.

Avant de valider définitivement le design, l’entreprise a décidé de réaliser un prototype. Vous êtes chargé de créer ce prototype en intégrant la maquette en HTML et CSS.

<details><summary><b>Spécifications fonctionnelles</b></summary>

- Les usagers pourront rechercher des hébergements dans la ville de leur choix. Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être édité par l’utilisateur. Il faut englober ce champ dans un formulaire pour que ce dernier soit valide auprès du W3C. La partie recherche ne doit pas être fonctionnelle.
- Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité (pas uniquement le titre). Pour l’instant, les liens sont vides. On peut utiliser un attribut `href=”#”` pour simuler la présence d’un lien.
- Les filtres doivent changer d’apparence au survol. Je te laisse décider de l’effet approprié, je n’ai pas encore eu le temps de me pencher dessus. Par contre, ils ne doivent pas être fonctionnels.
- Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils doivent mener respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.

</details>

<details><summary><b>Spécifications techniques</b></summary>

- [Une maquette a été réalisée](./public/assets/Maquette%20desktop.png) : Le site devra être également adapté aux formats mobile et tablette. Il est important qu’aucun élément ne soit coupé, et que le texte ait une taille suffisante.
- Plusieurs formats et tailles d’images ont été exportés. Il faudra choisir le format le plus adapté par rapport à la résolution et au temps de chargement.
- Les icônes proviennent de la bibliothèque Font Awesome. Nous pouvons passer par un CDN pour faciliter le chargement des icônes.
- Il est important d’utiliser les pixels et les pourcentages plutôt que les REM et les EM.
- Il est important d’utiliser Flexbox plutôt que Grid car c’est la techno que l’équipe maîtrise le mieux.
- Il est important d’utiliser des balises sémantiques (type `main`, `header`, `nav`, etc.).
- Le code doit être valide aux validateurs W3C HTML et CSS.
- La maquette doit être compatible avec les dernières versions de Google Chrome et de Mozilla Firefox. Il faudra tester le prototype sur ces deux navigateurs.

</details>

Vous commencez par vous plonger dans l’étude des maquettes à l’aide d’un papier et d’un crayon. Cela vous permet de définir les grandes sections de la page avant de démarrer votre intégration.

Bon courage !

#### Objectifs réalisés

- Transformer [une maquette](./public/assets/Maquette%20desktop.png) en site web HTML5/CSS3
- Respect de la sémantique et utilisation des balises HTML5
- Code passé dans le validateur W3C
- Architecture des dossiers et fichiers respectée
- Compatibilité du site avec les dernières versions de Google Chrome et de Mozilla Firefox
- Responsive

### [Prévisualisation du site](https://alex-pqn.github.io/Booki-ocr_dw/)

## Start App

Clone the project then open the [index.html](/index.html) file in your browser or use an extension to start a local server on this file.

> [!NOTE]  
> A [Github Pages preview](https://alex-pqn.github.io/Booki-ocr_dw/) is also available for this project

## Preview

![Booki](/public/assets/Booki.png)
<br/>
<br/>
<br/>
![Booki](/public/assets/Booki%20Responsive.png)
