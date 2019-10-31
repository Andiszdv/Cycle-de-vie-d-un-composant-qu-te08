Tu vas reprendre l'application développée pour le challenge de la quête "React 07 - Consommer une API". Pour cela, crée un fork de ta propre CodeSandbox publiée à cette occasion. CodeSandbox te demandera Do you want to fork your own sandbox?, ce à quoi tu devras répondre OK.

Modifie ensuite son code de façon à :

•
effectuer la requête à l'API de façon automatique, en utilisant componentDidMount

•
partir d'une valeur vide (null) dans le state, et effectuer l'affichage des données reçues de façon conditionnelle, en testant la valeur dans le state. Dans le cas où on n'a pas encore les données, affiche un message quel qu'il soit : "no data", "loading", etc.

Tu peux garder le bouton permettant de charger une nouvelle citation.

Critères de validation :
•
Le code est publié sur CodeSandbox

•
Une requête API est lancée depuis componentDidMount

•
Un rendu conditionnel est mis en place, pour n'afficher la citation qu'à partir du moment où on l'a dans le state.
