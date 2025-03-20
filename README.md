-- DOCUMENT TYPE --
ecommerce
📌 Description
Ce projet est une plateforme ecommerce permettant aux utilisateurs de consulter des produits, passer des commandes et gérer leurs achats. Il repose sur une base de données relationnelle bien structurée pour assurer une gestion efficace des clients.

🛠 Technologies utilisées
Base de données : MySQL
Backend : Pas encore intégré (prévu pour plus tard)
Frontend : Pas encore conxu (prevu pour plus tard)
Outils : VS code ( extension mysql de Weijan Chen) , Beekeeper Studio, cmd

📂 Structure de la base de données
Le projet contient plusieurs tables interconnectées pour gérer l’ensemble du processus ecommerce.

🔹 Tables et leurs rôles
customers 🧑‍💼=> Contient les informations des clients (nom, email, adresse...).Chaque client peut passer plusieurs commandes.

orders 🛒=> Stocke les commandes effectuées par les clients.Relie un client à plusieurs produits commandés.

products 🏷️=> Liste les produits disponibles à l’achat.Contient le nom, la description, le prix et le stock.

categories 📂=> Regroupe les produits par type (ex: électronique, vêtements...).

order_items 📦=> Associe chaque commande aux produits achetés.Indique la quantité et le prix unitaire des produits commandés.

payments 💳=> Stocke les transactions et modes de paiement.Relie une commande à un paiement validé.
