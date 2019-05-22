# Data_5sc

Voici le lien vers la table de données Hmvl : https://drive.google.com/drive/folders/11S4WY5FwE0HQMsaEEJR_uO9Jx43mJafU?usp=sharing
sous le nom de' Hmvl_1802_2402_2.csv'.

Ce fichier  représente les données individuelles qui sont stockées dans un fichier dit HMVL(Heure Minute Vitesse Longueur).
La table de données contient une ligne par passage d'un véhicule détecté sur un point de mesure du réseau.

Le format texte de chaque ligne est le suivant: « code ;id ; equipement_id ; date ; voie ; horodatage ; vitesse ; longueur » .

L’identité de la station est représentée par deux façons:
- Un code de 3 caractères par lequel nous pouvons connaitre la position d’une station SIREDO.( Par exemple : M7i où M7 signifie que la station est dans l’autoroute A0007, et le ’i’ minuscule indique le sens 2), et représente 90% des données.
- Un code de 20 caractères (Exemple : TPA-EXTBAU_RDTSTC002), et cela représente 10% des données.

La longueur de la table de données est de : 4.468.587 pour 18/02/2019 de 00:00 à 16:22 et elle contient les données de 139 stations.
Voici le lien vers la table STATIONS : https://drive.google.com/drive/folders/13iBqvdfa7oJupFo4XNljwHvju6sjYpsK.
Sous le nom de :  'df_STATIONS'. Cette dernière contient les stations et le pourcentage de leurs données par rapport à la totalité des données, et le fichier 'df_voie', contient la vitesse moyenne par voie.

Le fichier 'M7_i_j.csv' contient les données par voie des stations suivantes : M7i, M7I, M7j, M7J.
