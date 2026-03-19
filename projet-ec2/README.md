# Projet 2 — EC2 Sécurisé

## 🎯 Objectif
Lancer une instance EC2 sur AWS, s'y connecter en SSH et sécuriser l'accès.

## ✅ Ce qui a été fait
- Lancement d'une instance EC2 (Amazon Linux 2023)
- Création d'une paire de clés SSH (karsten-key.pem)
- Connexion SSH réussie depuis Mac
- Sécurisation du Security Group : accès SSH restreint à mon IP uniquement
- Navigation et manipulation de fichiers en Linux

## 🔐 Bonnes pratiques appliquées
- Principe du moindre privilège : port 22 ouvert uniquement pour mon IP
- Clé SSH sécurisée avec chmod 400
- Utilisation d'un utilisateur IAM (pas le compte root)

## 🧠 Ce que j'ai appris
- Lancer et configurer une instance EC2
- Se connecter en SSH à un serveur distant
- Commandes Linux de base (ls, mkdir, cd, touch, echo, cat)
- Configurer un Security Group comme firewall
- Différence entre IPv4 et IPv6

## 🛠️ Services AWS utilisés
- EC2
- IAM
- Security Groups (VPC)
