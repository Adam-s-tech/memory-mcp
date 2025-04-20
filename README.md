# Memory-MCP

## Description
**Memory-MCP** est une solution modulaire et extensible pour la gestion de graphes de connaissances. Elle permet de créer des entités, de définir des relations, et d'ajouter des observations. Le projet offre une interface flexible via des services SSE (Server-Sent Events) ou une CLI (interface en ligne de commande), et prend en charge plusieurs modes de stockage, notamment Redis (via Upstash) ou un système de fichiers local.

## Fonctionnalités
- **Gestion des entités et relations** :
  - Création, suppression, et mise à jour des entités et relations.
  - Ajout et gestion des observations liées aux entités.
- **Persistance des données** :
  - Stockage local sur disque.
  - Intégration avec Redis via Upstash.
- **Interface utilisateur** :
  - Serveur SSE pour des mises à jour en temps réel.
  - Interface CLI pour une gestion directe des graphes.
- **API extensible** via le protocole **Model Context Protocol (MCP)**.

## Prérequis
Avant de commencer, assurez-vous d'avoir les outils suivants installés :
- **Node.js** (version 16 ou supérieure)
- **NPM** ou **Yarn**
- (Optionnel) Un compte Upstash pour utiliser Redis en mode distant.

## Installation
1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/Adam-s-tech/memory-mcp.git
   cd memory-mcp

npm install
