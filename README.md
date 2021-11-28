### Auteur: CAMARA Laby Damaro

### github: https://github.com/camara94

### site: https://stardevcgroup.com/

# Push Notification Flutter Firebase

Dans ce tutoriel, nous allons réaliser une application mobile en flutter qui va recevoir des notification venant de Firebase cloud messaging, nous allons également utiliser des outils comme **Postman** et **curl** pour notifier l'application.


## Comment Créer un Projet Flutter avec package Personnaliser

`flutter create --org com.stardevcgroup push_notification `

* **package: ** com.stardevcgroup 
* **nom du projet: ** push_notification

## Les Dépendances Utilisées dans le Projet

Pour ajouter des dépendance, on va le fichier **pubspec.yml** puis dans la section **dependencies**, on les ajoute.

* *firebase_core: ^1.10.0*
* *provider: ^6.0.1*

* *font_awesome_flutter: ^9.0.0*

* *fluttertoast: ^8.0.8*

* *firebase_auth: ^3.2.0*

* *firebase_messaging: ^11.1.0*

* *flutter_local_notifications: ^9.1.4*

## Création et Configuration d'un Projet Firebase

![image 13](images/13.png)

On donne un mon au choix à notre projet Firebase puis  cliquez sur **Continue**![image 1](images/1.png)

encore **Continue**

![image 2](images/2.png)



En suite on selectionne **Google Analytique**

![image 3](images/3.png)





![image 4](images/4.png)



On a trois types de projets:

* **IOS: ** pour les projet les applications **IOS**
* **Android: ** pour les applications **Android**
* **Web: ** pour les applications **Web**

Puis que je travaille sur une application **Android**, alors je sélectionne le projet **Android**

![image 5](images/5.png)



![image 14](images/14.png)

On se rend sur le site  [https://developers.google.com/android/guides/client-auth](https://developers.google.com/android/guides/client-auth) pour générer une SH1 ou SH256 en fonctionne de notre système d'exploitation.

Par exemple moi je suis sous Windows donc je prend cette ligne de commande, je colle dans mon **CMD** pour avoir le **SHA1** et **SHA256**

![image 6](images/6.png)

Voici le résultat de cette commande:

![image 6](images/7.png)



Je colle le **SHA1** ci-dessous:

![image 8](images/8.png)

Puis je copie le fichier **JSON**

![image 9](images/9.png)

Je le colle dans le projet **app** de mon projet  **Android**

![image 10](images/10.png)



Puis je copie et colle la première ligne cocher dans le fichier **build.gradle** qui se trouve directement dans le dossier **Android**

en suite les autres dans le fichier **build.gradle** qui se trouve dans le dossier **Android/app**

![image 11](images/11.png)

Puis c'est terminé

![image 12](images/12.png)

