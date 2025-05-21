# todo
- avoire une deuxieme yubikey et la configurer pour google, outlook, github, apple, Discord, X, facebook ; puis enlever toutes les autres méthodes d'authentification (mobile, etc.) pour rendre les authentification plus sécurisées. 
- une IA qui écrit, à partir d'une simple description de dépendences, un Dockerfile **fonctionnelle** et, par la suite, le plus optimisé possible (càd, si libre de le faire, utiliser la dernière version des paquets/images, installer le moins de paquet possible, choisissant dans la mesure du possible les paquets les plus légers et les plus rapides, et ceux ayant le moins de vulnérabilité connues)
- stdx : ecrire/publier le bilan.
- hnf
- le meilleur gestionnaire de paquet, des logiciels performants et sûrs à 100% : tous les crates sont développés seulement en Rust (pour la performance et la sûreté), code coverage à 100% (pour la performance et la sûreté, pas de ligne qui ne sert à rien), audité par au moins deux sources de confiance (ces audits sont censés assurer le bon fonctionnement des blocs unsafes et assurer la non-présence de bug volontairement et explicitement mis dans le code (car si on le veut c'est actuellement possible de faire cela en Rust), tous les crates sont validés par cargo mutant, le gestionnaire de paquet benchmark chaque crate (cela pourrait permettre de comparer les différents crates développé pour un même but, par exemple les serveurs web, permettant par la suite de faire les choix les plus judicieux en matière de crate à ajouter/installer)), sur le site avoir un onglet "Hall of fame" dans lequel on liste tous les contributeurs au projet. Ajouter le gestionnaire de paquet sur la blockchain pour pouvoir detecter rapidement tout changement et pour pouvoir consulter tout historique? à voir les pros et cons.
- proposer à la CNIL le droit à la suppression de toute information personnelle contenue chez un hébergeant, que l'information personnelle soit sauvegardée sur notre compte de l'hebergeur OU SUR LE COMPTE D'UN TIER DE L'HEBERGEUR ; l'hebergeant pourra/devra utiliser l'IA pour vérifier/retrouver les photos de la personne qui veut supprimer ses données personnelles.
- Demander à Unicode des nouveaux caracteres grecs pour l'onciale grecque ; en parler à Caleb Maclennan
- avoir une I.A qui aide à mettre à jour mon statut (cf. mon repo statut), par exemple avoir une app dans laquelle je dicte avec ma voix ce que j'ai fais j'y joint une photo, et l'I.A enregistre tout ça, synthétise ou reformule s'il le faut et met à jour le statut.
- faire le mdbook epi.rs : epi.rs l'écosytème Rustique d'Epita.
- marque de bijoux ? collier pour femme ?
- l'IA : Ben
- pouvoir faire du scripting avec Rust, https://chatgpt.com/share/68136606-05dc-8005-8fc7-9bb2366b4834
- faire une serrure de porte non pour clé classique mais pour clé de sécurité (ex: yubikey) :) ça rendrait la serrure plus secure (clé + mot de passe au lieu de clé toute seule ; et ça permettrait de pouvoir laisser une clé à qqun sans que celui-ci puisse ouvrir la porte pour autant (du fait qu'il n'ait pas le PIN)) et ça permettrait d'avoir une même clé à la fois pour rentrer chez soi et à la fois pour les credentials dans le monde numérique, donc moins de clés sur le porte clé.
- creer des boxs types point Pickup mais non pas pour livrer des colis mais pour stocker des serveurs.
- creer un programme qui permet de partager l'authentification wifi pour les systemes linux (comme ca existe deja pour les iPhones), juste en partageant un fichier par exemple, et surtout que cela puisse fonctionner pour les hotspots temporaire.
- creer un programme informatique qui donne une signature mais plus au bit pres, un peu comme les fonctions equivalentes en math
- creer un programme qui genere l'algorithme d'un programme (afin de pouvoir facilement/directement verifier l'algorithme utiliser pour que le programme repond aux besoin de 'utilisateur : l'algorithme est-il le plus performant ? est-il sur ?) voir la conference de l'owasp de septembre 2025, elle parlera de ca normalement
- faire un pdf etudiant la securite de Tailscale pour un particulier ou une entreprise.

## hnf :
- verifier qu'on utilise bien la derniere version du binding Rust scylla + essayer de lier la config Docker a la config Nix (ex: pkgs.dockerTools.buildImage? switch to Quadlet (https://www.reddit.com/r/NixOS/comments/1ko69fz/goodbye_docker_hello_quadlet/)?)?
- revoir la PRG en raison de la failure Lighthouse au niveau du cache.
- réussir à faire fonctionner le certificat pour HTTP 3.
- ajouter les CSP
- NixOS : décrypter le disque dur par Yubikey.
- Ajouter des APIs pour Siri,  ChatGPT, etc. ?
- créer des I.A (par exemple 1000) qui imitent des humains : càd qui recherche chacune quelqu'un en particulier ; en guise de test.

- connexion et deconnexion niquel chrome : fonctionnement parfait + parfaitement securisee (gestion des tentatives de brute force, ddos, etc.).
- gestion parfaite des credentials : utiliser un ID pour chaque utilisateur ? hasher le mot de passe ? quel type dans la db etc.
- inscription : gestion de l'envoi de mail.
- 
