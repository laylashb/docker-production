# 🐳 Docker Production

Petit projet pour apprendre à utiliser Docker dans un contexte de déploiement simple.

## 🎯 Objectif

- comprendre les bases de Docker
- créer une image
- lancer un conteneur
- simuler un environnement de prod

## 🧠 Contexte

Projet réalisé dans le cadre de ma PRÉPA Master Cybersécurité à l’IPSSI.

## 🚀 Lancer le projet

```bash
docker build -t docker-production .
docker run -p 3000:3000 docker-production
