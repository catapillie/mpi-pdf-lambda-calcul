## Lambda-calcul, typage et inférence : pour un MPI

> [!NOTE]
> I've considered translating the document to English, but right now I'm not 100% certain I'll actually do it. It's a lot of work. Nonetheless, contributions are welcome, and would be greatly appreciated!

*[Accès au fichier PDF](./source/exposé.pdf).*

### Notes de l'auteur

Ce repo contient le code source LaTeX d'un document support pour un exposé que j'ai donné à mes camarades, lors de ma deuxième année de classe préparatoire (en filière MPI). L'exposé s'est déroulé sur deux séances de deux heures—je n'ai pas eu le temps de tout aborder.

Il avait pour but de donner une introduction « brève » au lambda-calcul, quelques applications (la représentation des booléens et entiers de Church, les tuples, les listes, la récursivité, etc...). Dans une deuxième partie l'exposé étend le lambda-calcul au lambda-calcul simplement typé $\left(\lambda_\rightarrow\right)$, et présente quelques preuves sur l'exécutions de programmes bien typés. Enfin une dernière partie (qui n'a pas été abordée) présente un algorithme bien connu de Hindley-Milner pour l'inférence de type dans le contexte du langage OCaml. Le choix de ce langage s'inscrit (bien entendu) dans le cadre du programme de MP2I/MPI (à ce jour en 2025).

Une dernière partie est laissée non-rédigée par manque de temps de et motivation, et visait à présenter d'autres extensions de systèmes de types, i.e. un bref aperçu de ce qui est possible avec d'autre théories.

Il y a sûrement pleins de fautes dans le document, qui a été rédigé très très vite (étant donné que j'avais cours pendant la même période). Des corrections sont les bienvenues, que ce soit directement dans le [fichier .tex source](./source/exposé.tex), ou en me contactant directement, sur Discord par exemple: `@catapillie`.

Bonne lecture !

### Liste des corrections
* [__3 mai 2025__](https://github.com/catapillie/mpi-pdf-lambda-calcul/commit/b58e2c10ac81600553c891af498abc8fd0c9a0dd)
  * typo "appellé" -> "appelé".
  * erreur dans la condition d'application de la substitution "`FV(a_1)`" plutôt que "`FV(b)`".
* [__3 mai 2025__](https://github.com/catapillie/mpi-pdf-lambda-calcul/commit/77c5bf9098207b87ad744de217f6ff368cefe2f7)
  * typo "ou nous" -> "ou non".
