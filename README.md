# Demo Ansible

Ce dépôt contient une présentation structurée d’**Ansible**, pensée comme support de démo ou de formation rapide.  
Il est organisé en trois parties progressives : introduction, bases, puis démonstrations pratiques.

---

## Résumé

- **Objectif** : Introduire Ansible et montrer comment l’utiliser simplement pour l’automatisation et la gestion de configuration.  
- **Contenu** :
  1. Comprendre ce qu’est Ansible et ses cas d’usage.
  2. Explorer les notions de base (inventaire, playbooks, variables, modules).
  3. Mettre en pratique avec des exemples concrets de playbooks.

---

## Index du dépôt

- [`1.introduction/`](1.introduction/)  
  Présentation générale d’Ansible, son rôle dans l’automatisation, et une mise en contexte.

- [`2.bases/`](2.bases/)  
  Les fondamentaux : structure d’un playbook, inventaires, variables, modules courants.

- [`3.demos/`](3.demos/)  
  Démonstrations pratiques avec des playbooks prêts à exécuter pour illustrer les concepts vus précédemment.

---

## Prérequis

- [Ansible](https://docs.ansible.com/) installé localement (`pip install ansible` ou via le gestionnaire de paquets de ta distribution).  
- Accès à une machine cible (ou à `localhost` pour les tests).

---

## Exécution rapide

[Réaliser le premier labo](3.demos/1.premier-playbook.md)
