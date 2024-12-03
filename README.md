# Born2BeRoot

**Born2BeRoot** est un projet d'administration système de l'école 42 qui consiste à configurer une machine virtuelle sécurisée avec un script de monitoring et des règles strictes en matière de sécurité. Ce projet permet de se familiariser avec la virtualisation, la gestion des utilisateurs, les pare-feux et les services essentiels comme SSH.

---

## 📝 Description du Projet

Le projet consiste à :

1. Installer un système d'exploitation minimal (Debian ou Rocky Linux).
2. Configurer la machine pour répondre à des exigences strictes :
   - Partitionnement sécurisé (LVM).
   - Politique de mot de passe forte.
   - Configuration stricte pour `sudo`.
   - Mise en place d'un pare-feu (UFW ou Firewalld).
3. Implémenter un script de monitoring (`monitoring.sh`) pour afficher des informations système toutes les 10 minutes.

---

## 📋 Contenu du Dépôt

- **`monitoring.sh`** : Script en bash qui affiche des informations système essentielles.
- **`commands.txt`** : Liste des commandes nécessaires pour vérifier la configuration pendant la correction.

#### **Note :** Ce projet ne peut pas être testé directement avec un `git clone`, car la machine virtuelle est enregistrée et configurée dans le logiciel **Oracle VM VirtualBox Manager**. Seul le script de monitoring et les fichiers de configuration sont présents dans ce dépôt.

---

## 🛠️ Rendu

- Un fichier `signature.txt` doit être placé à la racine du dépôt Git. Ce fichier contient la signature SHA1 du disque virtuel de votre machine virtuelle.
- Les fichiers `monitoring.sh` et `commands.txt` doivent être présents et fonctionnels.
- Aucun fichier ou élément non requis ne doit être inclus dans le dépôt.
- Durant la soutenance, la signature de la machine virtuelle sera comparée à celle du fichier `signature.txt`. Toute divergence entraînera une note de 0.

---

## 📜 Licence

Ce projet est soumis aux règles de l'école 42.
