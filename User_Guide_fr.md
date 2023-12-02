# Guide de l'utilisateur de Sound Transcriber

Ce guide de l'utilisateur a pour but de vous fournir une compréhension complète de Sound Transcriber et de vous aider à tirer le meilleur parti de ses fonctionnalités.

Nous vous recommandons vivement de lire ce guide pour garantir une utilisation optimale du programme.

## Introduction à Sound Transcriber

Sound Transcriber est un programme de conversion audio/texte accessible, conçu pour transcrire des fichiers audio et vidéo, il permet d'extraire des fichiers de sous-titres et bien plus encore.

Développé par Mahmoud Atef, Ahmed Bakr, et Qais Alrefai de l'équipe TecWindow.

## Fonctionnalités

Sound Transcriber offre les fonctionnalités suivantes :

- Conversion de fichiers audio et vidéo en texte à l'aide de divers services de transcription.
- Enregistrement des résultats de la conversion sous forme de fichiers .txt et .doc ou de fichiers de sous-titres .SRT.

## Fonctionnalités prévues :

Plusieurs fonctionnalités sont en cours d'élaboration, notamment

- Traduction des résultats de la conversion en plusieurs langues.
- Fonctionnalité de vérification orthographique avec dictionnaires.
- Conversion des résultats en audio à l'aide de moteurs de synthèse vocale.

## Services pris en charge :

Le logiciel ne prend actuellement en charge que la conversion en ligne à l'aide de la reconnaissance vocale de Google, de Whisper d'OpenAi et de wit.ai de Meta.

## Notes importantes :

Veuillez prendre note des informations importantes suivantes :

- Par défaut, le programme utilise le service Google. Pour utiliser d'autres services, vous devez obtenir une clé API auprès du fournisseur de services concerné.
- Pour obtenir les meilleurs résultats en matière de transcription en langue arabe, nous vous recommandons d'utiliser wit.ai.
- Whisper d'OpenAI a été inclus sur la base d'expériences antérieures, mais il se peut qu'il ne fonctionne pas comme prévu ou qu'il ne fonctionne pas du tout. Nous apprécions vos commentaires et vos expériences pour nous aider à résoudre les problèmes.
- Lors de la conversion d'un fichier, veillez à sélectionner la langue appropriée avant de lancer le processus de conversion. Si un fichier est multilingue, les mots dans des langues autres que la langue sélectionnée peuvent ne pas être convertis avec précision en raison des limitations des services.
- Avant la conversion, les fichiers sont divisés en segments d'une durée maximale de 60 secondes, en fonction des limites de chaque service. Par conséquent, certains mots peuvent être perdus au cours de ce processus. Pour obtenir des résultats optimaux, nous recommandons d'ajuster la durée du segment en fonction du temps de silence, de la longueur du fichier et de la durée du segment autorisés par chaque service.


## Extensions de fichiers supportées :

Sound Transcriber prend en charge les extensions de fichiers suivantes pour la conversion :

.mp3, .wav, .aac, .flac, .oga, .opus, .mp4, .avi, .mkv, .mov, .m4a, .ogg, .ram, .rm, .wma, .wmv, .3gp, .flv.

## Obtaining API Keys:

## Obtention des clés API :

### Wit.ai :

Si nous devions inclure une clé API dans le programme lui-même, elle serait probablement bloquée après une utilisation généralisée par de nombreux utilisateurs.
De plus, wit.ai fournit des clés API distinctes pour chaque langue. Cela signifie que vous devez créer une application dans la langue souhaitée et obtenir la clé API correspondante.
Malheureusement, il n'est pas possible pour nous de rassembler les clés API pour toutes les langues car elles varient en fonction des préférences individuelles.
C'est pourquoi nous vous fournissons des instructions sur la manière d'obtenir votre propre clé API privée.
Bien que les étapes suivantes puissent sembler longues, elles sont simples et ne doivent être effectuées qu'une seule fois.

- Ouvrez le [site web wit.ai](https://wit.ai)
- Connectez-vous avec votre compte Meta en cliquant sur "Continue with Meta".
- Suivez les étapes normales de création de compte ou cliquez sur "Continue with Facebook/Continuer avec Facebook"
- Allez en haut de la page, appuyez sur h ou 1 pour les utilisateurs de lecteurs d'écran.
- Cliquez sur ""New App/Nouvelle application" et donnez à l'application un nom quelconque en utilisant les lettres de l'alphabit latin, tel que test, mon application ou my app.
- Vous trouverez une boîte d'options pour la langue de l'application, ouvrez-la et choisissez la langue appropriée. Les fichiers audio seront convertis dans la langue choisie.
- Enfin, cliquez sur "Create/Créer".
- Trouvez le nom de l'application que vous avez créée, cliquez dessus, puis naviguez jusqu'au bouton "Management/Gestion".
- Lorsque vous atteignez ce bouton, appuyez sur la lettre b pour trouver un bouton appelé "Settings/Paramètres". Appuyez sur ce bouton.
- Déplacez-vous avec le chiffre 4 ou h pour les utilisateurs de lecteurs d'écran jusqu'à ce que vous trouviez une rubrique intitulée "Client Access Token", faites défiler vers le bas et vous trouverez votre clé sous la forme d'un bouton. Vous pouvez sélectionner le texte manuellement pour le copier ou appuyer sur le même bouton pour qu'il soit automatiquement copié.
- Retournez à Sound Transcriber et collez votre clé API dans le champ prévu à cet effet.

Vous pouvez répéter ces étapes et créer une nouvelle application avec un nom différent pour obtenir une clé API pour la transcription dans une autre langue. Si vous souhaitez utiliser plusieurs langues avec wit.ai, répétez simplement les étapes pour obtenir une clé API pour chaque langue.

## Whisper :

Sound Transcriber prend en charge la transcription en utilisant les clés API Whisper d'OpenAI, qui ne sont pas disponibles gratuitement.

La tarification est basée sur le nombre de caractères transcrits, et les plans spécifiques ne sont pas mentionnés ici.

Pour obtenir des informations détaillées sur les limites et les options d'abonnement, veuillez consulter [cette page/.](https://platform.openai.com/account/billing/overview). N'oubliez pas que la connexion et l'ajout d'une méthode de paiement se font à vos risques et périls.

Pour obtenir une clé API pour Sound Transcriber, rendez-vous sur la [page API key/clé API](https://platform.openai.com/account/api-keys) et cliquez sur "Create new secret key/Créer une nouvelle clé secrète". Copiez la clé générée et ajoutez-la dans les paramètres du programme comme indiqué ci-dessous.

## Interface de Sound Transcriber :

À l'ouverture du programme, vous trouverez une boîte d'édition affichant le résultat de la transcription. Utilisez la touche de tabulation pour naviguer dans les autres options.

La case "Langue" vous permet de spécifier la langue du fichier que vous souhaitez transcrire. Sélectionnez la langue appropriée à l'aide des touches fléchées.

Cliquez sur le bouton "Démarrer" pour lancer le processus de conversion.

Ensuite, vous trouverez le bouton "Enregistrer sous", qui vous permet de spécifier les préférences d'enregistrement de la sortie.

En dessous, il y a une boîte d'édition en lecture seule indiquant le chemin ou le lien du fichier à transcrire.

Utilisez le bouton "Parcourir" pour localiser et sélectionner le fichier que vous souhaitez transcrire.

En outre, vous pouvez utiliser des raccourcis clavier, qui seront expliqués plus loin.

Veuillez noter que l'ordre des éléments à l'écran peut différer lorsque vous naviguez avec la touche de tabulation.

## Menus

Le programme comprend plusieurs menus accessibles en appuyant sur la touche Alt.

### Fichier :

- Ouvrir : Utilisez cette option pour parcourir votre appareil et rechercher un fichier à transcrire.
- Enregistrer : Enregistre le résultat de la transcription avec l'extension spécifiée dans les paramètres.
- Enregistrer sous : Enregistrer le résultat avec une extension spécifique.
- Paramètres : Accéder aux options du programme et aux personnalisations.
- Quitter : Quitter le programme.

### Services :

Il contient les noms des services disponibles pour la conversion, vous pouvez sélectionner n'importe quel service.

### Aide :

- Guide de l'utilisateur : Affiche le fichier actuellement consulté.
- Quoi de neuf : Voir le journal des modifications de Sound Transcriber.
- Rechercher les mises à jour : Rechercher les mises à jour du programme.
- Contactez-nous : Affiche des menus avec des options pour contacter les développeurs du programme.
- À propos de : Fournit des informations sur Sound Transcriber.

## Paramètres de Sound Transcriber :

Tout comme les paramètres du lecteur d'écran NVDA, les paramètres de Sound Transcriber sont répartis en plusieurs sections, chacune contenant diverses options. Vous pouvez naviguer entre les sections à l'aide des flèches vers le haut et vers le bas. Utilisez les touches Tab et Shift+Tab pour faire défiler les options dans la section sélectionnée.

### Général :

Cette section comprend diverses options applicables à l'ensemble du programme :

- Langue de l'interface : Spécifie la langue du programme.
- Service : Spécifie le service utilisé pour la transcription des fichiers.
- Détection automatique de la présence d'un fichier dans le presse-papiers : Le programme vérifie votre presse-papiers au démarrage et, s'il trouve un fichier pris en charge, il sélectionne automatiquement son chemin d'accès pour une conversion rapide.
- Demander ce qu'il faut faire lorsqu'un fichier est détecté dans le presse-papiers : Si cette option est activée, le programme vous demandera comment traiter le fichier détecté.
- Sons : Activez les sons d'alerte au début et à la fin de la conversion.
- Enoncer les actions : Permet au lecteur d'écran de fournir des informations sur l'état de la conversion.
- Rechercher automatiquement les mises à jour : Recherche automatiquement les mises à jour du programme au démarrage.
- Restaurer les paramètres par défaut : Réinitialise les paramètres à leurs valeurs par défaut.

### Options d'enregistrement :

Les options de cette section affectent la fonctionnalité d'enregistrement dans le menu Fichier du programme.

- Enregistrement automatique des fichiers : Active l'enregistrement automatique des résultats de la conversion.
- Chemin d'enregistrement : Affiche le chemin d'accès actuel pour l'enregistrement des fichiers. Utilisez le bouton Parcourir pour le modifier.
- Enregistrer sous .txt : Active l'enregistrement automatique des fichiers avec l'extension .txt.
- Enregistrer sous .docx : Enregistre le fichier avec l'extension .docx.
- Enregistrer comme fichier de sous-titres : enregistrer le fichier avec l'extension .srt.
- Conserver les fichiers téléchargés : Les fichiers téléchargés sur Internet seront conservés après la conversion. Si cette option est désactivée, le fichier sera téléchargé, converti puis supprimé.

Si la fonction d'enregistrement automatique "Auto Save" est désactivée, l'option "Enregistrer" dans le menu "Fichier" exécutera la même fonction, en enregistrant les fichiers selon les extensions et le chemin spécifiés.

### Google :

Dans cette section, vous devez saisir une clé API sécurisée dans la zone de texte intitulée "Clé secrète". Vous pouvez cliquer sur le bouton "Modifier" pour modifier la clé. En outre, vous pouvez ajuster la durée du segment en spécifiant la durée de chaque partie du fichier lorsque vous utilisez ce service.

Notez que le fichier doit être divisé en plusieurs segments pour la conversion. La durée maximale par segment pour ce service est d'une minute.

### OpenAI :

Comme pour le service précédent, cette section vous permet d'introduire une clé API. Cependant, la durée maximale pour chaque fichier lors de l'utilisation d'OpenAI est de 30 secondes.

### Wit.ai :

Comme Wit.ai sépare les langues en fonction des clés API, cette section vous permet de combiner les langues comme suit :

Vous trouverez une liste des langues actuellement ajoutées.

Chaque langue a un champ d'édition caché correspondant pour la clé API.

Utilisez le bouton Modifier pour changer la clé ou le bouton Ajouter pour ajouter une nouvelle clé.

Sélectionnez la langue correspondant à votre application dans Wit.ai, collez la clé et cliquez sur Ajouter.

Répétez ces étapes pour chaque langue que vous avez l'intention d'utiliser. Après avoir obtenu une clé sur le site Wit.ai, revenez à la fenêtre de configuration pour l'ajouter.

Vous pouvez supprimer des clés individuelles ou toutes les clés enregistrées associées à ce service en utilisant les boutons prévus à cet effet.

Choisissez le format audio : Pour spécifier l'extension du fichier lors de la conversion. Choisissez ogg ou mp3 si votre connexion internet est mauvaise.

En choisissant wav, vous diviserez rapidement le fichier, mais il sera plus volumineux.

Enfin, vous pouvez spécifier la durée de chaque segment de fichier, de 4 à 20 secondes. Choisissez la durée que vous pensez donnera les meilleurs résultats.

Appuyez sur OK lorsque vous avez terminé de régler les paramètres.

## Raccourcis clavier: :

Sound Transcriber propose plusieurs raccourcis clavier pour améliorer la rapidité et la facilité d'utilisation.

- Ctrl+O : Ouvre la fenêtre d'exploration des fichiers pour sélectionner un fichier à convertir.
- Ctrl+V : Collez un fichier de votre presse-papiers pour le convertir.
- Ctrl+1 : Basculer vers le service Google.
- Ctrl+2 : Basculer vers le service Wit.ai.
- Ctrl+3 : Basculer vers Whisper.
- Ctrl+Entrée : Lancer le processus de conversion.
- P : Enoncer le pourcentage actuel de l'avancement de la conversion.
- Ctrl+S : Ouvrir les options d'enregistrement.
- Ctrl+Shift+S : Enregistrer le résultat au format .srt.
- Ctrl+Shift+T : Enregistrer le résultat au format .txt.
- Ctrl+Shift+D : Enregistrer le résultat au format .docx.
- Ctrl+U : Vérifier les mises à jour.
- Alt+S : Ouvrir les paramètres.
- Ctrl+W ou Ctrl+F4 : Fermer Sound Transcriber.

## Comment convertir des fichiers :

Pour convertir des fichiers, ouvrez Sound Transcriber et recherchez le fichier en cliquant sur "Parcourir" ou en utilisant le raccourci Ctrl+O. Vous pouvez également copier le fichier depuis votre appareil et le coller en utilisant Ctrl+V.

Vous pouvez également copier un lien vidéo à partir de sites tels que Facebook, Twitter (X), Youtube, SoundCloud et autres.

Choisissez la langue et le service souhaités à l'aide des raccourcis fournis ou réglez-les dans les paramètres. Appuyez sur "Démarrer" ou utilisez le raccourci Ctrl+Enter pour lancer la conversion.

### Notes :

- Pendant qu'une conversion est en cours, vous avez la possibilité de la mettre en pause, que ce soit pendant l'extraction du texte ou le téléchargement d'un fichier. Cependant, il est essentiel de noter qu'initier un nouveau processus entraînera l'ignorance de tout ce qui est lié au processus précédent.
- Si le processus est arrêté pendant la division des fichiers, il ne pourra pas être repris.

## Signaler les bogues :

Si vous rencontrez un bogue avec Sound Transcriber, vous pouvez utiliser les méthodes de communication disponibles dans le menu "Contactez-nous" de la section "Aide". Fournissez une explication détaillée des actions qui ont conduit au bogue. Nous vous recommandons de partager le fichier Sound Transcriber.log, qui nous aidera à comprendre et à résoudre le problème plus efficacement.

Vous trouverez ce fichier dans le chemin suivant :

AppData\Roaming\tecwindow\SoundTranscriber

## Remerciement spécial :

- Un grand merci à Riad Assoum pour la traduction du programme en français, la traduction du guide de l'utilisateur en anglais et la relecture des textes du programme en anglais et en arabe.
- Merci à Georgiana Frincu pour la traduction de Sound Transcriber en espagnol.
