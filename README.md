# Td : Analyse de sites 

## To-do list

1. [Anysurfer](https://www.anysurfer.be/fr/en-pratique/directives)
1. [GT-Metrix](https://gtmetrix.com/)
1. Repérer les problèmes existants sur le site
1. Création de contexte pour les tests utilisateurs
1. Tests utilisateurs (voir Amélie Boucher)
1. Synthèse des problèmes rencontrer
1. Refonte du site (attention difficile et bcp)

## Anysurfer

1. La navigation
	1. La totalité est utilisable au clavier : Oui, mais l'outline est difficile à reconnaître sur les images
	1. Les intitulés des liens sont significatifs : Il y a des aria-labels
1. Contenu
	1. Texte
		1. Chaque page possède un titre significatif
		1. 
		1. La langue de chaque page est indiquée lang="de" ou lang="fr-BE"
	1. Images
		1. Chaque image a un attribut alt : Non car ce sont des images de décoration.
		1. Les images complexes sont décrites par un texte : Oui mais avec des aria-label et pas des alts
		1. Les images d'arrière-plan qui contiennent de l'information ont une variante accessible : Oui, avec des aria-label
	1. Tableaux de données 
		1. /
	1. Vidéo et sons
		1. /
1. Mise en forme
	1. Texte
		1. Les liens sont fascilement identifiable comme tels : Oui, car il y a un changement de couleur. Mais il y a un porblème de reconnaissance dans les liens qui sont sous forme de cartes.
		1. Les espaces etc ne sont pas utilisés pour formatter
	1. Mise en page
    	1. Le contenu de la page suit un ordre logique /
    	1. Chaque cadre possède un nom et un titre significatifs NON
	1. Mouvement
    	1. Les textes et les images ne clignotent pas plus de 3 fois par seconde /
    	1. Les animations peuvent être arrêtées /
	1. Couleur et autre information visuelle
		1. Le contenu est compréhensible pour quelqu'un qui ne peut distinguer les couleurs : Oui, le contraste est assez élevé.
1. Interactivité
    1. Formulaires
        1. Les labels et éléments des formulaires sont intimement liés : non pas de for sur les labels
        1. Les champs sans label sont décrits par un tooltip : /
        1. L'étiquette des champs de saisie de date indique le format requis : Oui
        1. Les champs de formulaires liés sont regroupés par un fieldset : Non existant et remplacer par des balises de titrage
        1. Les regroupements d'éléments dans une liste déroulante se font avec optgroup : /
        1. Les champs obligatoires sont annoncés dans leur label : Manque dans la page d’inscription
        1. Chaque formulaire a un bouton d'envoi visible : Pas de bouton dans le champ de recherche
        1. Lors de la validation, les erreurs sont indiquées et expliquées par du texte : Oui
    1. Contraintes de temps
        1. Les actions ne sont pas strictement liées à des contraintes de temps : V
    1. Il est possible d'arrêter les mises à jour automatiques  /
    1. Les rafraîchissements dynamiques sont annoncés : Oui
    1. Les fenêtres pop-up n'apparaissent pas automatiquement : Non
1. Plug-ins et documents téléchargeables
    1. Flash /
    1. Microsoft Silverlight /
    1. Documents Office /
    1. Documents PDF /
