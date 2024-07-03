Voici une liste des fonctions couramment utilisées pour manipuler des tableaux en JavaScript :

1. **Array.from()** - Crée une nouvelle instance d'Array à partir d'un objet semblable à un tableau ou d'un objet iterable.
2. **Array.isArray()** - Détermine si l'objet passé est un tableau.
3. **Array.of()** - Crée une nouvelle instance d'Array avec un nombre variable d'arguments, indépendamment du nombre ou du type des arguments.

### Prototypes Methods

4. **concat()** - Fusionne deux ou plusieurs tableaux. Cette méthode ne modifie pas les tableaux existants, mais retourne un nouveau tableau.
5. **copyWithin()** - Copie une portion du tableau à un autre emplacement dans le même tableau et renvoie le tableau modifié, sans modifier sa longueur.
6. **entries()** - Renvoie un nouvel objet Array Iterator qui contient les paires clé/valeur pour chaque index du tableau.
7. **every()** - Vérifie si tous les éléments d'un tableau passent un test (fourni sous forme de fonction).
8. **fill()** - Remplit tous les éléments d'un tableau entre deux index avec une valeur statique.
9. **filter()** - Crée un nouveau tableau avec tous les éléments qui passent le test implémenté par la fonction fournie.
10. **find()** - Renvoie la valeur du premier élément du tableau qui satisfait la fonction de test fournie. Sinon, renvoie undefined.
11. **findIndex()** - Renvoie l'index du premier élément du tableau qui satisfait la fonction de test fournie. Sinon, renvoie -1.
12. **flat()** - Crée un nouveau tableau avec tous les éléments de sous-tableaux concaténés récursivement jusqu'à la profondeur spécifiée.
13. **flatMap()** - Applique une fonction à chaque élément du tableau, puis aplatit le résultat en un nouveau tableau.
14. **forEach()** - Exécute une fonction donnée sur chaque élément du tableau.
15. **includes()** - Détermine si un tableau contient une certaine valeur parmi ses entrées, renvoie true ou false selon le cas.
16. **indexOf()** - Renvoie le premier index pour lequel un élément donné peut être trouvé dans le tableau, ou -1 s'il n'est pas présent.
17. **join()** - Joint tous les éléments d'un tableau en une chaîne et renvoie cette chaîne.
18. **keys()** - Renvoie un nouvel objet Array Iterator qui contient les clés pour chaque index du tableau.
19. **lastIndexOf()** - Renvoie le dernier index pour lequel un élément donné peut être trouvé dans le tableau, ou -1 s'il n'est pas présent. Les tableaux sont parcourus de la fin au début.
20. **map()** - Crée un nouveau tableau avec les résultats de l'appel d'une fonction fournie sur chaque élément du tableau appelant.
21. **pop()** - Supprime le dernier élément d'un tableau et le renvoie. Cette méthode modifie la longueur du tableau.
22. **push()** - Ajoute un ou plusieurs éléments à la fin d'un tableau et renvoie la nouvelle longueur du tableau.
23. **reduce()** - Applique une fonction sur un accumulateur et chaque valeur du tableau (de la gauche vers la droite) afin de la réduire à une seule valeur.
24. **reduceRight()** - Applique une fonction sur un accumulateur et chaque valeur du tableau (de la droite vers la gauche) afin de la réduire à une seule valeur.
25. **reverse()** - Inverse l'ordre des éléments d'un tableau en place. Le premier élément du tableau devient le dernier et le dernier devient le premier.
26. **shift()** - Supprime le premier élément d'un tableau et renvoie cet élément. Cette méthode modifie la longueur du tableau.
27. **slice()** - Renvoie une copie superficielle d'une portion du tableau dans un nouvel objet tableau sélectionné du début à la fin (fin non incluse) où début et fin représentent l'index des éléments de ce tableau.
28. **some()** - Vérifie si au moins un élément du tableau passe le test implémenté par la fonction fournie.
29. **sort()** - Trie les éléments d'un tableau en place et renvoie le tableau.
30. **splice()** - Modifie le contenu d'un tableau en supprimant ou en remplaçant des éléments existants et/ou en ajoutant de nouveaux éléments en place.
31. **toLocaleString()** - Renvoie une chaîne de caractères représentant les éléments du tableau. Les éléments sont convertis en chaînes de caractères à l'aide de leurs méthodes toLocaleString respectives.
32. **toString()** - Renvoie une chaîne de caractères représentant les éléments du tableau.
33. **unshift()** - Ajoute un ou plusieurs éléments au début d'un tableau et renvoie la nouvelle longueur du tableau.
34. **values()** - Renvoie un nouvel objet Array Iterator qui contient les valeurs pour chaque index du tableau.

Ces méthodes couvrent une large gamme de manipulations et d'opérations possibles sur les tableaux en JavaScript.
