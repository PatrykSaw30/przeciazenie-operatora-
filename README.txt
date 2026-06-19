1) Nie, on musi być zaimplementowany wewnątrz niej
2) Tak, technicznie kompilator na to pozwoli, ale to zła praktyka.
3) Kiedy klasa zarządza pamięcią dynamiczną
4) m = p; Operator przypisania (operator=)
   X z = p; Konstruktor kopiujący
5) Po pierwsze, zyskujemy możliwość łańcuchowego przypisywania. Po drugie, oszczędzamy zasoby pamięci i procesora
6) Aby zabezpieczyć się przed samozniszczeniem danych
7) Pola stałe (const).
   Zmienne referencyjne (&).
8) 	1) Konstruktor standardowy:
	City: Warszawa | Population: 370000
	Nations: [ 0 0 0 0 0 0 0 ]

	2) Konstruktor kopiujacy:
	City: Warszawa | Population: 370000
	Nations: [ 0 0 0 0 0 0 0 ]

	3) Operator =:
	Przed przepisaniem:
		City: Bialystok | Population: 290000
		Nations: [ 0 0 0 0 0 ]

	Po przepisaniu:
		City: Warszawa | Population: 370000
		Nations: [ 0 0 0 0 0 0 0 ]
