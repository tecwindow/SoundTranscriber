# Quoi de neuf dans Sound Transcriber ?

## Version 1.4.5:

- Quelques améliorations.

## Version 1.4.4:

- Ajout de la traduction en vietnamien, un grand merci à Nguyen Anh Duc.
- Nous avons adopté un nouveau système pour traduire le journal des modifications et le guide de l'utilisateur de Sound Transcriber. Vous trouverez plus d'informations dans le guide de l'utilisateur.
- Correction d'un bug qui empêchait Sound Transcriber de télécharger correctement des vidéos YouTube.
- Correction d'un bug empêchant Sound Transcriber d'arrêter correctement les téléchargements lorsque l'option "Conserver les fichiers téléchargés" était activée.
- Correction d'un bug qui empêchait Sound Transcriber de correctement enregistrer les erreurs retournées par les services.
- Amélioration du guide utilisateur de Sound Transcriber.

Mis à niveau vers wxPython 4.2.2 et Python 3.12.7.

## Version 1.4.3:

- Correction d'un bug lié au téléchargement depuis YouTube.

## Version 1.4.2:

- Ajout de la traduction turque. Merci à Kadir öz.
- Correction d'un bug lié au téléchargement depuis YouTube.
- Correction d'un bug lié au téléchargement depuis YouTube.

## Version 1.4.1:

- Diverses améliorations mineures.

## Version 1.4.0:

- Ajout d'un système de mises à jour bêta. Vous pouvez activer cette option dans les paramètres pour recevoir les mises à jour bêta. Veuillez noter que les mises à jour bêta peuvent contenir des bogues importants. Vous pouvez désactiver cette option et revenir à la dernière version stable à tout moment.
- Ajout d'une option permettant de spécifier le nombre de fichiers à convertir simultanément.
- Sound Transcriber ne génère plus de journal d'événements par défaut. Vous pouvez l'activer dans les paramètres lorsque vous rencontrez des erreurs, puis répéter les étapes. Par défaut, le journal conservera les détails de la dernière étape, et les détails des opérations précédentes seront supprimés si désactivé.
- Les journaux affichent désormais davantage d'informations.
- La fonctionnalité du bouton de copie a été améliorée. En conséquence, le bouton de copie devrait rester disponible tant que le champ de résultat contient des textes transcrits.
- Ajout d'une option de donation pour les développeurs.
- Tentative de minimiser les erreurs renvoyées par le service Google.
- Correction de plusieurs bogues, en particulier ceux liés à la mise en pause et à la reprise du processus de transcription.
- Mise à jour du guide de l'utilisateur pour inclure les détails de la traduction, les mises à jour de la version bêta et d'autres informations importantes. Nous vous recommandons vivement de le consulter pour obtenir les dernières informations.
- Mise à jour de la version de Python utilisée à Python 3.12.
- Plusieurs améliorations mineures.

## Version 1.3.3 :

- Ajout d'une traduction en russe, merci à Danil.
- amélioration du code pour augmenter la vitesse de réponse et réduire la taille.
- Remplacement de Accessible Output 2 par PythonUniversalSpeech.
- Sound Transcriber n'utilise plus Sapi5 pour énoncer les actions lorsqu'il est utilisé sans lecteur d'écran.
- Mise à jour de la version de Python utilisée à Python 3.11.7.
- Diverses améliorations mineures.

## Version 1.3.2 :

- Vous pouvez désormais ajouter des fichiers par glisser-déposer.
- Correction d'un bogue majeur qui faisait que le texte extrait apparaissait dans le mauvais ordre lors de la conversion de longs fichiers.
- Correction d'un bogue qui entraînait la désactivation de l'option d'enregistrement si la conversion était annulée avant d'être terminée.
- Plusieurs améliorations de la traduction arabe. Un grand merci à Zeinab Bahaa.
- Diverses améliorations mineures ont été apportées pour une meilleure expérience utilisateur.

## Version 1.3.1 :

Quelques corrections et améliorations.

## Version 1.3.0 :

- Ajout de la traduction française. Un grand merci à Riad Assoum.
- Vous pouvez maintenant ouvrir des fichiers dans Sound Transcriber pour les transcrire à partir du menu contextuel des types de fichiers pris en charge.
- Vous pouvez désormais accéder rapidement à Sound Transcriber en tapant simplement "st" dans la boîte de dialogue Exécuter.
- Sound Transcriber est désormais capable de reconnaître automatiquement les traductions de l'interface et d'intégrer de nouveaux fichiers d'aide. Pour y contribuer, traduisez le fichier messages.pot à l'aide de Poedit et enregistrez les fichiers dans le même ordre que les fichiers de langue existants.
- Lorsque l'option de conservation des fichiers téléchargés est désactivée, Sound Transcriber les conserve jusqu'à la fermeture du programme. Ceci est particulièrement pratique si vous souhaitez répéter le processus de conversion avec différentes options.
- Merci à Dawlat Hassan pour l'information - de nombreux bogues liés à la fonction de collage dans le presse-papiers ont été éliminés. Des problèmes tels que l'ignorance de certains chemins, l'impossibilité de lancer la conversion à partir du message de détection, le collage de liens à n'importe quel moment, et bien d'autres encore, appartiennent désormais au passé.
- Correction d'un bogue qui provoquait parfois le démarrage de Sound Transcriber dans une langue différente après la dernière mise à jour.
- Vous ne pouvez plus ouvrir deux instances de Sound Transcriber simultanément.
- Des changements ont été apportés à la méthode d'arrêt de la conversion pour une expérience plus fluide.
- Diverses améliorations mineures ont été apportées pour une meilleure expérience utilisateur.

## Version 1.2.0 :

Important, à partir de cette version, Sound Transcriber ne prendra en charge que les versions 64 bits de Windows.

- Ajout d'une traduction en espagnol. Merci à Georgiana Frincu.
- Vous pouvez maintenant convertir des vidéos de Youtube, Facebook, Twitter (X) et d'autres services en texte, de sorte que Sound Transcriber téléchargera la vidéo et la convertira ensuite.
- Vous pouvez choisir de conserver le fichier original après la conversion ou de le supprimer dans les paramètres.
- La fonction de pause et de reprise a été ajoutée au processus de transcription.
- Vous pouvez désormais coller les chemins d'accès aux fichiers à convertir.
- Vous pouvez spécifier l'extension de fichier qui est envoyée à wit.ai pour la conversion à partir des paramètres.
- Sound Transcriber essaiera de traiter les fichiers dont le nom contient des Emojis.
- Sound Transcriber ne s'arrêtera plus pendant la conversion. Si cela se produit, vous pourrez toujours continuer le processus.
- Petites améliorations ici et là.

### Notes

- La mise en pause est prise en charge lors de l'extraction de texte, mais pas lors de la division de fichiers.
- Si vous arrêtez temporairement un processus et que vous démarrez ensuite un nouveau processus de conversion, vous perdrez tout ce qui est lié au processus précédent ; par conséquent, il est conseillé de sauvegarder le résultat actuel avant de démarrer une nouvelle conversion.
- Choisir le format wav dans les paramètres de wit.ai accélèrera le découpage des fichiers mais entraînera une conversion plus lente et une utilisation accrue des données. Envisagez d'essayer le format .ogg et de partager vos commentaires sur les résultats.

## Version 1.1.2 :

- Correction d'un bogue qui empêchait la conversion correcte des fichiers .mp4.
- Correction d'un bogue qui faisait que le format de fichier enregistré conservait l'extension du fichier d'origine avec les fichiers de sortie, et parfois enregistrait les fichiers de sortie avec la même extension que le fichier d'origine lors de l'ouverture d'un fichier via le presse-papiers.
- Il n'est plus possible de passer d'un service à l'autre et d'ouvrir les paramètres de Sound Transcriber pendant le processus de conversion.
- Sound Transcriber tentera désormais de vous alerter en cas de conversion à l'aide d'une clé API wit.ai incorrecte.
- Correction d'un bogue à cause duquel le bouton "Modifier" apparaissait deux fois après l'ajout d'une clé wit.ai.
- Correction d'un bogue à cause duquel les boutons "Mettre à jour" et "Annuler" apparaissaient en anglais lorsque Sound Transcriber était utilisé en arabe.
- Diverses autres corrections de bogues.

## Version 1.1.1 :

- Correction d'un bogue qui faisait que la position du curseur se déplaçait constamment au début du texte avec le lecteur d'écran lors de l'extraction du texte.
- Correction d'un bogue qui faisait que les options d'enregistrement ne fonctionnaient pas après la fin du processus d'extraction du texte.
- Correction d'autres bogues.

## Version 1.1 :

Cette version comprend plusieurs corrections de bogues et quelques nouvelles fonctionnalités.

- La prise en charge de divers formats de fichiers audio et vidéo a été ajoutée.
- Les fichiers Word sont désormais enregistrés au format .docx au lieu de .doc.
- Sound Transcriber affichera un avertissement si vous essayez de le fermer pendant la conversion d'un fichier.
- Si l'enregistrement automatique est désactivé et que le texte extrait n'est enregistré dans aucun fichier, Sound Transcriber vous demandera ce qu'il faut faire à la fermeture. Si vous choisissez d'enregistrer, le fichier sera enregistré selon les options spécifiées dans la section Options d'enregistrement des paramètres.
- Sound Transcriber mémorise désormais la langue sélectionnée pour la conversion des fichiers pour chaque service.
- Le texte extrait est désormais affiché pendant le processus d'extraction. En d'autres termes, si le processus d'extraction s'arrête pour une raison quelconque, vous ne perdrez pas le texte extrait. Le nouveau texte sera ajouté au fur et à mesure que le processus se poursuit.
- Vous pouvez désormais vérifier la progression de l'extraction en appuyant sur P.
- Correction d'un bogue qui empêchait le bouton "Parcourir" du chemin d'enregistrement automatique de fonctionner.
- Correction d'un bogue qui empêchait la modification des clés API pour les langues autres que la langue principale dans la liste des langues de wit.ai.
- Correction d'un bogue qui empêchait de convertir des fichiers avec une langue autre que la langue principale en utilisant Wit.ai.
- Correction d'un bogue qui empêchait la restauration des paramètres par défaut.
- Ajustement de la présentation de la boîte de dialogue des paramètres pour afficher les éléments correctement.
- Amélioration de la traduction en arabe.
- Correction de quelques bogues mineurs ici et là.

## Version 1.0 :

Version initiale.

