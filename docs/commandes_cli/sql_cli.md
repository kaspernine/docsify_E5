## Commandes SQL

* __Backup :__ pg_dump --username=username --encoding=utf8 dbname > outfile.sql

* __Restauration (fichier Custom) :__ pg_restore --username=nom_utilisateur --dbname=nom_base nom_fichier

* __Restauration (fichier sql) :__ psql -U db_user db_name < dump_name.sql