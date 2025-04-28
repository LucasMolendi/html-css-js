 sommaire :
- <span style="color: coral">I. intro sur le web</span>
- <span style="color: coral">II. HTML</span>
	 - <span style="color: green">base de l'<b>HTML</b></span>
	 - <span style="color: green">Commande et balise <b>HTML</b> importante</span>
- <span style="color: coral">III. CSS </span>
	- <span style="color: green">base du CSS</span>
	- 
- <span style="color: coral">IV. JavaScript</span>
- <span style="color: coral">Conclusion</span>
# <span style="color: coral"> I. intro sur le web : </span>

Le **WWW (ou World Wide Web)** imaginé et crée par ***Tim Berners Lee*** a partir de ***1989***, qu'il rend public en ***1993*** et qui repose sur des technologie fondamentale comme les **URL (Uniform Ressource Locator)**,**HTML (HyperText Markup Language)**, **HTTP** et **TCP/IP**. Toutes ensemble ces technologie on ouvert la voie a des avancées majeures dans le développement des sites web et des applications.
Aujourd'hui, le web permet non seulement de **créer** des **pages web** de façon classiques, mais aussi de concevoir des **app web** ainsi que des **logiciels de bureau**:
- *Discord*
- *VS code*
- *Teams*
- *etc...* 
Mais aussi des **applications mobiles** via des *Framework* tels que *React Native* ou *Ionic*, des **script** pour les *ligne de commandes (CLI)* et également des jeux vidéo. Ces outils et technologies sont devenus indispensable dans des domaines variés comme:
- ***la communication*** 
- ***le divertissement*** 
- ***le travail collaboratif*** 

# <span style="color: coral">II. HTML : </span>

## <span style="color: green">Les bases de <b>l'HTML </b>:</span>

Le ***HTML (HyperText Markup Language)*** est le langage fondamental utilisé pour structurer les pages web. il permet de décrire l'organisation d'une page web. Il permet de décrire l'organisation d'un document en définissant les élément qui le compose comme les *titre, paragraphes, image ou liens*. Il suit une structure bien défini qui commence par la déclaration du type de document (`<!DOCKTYPE html>`) et est organisé autour des balises `<html>`,`<head>`, `<body>`:
	- La balise `<html>`englobe tout le contenu d'une page web et définit la langue du document à l'aide de l'attribut `lang`(par exemple, `<html lang="fr">`)
	-  La section `<head>`contient des informations non visibles directement par l'utilisateur, comme le titre de la page ( `<title>`), les méta informations ( `<meta charset="UTF-8">`pour définir l'encodage), ou encore des liens vers des fichiers externes comme des feuilles de style CSS ( `<link>`) .
	- La section `<body>`héberge le contenu visible, comme les textes, images et autres éléments interactifs.
HTML se distingue par son rôle de structureur : il pose les bases d'une page web à laquelle CSS et JavaScript ajoutent style et dynamisme.

## <span style ="color: green">Commandes et balises <b>HTML</b> importantes</span>:

HTML utilise des balises pour définir des éléments spécifiques dans une page web. Ces balises peuvent être imbriquées les unes dans les autres et possèdent parfois des attributs qui modifient leur comportement ou leur apparence. Voici quelques balises essentielles :

- **Titres** : `<h1>`à `<h6>`servir à hiérarchiser les titres et sous-titres d'une page, `<h1>`étant le plus important.
- **Paragraphes** : `<p>`permet de structurer les blocs de texte.
- **Listes** :
    - Ordonnées (avec des numéros) : `<ol>`accompagnées de `<li>`pour chaque élément.
    - Non ordonnées (avec des puces) : `<ul>`et `<li>`.
- **Images** : `<img src="chemin">`insérer une image en spécifiant son chemin via l'attribut `src`.
- **Liens** : `<a href="URL">`permet de créer un lien hypertexte vers une autre page ou un document.
- **Mise en page** : `<header>`, `<footer>`, et `<div>`organisent les grandes sections d'une page, tandis que `<span>`s'utilisent pour styliser des portions de texte précis.
- **Éléments spéciaux** :
    - `<br>`:retour à la ligne.
    - `<hr>`: ligne horizontale servant à séparer les sections.
    - `<input>`: utilisé pour créer des champs de saisie dans les formulaires.

Enfin, certaines balises comme `<img>`ou `<input>`sont dites auto-fermées car elles ne doivent pas de balise de fermeture explicite. Maîtriser ces commandes et leur syntaxe est essentiel pour construire des pages web claires et fonctionnelles.

# <span style ="color: coral">III. CSS :</span>

## <span style = "color: green">Les bases du <b>CSS</b>:</span>

Le CSS (Cascading Style Sheets) est un langage utilisé pour styliser les éléments HTML d'une page web. Il permet de contrôler l'apparence visuelle d'un site en appliquant des règles de style comme les couleurs, les polices, les marges ou encore les dimensions. Contrairement au HTML, qui définit la structure et le contenu, le CSS se concentre sur l'aspect esthétique et la mise en forme.

Le CSS fonctionne en associant des styles aux éléments HTML à l'aide de sélecteurs. Par exemple, pour appliquer une couleur de fond à tous les paragraphes ( `<p>`), ou utiliser une règle CSS telle que :

```css
p {     background-color: lightblue; }
```

Le CSS peut être intégré de trois manières principales :

1. **Interne** : Inclus directement dans une balise `<style>`à l'intérieur du fichier HTML.
2. **Externe** : Placé dans un fichier `.css`séparé, lié au document HTML via la balise `<link>`dans la section `<head>`.
3. **En ligne** : Appliqué directement aux éléments HTML avec l'attribut `style`. Cependant, cette méthode est déconseillée car elle complique la maintenance du code.

Le CSS est également essentiel pour le responsive design, permettant à un site de s'adapter aux différentes tailles d'écran grâce à des unités flexibles et des media queries.

---

## <span style ="color: green">Commandes et propriétés <b>CSS</b> importantes :</span>

Le CSS repose sur un ensemble de propriétés et d'outils puissants permettant une personnalisation avancée des éléments HTML. Voici une sélection des propriétés les plus utilisées utilisées :

- **Couleurs et arrière-plan** :
    - `color`: définit la couleur du texte.
    - `background-color`: modifier la couleur d'arrière-plan.
- **Texte et politiques** :
    - `font-family`: définir le style de la police.
    - `font-size`: ajuster la taille du texte.
    - `text-transform`: modifier la casse (majuscules, minuscules).
- **Dimensions et positionnement** :
    - `width`et `height`: signifie la largeur et la hauteur.
    - `margin`et `padding`: contrôlent les espaces externes et internes autour des éléments.
    - `position`: permet de positionner les éléments avec des valeurs comme `static`, `relative`, `absolute`, `fixed`ou `sticky`.
- **Bordures et angles arrondis** :
    - `border`: ajoute une bordure autour d'un élément.
    - `border-radius`: arrondit les pièces d'un élément.
- **Flexbox** : Simplifie l'organisation et l'alignement des éléments dans une page.

#### <span style = "color: salmon">Outils et concepts avancés :</span>

- **Box Model** : Chaque élément HTML est représenté comme une boîte composée de quatre parties : le contenu, le padding, la bordure et la marge. Comprendre ce modèle est crucial pour le placement et la dimension des éléments.
	![[Pasted image 20241202084817.png]] 
- **Unités CSS** : Utilisation d'unités comme `px`, `%`, `em`, `rem`, ou encore `vh`et `vw`pour une mise en page adaptative.
- **Pseudo-classes et pseudo-éléments** :
    - Pseudo-classes : `:hover`pour les effets au survol ou `:first-child`pour cibler le premier enfant d'un élément.
    - Pseudo-éléments : `::before`et `::after`pour ajouter du contenu avant ou après un élément sans modifier le HTML.

En combinant ces outils, le CSS permet de transformer une page HTML basique en une interface attrayante et ergonomique, adaptée à tous types d'appareils.
## <span style="color: green">Flexbox et Justify-Content en CSS</span>

Le module **Flexbox** (Flexible Box Layout) est une méthode moderne et puissante pour organiser et aligner des éléments dans un conteneur. Il est conçu pour répondre aux besoins complexes de mise en page et d'alignement en offrant un contrôle précis sur la distribution de l’espace entre les éléments, leur alignement, et leur ordre.

#### <span style="color: salmon">Introduction à Flexbox</span>

Flexbox fonctionne sur deux axes principaux :

- **L’axe principal (main axis)** : Défini par la direction du flux des éléments (horizontale ou verticale).
- **L’axe croisé (cross axis)** : Perpendiculaire à l’axe principal.

Pour activer Flexbox, il faut définir une propriété sur un conteneur :

```css
.container {
    display: flex;
}
```

#### <span style="color: salmon">Propriété Justify-Content </span>

La propriété **justify-content** contrôle l’alignement des éléments enfants le long de l'axe principal. Elle est souvent utilisée pour répartir l’espace ou positionner les éléments selon différentes stratégies.

**Valeurs principales de justify-content** :

- **`flex-start`** : Aligne les éléments au début de l’axe principal (par défaut).
- **`flex-end`** : Aligne les éléments à la fin de l’axe principal.
- **`center`** : Centre les éléments le long de l’axe principal.
- **`space-between`** : Distribue les éléments avec un espace égal entre eux.
- **`space-around`** : Ajoute un espace égal autour de chaque élément.
- **`space-evenly`** : Ajoute un espace uniforme entre les éléments, y compris sur les bords du conteneur.

**Exemple de code :**

```css
.container {
    display: flex;
    justify-content: center;
}
```

Dans cet exemple, tous les éléments enfants du conteneur seront centrés horizontalement.

#### <span style="color: salmon"> Exemples pratiques </span>

Voici un exemple visuel des différentes valeurs de `justify-content` :

- **HTML :**

```html
<div class="container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
</div>
```

- **CSS :**

```css
.container {
    display: flex;
    justify-content: space-between;
    background-color: lightgrey;
}

.item {
    width: 50px;
    height: 50px;
    background-color: steelblue;
    margin: 5px;
    text-align: center;
    line-height: 50px;
    color: white;
    font-weight: bold;
}
```

Dans cet exemple, les trois éléments enfants auront un espace égal entre eux.

#### <span style="color: salmon"> Combinaison avec d'autres propriétés Flexbox</span>

Flexbox ne se limite pas à `justify-content`. Il peut être combiné avec d'autres propriétés pour un contrôle complet, comme :

- **`align-items`** : Aligne les éléments le long de l'axe croisé.
- **`flex-wrap`** : Permet aux éléments de passer à une nouvelle ligne si nécessaire.
- **`gap`** : Ajoute un espacement fixe entre les éléments.

Ces propriétés, combinées avec `justify-content`, permettent de créer des mises en page adaptatives et réactives adaptées à toutes les tailles d’écran.
# <span style="color: coral">JavaScript:</span>

## <span style = "color: green"><b>JavaScript</b> : Les bases :</span> 

JavaScript, souvent abrégé JS, est un langage de programmation essentiel pour ajouter de l'interactivité et du dynamisme aux pages web. Créé en 1995 par Brendan Eich pour Netscape, il est rapidement devenu populaire grâce à sa flexibilité et son intégration directe dans les navigateurs web. Contrairement à Java, qui est un langage compilé, JavaScript est un langage interprété, c'est-à-dire que son code est exécuté directement par un moteur d'exécution comme **V8** de Google Chrome ou **SpiderMonkey** de Mozilla Firefox.

Le JavaScript est utilisé pour répondre aux actions des utilisateurs, manipuler le contenu des pages (DOM), valider des formulaires, ou encore communiquer avec des serveurs via AJAX pour des applications web dynamiques. Bien qu'il soit principalement conçu pour le web, son extension via des outils comme Node.js (introduit en 2009) permet également de l'utiliser côté serveur.

JS est un langage non typé, ce qui signifie qu'une variable peut changer de type au cours du programme, contrairement aux langages strictement typés comme Java ou TypeScript. Il est aussi dynamique, ce qui le rend très souple, mais cela peut entraîner des erreurs si le code est mal structuré.

---

## <span style ="color: green">Commandes et concepts <b>JavaScript</b> importants :</span>


JavaScript repose sur plusieurs structures, commandes et concepts essentiels à son fonctionnement :

#### <span style ="color: salmon"> Les structures de contrôle :</span>

- **Conditions** :
    - `if`: Exécutez un bloc de code si une condition est vraie.
    - `else`: Exécute un bloc alternatif si la condition est fausse.
    - `switch`: Gère plusieurs cas basés sur une valeur.
    
```javascript
if (age > 18) {     
	console.log("Adulte"); 
} 
else { 
	console.log("Mineur"); 
}
```
    
    
- **Boucles** :
    
    - `for`: Répète un bloc de code avec une initialisation, une condition et une incrémentation.
    - `while`: Répète un bloc tant qu'une condition est vraie.
    - `do...while`: Exécute au moins une fois avant de vérifier la condition.
```javascript
for (let i = 0; i < 5; i++) {    
	console.log(i); 
	}
```
####  <span style = "color: salmon">Types de données :</span>

JavaScript gère différents types de données :

- **Primitifs** :
    - `Number`: Nombre (ex. 10, 3.14).
    - `String`:Texte (ex. "Bonjour").
    - `Boolean`: Valeurs logiques ( `true`ou `false`).
    - `Null`:Valeur vide intentionnelle.
    - `Undefined`: Variable déclarée mais non initialisée.
- **Complexes** :
    - `Array`: Liste de valeurs.
    - `Object`: Ensemble de paires clé-valeur.

#### <span style = "color: salmon">Variables et portée :</span>

Les variables en JS se déclarent avec :

- `var`: Déclaration globale ou locale (ancienne méthode).
- `let`: Déclaration avec portée limitée au bloc.
- `const`: Déclaration de constante (ne peut pas être réaffectée).
 
Exemple :
```javascript
let age = 25; const pi = 3.14; var nom = "Jean";
```
####  <span style="color: salmon">Fonctions : </span>

Les fonctions permettent d'organiser et de réutiliser du code. Elles peuvent être :

- **Déclarées** :
	```javascript
	    function addition(a, b) {     return a + b; }
    ```
- **Anonymes** (souvent utilisé dans les callbacks) :
    ```javascript
    const addition = function(a, b) {     return a + b; };
    ```
- **Fléchées** (plus concises) :
```javascript
	const addition = (a, b) => a + b; 
```

#### <span style = "color: salmon"> DOM et manipulation d'éléments HTML : </span>

Le DOM (Document Object Model) est l'interface qui permet à JavaScript de manipuler les éléments HTML d'une page. Les fonctions courantes incluent :

- `document.querySelector()`: Sélectionne un élément HTML.
- `document.createElement()`:Créé un nouvel élément.
- `element.addEventListener()`: Ajoute un événement (ex. clic, survol).

Exemple :

``` javascript
document.querySelector('button').addEventListener('click', () => {
    alert('Bouton cliqué !');
});
```

#### <span style ="color: salmon"> Concepts avancés :</span>

- **Asynchronicité** :
    
    - Les promesses ( `Promise`) et `async/await`permettre de gérer les opérations asynchrones, comme les requêtes réseau.
    
``` javascript
async function fetchData() {    
	let response = await fetch('https://api.example.com/data'); 
	let data = await response.json();    
	console.log(data); }
```
- **Prototype et héritage** :
    - JavaScript utilise un modèle basé sur des prototypes pour créer des objets et gérer l'héritage.
- **Modules** :
    - Avec ES6, il est possible de diviser le code en modules réutilisables à l'aide de `export`et `import`.

En combinant ces fonctionnalités, JavaScript est devenu un langage incontournable, non seulement pour le développement web, mais aussi pour des domaines comme les applications serveur ou les jeux interactifs.

# <span style="color: coral">Conclusion :</span>

Les technologies web, composées de ***HTML, CSS et JavaScript***, forment un socle indispensable pour la création et le développement de sites et d’applications modernes. Chaque composant joue un rôle unique mais complémentaire : ***HTML*** **structure le contenu**, ***CSS*** **stylise l’apparence**, et ***JavaScript*** **ajoute dynamisme et interactivité**. Ensemble, ils permettent de répondre aux besoins variés des utilisateurs et d’offrir des expériences immersives, accessibles et performantes.

Ces langages, bien qu’intuitifs dans leurs bases, intègrent des concepts et des outils avancés qui exigent une maîtrise approfondie pour en tirer pleinement parti. Des pratiques telles que l’utilisation de balises sémantiques, le respect des standards du ***W3C***, et l’adoption de techniques modernes comme le responsive design assurent une meilleure accessibilité, une compatibilité étendue et une maintenance simplifiée.

Enfin, l’évolution continue des technologies web, avec des outils comme Node.js ou des Framework comme React, démontre leur adaptabilité à des usages toujours plus diversifiés, du développement mobile aux applications serveur. Comprendre et maîtriser ces outils n’est pas seulement une compétence technique, mais un atout stratégique dans un monde de plus en plus numérique.