# Projet 1 — Bucket S3 Sécurisé

## 🎯 Objectif
Créer et sécuriser un bucket S3 sur AWS en suivant les bonnes pratiques de sécurité.

## ✅ Ce qui a été fait
- Création d'un bucket S3 (carton-fichiers)
- Blocage de tous les accès publics
- Chiffrement activé (SSE-S3)
- Accès restreint via utilisateur IAM (karsten-admin)
- MFA activé sur le compte

## 🔐 Bonnes pratiques appliquées
- Principe du moindre privilège : accès IAM restreint
- Chiffrement côté serveur activé par défaut
- Aucun accès public autorisé
- Compte root non utilisé

## 🧠 Ce que j'ai appris
- Différence entre compte root et utilisateur IAM
- Importance du chiffrement au repos
- Configuration des permissions S3
- Activation et utilisation du MFA

## 🛠️ Services AWS utilisés
- S3
- IAM
