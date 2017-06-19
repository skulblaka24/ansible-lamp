# ansible-lamp

Ansible Lamp est un repository pour déployer un service lamp simple sur deux machines préalablement provisionnées.

# Prérequis
- Pour que l'index.php soit généré correctement, il est important de respecter la syntaxe de l'inventaire.

[db] <br>
IP_POUR_LA_BDD	dbname=NOM_BDD	dbuser=NOM_USER_BDD dbpass=PASS_BDD

[web]
IP_POUR_L_APACHE
