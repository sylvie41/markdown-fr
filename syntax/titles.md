# Titres


Comme nous venons de commencer la rédaction d'un document markdown, nous avons besoin d'un titre et de quelques sous-titres.

Markdown support deux types de titres, le Setext et le atx.

Les titres Setext sont "soulignés", soit avec le signe égal (pour les titres h1), soit par les tirets (pour le signe h2). Prenons un exemple :

```
Voici un h1
===========

Voici un h2
-----------
```

Quelque soit le nombre de égal ou tirets utilisés, cela fonctionnera.

Les titres Atx utilisent entre un et six dièses au début de la ligne, qui correspondent au niveau du titre voulu. Prenons un exemple :

```
# Voici un h1

## Voici un h2

###### Voici un h6
```

Nous pouvons aussi, si nous le souhaitons, "fermer" les titres Atx. C'est purement esthétique - nous pouvons l'utiliser si nous pensons que cela rendra mieux. Il n'est pas obligatoire de mettre autant de dièses à la fin qu'au début (le nombre de dièses déterminant le niveau du titre):

```
# Voici un h1 #

## Voici un h2 ##

### Voici un h3 ######
```


---

Voici un quiz sur les titres en markdown.

Selectionnez le bon titre :
- [x] `# hello`
- [ ] `#hello`

> Le titre a besoin d'un espace entre le dièse et le texte.

Selectionnez le bon titre :
- [ ]  
```
teste
#####
```
- [x]   
```
teste
=====
```

> Seul les '=' et les "-" sont acceptés pour souligner les titres.

---


