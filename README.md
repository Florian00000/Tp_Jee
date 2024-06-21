# Tp_Jee

Ce projet est une application web JEE qui gère les patients d'un hôpital.

[Voici le lien vers le sujet](https://github.com/Florian00000/Tp_Jee/blob/main/Tp_jee.md) 

## Instruction de configuration

1. **Cloner le dépôt :** Clonez ce dépôt sur votre machine locale.
2. **Configurer le serveur :**  Assurez-vous d'avoir un serveur compatible JEE comme Apache Tomcat installé.
3. **Créer votre BDD :** Assurez-vous d'avoir créer votre BDD avec MySQL.
4. **Ajouter Hibernate.Properties :** Créer un fichier hibernate.properties à l'emplacement suivant `Tp_JEE\src\main\resources`.  
Voici un exemple de configuration: 
```text
## MYSQL
#hibernate.dialect = org.hibernate.dialect.MariaDBDialect
hibernate.dialect = org.hibernate.dialect.MySQL8Dialect
hibernate.connection.driver_class = com.mysql.jdbc.Driver
hibernate.connection.url = jdbc:mysql://localhost/tp_jee
hibernate.connection.username = root
hibernate.connection.password = Root
hibernate.show_sql = true
hibernate.hbm2ddl.auto = update
hibernate.connection.autocommit = false
```
5. **Déployer l'application :** Déployez l'application sur votre serveur.
6. **Accéder à l'application :** Ouvrez votre navigateur et accédez à http://localhost:8080/Tp_JEE_war_exploded