Speech recognition:
	- audio files fetching. 
        > conseguimos los soundtracks del juego en internet, hay que separar los que sean de dialogos^{1}
	- audio representation apt for processing.
	- espectrograma de los audios.^{2}
		> ¿cuál va a ser nuestra representación canónica?
		> ¿qué representación sería fácil procesar?
		> ¿cuál es "más invertivble"?	
		> ¿cuál es fácil de guardar?
	- association (phones string) <----> (espectrograma). 
    - sacar lista de fonos del espectograma
    - construir reglas de unidades silábica consistentes con las listas de fonos^{3}


    1) Emi va a buscar como eliminar los demás por bash. Por ahora "los demás" son los que no dice "talk"
    2) Emi va a preguntar como sacar un espectograma de un wav
    3) Juampi contruye la función booleana y, si lelga, una primera función guesser 
