# Activité Pratique N°5

## Objectif
L'objectif de cette activité pratique était de créer un Web service SOAP en utilisant JAX-WS, déployer ce service et tester ses opérations à l'aide d'outils tels que SoapUI, tout en créant également un client SOAP Java pour interagir avec le service.

## Détails de l'Activité

### 1. Création du Web service
Nous avons créé un Web service avec les fonctionnalités suivantes :
- Conversion d'un montant de l'euro en DH (Dirham marocain).
- Consultation d'un compte.
- Consultation d'une liste de comptes.

  ![image](https://github.com/ducloser90/SD_Activite5/assets/167253342/305ed049-dbd4-44ac-a9af-4cec2aa59fb3)

### 2. Déploiement du Web service
Le Web service a été déployé en utilisant un serveur JAX-WS, conforme aux spécifications et aux standards de déploiement.

![image](https://github.com/ducloser90/SD_Activite5/assets/167253342/ee41fe00-3db4-4b5f-a953-20e2e2715170)


### 3. Analyse du WSDL
Nous avons consulté et analysé le WSDL (Web Services Description Language) généré par notre service en utilisant un Browser HTTP. Cela nous a permis de comprendre la structure et les détails des opérations exposées par le service.

![image](https://github.com/ducloser90/SD_Activite5/assets/167253342/1cf42c2c-7564-4969-9cb3-f7034fb909bd)

![image](https://github.com/ducloser90/SD_Activite5/assets/167253342/647f11dc-0917-425d-ba17-68bd4d31c388)

### 4. Test avec SoapUI
Pour tester les opérations du Web service, nous avons utilisé SoapUI. Cet outil nous a permis de soumettre des requêtes SOAP aux différentes méthodes du service et de vérifier les réponses renvoyées.

![image](https://github.com/ducloser90/SD_Activite5/assets/167253342/192e8bda-e981-4f94-9c7d-12c6b23257d1)


### 5. Création d'un Client SOAP Java
Pour interagir avec le Web service depuis une application Java, nous avons effectué les étapes suivantes :
- Génération du Stub à partir du WSDL : Nous avons utilisé des outils comme `wsimport` pour générer les classes Java nécessaires à la communication avec le service.
- Création d'un client SOAP : Nous avons développé un client Java qui utilise les classes générées pour appeler les méthodes du Web service et traiter les réponses.


