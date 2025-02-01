# HUNO-PostgreSQL
Huno LC/NC database Download and Restore

download db file from git repository 

sudo -i

mkdir /opt/huno

copy your db chunks into /opt/huno

#cp -rp db.zip* /opt/huno

#cd /opt/huno

#cat db.zip* > db.zip

#unzip db.zip

restore databaseusing below script 

#createdb -h 127.0.0.1 -p 5432 -U postgres huno

enter db password 

#psql -U postgres -h localhost -p 5432 -d huno -f "/opt/huno/db.sql
enter db password
