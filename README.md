

  *Objectif:
  
Ce projet est une application simple de gestion de tâches (Task Manager) développée avec :

Frontend : ReactJS

Backend : Node.js avec Express

Base de données : MongoDB Atlas (base cloud)

 *Structure technique:
 
Frontend (ReactJS)
Affiche la liste des tâches stockées en base de données.

Permet d’ajouter, supprimer et afficher les tâches.

Communique avec le serveur backend via Axios (API REST).

Backend (Node.js + Express)
API REST qui gère les routes suivantes :

GET /api/tasks : récupérer toutes les tâches.

POST /api/tasks : créer une nouvelle tâche.

DELETE /api/tasks/:id : supprimer une tâche.

Connexion sécurisée à MongoDB Atlas.
