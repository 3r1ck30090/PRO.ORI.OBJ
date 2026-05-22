# PRO.ORI.OBJ
## Omori Simulator Fight
La idea principal es recrear una pelea básica en Omori es decir niveles básicos y con los 4 principales: Omori, Kel, Hero y Aubrey contra algun Npc random ya sea un slime o una cebolla o incluso si me la curro incluiria jefes como Captain Ex-Husban, Abbi o Sweetheart. pero esa es la idea simular un combate de Omori usando sus emociones para mejorar la defensa, ataque, étc. Usando tambien el jugo de estos. se compone de 4 clases la cual es.
- `Personaje`
-- Aqui podremos dar estadisticas a los personajes tanto nuestro equipo como el enemigo y con ello podremos hacer como hacer referencia para que ataquen y pierdan vida
    - string nombre;
    - int vida;
    - int ataque;
    - string emocion;
    - bool vivo;
  -  $ Con esto podremos darle los atributos a cada uno en el main y con ello podremos hacer que hereden esos atributos para expresarlos en el combate --
   - Personaje(string n, int v, int a, string e);
    - void atacar(Personaje &objetivo);
    - void recibirDanio(int danio);
    - bool estaVivo();
    - string getNombre();
    - int getVida();
- `Aliado`
-- Aqui estan toda la pantilla es decir los 4 principales cada uno con su vida ataque y emocion.

- `Enemigo`
-- Aqui estara cualquier enemigo random que se me ocurra.

- `Combate`
-- Aqui es donde podremos hacer que se ejecuten las cosas para que el combate funcione usando referencia para que el enemigo cambie su vida hasta ser 0 o su aliado 
  
- `main`
-- Aqui esta todo lo que pasara aqui sera la fuente principal aqui con todo ya lo dado hara que puedas jugar por turno y a su vez el enemigo pueda atacar y deberas ir pensando que hacer
  
  ## Ejecucion
  g++ main.cpp Aliado.cpp Enemigo.cpp Combate.cpp Personaje.cpp -o juego
