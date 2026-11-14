# TP 01 — Correction (point de départ du TP 02)

Ce dossier contient le code du TP 01 terminé : l'écran de connexion.
Utilisez-le si vous n'avez pas fini le TP 01, ou si votre projet ne fonctionne plus.

## Cas 1 : vous n'avez pas de projet (ou il est cassé)

1. Décompressez le zip. Vous obtenez un dossier `ma_premiere_app`
   qui contient `pubspec.yaml`, `lib` et `test`.
2. Ouvrez ce dossier dans VS Code (Fichier > Ouvrir le dossier).
3. Ouvrez un terminal dans VS Code (Terminal > Nouveau terminal) et tapez :

       flutter create --project-name ma_premiere_app .

   N'oubliez pas le point à la fin. Cette commande ajoute les dossiers
   `android`, `ios`, `web`… sans toucher à votre code.
4. Choisissez un appareil en bas à droite de VS Code, puis appuyez sur F5.
   L'écran « Connexion » doit s'afficher.

## Cas 2 : vous avez déjà le projet du TP 01

Remplacez simplement le contenu de votre fichier `lib/main.dart`
par celui du fichier `lib/main.dart` de ce zip, puis enregistrez.

## Contenu

- `lib/main.dart` : le code de l'application (TP 01 terminé)
- `pubspec.yaml` : la configuration du projet
- `analysis_options.yaml` : les conseils de VS Code (soulignements bleus)
- `test/widget_test.dart` : un test qui vérifie que l'écran de connexion s'affiche
