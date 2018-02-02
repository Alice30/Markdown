# Markdown 

![](http://kirkstrobeck.github.io/whatismarkdown.com/img/markdown.png)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## I.&nbsp;&nbsp;&nbsp;Qu'est ce que Markdown? :
## II.&nbsp;&nbsp;Création de Markdown :
## III.&nbsp;&nbsp;Le format :
## IV.&nbsp;&nbsp;&nbsp;La syntaxe : 
## V.&nbsp;&nbsp;La continuité : 

&nbsp;
&nbsp;
&nbsp;
&nbsp;


## I. Qu'est ce que Markdown? : 

Markdown est un système d’édition et de formatage de texte, qui peut être lu par les humains et peut être facilement converti en HTML. Markdown possède :

* Sa propre syntaxe (cf partie V)
* Un script de conversion texte pour le convertir en HTML 
* Un format de fichier (cf partie IV).

Le but de Markdown est d'offrir une syntaxe facile à lire et à écrire, sans interpréteur particulier en mode texte. Malgré une syntaxe spécifique Markdown se veut épuré, et lisible même non convertis (cf 1ère photo partie de gauche), contrairement au langage balisé, qui peut être plus compliqué à comprendre.

De plus, une fois l'édition d'un fichier Markdown faite. On peut procéder à une conversion en HTML. Pour cela le script contenu dans le langage Markdown va enrichir le fichier des balises requises, donc le fichier sera converti en HTML (cf photo 2) et pourra être mise en forme par la suite par un navigateur.


&nbsp;
&nbsp;
&nbsp;
&nbsp;

La photo 1: ci dessous montre à gauche la syntaxe Markdown pure et à droite la conversion du contenu par un éditeur :
![](https://gitbookio.gitbooks.io/markdown/content/assets/preview.png)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

La photo 2: ci dessous montre à droite la syntaxe Markdown pure et à gauche la conversion du contenu en HTML :
![](http://tekeye.uk/md_cms/images/online-html-to-markdown.png)


## II. Création de Markdown 

Markdown a été créé en 2004 par John Gruber et Aaron Swartz. Les créateurs de Markdown trouvaient que ce n'était pas vraiment pratique de devoir mettre en forme manuellement des textes en HTML. Leur idée était de pouvoir mettre en forme du texte sans avoir besoin de recourir à la souris… et sans avoir besoin de taper souvent à la main des balises HTML. 

Depuis sa création, Markdown n'a pas connu d'évolution notoire de la part de ses auteurs. De plus, ce format n'a jamais été formellement standardisé


## III. Le format 

Comme je l'ai évoqué précedemment Markdown possède son propre format de fichier, enregistré avec l’extension .md (ou .markdown).
Ce format fichier est souvent utilisé pour créer de la documentation (projets, archives...) ou pour contenir des informations sur les autres fichiers d'un même répertoire, souvent nommé readme.md. 



## IV. La syntaxe

Les éléments de syntaxe du Markdown sont des caractères de ponctuation que l'on comprend même non convertis. En voici un petit condensé : 

##### Paragraphes

```
Ceci est un paragraphe de texte.

Ceci est un autre paragraphe de texte !

```

##### Emphase faible (italique)

```
Voici un mot *important* 
```

##### Emphase forte (gras)

```
Voici des mots **très importants**
```

##### Les titres

```
# Titre de niveau 1

## Titre de niveau 2

### Titre de niveau 3 ...
```

#### Les listes
##### Les listes à puces

```
* Une puce
* Une autre puce
* Et encore une autre puce !

```
##### Les listes à puces numérotées

```
1. Et de un
2. Et de deux
3. Et de trois

```

##### Les citations

```
> Ceci est un texte cité.
> Ceci est un texte cité.
>  !

```

##### Les liens

```
[Je suis un lien](https://gitbookio.gitbooks.io/markdown/content/syntax/titles.html) 
pour en apprendre plus sur la syntaxe Markdown!
```

##### Les images

```
![](http://uploads.siteduzero.com/files/420001_421000/420263.png)
```

##### Barre de séparation (sert pour créer également des tableaux)

```
-----------------
```




## V. La continuité

Comme je l'ai évoqué en première partie le script contenu dans le langage Markdown, procède à la conversion en HTML.
Aujourd’hui il existe de très nombreuses implémentations dans divers langages et des variantes augmentées de ce script pour générer du contenu lisible avec une mise en forme plus riche à partir du markdown. Tel que GitHub -pour les fichiers de documentation des projets- et Stack Overflow -pour écrire vos questions et vos réponses.


De nombreux éditeurs Markdown existent, pour une présentation plus claire et visuelle du contenu (sans la syntaxe Markdown visible).

Sous window : Typora, Markdownpad, WriteMonkey, Atom
Sous Mac : MacDown, Atom, Typora, Mou


