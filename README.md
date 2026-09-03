# Gestionnaire de Tâches

Application Android simple affichant un écran de confirmation lorsque toutes les tâches sont terminées.

##  Description
Cet écran présente :
-  Une icône de validation
-  Un titre : "All tasks completed"
-  Un sous-titre : "Nice work!"

Tout le contenu est centré verticalement et horizontalement sur l'écran.

##  Technologies utilisées
- **Langage** : Kotlin
- **Interface** : Jetpack Compose
- **Minimum SDK** : API 24
- **Thème** : Material Design 3

##  Structure du projet
app/
├── src/main/
│ ├── java/.../MainActivity.kt # Écran principal
│ └── res/drawable/ # Icône de validation
└── README.md
plaintext

##  Étapes de réalisation
Le projet a été construit étape par étape avec des commits réguliers :

1. **Commit initial** — Mise en place du projet "Projet Initial Android Studio"
2. **Étape 1** — Création de TacheCompleteScreen avec colonne centrée
3. **Étape 2** — Ajout de l'icône de validation centrée
4. **Étape 3** — Ajout des textes et mise en forme finale

##  Résultat attendu
- Icône de validation verte centrée
- Titre en gras (24sp) avec une marge inférieure de 8dp
- Sous-titre (16sp)
- Espacement de 24dp entre l'icône et le titre

---

##  Installation
1. Ouvrir le projet dans Android Studio
2. Synchroniser les dépendances
3. Ajouter l'icône `ic_task_completed.png` dans `res/drawable/`
4. Exécuter sur un émulateur ou un appareil Android