# desktop-app
Tuto.com Desktop Application Release Repository

### Release v6.5.0

#### Fonctionnalités :
* Parcours: Affichage du bouton vers les exercices dans le module projet
* Parcours: Affichage des informations/alertes concernant la validation des QCMs
* Catalogue: Mise à jour des couleurs, affichage des badges promo et prix
* Lecture video: Affichage des sous-titres sur le player tuto (online/offline) et player preview
* 
#### Correctifs :
* Correctif du bouton de validation des QCM sur Desktop

### Release v6.3.2

#### Fonctionnalités :
* Renseignement du temps passé sur le projet du parcours.
* Gestion du blocage des QCM lorsque le parcours est terminé

#### Correctifs :
* Correctif du bouton validé qui reste bloqué sur les QCM de parcours.
* Correctif du bouton intercom qui reste affiché lors de l'accès aux tutos et QCM

### Release v6.3.0

#### Fonctionnalités :
* Espace abonnement
* Parcours:
    * Modale de "positionnement administratif"
    * Prise de RDV parcours
    * Téléchargement du certificat de formation
    * Boutons de contacts et prise de rdv mentors/référent 
    * Workflow d'introduction au parcours / QCM
    * Affichage de plusieurs mentors

#### Correctifs :
* Mise à jour du message de confirmation de la suppression de compte (via API)
* Renouvellement de session perdue suite à la connexion sur un autre appareil / navigateur
* Correctifs passage des QCM parcours

#### Amélioration :
* Redesign de l'app (harmonisation de la couleur des headers)

### Release v6.2.1

#### Fonctionnalités :
* Archivage / désarchivage des tutoriels 
* Filtre par tutoriels archivés
* Suppression du compte

#### Correctifs :
* Fix du téléchargement des sources de travail sur windows
* Fix de la configuration du proxy

### Release v6.1.1

#### Core :
* Update Cordova 10

#### Fonctionnalités :
* Modale d'engagement parcours

#### Correctifs et améliorations :
* Mise à jour de la popin RGPD
* Accès à la politique de confidentialité online / offline
* Nombreux correctifs graphiques et UX
* Kiosk mode: déplacement de la fenêtre en bas à droite à l'activation

### Release v6.0.0-beta.2

#### Core :
* Tag de l'architecture processeur sur intercom (utile pour les prochaines mises à jours)

#### Correctifs et améliorations :
* Écrasement de l'ancienne app osx lors de la mise à jour


### Release v6.0.0-beta.1

#### Core :
* Passage de la plateforme d'hybridation desktop NW.js à la plateforme Electron.js 
  * Implémentation de toutes les fonctionnalités faisant appel à l'API de la plateforme
  * Configuration des installeurs
* Scripts intermédiaire de compilation (signature, publication sur GitHub Release)

#### Fonctionnalités:
* Effet de transparence autour de la souris ajouté au Kiosk Mode (Alias James Bond Gun Barrel)
* Mise en place du nouveau système de mise à jour d'Electron
* Titlebar intégrée à l'application

#### Correctifs et améliorations :
* Authentification via le navigateur
* Nouveau logo Tuto.com


