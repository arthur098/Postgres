# Postgres
BackUp Postgres

#Backup Postgres

#!/bin/sh

#bkp_BancoDeDados.sh

#DATA DATA='/bin/date+%Y-%m-%d'

#Nome do arquivo de BACKUP

#Arquivo salvo:

#/www/virtual/backup é uma pasta publica do apache.

#diretorio do BACKUP. NOME="/www/virtual/backup/BancoDeDados.sh-$DATA.sql"

#Variaveis do POSTGRESQL HOST="localhost"

USER="postgres"

PASSWORD="senha"

DATABASE="BancoDeDados.sh"

pg_dump -h $localhost -u $postgres -p $12345 $BancoDeDados.sh > $BancoDeDados.backup
