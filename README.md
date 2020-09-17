Fork of Litarvan/pronote-api

Personal using for @bugsounet and MMM-Pronote module of MagicMirror

Don't use it, please use Original npm library located in https://npmjs.org/package/pronote-api

---

API Pronote **2020/2021** complète et plutôt stable avec intégration de nombreux CAS (connexion avec comptes spéciaux pour les régions).

Disponible en tant que :
- Librairie Node.JS [via NPM](https://www.npmjs.com/package/pronote-api) (note : **support TypeScript** complet)

**Nouveauté 2020/2021 : [Session conservable](#conserver-la-session)**

## Données récupérables

- Infos Pronote, établissement et utilisateur
- Emploi du temps
- Devoirs
- Notes
- Compétences/évaluations
- Absences/punitions/retenues
- Informations
- Menu de la cantine

À chaque fois, il est possible de choisir quelle période voire quel intervalle de jours récupérer précisément.

## Comptes région supportés

**Uniquement dans le cas où vous ne pouvez PAS vous connecter directement par Pronote, mais devez passer par une interface régionale spéciale**

**Si vous pouvez vous connecter directement sur l'interface de Pronote, l'API devrait fonctionner PEU IMPORTE VOTRE ACADÉMIE**

Sinon, l'API propose de se connecter à Pronote avec des comptes des académies suivantes :

- Académie de Lyon (CAS : `ac-lyon`)
- Académie de Montpellier (CAS : `ac-montpellier`)
- Académie de Toulouse (CAS : `ac-toulouse`)
- Académie de Grenoble (CAS : `ac-grenoble`)
- Académie de Rouen (CAS : `ac-rouen`)
- Académie de Rouen (Arsene76) (CAS : `arsene76`)
- Académie de Lille (CAS : `ac-lille`)
- Académie de Clermont-Ferrand (CAS : `ac-clermont`)
- Académie de Reims (CAS : `ac-reims`)
- Académie de Nancy-Metz (CAS : `ac-nancy-metz`)
- Académie de Strasbourg (CAS : `ac-strasbourg`)
- Académie de Caen (CAS : `ac-caen`)
- Académie d'Orleans-Tours (CAS : `ac-orleans-tours`)
- Académie de Besançon (CAS : `ac-besancon`)
- Académie de Nantes (CAS : `ac-nantes`)
- Académie de Bordeaux (CAS : `ac-bordeaux`)
- Académie de Limoges (CAS : `ac-limoges`)
- Académie de Poitiers (CAS : `ac-poitiers`)
- Académie de Dijon (CAS : `ac-dijon`)
- ENT "Île de France" (CAS : `iledefrance`)
- ENT "Hauts-de-France" (CAS : `hdf`)
- ENT "Seine-et-Marne" (CAS : `seine-et-marne`)
- ENT "Toutatice" (Rennes) (CAS : `toutatice`)
- ENT "Haute-Garonne" (CAS : `haute-garonne`)
- ENT "Somme" (CAS : `somme`)
- ENT "Agora 06" (Nice) (CAS : `agora06`)
- ENT "Lycee Connecte" (Nouvelle-Aquitaine) (CAS : `lyceeconnecte`)
- ENT "La Classe" (Lyon) (CAS : `laclasse`)
