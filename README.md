# Lala World

Juego 2D tipo Avatar World en el universo de **Lala y Bubu**. Se explora una ciudad, se entra a la casa de Lucía y se juega libremente: arrastrar a Lucía y los objetos, decorar, vestirla, cumplir tareas y encontrar las estrellas de Bubu escondidas.

**Jugar (2D):** https://migue05101.github.io/lala-world/

**Prototipo 3D de mundo abierto:** https://migue05101.github.io/lala-world/3d/

Funciona en celular, tablet y computador. En el celular conviene ponerlo horizontal.

## Cómo se juega

- **Mantener presionado y arrastrar** un objeto lo mueve a otro lugar.
- **Arrastrar a Lucía** por el piso la hace caminar. Si se sube y se suelta en el sofá, la cama o el columpio, lo usa.
- **Tocar** usa las cosas: tele, lámparas, sillas, juguetes, pelota, arena, tablero.
- Botones: **Vestir**, **Bolso**, **Tareas**, **Estrellas**, **Mapa**, **Casa** y **¿Qué hago?**

El diseño completo está en [DISENO.md](DISENO.md).

## Prototipo 3D

En `3d/` está la evolución a mundo abierto 3D, con la misma base técnica que Los Guardianes de Piedra (Three.js, estilo caricatura con contornos, cámara en tercera persona y joystick en el celular).

- **Menú** con la panorámica de la ciudad de la versión 2D.
- **Crear mi personaje:** niña o niño, nombre, color de piel, peinado y color de pelo, ojos, tipo de ropa y colores, zapatos, moño y accesorio, con vista 3D que gira. Algunos peinados, prendas y accesorios se ganan con tareas y estrellas.
- **Jugar con amigos:** se crea una sala con un código de 4 letras (o un enlace) y los demás entran desde su celular, tablet o computador. Se ven caminar, saltar, sentarse y columpiarse, y se saludan con frases fijas (no hay chat libre).
- Ciudad libre: plaza con fuente, casa de Lucía (se entra caminando y el frente se oculta), casas de Lala y Juan con las fachadas de la ilustración de la calle, parque, cancha, frutería, escuela, lago con muelle y la Isla de Bubu.
- Lucía, Lala, Juan y Bubu pasean por la ciudad y se puede hablar con ellos.
- Botón ACCIÓN según lo que haya cerca: hablar, tomar y soltar objetos, sentarse, dormir (cambia a noche), columpio, tobogán, castillos de arena, patear la pelota y viajar en bote.
- 8 tareas con premios y 12 estrellas de Bubu. Con 6 estrellas se abre la isla.

### Probar en varios dispositivos

1. GitHub Pages debe estar activo: *Settings → Pages → Deploy from a branch → main / (root)*.
2. Abrir https://migue05101.github.io/lala-world/3d/ en cada dispositivo.
3. Crear el personaje → *Jugar con amigos* → *Crear una sala*. Compartir el código o el botón *Invitar con un enlace*.

El modo con amigos usa por ahora un servidor MQTT público de pruebas (`broker.emqx.io`). Sirve para probar, no para la versión final: ahí conviene un servidor propio con salas privadas y control de los papás.
