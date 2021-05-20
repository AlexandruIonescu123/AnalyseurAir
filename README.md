# AnalyseurAir

Ce projet est réalisé dans le cadre du module Communication Sans Fil en Licence 1 à l'Université Nice Sophia Antipolis.

Dans l'esprit de la domotique, j'ai choisi de travailler sur un système analyseur de la qualité de l'air ambiant. N'ayant pas d'expérience antérieure avec Arduino ou la programmation en général, je me suis dit que ce serait un bon point de départ. 

Cet analyseur recueille la température, l'humidité et enfin la concentration de particules fines dans l'air, qui peuvent être source d'allergies, ou tout simplement polluantes. 

Liste de matériel : 

* carte Arduino
* capteur DHT22 température et humidité
* capteur PPD42 particules fines
* câbles mâle-mâle

Au départ, je me suis proposé de faire en sorte que le système recueille les données à des intervalles précis, puis les envoie par l'intermède de LoRaWAN. De plus, toujours dans l'esprit de la domotique, toute personne devraient être capable de l'utiliser facilement ; c'est pour cela que je pensais montrer les différents paramètres à l'aide de l'application Cayenne, très user friendly, avec une interface propre. 

Néanmoins, après avoir passé plus de temps avec ce projet, je me suis rendu compte de quelques limitations. Premièrement, c'est un projet rudimentaire : sa fonction est limitée. Effectivement, il aurait été intéressant de pousser l'idée plus loin, attacher un servomoteur par exemple et simuler l'ouverture d'une fenêtre si la chambre devient chargée. Et deuxièmement, même si le protocole LoRaWAN présente l'avantage de pouvoir envoyer des données sur des longues distances, une gateway LoRa est nécessaire pour l'envoi des données, or une telle gateway n'est pas présente partout. J'ai dû par conséquent travailler près, ou sur le campus, car il n'y avait aucune gateway à proximité de ma maison. Pour un projet de ce type, il serait plus envisageable de passer par un protocole WiFi.

En conclusion, ce projet m'a permis de découvrir Arduino et sa programmation, ainsi que le protocole de communication LoRa. Pour débuter dans le monde Arduino et des télécommunications de ce type, c'est un projet parfait, dont l'idée peut être d'autant plus perfectionnée pour ceux qui souhaitent d'aller plus loin dans ce domaine.

