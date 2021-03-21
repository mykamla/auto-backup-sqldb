# auto-backup-sqldb

#### https://twitter.com/kamlabertrand

### Prérequis:

    -> L'hôte distant doit pouvoir autoriser les connexions SSH entrantes:
    
        - windows: https://fr.railstoolkit.com/comment-configurer-un-serveur-sftp-sous-windows-avec-openssh
        - linux:
        - mac:

* Le script fonctionne uniquement avec MySQL et PostgreSQL.

* Sur le SGBD, je vous recommande de créer un autre utilisateur (avec un mot de passe) qui aura des droits uniquement sur la base de données à  ll sauvegarder.

      -> Ce Script ne réalise la sauvegarde que pour une base de données à la fois.

### Lors de la restauration de la BD:
    - Pour MySQL, créer dabord une nouvelle base de données.
    - Pour PostgreSQL,Le script créera automatiquement la base de données.