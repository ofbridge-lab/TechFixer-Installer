<div align="center">
🛡️ TechFixer Installer

Prépare une clé USB de dépannage TechFixer complète en quelques clics : Ventoy, suite TechFixer, ISO Windows officiel — tout automatisé.

Version Plateforme .NET Licence

Un outil Ofbridge Lab

</div>
Sommaire
À propos
Fonctionnalités
Captures d'écran
Installation
Utilisation
Licence
À propos

TechFixer Installer est l'outil qui automatise la fabrication d'une clé USB de dépannage informatique bootable, basée sur Ventoy et la suite d'outils TechFixer. Fini le formatage manuel et la copie de fichiers à la main : l'installeur détecte ce qu'il faut, télécharge, vérifie l'intégrité, et déploie — le tout depuis une interface unique.

Il remplace la procédure manuelle historique (voir l'ancien tutoriel) par un processus guidé, fiable et reproductible, pensé pour les techniciens qui préparent régulièrement des clés de dépannage.

Fonctionnalités
Gestion automatique des dépendances — détecte et installe Ventoy, Fido, 7-Zip (7zr), les plugins VHD Boot / WIM Boot et Memtest86+ depuis leurs sources officielles.
Récupération de l'archive TechFixer — téléchargement via miroirs (bascule automatique en cas d'indisponibilité) avec vérification d'intégrité de la version récupérée.
ISO Windows officiels (optionnel) — intégration Fido pour récupérer un ISO directement depuis les serveurs Microsoft (version, révision, édition, langue), avec possibilité d'en embarquer plusieurs sur la même clé.
Déploiement en un clic — formatage Ventoy (MBR/NTFS, Secure Boot) puis extraction de la suite TechFixer sur la clé, avec confirmation avant toute opération destructive.
Mise à jour sans reformatage — relance l'installeur sur une clé déjà préparée pour ne copier que ce qui a changé (nouvel ISO, nouvelle version de l'archive…).
Journal de bord détaillé — chaque opération de déploiement (formatage, fichiers copiés, vérifications) est tracée et consultable directement dans l'application.
Captures d'écran
	
Afficher l'image	Afficher l'image
Écran principal — archive vérifiée, prêt à installer	Sélection de l'ISO Windows via Fido
Afficher l'image	Afficher l'image
Confirmation avant formatage de la clé	Journal de bord détaillé du déploiement

➡️ Le tutoriel d'installation complet détaille chaque étape avec toutes les captures.

Installation
Télécharge la dernière version depuis l'onglet Releases du dépôt.
Lance l'archive auto-extractible TechFixerInstaller et choisis un dossier d'extraction.
Ouvre le dossier extrait et lance le raccourci TechFixerInstaller.

Prérequis : Windows 10/11, une connexion internet, et une clé USB d'au moins 8 Go (son contenu sera intégralement effacé lors de l'installation).

Utilisation

Pour un guide pas-à-pas complet — premier lancement, récupération de l'archive, ISO Windows optionnel, installation sur la clé, et lecture du journal de bord — consulte le tutoriel d'installation.

Licence

Distribué sous double licence : GPL v3 pour un usage personnel, et licence commerciale pour une intégration ou un usage professionnel. Voir LICENSE pour le détail.

<div align="center">

Un projet Ofbridge Lab — blog · suite TechFixer

</div>
