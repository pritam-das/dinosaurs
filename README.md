SQL Queries (Dinosaurs)

1. SELECT COUNT(name) FROM dinos;
2. SELECT name, period FROM dinos WHERE period='Jurassic' ORDER BY name;
3. SELECT SUM(length) FROM dinos WHERE period='Cretaceous';
4. SELECT name,species, period, length FROM dinos WHERE period='Jurassic' OR period='Cretaceous' ORDER BY species;
5. SELECT name, species, period, diet FROM dinos WHERE t_order='Saurischia' AND diet='Herbivorous' ORDER BY name;
6. SELECT name, species, period, length,id FROM dinos ORDER BY length ASC LIMIT 1;
   UPDATE dinos
   SET name= 'Shortie'
   WHERE id=160;
7. SELECT name, species, period, id FROM dinos ORDER BY name ASC LIMIT 1;
8. UPDATE dinos
   SET name='The Famous Five'
   WHERE id= 61, 299, 38, 280, 106
