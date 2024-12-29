

 ## 🚀 Système de réservation de salles de coworking
 
# 📄 Description :
Une application pour gérer la réservation de salles dans des espaces de coworking. Ce système permet aux utilisateurs de rechercher, réserver et gérer les salles. Les administrateurs peuvent gérer les salles, suivre les réservations et les revenus.

# 🌟 Fonctionnalités principales :

# 👤 Utilisateur :
🛋️ Réservation de salles avec paiement en ligne.
✏️ Annulation ou modification des réservations existantes.
# 🔑 Administrateur :
🏢 Gestion des salles (ajout, modification, suppression).
📊 Suivi des réservations et des revenus générés.
# 📈 Tableau de bord dynamique :
📊 Statistiques sur l'utilisation des salles.
📉 Visualisation graphique des réservations et des revenus.

# 🛠️ Technologies :
# 🖥️ Backend :
Spring Boot (gestion des réservations avec validations complexes).
# 🌐 Frontend : 
React.
# 🗄️ Base de données :
MySQL.
# 💳 Paiement :
Reçu généré et téléchargeable en ligne.

# 📂 Architecture du projet :
🛡️ Backend
Le backend utilise Spring Boot pour créer une application robuste et scalable.

# 📑 Structure du Projet :
📌 ma.projet.coworking
🚀 CoworkingApplication.java: Point d'entrée de l'application Spring Boot.
🌍 controller: Gère les requêtes HTTP.
⚠️ exception: Gestion des exceptions.
📊 model: Définition des entités JPA.
🗃️ repository: Interfaces Spring Data JPA.
📥 request: Objets pour les données des requêtes.
📤 response: Structuration des réponses HTTP.
🔒 security: Configuration JWT.
🧠 service: Logique métier.

# 📑 diagramme de classe :
![image](https://github.com/user-attachments/assets/2914135a-5e28-4148-ae21-41094fa1e02d)

# 📑 Conception des fonctionnalit´es du systeme :
![image](https://github.com/user-attachments/assets/fef25cc3-c823-4a91-aea4-3ca83e6234a9)


 # video demo :


https://github.com/user-attachments/assets/e0e47fd2-9cae-46e9-a975-ba6f9ec8e599


# 🎨 Frontend
Le frontend est développé avec React, permettant une navigation fluide et intuitive.

# 🐳 Docker Image
Le projet peut être facilement conteneurisé avec Docker pour simplifier le déploiement.

## 🚀 Guide de démarrage :
# ✅ Prérequis :
📦 Git
☕ Java Development Kit (JDK)
🛠️ Apache Maven
🗄️ MySQL
🌐 Node.js et npm
⚙️ Configuration Backend :
📥 Clonez le projet :
git clone <repository_url>
cd <E:\examnewversion\salle-coworking\salle-coworking\back-end>
🛠️ Configurez la base de données :
spring.datasource.url=jdbc:mysql://localhost:3306/cocoworking?useSSL=false
spring.datasource.username=root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update 
 # 📦 Installez les dépendances :
mvn clean install
 # 🚀 Démarrez le backend :
mvn spring-boot:run
Accédez à : http://localhost:9090
# 🖥️ Configuration Frontend :
📥 Clonez le projet :
git clone <repository_url>
cd <E:\examnewversion\salle-coworking\salle-coworking\coworking-frontend>
 # 📦 Installez les dépendances :
npm install
# 🚀 Démarrez le frontend :
npm start
Accédez à : http://localhost:3000
🔐 Authentification :
# 👤 Utilisateur :
✉️ Email : ihssane@ihssane
🔑 Mot de passe : 123
✉️ Email : kaoutarokayl4@gmail.com
🔑 Mot de passe : 123456

# 🛡️ Administrateur :
✉️ Email : test@example.com
🔑 Mot de passe : password123

🤝 Contribuer :
Nous encourageons les contributions !

# 🍴 Forkez le projet
🌱 Créez une branche
📝 Ajoutez vos modifications
📤 Soumettez une Pull Request

# 👥 Contributeurs :
🧑‍💻 Ihssane Elmaizi — GitHub
👩‍💻 Kaoutar Okayl — GitHub
👨‍💻 Mohamed Lachgar
