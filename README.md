Ce repository n'existe pour l'instant que dans le cadre d'une plus grande compréhension des fonctions natives relatives au Array de ma part. Comment savoir quelle fonction utiliser dans un cas ou un autre, quelles sont les meilleures performances, etc...

# Array methods


## Ces méthodes ne modifient pas le tableau initial

Besoin de vérifier que tous les éléments du tableau répondent à une seule et même condition ? 
=> Array.every()

Besoin de soumettre chaque valeur à une condition et ne remplir l'array de retour qu'avec les valeurs ayant renvoyées un true ? 
=> Array.filter()

Besoin de récupérer le premier élément d'un tableau à valider une condition ? 
=> Array.find()

Besoin de récupérer l'index du premier élément d'un tableau à valider une condition ? 
=> Array.findIndex()

Besoin de savoir si une valeur existe dans un tableau ? 
=> Array.includes()

Besoin de récupérer l'index d'une valeur présente dans un tableau ? 
=> Array.indexOf()

Besoin de récupérer un tableau avec chaque résultat transformé selon une même fonction ? 
=> Array.map()

Besoin de transformer les éléments d'un tableau pour obtenir un nouveau tableau OU une valeur ? 
=> Array.reduce()

Besoin de transposer les éléments d'un tableau en l'inversant totalement ? 
=> Array.reverse()

Besoin d'obtenir une copie de tableau en réduisant les éléments via des index ? 
=> Array.slice()

Besoin de savoir si au moins un élément de tableau répond à une condition ? 
=> Array.some()

Besoin d'obtenir le contenu du tableau sous forme de string séparée par des virgules ? 
=> Array.toString()

Besoin d'obtenir le contenu du tableau sous forme de string en choisissant le séparateur ? 
=> Array.join()






## Ces méthodes ne modifient pas le tableau initial et crééent un itérateur

// Très peu performant !! Préferer si possible Array.keys() pour les clés et Array.values() pour les valeurs
Besoin d'obtenir un itérateur à partir du tableau renvoyant et la valeur, et la clé ? 
=> Array.entries()

Besoin d'obtenir un itérateur à partir du tableau renvoyant la clé de l'élément ?
=> Array.keys()

Besoin d'obtenir un itérateur à partir du tableau renvoyant la valeur de l'élément ?
=> Array.values()





## Ces méthodes modifient le tableau initial 

Besoin de récupérer le dernier élément d'un tableau ? 
=> Array.pop()

Besoin de récupérer le premier élément d'un tableau ? 
=> Array.shift()

Besoin de réduire un tableau en supprimant un élément via un index ? 
=> Array.splice()

Besoin de trier un tableau suivant une fonction particulère ? 
=> Array.sort()



