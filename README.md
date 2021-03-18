"# auto-backup-sqldb" 

https://twitter.com/kamlabertrand

Prérequis:

- L'haute distant doit pouvoir autoriser les connexions SSH entrantes.
    windows: https://fr.railstoolkit.com/comment-configurer-un-serveur-sftp-sous-windows-avec-openssh

- Le script fonctionne uniquement avec MySQL.

- Sur MySQL, je vous recommande de créer un autre utilisateur (avec un mot de passe) qui aura des droits uniquement sur la base de données à sauvegarder.



Ce Script ne réalise la sauvegarde que pour une base de donnees à la fois.