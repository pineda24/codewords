# Codewords

Se trata de un juego de palabras en el que se debe adivinar una palabra a partir de una serie de pistas. El juego se desarrolla en un tablero de **nxn** casillas, en el que cada casilla contiene una letra. El objetivo del juego es adivinar una palabra a partir de una serie de pistas. Las pistas se componen de una **palabra y un número**, con un significado relacionado al de la palabra, mientras que el numero es libre, y puede ser interpretado el tamaño de la palabra.

## Jugador

El jugador cuando sea su turno, debe adivinar la palabra a partir de las pistas que se le han dado. Para ello, debe seleccionar las casillas que contienen las letras de la palabra. Si la palabra es correcta, el jugador ganará otro turno para adivinar, hasta que este se equivoque.

## Espía

El espía es el jugador que debe dar las pistas. Para ello, debe seleccionar una palabra y un número. El espía debe dar pistas que no sean demasiado obvias, pero que permitan al jugador adivinar la palabra.

## Instalación

Para ejecutar el juego, es necesario tener instalado **Flutter**. Para ello, se puede seguir la guía de instalación de la página oficial de Flutter: https://flutter.dev/docs/get-started/install.

Una vez se tenga instalado Flutter, se puede ejecutar el juego com un servidor web local, con el comando:

```bash
flutter run -d web-server --web-port 8080
```

Por lo que el juego se podrá acceder desde la dirección: http://localhost:8080.
