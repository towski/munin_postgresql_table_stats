# munin_postgresql_table_stats
munin scripts for postgresql on a per table basis

if you link the postgres_setup_db_[database] it will setup select and insert munin graphs for every normal table in your database, however the /etc/munin/plugins
  directory must be writable by your munin process. 
