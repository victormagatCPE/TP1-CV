<h1> Victor Magat - HTML CSS </h1>

<h2> 1) HTML </h2>

<h3> Exercice 0 </h3>

Version corrigée du code :

```html
<!DOCTYPE html>
<html>

<head>
  <title>Page à valider</title>
  <meta charset="utf-8">
</head>

<body>
  <div id="preamble">
    Menu:
    <table>
      <tr>
        <th><a href="cpe.fr">Le site de CPE</a></th>
        <th><a href="w3.org"><img width=50 src="img/W3C.png" alt="Erreur">Le site du W3C</a></th>
      <tr>
        <td></td>
        <td><a href="http://validator.w3.org/">Validateur du w3c</a></td>
      </tr>
      <tr>
        <td><a href="http://jigsaw.w3.org/css-validator/">Validateur CSS du w3c</a></td>
      </tr>
    </table>

    <h2>Changer la couleur</h2>
    <input id="background-color" name="couleur" type="color" />
  </div>
  <div id="corps">
    <h1>Petit texte</h1>
    <div id="mw-content-text" class="mw-content-ltr" lang="fr" dir="ltr">
      <p>
        L'<b>accessibilité du web</b>
        est la problématique de l'accès aux
        <a title="World Wide Web" href="https://fr.wikipedia.org/wiki/World_Wide_Web">services et contenus en ligne</a>
        non seulement pour les
        <a title="Handicap" href="https://fr.wikipedia.org/wiki/Handicap">handicapés</a>
        et les
        <a title="Vieillesse" href="https://fr.wikipedia.org/wiki/Vieillesse">seniors</a>
        , mais aussi de manière plus générale pour tous les utilisateurs qui ne disposent pas du confort offert par un ordinateur de bureau situé dans une pièce tranquille
        . En effet son application concerne également les utilisateurs « normaux » placés dans des situations moins confortables comme avec un téléphone mobile, une tablette
        … ou placés en situation particulière de bruit, de dimension d’affichage,
        <i>etc</i>
        . Définie par des normes
        <a title="Technique" href="/wiki/Technique">techniques</a>
        établies par la
        <i>
          <a title="Web Accessibility Initiative" href="https://fr.wikipedia.org/wiki/Web_Accessibility_Initiative">
            <span class="lang-en" lang="en" xml:lang="en">Web Accessibility Initiative</span>
          </a>
        </i>
        (WAI) du
        <i>
          <a title="World Wide Web Consortium" href="/wiki/World_Wide_Web_Consortium">
            <span class="lang-en" lang="en" xml:lang="en">World Wide Web Consortium</span>
          </a>
        </i>
        (W3C), elle nécessite un traitement tout au long du cycle de vie d'un
        <a title="Site web" href="/wiki/Site_web">site web</a>
        , par l'ensemble de ses acteurs, via des méthodes d'applications, des référentiels métiers et une démarche de suivi. Bien qu'elle soit une composante et un levier d'amélioration de leur qualité globale, le degré d'accessibilité effectif des
        sites Web reste très faible en 2008
        .
      </p>
      <p></p>

      <h2 style="color:green">Normes d'accessibilité internationales</h2>

      L'accessibilité Web dépend de plusieurs composantes interdépendantes :
      <ul>
        <li>le contenu Web, c'est-à-dire « l'ensemble de l'information et de l'expérience sensorielle qui est communiquée à l'utilisateur par le biais d'un agent utilisateur, incluant le code ou le balisage qui définit la structure du contenu, sa
          présentation et les interactions avec lui »W3C 8 ;</li>
        <li>les agents utilisateurs qui exploitent le contenu et le restituent aux internautes : navigateurs, plugins, etc. ;</li>
        <li>les technologies d'assistance logicielles (lecteurs d'écran, logiciels d'agrandissement, etc.) et matérielles (claviers adaptés, commutateurs, etc.) ;</li>
        <li>les outils d'édition du contenu ;</li>
        <li>les outils d'évaluation de l'accessibilité Web ;</li>
        <li>les développeurs de contenu, d'agents utilisateurs, de technologies d'assistance, d'outils d'édition et d'évaluation.</li>
      </ul>
      Pour permettre le développement de l'accessibilité à travers ces composants, le W3C a créé des recommandations à travers le projet Web Accessibility Initiative (WAI) créé en 1996. Ces recommandations sont organisées selon trois points de vue
      :
      <ol>
        <li> les outils de production de contenu doivent d'une part pouvoir être utilisés par tous, et d'autre part autoriser et favoriser la production d'un contenu accessible. Il s’ensuit qu'ils doivent suivre des lignes de conduite particulières
          ;
          ces lignes de conduite sont répertoriées dans les Authoring Tools Accessibility Guidelines ;</li>
        <li>le contenu mis en ligne lui-même doit être accessible ; c'est ce que l'on entend habituellement par l'accessibilité du Web et dont les recommandations sont regroupées dans les Web Content Accessibility Guidelines ;</li>
        <li>afin de tirer parti de ce contenu accessible, les outils de consultation (par exemple les navigateurs Internet) doivent être utilisables par tous et exploiter les informations spécifiques qui ont été ajoutées aux contenus pour les
          rendre
          accessibles. Les lignes de conduite pour les outils de consultation sont exposées dans les User Agent Accessibility Guidelines.</li>
        <li>La WAI intervient également lors de l'élaboration de toutes les spécifications du W3C afin de s'assurer de leur compatibilité avec les directives d'accessibilité. Son groupe de travail sur les protocoles et les formats est ainsi à
          l'origine d'améliorations du format HTMLW3C 9 ainsi que des feuilles de style en cascade (CSS)W3C 10. Enfin, d'autres recommandations en chantier sont consacrées notamment au interfaces riches, ou à XML, SVG, SMILW3C 11.
        </li>
      </ol>
    </div>
    <hr>
    <p>Ce qui suit et cette image (ancien logo CPE) n'ont rien à voir avec le sujet : <img src="http://upload.wikimedia.org/wikipedia/fr/d/d3/Logo_cpe_lyon.gif" alt="Erreur">, mais ils sont là, et aussi vrai que 0 &lt; 1, elles y <i>resteront</i>.
    </p>
    <p>Proverbe extrait du site <a href="https://www.proverbes-francais.fr/"><i>proverbes français</i></a></p>

    Mieux vaut ne pas commencer que de cesser. <strong>Les proverbes et locutions latines (1835).</strong> Suivez l'actualité de ce site en consultant régulièrement notre rubrique consacrée aux derniers proverbes publiés extraits d'anciens
    dictionnaires des proverbes français ou étrangers.
  </div>
</body>

</html>
```
<h3> Exercice 2 et 3 </h3>

[lien pour le site du CV](https://victormagatcpe.github.io/TP1-CV/)

<h2> 2) CSS </h2>

<h3> Exercice 0 </h3>

fichier html corrigé :

```html
<!DOCTYPE html>
<html>

<head>
	<title>Titre de la page</title>
	<meta charset="utf-8">
	<link rel="stylesheet" href="style.css">
</head>

<body>

	<p>If you need to relax, press the
		<strong><u>S</u></strong>tress reliever!
	</p>

	<code>
		<label for="texta">nom :</label>
		<input id="texta" type="text" accesskey="a" />
	</code>

	<button accesskey="s">Stress reliever</button>

	<br>

	<div class="titre">
		<em>
			Titre
		</em>
	</div>


	<p>Proverbe extrait du site <a href="https://www.proverbes-francais.fr/"> <i>proverbes français</i></a></p>

	Mieux vaut ne pas commencer que de cesser. <span class="texteVert">Les proverbes et locutions latines (1835).</span> Suivez l'actualité de ce site en consultant régulièrement notre rubrique consacrée aux derniers proverbes publiés extraits
	d'anciens
	dictionnaires des proverbes français ou étrangers.

	<hr>

	<input id="background-color" name="couleur" type="color" />

	<p>Ce qui suit et cette image n'ont rien à voir avec le sujet : <img src="http://upload.wikimedia.org/wikipedia/fr/d/d3/Logo_cpe_lyon.gif" alt="Erreur">, mais ils sont là, et aussi vrai que 0&lt;1, elles y <i>resteront</i>.</p>

	<table>
		<tr class="subtitles">
			<td><b>Titre de colonne 1</b></td>
			<td>
				<h2>Titre de colonne 2</h2>
		</tr>
		<tr>
			<td>Une première case</td>
			<td>Une deuxième case</td>
		</tr>
		<tr>
			<td>Une troisième...
		<tr>
			<td>... et la dernière&nbsp;!
	</table>

</body>

</html>
```

fichier css corrigé :

```css
label {
  background-color: white;
  color: red;
}

em {
  text-align: center;
}

span.textVert {
  background-color: white;
  color: green;
}

body {
  background-color: azure;
  color: black;
}

.titre {
  text-align: center;
  font-size: 30px;
}

table {
  background-color: lime;
  color: black;
}

table tr td{
  text-align: left;
  border: 1px solid black;
}

.subtitles {
  background-color: lime;
  color: yellow;
}
```

L’intérêt d’une telle validation est de permettre aux lecteurs d’écran de pouvoir lire sans problème un code vérifié sans erreurs et donc de permettre aux personnes malvoyantes de comprendre la page sur laquelle elles sont.

<h3> Exercice 1 </h3>

- div p{} 
 ce sélecteur s'applique sur tous les paragraphes à l'intérieur d'une balise div
- div ~ p {}; 
 ce sélecteur s'applique sur les pararaphes qui sont utilisés après une div. 
- h2#byName, span.byClass{}; 
 ce sélecteur s'applique à tous les h2 qui ont un id byName et tous les spans qui ont une class byClass. 
- div#byName > Img:nth-child(2n) {}; 
 ce sélecteur s'applique aux images paires (2n) filles directes d'une div avec un id byName 
- p#byName > b:hover {}; 
 ce sélecteur s'applique aux éléments en gras fils directes des paragraphes dont l'id est byName lorsque l'utilisateurs passe sa souris dessus. 
- div#byName > p:nth-child(2n+1) span[class*=re] {}; 
 ce sélecteur s'applique aux paragraphes impairs et aux spans dont la classe contient "re" à un endroit. Ils doivent aussi être descendants directs d'une div dont l'id est "byName" 
- article p+p.description:nth-child(2n+1) {}; 
 ce sélecteur s'applique aux paragraphe de la classe description, impairs (2n+1) qui sont juste après un paragraphe ou un article

<h3> Exercice 2 </h3>

fichier html :

```html
<!DOCTYPE html>
<html>

<head>
  <title>Exo 2</title>
  <link rel="stylesheet" href="style.css" type="text/css" media="screen" />
  <meta charset="utf-8">
  <meta name="keywords" content="CV, Curriculum Vitae, Etudiant, CPE" />
</head>

<div class="title bgc">
  <p>ma boite en cibersécurité</p>
</div>

<div class="spans">
  <span>menu1</span>
  <span>menu2</span>
  <span>menu3</span>
</div>

<div class="bgc">
  <h1>News Section</h1>

  <div class="">
    <h2>News Article</h2>
    <p>bla bla bla ...</p>
    <p>bla bla bla ...</p>
    <p>bla bla bla ...</p>
  </div>

  <div class="">
    <h2>News Article</h2>
    <p>bla bla bla ...</p>
    <p>bla bla bla ...</p>
    <p>bla bla bla ...</p>
  </div>
</div>

<div id="copyrights" class="bgc">
  <p>© maboite Cybersécurité. All rights reserved.</p>
</div>

</html>
```

fichier css :

```css
.title {
  color: blue;
  font-weight: bold;
  padding: 3px;
  font-size: 25px;
  padding: 10px;
}

.bgc {
  background-color: rgba(78, 210, 202, 0.15);
}

div {
  border: solid 1px black;
  margin-bottom: 10px;
  padding: 10px;
  background-color: white;
}

.spans {
  border: none;
}

span {
  margin-right: 10px;
}

#copyrights {
  color: blue;
}

```

<h3> Exercice 3 </h3>

[lien pour le site du CV](https://victormagatcpe.github.io/TP1-CV/)
