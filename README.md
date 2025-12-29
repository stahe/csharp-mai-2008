# Introduction au langage C#

Ce dépôt contient le support de cours pour l'apprentissage du langage C#.

🔗 **[Consulter le cours en ligne](https://stahe.github.io/csharp-mai-2008/)**

## Présentation du langage et de la plateforme .NET

C# est un langage apparu officiellement en février 2002, conjointement avec la plate-forme .NET 1.0 de Microsoft à laquelle il est intrinsèquement lié. C# nécessite cet environnement d'exécution pour fonctionner, lequel fournit un ensemble très important de classes.

En première approche, la plate-forme .NET est un environnement d'exécution analogue à une machine virtuelle Java, avec quelques différences notables :

**Multi-plateformes** : Si Java s'exécute sur différents OS depuis ses débuts , .NET était initialement réservé à Windows. Cependant, le projet **[Mono](http://www.mono-project.com)** permet désormais d'utiliser .NET sur des systèmes comme Unix et Linux.


**Multi-langages** : La plate-forme .NET permet l'exécution de programmes écrits en différents langages, pour peu que leur compilateur produise du code IL (Intermediate Language). Toutes les classes .NET sont disponibles pour ces langages, ce qui tend à gommer les différences entre eux ; le choix d'un langage .NET devient alors une affaire de goût plus que de performances.



## Évolution du langage

En 2002 (C# 1.0), le langage était très proche de Java, facilitant la transition d'un environnement à l'autre. Depuis, les spécificités de chaque langage se sont affirmées.

Avec l'arrivée de C# 3.0 et du framework .NET 3.5, de nombreuses nouveautés sont apparues, dont la plus importante est probablement **LINQ** (Language INtegrated Query). LINQ permet de requêter de façon uniforme (proche de SQL) des tableaux, des listes, des bases de données ou des fichiers XML.

> 
> **Note** : Ce document n'est pas un cours exhaustif et n'aborde pas LINQ. Il est destiné à des personnes connaissant déjà la programmation et souhaitant découvrir les bases de C#. Il s'agit d'une révision du document originel paru en 2002.
> 
> 

## Sources et Bibliographie

Plusieurs ouvrages et ressources ont aidé à la rédaction de ce cours :

* *Professional C# programming*, Editions Wrox
* *C# et .NET* (et sa mise à jour *C# et .NET 2005*), Gérard Leblanc, Editions Eyrolles
* La documentation MSDN de Visual Studio Express 2008
* *C# 3.0 in a Nutshell*, Joseph et Ben Albahari, Editions O'Reilly (recommandé)

## Ressources

Les codes source des exemples de ce document sont disponibles à l'adresse suivante :
👉 **[http://tahe.developpez.com/dotnet/csharp/](http://tahe.developpez.com/dotnet/csharp/)**