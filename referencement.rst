Analyse des données de la table Référencement
=============================================

Dans le cadre de l'initialisation du marché, le titulaire a établie une table des circuits, livrée sous la forme du fichier :  :download:`Référencement Lot 1 pour DiRIF - 29.07.22-1<_static/Référencement Lot 1 pour DiRIF - 29.07.22-1.xlsx>` 

On se propose ici d'analyser les données présentes dans cette table et d'en discuter la qualité.

Les 20 tunnels renseignés dans cette table sont : ``'A14', 'A86/NANTERRE', 'AMBROISE PARE', 'BELLE RIVE', 'BICETRE', 'BOBIGNY', 'BOISSY', 'CHAMPIGNY', 'CHENNEVIERES', 'ITALIE', 'LA COURNEUVE', 'LANDY', 'LUMEN', 'NEUILLY', 'NOGENT', 'NORTON', 'ORLY', 'SAINT CLOUD', 'SEVINES', 'TAVERNY'``

Les tunnels de Thiais, de Fontenay, de Fresnes et d'Antony qui étaient en travaux ne sont pas renseignés.
Le tunnel du Landy a été renseigné sur la base de son état avant les travaux.

Une partie des circuits n'est que partiellement renseignée. C'est en particulier le cas pour le nombre de luminaires. Certains tunnels tels que La Courneuve sont particulièrement mal renseignés.
On a calculé par tunnel dans la table ci-dessous, le nombre de circuits pour lesquels le nombre de luminaires est renseigné.

.. csv-table::
   :header: "Tunnel", "Nombre de circuits renseignés", "Nombre de circuits vides"
   :widths: 40, 10, 10
   :width: 30%

   A14,201,21
   A86/NANTERRE,84,1
   AMBROISE PARE,40,0
   BELLE RIVE,57,2
   BICETRE,77,7
   BOBIGNY,66,10
   BOISSY,19,0
   CHAMPIGNY,44,5
   CHENNEVIERES,29,0
   ITALIE,8,6
   LA COURNEUVE,1,23
   LANDY,23,17
   LUMEN/NORTON,36,14
   NEUILLY,16,0
   NOGENT,59,3
   ORLY,28,5
   SAINT CLOUD,48,0
   SEVINES,20,0
   TAVERNY,32,0

Pour le tunnel de La Courneuve, une seule ligne indique un nombre de luminaires. En examinant les 23 circuits associés à ce tunnel, on constate des valeurs significatives pour 3 circuits ce qui signifie probablement que plus d'un circuit était en service.

Pour certaines lignes les valeurs des champs *Information départ* &	*régime du départ* ne sont pas cohérentes, comme par exemple ci-dessous:

.. csv-table::
   :header: Information départ,régime du départ
   :widths:  30, 10

   NUIT TUNNEL SUD,	SECOURS
   NUIT TUNNEL NORD,	SECOURS
   ECLAIRAGE JOUR 1 TUNNEL SUD,	BASE






