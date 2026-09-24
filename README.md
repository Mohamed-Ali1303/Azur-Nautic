Azur Nautic — Mise en place du système d'information

Projet étudiant de conception d'un système d'information pour Azur Nautic, PME fictive exploitant une base nautique à Port-Fréjus (Var).

Contexte

Azur Nautic propose la location de jet skis et de bateaux à moteur, des sorties encadrées par des moniteurs, l'entretien de sa flotte et la vente d'accessoires nautiques. L'entreprise compte jusqu'à 18 salariés en haute saison (juin à septembre).

Elle fonctionne aujourd'hui sans système informatique centralisé : cahier de réservations papier, fichier Excel, carnet d'entretien, planning affiché, contrats et états des lieux archivés en classeurs. Aucun de ces supports ne communique avec les autres.

Problématique

Comment mettre en place un système d'information permettant à Azur Nautic de centraliser ses activités, de connaître à tout moment la disponibilité réelle de sa flotte et d'assurer la traçabilité de ses locations ?

Périmètre fonctionnel
Module	Rôle
Réservations & flotte	Cœur du SI : base de données unique, un engin ne peut pas être engagé sur deux créneaux qui se chevauchent
Maintenance	Demandes de réparation, immobilisations, entretien préventif par seuil d'heures moteur
Planification des moniteurs	Qualifications et dates de validité, affectation contrôlée aux sorties
CRM	Clients, prospects, partenaires pros (campings, hôtels, CE), données partagées avec les réservations sans ressaisie
Facturation & activité	Grille tarifaire par saison, encaissements, chiffre d'affaires, taux d'occupation
Site Internet	Vitrine responsive, consultation des disponibilités, demande de réservation, sans exposer la base interne
Utilisateurs & fichiers	Comptes par service, création/désactivation rapide des saisonniers, documents numérisés
Support & supervision	Ticketing interne, surveillance des serveurs, services et équipements
Utilisateurs

Direction · Accueil · Administration · Moniteurs · Atelier · Responsable informatique · Clients

Contraintes principales
Jusqu'à 25 utilisateurs, architecture évolutive et documentée
Charge concentrée l'été et les week-ends : pas de dégradation du service en période de pic
Accès depuis le ponton et la zone de départ (postes fixes et terminaux mobiles), équipements adaptés au milieu salin
Sécurité : contrôle des accès, filtrage, Wi-Fi extérieur sécurisé, accès administrateurs limités
Données personnelles (permis, pièces justificatives) protégées, avec une durée de conservation définie
Continuité de service : consultation des disponibilités, édition des contrats et encaissement sont critiques ; mode dégradé prévu ; tests de reprise hors haute saison
Sauvegardes régulières avec procédure de restauration testée
Aucune technologie imposée : chaque choix technique doit être justifié
Livrables
Cahier des charges (Cahier_des_charges_Azur_Nautic.pdf)
Schéma réseau et captures des tests (Cisco Packet Tracer)
Schéma d'infrastructure
Planning Trello (M+1 minimum)
Modèle de données MCD / MLD (Merise)
Auteur

Mohamed-Ali
