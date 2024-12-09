# L'Observateur d'évènements Windows

**💪 Challenge**

Crée une machine virtuelle Windows Server, installe le rôle DNS, puis crée une vue personnalisée dans l'Event Viewer pour surveiller spécifiquement les événements liés au service DNS et son état.
```
Configuration de ta vue personnalisée :

Niveaux à surveiller
Critique (1)
Erreur (2)
Avertissement (3)
Information (4) - Pour les démarrages/arrêts
Sources d'événements à inclure
DNS-Server-Service: Pour les opérations du serveur DNS

DNS Client Events: Pour les événements côté client

Événements critiques (ID principaux)
2: Démarrage du serveur DNS
4: Arrêt du serveur DNS
409: Erreur de résolution de nom
501-502: Échec de chargement de zone
6001-6002: Problèmes de réplication DNS
```

**🧐 Critères d'acceptation**
```
Configure la vue personnalisée dans l'Event Viewer avec les critères demandés.
Attribue un nom descriptif à la vue personnalisée.
Exporte la vue au format XML.
Sur un dépôt GitHub, ajoute le fichier XML et inclue un bref README expliquant ta vue personnalisée.
```
