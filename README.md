### Smart-Mobile-Works-1.0-GoogleCloudFunction
 Ce repository constitue la liaison entre la deuxieme et la troisieme partie. 
 
 Cette liaison consiste à creer une fonction Cloud (Service FaaS);
 
 Cette fonction est associée à un déclencheur spécifique.
 
 Le type de déclencheur détermine comment et quand votre fonction s'exécute.
 
 Dans notre cas le declencheur est Cloud PUB/SUB.
 
 Les messages reçus de ce declencheur sont dirigés vers le FireStore de Firebase.
 
 ### PS: Il faut faire attention dans cette étape aussi  à l'authentification et l'implementation du fichier JSON generé par Firebase pour avoir accès 
