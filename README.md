# intro-to-postgresql

A great resource: https://www.postgresqltutorial.com/

Code to run on https://postgres.devmountain.com/

-- CREATE TABLE star_wars_character (

--   star_wars_character_id SERIAL PRIMARY KEY,

--   name VARCHAR(250),

--   species VARCHAR(250)

-- );

-- INSERT INTO star_wars_character (name, species)

-- VALUES ('Chewbacca', 'Wookie');

-- INSERT INTO star_wars_character (name, species)

-- VALUES ('Mandolorian', 'Human'), ('Luke', 'Human');

-- SELECT * FROM star_wars_character;

-- SELECT name FROM star_wars_character;

-- SELECT species, name FROM star_wars_character;

-- SELECT * FROM star_wars_character

-- WHERE star_wars_character_id >= 3 AND star_wars_character_id < 6;

-- SELECT * FROM star_wars_character

-- WHERE star_wars_character_id != 3;

-- INSERT INTO star_wars_character (name) VALUES ('R2D2');

-- SELECT * FROM star_wars_character

-- WHERE species IS NOT NULL;

-- SELECT * FROM star_wars_character

-- WHERE star_wars_character_id BETWEEN 3 AND 5

-- ORDER BY species;

-- SELECT * FROM album

-- WHERE artist_id IN (2, 3, 4);

-- SELECT COUNT(title) FROM employee;

-- UPDATE employee

-- SET last_name = 'Manwill'

-- WHERE employee_id = 2;

-- DELETE FROM star_wars_character

-- WHERE name = 'Chewbacca';

-- -- WHERE employee_id = 2;

-- SELECT * FROM star_wars_character;

DROP TABLE star_wars_character; -- DELETES ENTIRE TABLE (poof!)

-- DELETE FROM will delete a row/rows where condition exists

-- Truncate will delete all rows but keep table
