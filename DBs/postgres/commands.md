##apply script 0.all.sql to database tester_jun
psql -U postgres -d tester_jun -a -f 0.all.sql

##change password
sudo -u postgres psql
\password

\list or \l: list all databases
\dt: list all tables in the current database

\connect or \c database_name: switch beetween databases
