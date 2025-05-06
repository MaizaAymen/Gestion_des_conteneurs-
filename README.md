# 🔬 TP 2 : Gestion des conteneurs et images Docker – Création et publication sur Docker Hub

## 👤 Étudiant
- **Nom :** Aymen
- **Établissement :** ISET Tozeur
- **Date :** Mai 2025

---

## 🎯 Objectifs

- Rechercher et utiliser des images Docker officielles depuis Docker Hub
- Gérer des conteneurs Docker (exécution, inspection, arrêt, suppression)
- Créer une image personnalisée avec `docker commit`
- Pousser une image personnalisée vers Docker Hub

---

## 📘 Partie 1 : Utilisation d'images Docker Hub

### 🔍 Recherche sur Docker Hub
Lien : [https://hub.docker.com](https://hub.docker.com)

### 📥 Téléchargement d'images

```bash
docker pull alpine
```
![image](https://github.com/user-attachments/assets/da818b87-038f-458e-912b-74b6ae7272d9)
```bash
docker pull nginx
```
![image](https://github.com/user-attachments/assets/f1ae0054-7992-47e2-80fb-e184f56d318f)
```bash
docker pull python
```
![image](https://github.com/user-attachments/assets/bf66189b-dfaa-4660-88eb-705daf54f84b)
```bash
docker run -it alpine sh
# exit
```
![image](https://github.com/user-attachments/assets/24ded74c-f75e-4f4f-8820-c5eeac648c79)

```bash
docker run -d --name web nginx
```
![image](https://github.com/user-attachments/assets/fc23d2f3-2da7-4d68-aaa7-075ff266171b)

docker run -it python bash
![image](https://github.com/user-attachments/assets/a70cf061-96c1-4e75-a9c9-3c4a41295fcc)

```bash
docker ps -a
```
![Uploading image.png…]()
```bash
docker inspect web
```
![Uploading image.png…]()
```bash
docker logs web
```
![Uploading image.png…]()


