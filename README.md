# FirstDatabaseProject

Here is the first SQLite project i made.

### Here are some commands i wrote into the console after the first commit:

´´´java
INSERT INTO Opskrifter (navn, fremgangsmaade, billede) VALUES ('Kylling i karry', 'Lav kyllingen, bagefter lav karry sovsen og tilsæt ris efter.', 'Kylling_i_karry.png');

INSERT INTO Opskrifter (navn, fremgangsmaade, billede) VALUES ('Oriental Rice', 'Brun oksekød, hæld vand og krydderrier i, kog op og tilsæt ris, lad det små koge i 20 min.', 'Oriental_Rice.png');

INSERT INTO Opskrifter (navn, fremgangsmaade, billede) VALUES ('Bøf med ris', 'Form oksekød til bøffer og steg dem på panden, når de er steget til din preference(medium/gennemstægt), så kan du lave noget sauce/sovs til side, men ellers spis med nogle nykogte ris til siden.', 'Bøf_med_ris.png');


INSERT INTO Ingredienser (navn, kalorier_pr_100g) VALUES ('Ris', 20);

INSERT INTO Ingredienser (navn, kalorier_pr_100g) VALUES ('Kylling', 75);

INSERT INTO Ingredienser (navn, kalorier_pr_100g) VALUES ('Krydderi mix', 5);

INSERT INTO Ingredienser (navn, kalorier_pr_100g) VALUES ('Salt', 1);

INSERT INTO Ingredienser (navn, kalorier_pr_100g) VALUES ('Peber', 1);


SELECT * FROM Ingredienser ORDER BY navn;


UPDATE Opskrifter SET navn = 'Orientalsk ris' WHERE navn = 'Oriental Rice';

DELETE FROM Opskrifter WHERE navn = 'Bøf med ris';


SELECT * FROM Opskrifter ORDER BY navn;


SELECT * FROM Ingredienser ORDER BY kalorier_pr_100g DESC;
´´´
