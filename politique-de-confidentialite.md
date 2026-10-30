<!-- TRADUCTION AUTOMATIQUE : à faire relire par une personne de langue maternelle française avant publication. La version anglaise (privacy-policy.md) fait foi pour le contenu ; les deux doivent rester identiques sur le fond. -->

# Politique de confidentialité de Phone Guard

En vigueur le : 29 octobre 2026
Version 1.0, pour l’application Phone Guard (Android, paquet `com.phoneguard.app`)
English version: [privacy policy](privacy-policy.md)

## Qui nous sommes

Phone Guard est conçu par Jacques Dev, développeur individuel au Québec, Canada (« nous »).

Personne responsable de la protection des renseignements personnels (Loi 25, Québec) : Jacques Dev, jacques_dev@icloud.com.
Écrivez à cette adresse pour toute question ou demande sur la confidentialité. Nous répondons dans un délai de 30 jours.

## En bref

- Phone Guard vérifie vos applications et vos fichiers sur votre téléphone. Tout ce qu’il lit, calcule ou enregistre reste sur votre téléphone. Rien n’est envoyé ni à nous ni à qui que ce soit.
- Phone Guard n’a pas accès à Internet. Il ne peut rien envoyer, ni à nous ni à qui que ce soit. Ses règles et ses listes sont incluses dans l’application et se mettent à jour avec l’application, par Google Play.
- Nous ne vendons pas de données. Nous n’affichons pas de publicité. Phone Guard ne contient aucun code de publicité, de statistiques ou de rapport de plantage.
- Phone Guard ne partage les données des utilisateurs avec personne.
- Phone Guard n’a pas de comptes.

## 1. Ce que Phone Guard lit, uniquement sur votre téléphone

Phone Guard lit chacun des éléments ci-dessous seulement après que vous avez accepté un écran qui l’explique. Rien de tout cela ne quitte votre téléphone.

**Vos applications** (après votre accord à l’étape « voir vos applications »)
- Pour chaque application installée : son nom, sa version, qui l’a signée, ce à quoi elle a accès (ses autorisations), d’où elle a été installée, et quand elle a été installée et mise à jour pour la dernière fois.
- Les fichiers d’installation de chaque application, pour y chercher du code de réseaux publicitaires et calculer une empreinte de chaque fichier. Cette vérification se fait dans une partie séparée et verrouillée de Phone Guard, sans accès à vos données. Phone Guard n’exécute jamais le code d’autres applications.
- Phone Guard le fait quand vous l’ouvrez, et une fois par jour en arrière-plan pour vérifier les applications nouvelles ou mises à jour.

**Utilisation** (seulement si vous activez l’accès à l’utilisation)
- Quand vous avez ouvert chaque application pour la dernière fois, combien de temps chaque application a fonctionné en arrière-plan, combien de données mobiles et Wi-Fi chaque application a utilisées et quelle part en arrière-plan, et l’espace de stockage pris par chaque application et ses données.

**Comptes de notifications** (seulement si vous activez l’accès aux notifications)
- Pour chaque notification : l’application qui l’a envoyée, son heure d’arrivée, son type (par exemple « message » ou « promotion ») et l’importance que l’application lui a donnée.
- Phone Guard ne lit et ne garde jamais le titre, le texte, les images ni l’expéditeur d’une notification. Il ne ferme, ne reporte et n’ouvre jamais vos notifications.

**Vos fichiers** (seulement dans les dossiers que vous choisissez)
- Phone Guard regarde seulement les dossiers que vous choisissez dans le sélecteur de dossiers d’Android, et les fichiers que vous choisissez dans Téléchargements. Phone Guard demande au sélecteur de n’afficher que le stockage de votre téléphone, pas le stockage en ligne.
- Pour chaque fichier, il lit le nom, le dossier, la taille, le type et la date. Pour les fichiers de même taille, il lit aussi le contenu, pour trouver les copies identiques. Pour les fichiers d’installation, il lit aussi le nom de l’application et le numéro de version qu’ils contiennent.
- Il regarde seulement pendant que l’écran des fichiers est ouvert. Il ne garde pas la liste des fichiers trouvés, sauf les fichiers que vous lui demandez de garder et les fichiers qu’il a placés dans la corbeille (section 2).

## 2. Ce que Phone Guard enregistre sur votre téléphone, et pour combien de temps

| Quoi | Conservé |
|---|---|
| Quand vous avez accepté chaque écran d’explication, et quelle version | Jusqu’à ce que vous supprimiez les données de Phone Guard ou que vous le désinstalliez |
| Vos réglages (vérification quotidienne, comptage des notifications) | Jusqu’à ce que vous supprimiez les données de Phone Guard ou que vous le désinstalliez |
| Les résultats pour chaque application (points relevés, raisons, inutilisée ou en double) | Remplacés à chaque vérification |
| Les résultats de la vérification des fichiers d’installation (réseaux publicitaires trouvés, empreintes de fichiers) | Tant que l’application reste installée ; supprimés à la vérification suivante après sa désinstallation |
| Les comptes de notifications | 14 jours, puis supprimés. « Arrêter le comptage et supprimer les comptes » les supprime aussitôt |
| Les applications choisies pour un nettoyage, et le résultat pour chacune | Jusqu’à la fin de ce nettoyage et la fermeture de son résumé |
| Les dossiers partagés avec Phone Guard | Jusqu’à ce que vous touchiez Retirer l’accès dans la liste des dossiers |
| Les fichiers que vous avez demandé de garder (nom, dossier, taille, date) | Jusqu’à ce que vous changiez d’avis ou que vous supprimiez les données de Phone Guard |
| Les fichiers placés par Phone Guard dans la corbeille d’Android (nom et taille) | Jusqu’à ce que vous les restauriez ou les supprimiez, 35 jours au plus |

Phone Guard désactive la sauvegarde Android et le transfert d’appareil à appareil pour toutes ses données. Rien n’est donc copié dans votre compte Google ni sur un autre téléphone.

## 3. Ce qui quitte votre téléphone

Rien. Phone Guard n’a pas accès à Internet. Il ne peut rien envoyer, ni à nous ni à qui que ce soit.

Google Play gère les téléchargements et les mises à jour de l’application selon la politique de confidentialité de Google.

## 4. Pourquoi Phone Guard demande chaque autorisation

- **Voir toutes les applications** (`QUERY_ALL_PACKAGES`) : pour vérifier chaque application installée, y compris celles sans icône.
- **Accès à l’utilisation** (facultatif) : pour les informations d’utilisation de la section 1.
- **Accès aux notifications** (facultatif) : pour les comptes de notifications de la section 1.
- **Demander la suppression d’applications** (`REQUEST_DELETE_PACKAGES`) : pour ouvrir la fenêtre de désinstallation d’Android pour les applications que vous choisissez. Android vous demande de confirmer chaque suppression.
- **Lancement au démarrage** (`RECEIVE_BOOT_COMPLETED`) et **voir l’état du réseau** (`ACCESS_NETWORK_STATE`) : ajoutées par la bibliothèque de tâches en arrière-plan d’Android, pour que la vérification quotidienne reste prévue après un redémarrage. Voir l’état du réseau ne permet rien d’envoyer.

Phone Guard accède à vos fichiers seulement par les sélecteurs de dossiers et de fichiers d’Android. Il n’a aucune autorisation pour lire toutes vos photos, vidéos ou fichiers.

## 5. Réglages par défaut, et comment désactiver chaque partie

| Partie | Par défaut | Comment la désactiver |
|---|---|---|
| Vérification des applications à l’ouverture | Activée après votre accord | Désinstaller l’application |
| Vérification quotidienne en arrière-plan | Activée après votre accord | Réglages de Phone Guard > Vérification quotidienne |
| Accès à l’utilisation | Désactivé tant que vous ne l’activez pas | Réglages Android > Accès à l’utilisation > Phone Guard |
| Comptage des notifications | Désactivé tant que vous ne l’activez pas | Réglages de Phone Guard > Arrêter le comptage et supprimer les comptes. Pour retirer aussi l’accès : Réglages Android > Accès aux notifications > Phone Guard |
| Accès aux dossiers | Aucun tant que vous ne choisissez pas de dossier | Retirer l’accès dans la liste des dossiers de l’écran des résultats |

## 6. Supprimer vos données

- **Supprimer toutes les données :** dans Phone Guard, ouvrez Réglages > Supprimer toutes les données de Phone Guard. Cette commande utilise la fonction « Vider le stockage » d’Android. Elle supprime tout ce qui figure à la section 2, retire l’accès aux dossiers, désactive l’accès aux notifications, annule la vérification quotidienne et ferme Phone Guard.
- **Désinstaller :** désinstaller Phone Guard supprime tout ce qu’il a enregistré.
- Deux choses restent, parce qu’elles appartiennent à Android et non à Phone Guard :
  - Les fichiers placés dans la corbeille y restent jusqu’à ce que vous les restauriez ou qu’Android les supprime, après environ 30 jours.
  - L’accès à l’utilisation reste activé jusqu’à ce que vous le désactiviez dans les réglages d’Android. Phone Guard ne s’en sert plus tant que vous n’avez pas donné de nouveau votre accord.

Nous ne détenons aucune donnée vous concernant sur un serveur ; il n’y a donc rien à supprimer de notre côté. La seule exception est un courriel que vous nous envoyez (section 7).

## 7. Notre site Web et le courriel

L’application Phone Guard n’a pas de serveur. Notre site Web, où cette politique est publiée, est hébergé sur GitHub Pages. Il n’utilise ni témoins (cookies) ni outils de statistiques. GitHub conserve ses propres journaux de visite selon la déclaration de confidentialité de GitHub.

Si vous nous écrivez, nous utilisons votre courriel seulement pour vous répondre, et nous le supprimons dans un délai de 12 mois.

## 8. Aucune vente, aucune publicité, aucun partage

Nous ne vendons pas de données. Nous n’affichons pas de publicité. Phone Guard ne contient aucun code de publicité, de statistiques ou de rapport de plantage, et n’utilise pas l’identifiant publicitaire. Nous ne vendons, ne partageons et n’utilisons jamais votre liste d’applications pour la publicité, les statistiques ou tout autre usage, parce que nous ne la recevons jamais.

La section Sécurité des données de Google Play pour Phone Guard indique qu’il ne collecte et ne partage aucune donnée utilisateur. Cela correspond à cette politique : l’application n’envoie rien hors de votre téléphone.

La liste des réseaux publicitaires recherchés par Phone Guard provient en partie de la base de données de traqueurs d’Exodus Privacy (licence ODbL). Elle est incluse dans l’application ; Phone Guard ne contacte pas Exodus Privacy.

## 9. Vos droits

Selon l’endroit où vous vivez (par exemple au Québec, ailleurs au Canada, dans l’Union européenne ou au Royaume-Uni), vous pouvez nous demander d’accéder aux renseignements personnels que nous détenons sur vous, de les corriger ou de les supprimer, ou vous opposer à leur utilisation. L’application ne nous envoie rien ; les seuls renseignements personnels que nous pourrions détenir sur vous sont donc ceux d’un courriel que vous nous avez envoyé. Écrivez à jacques_dev@icloud.com. Vous pouvez aussi porter plainte auprès d’une autorité de protection des données, comme la Commission d’accès à l’information du Québec.

Union européenne et Royaume-Uni : si vous nous écrivez, nous traitons votre courriel sur la base de notre intérêt légitime à vous répondre (article 6(1)(f) du RGPD).

Nous ne vendons ni ne partageons de renseignements personnels au sens des lois des États américains sur la vie privée.

## 10. Enfants

Phone Guard ne s’adresse pas aux enfants. Il est destiné aux personnes de 13 ans et plus. Phone Guard ne collecte aucun renseignement personnel, auprès de qui que ce soit.

## 11. Modifications

Si nous modifions cette politique, nous mettons à jour la date en haut de la page. Si une future version de Phone Guard devait envoyer quoi que ce soit hors de votre téléphone, nous mettrions à jour cette politique et la section Sécurité des données de Google Play avant la sortie de cette version, et l’application vous l’expliquerait et vous demanderait d’abord votre accord.

## 12. Contact

Jacques Dev, Québec, Canada. jacques_dev@icloud.com.
