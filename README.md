## KekesVoyage
```
 /$$$$$$$  /$$$$$$$  /$$$$$$ /$$$$$$$$ /$$$$$$$$       /$$   /$$ /$$      /$$ /$$      
| $$__  $$| $$__  $$|_  $$_/| $$_____/| $$_____/      | $$  | $$| $$$    /$$$| $$      
| $$  \ $$| $$  \ $$  | $$  | $$      | $$            | $$  | $$| $$$$  /$$$$| $$      
| $$$$$$$ | $$$$$$$/  | $$  | $$$$$   | $$$$$         | $$  | $$| $$ $$/$$ $$| $$      
| $$__  $$| $$__  $$  | $$  | $$__/   | $$__/         | $$  | $$| $$  $$$| $$| $$      
| $$  \ $$| $$  \ $$  | $$  | $$      | $$            | $$  | $$| $$\  $ | $$| $$      
| $$$$$$$/| $$  | $$ /$$$$$$| $$$$$$$$| $$            |  $$$$$$/| $$ \/  | $$| $$$$$$$$
|_______/ |__/  |__/|______/|________/|__/             \______/ |__/     |__/|________/
```
# Brief diagrammes UML (User Case / Séquences / Classe)

Il nous a été demandé de concevoir la modélisation UML d'un système simplifié de réservation de vols pour une agence de voyages <br>
Notre client souhaite proposer la possibilité de réserver en ligne des billets d'avion à leurs clients <br>
Notre mission principale : Concevoir à l'aide du stadard UML la modélisation de la plateforme

Les détails de la plateforme :
<ul>
    <li>Un vol est ouvert à la réservation et refermé sur ordre de la compagnie</li>
    <li>Un vol peut être annulé par la compagnie</li>
    <li>Un client peut réserver un ou plusieurs vols, pour des passagers différents</li>
    <li>Une réservation concerne un seul vol et un seul passager</li>
    <li>Une réservation peut être annulée ou confirmée</li>
    <li>Un vol a un aéroport de départ et un aéroport d'arrivée</li>
    <li>Un vol a un jour et une heure de départ, et un jour et une heure d'arrivée</li>
    <li>Un vol peut comporter des escales dans des aéroports</li>
    <li>Une escale a une heure d’arrivée et une heure de départ</li>
    <li>Chaque aéroport dessert une ou plusieurs villes</li>
    <li>Des compagnies aériennes proposent différents vols</li>
</ul>

# Tâches à effectuer pour le Brief UML

En tant que Concepteur Développeur d'Application, nos différentes tâches sont : 
<ul>
    <li>Analyse des besoins du client :</li>
        <ul>
            <li>Rencontre avec le client pour comprendre ses exigences spécifiques en matière de gestion d'information</li>
            <li>Identification des acteurs du système, des flux d'information et des fonctionnalités requises</li>
        </ul>
    <li>Recensement des règles de gestion :</li>
        <ul>
            <li>Énumération des règles de gestion qui régissent le système, comme la validation des données</li>
        </ul>
    <li>Création du diagramme de cas d'utilisation :</li>
        <ul>
            <li>Identification des cas d'utilisation principaux du système, tels que "Créer un utilisateur", "Gérer les données clients"</li>
        </ul>
    <li>Élaboration du diagramme de classes :</li>
        <ul>
            <li>Identification des classes principales du système, telles que "Utilisateur", "Donnée", "Processus"</li>
        </ul>
    <li>Définition des règles de gestionn dans le diagramme de classes :</li>
        <ul>
            <li>Intégration des règles de gestion dans le diagramme de classes, par exemple, les contraintes d'intégrité des données</li>
        </ul>
    <li>Création du diagramme de séquence :</li>
        <ul>
            <li>
                Modélisation des interactions entre les différents objets du système lors de scénarios spécifiques tels que la création d'un utilisateur ou la mise à jour des données
            </li>
        </ul>
    <li>Raffinement du modèle avec les règles de gestion :</li>
        <ul>
            <li>Intégration des règles de gestion spécifiques dans le diagramme de séquence pour garantir la cohérence du système</li>
        </ul>
    <li>Validation du modèle avec le client :</li>
        <ul>
            <li>Présentation du modèle UML au client pour validation</li>
        </ul>
    <li>Documentation du modèle :</li>
        <ul>
            <li>Rédaction d'une documentation détaillée décrivant chaque élément du modèle UML, y compris les règles de gestion intégrées</li>
        </ul>
    <li>Préparation pour le développement :</li>
        <ul>
            <li>
                Préparation des artefacts nécessaires pour le passage à la phase de développement, tels que la génération de code à partir du modèle UML
            </li>
        </ul>
</ul>

# Contenus du Dépôt

Ce dépôt Github contient :
<ul>
  <li>Un dossier pour chaque type de diagramme utilisés (.png & .drawio + lien ci-dessous)</li>
        <ul>
            <li>---> <a href="https://app.diagrams.net/#G1k6tgZQBUXRyRIyZfXL8axuA9HAaVM6Tm">Diagramme de Cas d'Utilisation</a> <---</li>
            <li>---> <a href="https://app.diagrams.net/#G1wZieCp3dTlrnX8PszaGsKKJsQ2BpAb-b">Diagramme de Classes</a> <---</li>
            <li>---> <a href="https://app.diagrams.net/#G1QuJweTHZ9rHLLEdfLY3liZT_v81_lRsC">Diagrammes de Sequence</a> <---</li>
        </ul>
    <li>Un document qui réfère les différentes règles de gestion de l'application</li>
    <li>La Documentation du Modèle</li>
</ul>

