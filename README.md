README TP1 Appli Design
Sujet : Reproduire un design Figma sur Android Studio (XML)
Lien des designs :  https://www.figma.com/file/6Y0MqDlAYqppkI1uefrnE1/TP-Application-design?type=design&node-id=0-1&mode=design&t=NlxffDnkfE5Dngec-0
Lien GITHUB repository : https://github.com/dikotyannick/AppliDesign_MyApplication 

Design Choisi : Design 5 (les plantes)
•	Il s'agit du code XML de mise en page pour une application de soins des plantes, comprenant une barre de recherche et des images de plantes avec des détails. J’ai eu à utiliser le code Android sur Figma de certains éléments pour m’aider dans l’écriture en XML (dimensions & couleurs notamment)
Barre de Recherche
•	La barre de recherche verte transparente est mise en œuvre à l'aide d'un `CardView` avec un `LinearLayout` horizontal. Elle contient des options telles que "Houseplant", "Evergreen trees " et "Palm Trees".
 Images de Plantes
•	La section des images de plantes est structurée à l'aide d'un `RelativeLayout` contenant un `LinearLayout` vertical. Chaque plante est représentée par un `CardView` avec une image et du texte, affiché dans un `GridLayout` (2x2) avec deux colonnes. Les images et les textes sont centrés verticalement et horizontalement dans chaque `CardView`.
Images à Droite
•	Deux images (`imageView6` et `imageView7`) sont positionnées dans le coin supérieur droit à l'aide d'un `LinearLayout` horizontal comme ça elle se déplacent ensemble. L'attribut `android:gravity="end"` est utilisé pour les aligner à droite.  
Ce qui a le moins fonctionné : 
Même en modifiant cette partie c’est-à-dire en changeant le « dp » je n’ai pas pu bouger/baisser les images en haut à droite c’est pourquoi elles ne sont pas au même niveau que la plante en haut à gauche : android:layout_marginBottom="50dp"
•	Faire dépasser les images des 4 plantes du cadre malgré la modification du cadreView & le changement de Width/Height des plantes. Lorsque je changeais les valeurs, les cadres disparaissaient et devenaient beaucoup trop grand.
•	 Les boutons de flèches à droite de chaque image je n’ai pas pu les mettre MEME AVEC LA FONCTION ImageButton car peu de places sur les cadres et les encercler en vert a été aussi compliqué. Mais j’avais bien l’image dans le drawable : « bouton_fleche »




Captures d'écran DESIGN ATTENDU vs MON DESIGN (voir readme pdf)

                   
