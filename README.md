# TinyML---IA
## Projet1: En utilisant TensorFlow Lite, Arduino ainsi que la carte Nano 33 Sense BLE, réalisez un projet qui permet de détecter le signe Yes (✓) ainsi que le signe No(X)

Voici les étapes générales à suivre pour réaliser ce projet:

- Collectez des données d'entraînement pour les signes Yes (✓) et No (X) à l'aide      du code d’Arduino “IMU_Capture.ino”.

- Ensuite, utilisez TensorFlow Lite pour entraîner un modèle de reconnaissance de signes sur ces données.

- Téléchargez le modèle entraîné sur la carte Nano 33 Sense BLE → “ le fichier model.h sur colab “.

- Écrivez du code pour la carte Nano 33 Sense BLE qui utilise le modèle TensorFlow Lite pour détecter le signe Yes (✓) ou No (X) à partir des données en temps réel   capturées par les capteurs de la carte.

- Et enfin, testez le projet pour s’assurer qu'il fonctionne correctement et affiche les résultats de la détection de signes de manière cohérente.


 * Resultat obtenu: Voir le Dossier Projet_1 ainsi que les images.


## Projet 2: En utilisant la plateforme Edge Impulse, réalisez un projet qui permet de détecter les mots suivants: résistance, transistor, FPGA, microcontrôleur. Utilisez le mécanisme développé dans la première étape de ce projet pour faire clignoter la led L graduellement à chaque fois qu’on prononce un mot particulier. 


Voici les étapes générales à suivre pour réaliser ce projet:

- Créer un compte sur la plateforme Edge Impulse et se connecter.

- Créer un nouveau projet en sélectionnant "Sound classification" dans la liste des modèles prédéfinis.

- Suivre les étapes de la configuration initiale du projet, en sélectionnant le type de microcontrôleur et le matériel qu’on utilisera.

- Enregistrer des échantillons de voix (20x4 échantillons) pour chaque mot qu’on souhaite détecter (résistance, transistor, FPGA, microcontrôleur). 

- Entraîner le modèle en utilisant les échantillons d'enregistrement que nous avons précédemment ajoutés. Une fois l'entraînement terminé, nous voyons un score de précision pour chaque mot (94% dans l’ensemble).

- On télécharge le code généré par Edge Impulse sur notre microcontrôleur(Arduino Sense BLE). “ plutôt une bibliothèque dans notre cas ei-bambafall-project-1-arduino-1.0.1 “

- On ajoute/modifie du code pour faire clignoter la LED de manière graduelle chaque fois qu'un mot particulier est détecté.

- Et enfin, on teste notre projet en prononçant chaque mot devant la carte Arduino Sense BLE et en vérifiant que la LED clignote de manière appropriée.


Resultat obtenu: Voir le Dossier zippé Projet_2 ainsi que les images 

