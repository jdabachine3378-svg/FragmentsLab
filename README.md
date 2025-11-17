# 🧩 TP Android — Navigation entre Fragments

Ce projet illustre l’utilisation des **Fragments** dans une application Android.  
L’objectif est d’apprendre :

- Comment créer plusieurs fragments
- Comment les afficher dynamiquement dans une activité
- Comment naviguer entre eux
- Comment sauvegarder l’état d’un fragment
- Comment utiliser `FragmentManager` et `FragmentTransaction`

---

## ✅ Étape 1 — Création du projet

Créer un projet Android Studio :
- Type : **Empty Activity**
- Nom : `FragmentsLab`
- Langage : **Java**
- Minimum SDK : **API 21**

---
## structeur de projet :

<img width="484" height="704" alt="image" src="https://github.com/user-attachments/assets/e66b8862-1d29-434c-91c8-a76b06fe379f" />

## Navigation entre fragments

-L’activité contient un FrameLayout vide
-replaceFragment() remplace le contenu par un nouveau fragment
-Ajout facultatif à la pile de retour (BackStack)
-Appuyer sur Back → retour au fragment précédent
📌 Résultat final

##  L’application affiche :

-Une barre de boutons : Fragment 1 / Fragment 2
-Un contenu dynamique affiché dans un FrameLayout
-FragmentOne → affiche un texte et un bouton
-FragmentTwo → SeekBar + affichage de la valeur
-Navigation fluide + retour arrière


https://github.com/user-attachments/assets/968f17f6-18cb-4c91-afeb-d789c76ed615


https://github.com/user-attachments/assets/43c9f303-9200-4592-bef4-688c2aff84f6



