# Q1 : Quels sont  les avantages de Gitpod ?
Réponse: 
- Prêt en un clic : Pas besoin de configurer ton environnement, tout est prêt direct depuis ton repo.
- Accessible partout : Tu peux coder depuis n’importe quel appareil avec un navigateur.
- Travail en équipe facile : Partage ton environnement et collabore en temps réel.
- Automatisation : Fini les tâches répétitives, tout se lance tout seul (merci les prebuilds).
- Intégré à des outils connus : Compatible avec GitHub, GitLab, VS Code, etc...

# Q2 : Quels sont les défauts de Gitpod ?
Réponse:
- Internet obligatoire : Sans connexion, impossible de travailler.
- Pas toujours adapté : Certaines tâches spécifiques demandent des ressources locales.
- Apprentissage : Peut être un peu compliqué au début si t’es pas habitué au cloud.
- Payant pour certaines options : Les ressources ou fonctions avancées peuvent coûter cher.

# Q3 : Quelle est la taille du fichier jar `api-springboot-0.0.1-SNAPSHOT.jar` ?
Réponse: On execute la commande `ls -lh api-springboot/target/api-springboot-0.0.1-SNAPSHOT.jar` et on obtient 19M pour la taille du fichier.

# Q4 : Qu'est ce que  la RSS ?
Réponse: RSS pour Resident Set Size est la quantité de mémoire physique (RAM) qui est utilisé par un processus. 
Cela va donc inclure toutes les pages mémoire en RAM mais va ne pas prendre en compte celles échangées sur disque.

# Q5 : Quelle est la valeur de la RSS utilisée par l'api SpringBoot (Préciser l'unité)?
Réponse: 319844 KB soit environ 312 MB (division par 1024)

# Q6 : Quel est le temps de démarrage l'api SpringBoot ?
Réponse: D'après le terminal, le temps de démarrage de l'api SpringBoot est 1.984 seconds.

# Q7 : Quelle est la taille du fichier jar `quarkus-run.jar` ?
Réponse: La taille du fichier jar `quarkus-run.jar` est de 694 bytes

# Q8 : Quelle est la valeur de la RSS utilisée par l'api quarkus en mode JVM (Préciser l'unité)?
Réponse: La valeur de la RSS est 107396 KB  soit environ 105 MB (division par 1024)

# Q9 : Quel est le temps de démarrage l'api Quarkus en mode JVM ?
Réponse: Le temps de démarrage de l'api Quarkus en mode JVM est de 0.894s

# Q10 : Quelle est la valeur de la RSS utilisée par l'api quarkus en mode natif (Préciser l'unité)?
Réponse: En mode natif, la valeur de la RSS utilisée par l'api quarkus est de 2300 KB soit environ 2.25 MB (division par 1024)

# Q11 : Quel est le temps de démarrage l'api Quarkus en mode natif ?
Réponse: Le temps de démarrage de l'api Quarkus en mode natif est de 0.021s

PS : Question 11 il faut lancer le fichier runner de target : `./api-quarkus-1.0.0-SNAPSHOT-runner`