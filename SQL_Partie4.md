# Exercice 01:
## Dans la table languages insérez les données suivantes :
* PHP version 5 
* PHP version 6
* PHP version 7
* PHP version 7.4
* PHP version 8

INSERT INTO 'languages' (language, version) 
VALUES ('PHP', '5'), ('PHP','6'), ('PHP', '7'), ('PHP', '7.4'), ('PHP', '8');

# Exercice 02:
## Dans la table frameworks insérez les données suivantes :
* REACT version 16.1
* REACT version 16.3
* REACT version 16.4
* REACT version 16.5

INSERT INTO 'frameworks' (framework, version)
VALUES ('REACT','16.1'), ('REACT', '16.2'), ('REACT', '16.3'), 
('REACT', '16.4'), ('REACT', '16.5');

# Exercice 03:
## Dans la table languages, afficher toutes les données de la table.

SELECT * FROM 'languages';

# Exercice 04: 
## Dans la table languages, afficher toutes les versions de PHP.

SELECT version FROM languages WHERE language='PHP';

# Exercice 05: 
## Dans la table languages, afficher les lignes ayant pour id 1,3,4.

SELECT * FROM languages WHERE id IN (1,3,4); 
ou
SELECT * FROM languages WHERE id=1 OR id=3 OR id=4;

# Exercice 06:
## Dans la table frameworks, afficher les deux premières entrées de REACT.

SELECT * FROM 'frameworks' WHERE 'id' BETWEEN 1 AND 2;
ou
SELECT * FROM framworks WHERE id=1 OR id=2;