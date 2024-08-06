# python_project

A25-"La expedición" es un jueego de disparos desarrollado en Pygame. El objetivo es controlar una nave espacial, evitar colisiones con meteoritos y disparar para destruirlos. El movimietno de la nave es mediante el uso de la flecha izquierda y derecha, además de la barra espaciadora para disparar.

Dependencias necesarias:
Python 3.x
Pygame

Se utilizan varios activos presentes en la carpeta 'assets', como la imagen del jugador, la imágenes de meteoritos y explosiónes, así también los diferentes sonidos del juego.

Se utilizar 4 clases: player (representa al jugador, gestiona su movimiento y los disparos), Meteor (define los meteoritos que se generan alteatoriamente), Bullet (representa a los disparos) y Explosion (gestiona las animaciones de las explosiones) 

Se utiizaron 4 funciones: 
get_font(size): carga y devuelve una fuente personalizada del tamaño especificado.
draw_text(surface, text, size, x, y): dibuja texto en la pantalla con la fuente personalizada.
draw_shield_bar(surface, x, y, percentage): dibuja la barra de escudo del jugador en la pantalla, mostrando la cantidad restante.
show_go_screen(): muestra la pantalla de inicio del juego, que se ve cuando el jugador pierde o inicia una nueva partida.
