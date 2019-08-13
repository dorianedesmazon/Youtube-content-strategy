# Youtube-content-strategy

Un youtubeur déjà très célèbre que nous appellerons Normal par soucis d'anonymat, souhaite (re)devenir le numéro 1 grâce à l'analyse de données. Il fait appel à toi pour trouver une stratégie lui permettant de gagner encore plus d'abonnés. Dans ce challenge tu vas utiliser le clustering pour l'aider.  



Tu disposes d'un dataset YoutubeFRvideos.csv. Il contient une liste de vidéos du domaine Youtube français ainsi que d'autres informations utiles. Un autre fichier YoutubeFR_category_id au format json permet de faire correspondre la category_id de YoutubeFRvideos.csv qui est numérique à son nom au format texte.  

YoutubeFRvideos.csv. 
YoutubeFR_category_id.json.  


Après avoir transformé le fichier YoutubeFRvideos.csv en dataframe, ajoute une colonne et nomme la category_title. Remplis la grâce aux valeurs title du fichier YoutubeFR_category_id.json.Ensuite utilise le Kmeans sur les colonnes ci-dessous du dataset pour trouver des clusters (à toi de choisir leur nombre) :  


category_id. 
views. 
likes. 
dislikes  
comment_count. 


Analyse les clusters en comparant les labels attribués aux individus et les valeurs des colonnes utilisées pour le clustering. Aide toi de visualisations pour cela. Propose à Normal une stratégie qui le permettra de (re)devenir le bosse sur Youtube.
Fournis ton notebook de travail commenté et contenant des visualisations, avec tes suggestions de stratégie.
