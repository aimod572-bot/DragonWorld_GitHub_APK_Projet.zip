DRAGON WORLD — COMPILATION APK AVEC GITHUB

Ce projet est prêt pour GitHub Actions.

1. Crée un nouveau dépôt GitHub (par exemple DragonWorld).
2. Envoie TOUS les fichiers et dossiers de ce projet dans le dépôt.
3. Ouvre l’onglet Actions.
4. Choisis “Build DragonWorld APK”.
5. Appuie sur “Run workflow”.
6. Quand le travail est terminé avec une coche verte, ouvre l’exécution.
7. Dans “Artifacts”, télécharge “DragonWorld-APK”.
8. Décompresse l’archive téléchargée : elle contient app-debug.apk.

Le workflow installe Java 17, Gradle 8.7 et le SDK Android 35 puis lance assembleDebug.

Configuration actuelle du projet : Android Gradle Plugin 8.5.2, compatible avec Gradle 8.7.
