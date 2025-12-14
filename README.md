<img width="494" height="28" alt="image" src="https://github.com/user-attachments/assets/f50e6221-a35c-420b-8611-41e366ff3b99" /># Gestion Git du projet MLOps Lab

Ce README décrit les principales commandes Git utilisées tout au long du projet afin de versionner le code, gérer les branches et manipuler l’historique.

---

## Étape 1 : Initialiser Git dans le projet

Cette étape permet d’initialiser le dépôt Git du projet.

* Initialiser le dépôt Git :

<img width="755" height="95" alt="image" src="https://github.com/user-attachments/assets/fee7f774-cb72-4512-abfa-66af328bcab0" />

* Créer le fichier `.gitignore` et y ajouter :

* Vérifier l’état du dépôt :

<img width="584" height="194" alt="image" src="https://github.com/user-attachments/assets/3793fa6b-e777-4652-85ab-2917d52fcc3c" />

---

## Étape 2 : Premier commit du projet MLOps

Cette étape permet de créer le premier commit du projet.

* Ajouter les fichiers et dossiers principaux :

<img width="663" height="134" alt="image" src="https://github.com/user-attachments/assets/a833acbc-4ffc-49a9-87b3-80c73ff5d761" />

* Créer le premier commit :

<img width="860" height="72" alt="image" src="https://github.com/user-attachments/assets/8c1bfaab-7b00-4452-9692-d29130833115" />


* Afficher l’historique :
  
<img width="960" height="182" alt="image" src="https://github.com/user-attachments/assets/37b70795-178f-472f-9ecb-6eb445249cff" />

---

## Étape 3 : Observer une modification avec git diff

Cette étape permet d’observer les changements avant validation.

* Modifier un script existant (`src/monitor_drift.py`) :

* Afficher les différences :
  
<img width="698" height="281" alt="image" src="https://github.com/user-attachments/assets/3e4f088b-0c72-4172-865f-e454d088ff90" />

* Ajouter le fichier modifié :

<img width="610" height="38" alt="image" src="https://github.com/user-attachments/assets/b114e199-4cd5-4aeb-9de5-2bb2764b5bc5" />

* Afficher les différences en staging :

<img width="701" height="266" alt="image" src="https://github.com/user-attachments/assets/e153840f-2068-45ce-970d-7719e24de761" />

* Créer un commit :

<img width="950" height="64" alt="image" src="https://github.com/user-attachments/assets/8b59020d-9dc6-4f53-bddd-a6f12cd36251" />

---

## Étape 4 : Créer une branche de fonctionnalité

Cette étape permet de travailler sur une fonctionnalité isolée.

* Créer une branche :

<img width="678" height="52" alt="image" src="https://github.com/user-attachments/assets/bafc94f9-f14a-4328-9566-58c8c9f46ae5" />

* Modifier `src/api.py` :

* Ajouter et committer :

<img width="823" height="108" alt="image" src="https://github.com/user-attachments/assets/ae2a436a-8735-4969-8fa2-d23a62560ed2" />

* Lister les branches :

<img width="436" height="87" alt="image" src="https://github.com/user-attachments/assets/711ba763-2eab-44b4-a0af-06767e2ba417" />

* Revenir sur la branche principale :
  
<img width="498" height="30" alt="image" src="https://github.com/user-attachments/assets/18808042-bff5-4700-ad91-3a74a8c3eea4" />

---

## Étape 5 : Fusionner une branche feature

Cette étape permet d’intégrer une fonctionnalité validée.

* Fusionner la branche :

<img width="627" height="27" alt="image" src="https://github.com/user-attachments/assets/9457354e-e67f-400c-8850-7c1c6bb55362" />


* Vérifier l’historique :

<img width="960" height="222" alt="image" src="https://github.com/user-attachments/assets/19ba16f5-a0e8-436c-a97f-bbae3fc2d5e0" />

---

## Étape 6 : Gérer un conflit de merge

Cette étape permet de comprendre et résoudre un conflit Git.

* Créer une nouvelle branche :

<img width="665" height="26" alt="image" src="https://github.com/user-attachments/assets/1e1f30a4-c995-433c-9ad1-24a22a11610d" />

* Modifier `src/train.py` et committer :
  
<img width="836" height="106" alt="image" src="https://github.com/user-attachments/assets/ce8fd940-7405-43dd-adb1-391d6d1b225e" />

* Revenir sur la branche principale et modifier la même ligne :

<img width="494" height="28" alt="image" src="https://github.com/user-attachments/assets/f77a0fce-a9cd-4217-8a67-4004f32585bb" />

<img width="841" height="109" alt="image" src="https://github.com/user-attachments/assets/1e0eeb38-0f0d-4bc2-a464-a3bcbb14c807" />

* Tenter la fusion :

<img width="599" height="56" alt="image" src="https://github.com/user-attachments/assets/d6b0dcc5-c7c4-4f2d-834c-65e1c8251f01" />

* Résoudre le conflit puis committer :

<img width="894" height="183" alt="image" src="https://github.com/user-attachments/assets/efcde7b8-0aab-47fd-8154-1aaab6b21766" />

---

## Étape 7 : Utiliser git stash

Cette étape permet de sauvegarder temporairement des modifications.

* Modifier un fichier sans commit :

* Vérifier l’état :

<img width="646" height="246" alt="image" src="https://github.com/user-attachments/assets/45e79868-1e18-46aa-b44e-d941a26a6072" />


* Mettre les modifications de côté :

<img width="936" height="59" alt="image" src="https://github.com/user-attachments/assets/f20c3511-edd5-4429-a7cd-eaa54e057621" />


* Lister les stash :

<img width="683" height="81" alt="image" src="https://github.com/user-attachments/assets/a0a64446-ad80-4b42-9b34-35ce6c419b26" />


* Récupérer les modifications :

<img width="647" height="240" alt="image" src="https://github.com/user-attachments/assets/f9804cd8-ab71-49ec-bd04-887f8b46c42e" />

* Option alternative pour appliquer + supprimer :

<img width="717" height="313" alt="image" src="https://github.com/user-attachments/assets/749f6043-52dd-4bc2-8a31-01b23d5cd553" />

## Étape 8 : Tester git reset

Cette étape permet d’explorer les différents types de reset.

* Créer un dossier et un fichier de test :

<img width="697" height="77" alt="image" src="https://github.com/user-attachments/assets/589da3c1-70d3-42ca-9a8f-f54533a0da05" />


* Ajouter et committer :

<img width="811" height="130" alt="image" src="https://github.com/user-attachments/assets/bcefce27-8947-4bd0-9fd7-246422f7000a" />


* Modifier et committer plusieurs fois :

<img width="876" height="302" alt="image" src="https://github.com/user-attachments/assets/f4cb5ae2-4ce1-4e09-8e60-20f40d41f0f8" />


* Reset soft :

<img width="652" height="318" alt="image" src="https://github.com/user-attachments/assets/78cfc397-af92-46e0-bb37-e1f9eb1b05a9" />


* Reset mixed :

<img width="646" height="357" alt="image" src="https://github.com/user-attachments/assets/a2da3e06-2e78-40df-89dd-afd969ddcf63" />

* Reset hard :

<img width="722" height="360" alt="image" src="https://github.com/user-attachments/assets/23c569ad-b76e-446e-aaea-69386fbb7eac" />


---

## Étape 9 : Annuler un commit avec git revert

Cette étape permet d’annuler un commit sans réécrire l’historique.

* Ajouter un changement non souhaité :

<img width="649" height="44" alt="image" src="https://github.com/user-attachments/assets/b9090885-ed33-4319-87e2-121b5241c9db" />

* Committer :

<img width="961" height="397" alt="image" src="https://github.com/user-attachments/assets/7099756a-416d-4e64-8490-24a0b1ab9ed3" />


* Revert du commit :

<img width="484" height="67" alt="image" src="https://github.com/user-attachments/assets/3571654f-079c-4a1a-bf10-c54aa711f7ba" />


* Vérifier le fichier :

<img width="594" height="627" alt="image" src="https://github.com/user-attachments/assets/952283f3-af83-4002-9344-839e7176bd01" />

<img width="570" height="675" alt="image" src="https://github.com/user-attachments/assets/4c843da8-5f9a-478c-be3a-3a5896667b38" />

<img width="574" height="639" alt="image" src="https://github.com/user-attachments/assets/e18a063b-4371-468e-bcf3-9b0c1fe7896e" />

<img width="481" height="658" alt="image" src="https://github.com/user-attachments/assets/ad82e3a9-bcad-4444-b646-e87e0133d73c" />

<img width="506" height="677" alt="image" src="https://github.com/user-attachments/assets/9585125a-3ceb-4af6-9671-1291931bd34c" />

<img width="471" height="679" alt="image" src="https://github.com/user-attachments/assets/9b92db6e-8026-4f79-ab2f-6d0ccc57d0ca" />

<img width="533" height="516" alt="image" src="https://github.com/user-attachments/assets/529645a9-b85d-45c7-be5d-5548cec0efd5" />

## Étape 10 : Rebase d’une branche feature

Cette étape permet de rejouer une branche sur la branche principale.

* Créer une branche feature :

<img width="677" height="52" alt="image" src="https://github.com/user-attachments/assets/9d68420c-be12-449a-aa11-fa3e11b30852" />


* Modifier et committer :

<img width="846" height="101" alt="image" src="https://github.com/user-attachments/assets/30290f12-f5e7-4a3a-b84d-18debe7ea4ef" />


* Ajouter un commit sur la branche principale :

<img width="847" height="191" alt="image" src="https://github.com/user-attachments/assets/a2d614b6-a7e8-4051-bc93-ef9c0f240372" />

* Revenir sur la branche feature et rebaser :

<img width="843" height="173" alt="image" src="https://github.com/user-attachments/assets/b5883e44-1063-4104-a0fc-bae0af5c5735" />


* Vérifier l’historique :

<img width="971" height="338" alt="image" src="https://github.com/user-attachments/assets/fffee170-14ba-4a40-9dcc-2541f537a111" />

