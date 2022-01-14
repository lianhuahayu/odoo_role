# Installation de odoo et postgres avec docker

## Variables par défaut

### Utilisateur par defaut
ansible_user: ubuntu

### Postgres variables
postgres_container: postgres_container
postgres_image: postgres:latest
postgres_port: 5432
postgres_db: postgres
postgres_user: postgres
postgres_password: postgres
postgres_data: backup/postgres/db-data

#### Odoo variables
odoo_container: odoo_container
odoo_image: odoo:13
odoo_port: 8069

