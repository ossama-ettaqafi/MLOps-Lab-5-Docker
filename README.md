# MLOps Lab 5 - Docker

Ce lab illustre la conteneurisation d'une API churn avec Docker et Docker Compose.

---

## Étapes

### 1. Vérifier l’installation de Docker
![Étape 1](01.png)

### 2. Lancer un serveur Nginx dans un conteneur
![Étape 2](02-docker_ps.png)
![Étape 2](02-final.png)
![Étape 2](02-nginx_cmd_localhost.png)

### 3. Ouvrir un shell Linux isolé dans un conteneur
![Étape 3](03-1-2.png)
![Étape 3](03-3-apt-get-install.png)
![Étape 3](03-3-apt-get-update.png)
![Étape 3](03-4-5-6.png)

### 4. Comprendre la structure d’une commande docker run
![Étape 4](04.png)

### 5. Conteneuriser l’API churn du projet mlops-lab-01
![Étape 5](05.png)

### 6. Créer un fichier requirements.txt pour l’image Docker
![Étape 6](06.png)

### 7. Créer un Dockerfile pour l’API churn
![Étape 7](07.png)

### 8. Préparer un modèle actif avant de construire l’image
![Étape 8](08-1-2.png)
![Étape 8](08-3-4.png)

### 9. Construire l’image Docker du projet churn
![Étape 9](09-1.png)
![Étape 9](09-completed.png)

### 10. Lancer l’API churn dans un conteneur
![Étape 10](10-1-2-3.png)
![Étape 10](10-4.png)
![Étape 10](10-4-POST.png)

### 11. Vérifier les logs générés à l’intérieur du conteneur
![Étape 11](11.png)

### 12. Orchestration locale avec Docker Compose
![Étape 12](12.png)

### 13. Démarrer l’API via Docker Compose
![Étape 13](13-1-2-3.png)
![Étape 13](13-4.png)

### 14. Lancer les services en arrière-plan et observer les logs
![Étape 14](14-1-2-3-4-health.png)
![Étape 14](14-1-2-3-4-predict.png)
![Étape 14](14-5.png)

### 15. Lier Docker Compose au reste du cours (Git + DVC)
![Étape 15](02-final.png)
