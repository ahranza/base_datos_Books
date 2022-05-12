# base_datos_Books
First SQL data base

/**Libros:
La campana de cristal (1)
Los reyes malditos (3)
La iliada (2)
**/

CREATE TABLE Libros (id INTEGER PRIMARY KEY, name TEXT, rating INTEGER);

INSERT INTO Libros VALUES (1, "La campana de cristal", 1);
INSERT INTO Libros VALUES (2, "la iliada", 2);
INSERT INTO Libros VALUES (3, "los reyes malditos", 3);
SELECT * FROM Libros;
