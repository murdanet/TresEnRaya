# TresEnRaya

La clase MainActivity controla la lógica del juego. La variable playerOneActive indica qué jugador está activo. Se declaran varios componentes de interfaz de usuario, como TextViews y Buttons, para mostrar la puntuación y el estado del juego. 
El arreglo de buttons contiene las referencias a los botones del tablero. El arreglo gameState almacena el estado actual del juego.


El arreglo winningPositions contiene las combinaciones ganadoras posibles. Las variables playerOneScoreCount y playerTwoScoreCount guardan la puntuación de los jugadores. 
En onCreate(), se inicializan los componentes de la interfaz de usuario y se configuran los listeners de los botones. En onClick(), se maneja la lógica del juego al hacer clic en un botón. checkWinner() verifica si hay un ganador. playAgain() reinicia el juego y el tablero. updatePlayerScore() actualiza la puntuación de los jugadores en la interfaz de usuario. 
Esta implementación ofrece una funcionalidad básica de un juego de Tres en Raya en Android, permitiendo que los jugadores coloquen su marca y verificando si hay un ganador después de cada movimiento.
