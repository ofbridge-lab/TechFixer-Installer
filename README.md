<div align="center">
 <img width="150" height="150" alt="logo" src="https://github.com/user-attachments/assets/3145967d-30eb-4515-97c0-cd5f7ba11c79" />

	
# **TechFixer Installer**
</div>

Prépare une clé USB de dépannage TechFixer complète en quelques clics : Ventoy, suite TechFixer, ISO Windows officiel — tout automatisé.

Version Plateforme .NET Licence

Un outil Ofbridge Lab

**Sommaire**

À propos
Fonctionnalités
Captures d'écran
Installation
Utilisation
Licence
À propos

TechFixer Installer est l'outil qui automatise la fabrication d'une clé USB de dépannage informatique bootable, basée sur Ventoy et la suite d'outils TechFixer. Fini le formatage manuel et la copie de fichiers à la main : l'installeur détecte ce qu'il faut, télécharge, vérifie l'intégrité, et déploie — le tout depuis une interface unique.

Il remplace la procédure manuelle historique (voir l'ancien tutoriel https://ofbridgelab.blogspot.com/2024/06/tutoriel-dinstallation-techfixer.html) par un processus guidé, fiable et reproductible, pensé pour les techniciens qui préparent régulièrement des clés de dépannage.

**Fonctionnalités**
Gestion automatique des dépendances — détecte et installe Ventoy, Fido, 7-Zip (7zr), les plugins VHD Boot / WIM Boot et Memtest86+ depuis leurs sources officielles.
Récupération de l'archive TechFixer — téléchargement via miroirs (bascule automatique en cas d'indisponibilité) avec vérification d'intégrité de la version récupérée.
ISO Windows officiels (optionnel) — intégration Fido pour récupérer un ISO directement depuis les serveurs Microsoft (version, révision, édition, langue), avec possibilité d'en embarquer plusieurs sur la même clé.
Déploiement en un clic — formatage Ventoy (MBR/NTFS, Secure Boot) puis extraction de la suite TechFixer sur la clé, avec confirmation avant toute opération destructive.
Mise à jour sans reformatage — relance l'installeur sur une clé déjà préparée pour ne copier que ce qui a changé (nouvel ISO, nouvelle version de l'archive…).
Journal de bord détaillé — chaque opération de déploiement (formatage, fichiers copiés, vérifications) est tracée et consultable directement dans l'application.
Captures d'écran
	
<img width="200" height="209" alt="05-ecran-principal-initial" src="https://github.com/user-attachments/assets/42571984-35f5-4123-92f7-9a84a44d0f2c" /> <img width="200" height="209" alt="15-confirmation-formatage" src="https://github.com/user-attachments/assets/c4c17f59-b4a2-415f-9656-c498219abb8f" />


Écran principal — archive vérifiée, prêt à installer	Sélection de l'ISO Windows via Fido

<img width="200" height="209" alt="04-telechargement-outils" src="https://github.com/user-attachments/assets/88295182-8058-42d5-85dd-91e3faf6f4bf" />	<img width="395" height="209" alt="20-journal-de-bord" src="https://github.com/user-attachments/assets/67009548-2654-4e3f-bc4f-ee1319c51e72" />


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
