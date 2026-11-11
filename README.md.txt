TP 5 – Développement d'applications réparties avec Java RMI

Faculté des Sciences de Sfax
Département d'informatique et des Communications
Année universitaire : 2026–2027
Auditoire : LSI 3

Présentation

Ce repository contient les deux activités du TP 5 consacré à l'invocation des méthodes sur des objets distants avec Java RMI.

Activité 5-1 : Service de conversion de devise
Objectif

Développer une application répartie permettant de convertir un montant en euros vers le dinar tunisien à travers une communication client/serveur avec Java RMI.

Projets
RMIConversion_Server : implémentation et publication du service distant.
RMIConversion_Client : recherche du service et invocation de la méthode convertirMontant().
Résultat

La conversion de 500 EUR a donné 1650 TND.

Captures d'écran

À compléter avec les captures du serveur, du client et du résultat de conversion.

Activité 5-2 : Service bancaire avec RMI et JNDI
Objectif

Développer une application répartie de gestion de comptes bancaires.

Un compte bancaire contient :

Un code.
Un solde.
Une date de création.
Projets
RMIBanque_Server : gestion des comptes et publication du service distant.
RMIBanque_Client : invocation des méthodes distantes.
Méthodes distantes
creerCompte(Compte c) : création d'un compte bancaire.
getInfoCompte(int code) : consultation d'un compte bancaire.
Utilisation de JNDI

L'enregistrement et la recherche de l'objet distant sont réalisés avec InitialContext, grâce au fichier jndi.properties.

Résultats des tests
Création d'un compte avec le code 1 et un solde de 5000.
Consultation réussie des informations du compte.
Refus de création d'un deuxième compte avec le même code.
Captures d'écran

À compléter avec les captures du serveur, du client, de la configuration JNDI et des résultats des tests.

Conclusion

Ce TP a permis de mettre en pratique la communication entre applications réparties avec Java RMI, de comprendre le fonctionnement des interfaces distantes et de découvrir l'utilisation de JNDI pour l'enregistrement et la recherche des objets distants.