# Mapa transmedia · cambios del TP3 al TP4

Base: la web del mapa del TP3 (`Naciohh/Tp-3-afiches/mapa-transmedia`, sin modificar). Los cambios siguen el documento `MAPA_TRANSMEDIA_ACTUALIZAR.md`.

**Cifras nuevas:** 41 nodos (35 de contenido + 6 personas) y 87 conexiones (84 de recorridos + 3 de circulación de la campaña). El TP1 tenía 19 nodos y 40 conexiones.

## Selector de versión
Debajo del título hay tres botones: **TP1 · Original**, **TP3 · Teles** y **TP4 · Evento** (la versión nueva, que abre por defecto). Se puede enlazar cada una con `#tp1`, `#tp3` o `#tp4`. El TP2 no cambió el mapa, así que no tiene versión propia.
- **TP1:** el código sale de https://mapa-transmedia.vercel.app (19 nodos y 40 conexiones, con sus íconos originales).
- **TP3:** el código del repo `Tp-3-afiches/mapa-transmedia`.
- **TP4:** la versión nueva.
Las tres comparten el panel de accesibilidad, el zoom y los recorridos por persona.

## Espaciado
El TP4 tiene un lienzo más grande y más ancho (6000 × 3000, contra 3960 × 2470 del TP1 y el TP3). Las piezas de afuera se alejaron del centro y las del evento se reacomodaron en columnas: pre-visita arriba, recepción debajo, piso 9 a la izquierda, piso 5 a la derecha y el cierre abajo.
Además, las etiquetas de las flechas ya no se muestran en la vista general (se ven al acercar o al elegir una persona); antes aparecían demasiado pronto en pantallas anchas y se pisaban.

## Datos generales
- Evento: jueves 28, viernes 29 y sábado 30 de octubre de 2027, de 14 a 20 h, en el Palacio Libertad. Va en el nodo central y en el texto de la web.
- Seis personas (se suma Tomás Ledesma).
- El evento deja de ser un nodo final: es el centro, con sus piezas alrededor. El nodo «Último desbloqueo» pasa a decir «Ventaja para reservar» (ya no es una condición).
- Siguen quitados el hackeo y el final oculto.

## Nodos nuevos
- **Canal:** Grupo del curso (entrada de Tomás).
- **Piezas de la Etapa 3 (azules):** Landing del evento, Mini demo, Reserva por web, Banda del evento en los afiches, Cartelería y señalética, Recepción, Pantalla de turnos, Folleto, Tarjeta por QR y cuestionario.
- **Instalaciones, juego y charlas (borde naranja):** Mesa de noticias, Tótem de foto y mensaje, Pared del año, Escultura de cubos, Cabina «Tu voz» (piso 5); Tótems de mensajes y Juego de investigadores (piso 9 y Cúpula); Charla 01 y Charla 02.
- **No van en el mapa** (como pide el documento): moodboard audiovisual y testeo de la landing.

## Recorridos
Cada recorrido sigue el orden del documento: se entera, reserva, llega, espera y recorre, juega, charla (opcional) y se va.
- **Tomás** (nuevo): grupo del curso o redes → landing → mini demo → reserva (jueves, 17:20) → recepción → pantalla de turnos → mesa de noticias → tótem de foto → escultura → juego → charla 01 → tarjeta.
- **Yamila:** afiche y banda → grupo de WhatsApp → landing → reserva → recepción → turnos → tótem de foto → tótems de mensajes → juego → (sin charla) → tarjeta → redes.
- **Raúl:** afiche y banda con fecha, hora y lugar escritos → cartelería → recepción sin reserva → folleto → pared del año → juego → charla 02 → tarjeta impresa → su familia. No toca redes, landing ni QR.
- **Marcelo:** asesores → landing → reserva (o sin reserva) → recepción → folleto → cabina «Tu voz» → juego → charla 02 → tarjeta → vuelve a los asesores. No toca redes y sin trato preferencial.
- **Carla:** monitoreo, juego y afiches (revisa los cuatro) → landing (prensa) → recepción con acreditación opcional → mesa de noticias → juego con colegas → charla 01 → tarjeta → nota en redes.
- **Iván:** creadores, juego y afiches (completa los cuatro) → landing con «Ajustes de color» → reserva → recepción → tótem de foto → juego → charla → tarjeta → discusión sobre accesibilidad → redes.
- **Circulación de la campaña (línea punteada):** la banda y las redes llevan a la landing.

## Accesibilidad del mapa
Tomás tiene su propio patrón de trazo (raya, punto, punto), una paleta en cada modo de daltonismo (amarillo en el modo normal), su recorrido en el panel lateral y su foto.

## Para confirmar (lo decidimos al dibujar, el documento no lo dice)
- **Iván → Charla 01:** el documento dice solo «Charla». Se dibujó la 01.
- **Folleto:** se asignó a Raúl y a Marcelo (se recibe en recepción). Pendiente del documento: ¿también se entrega en la vía pública?
- **Pantalla de turnos:** se asignó a Tomás y a Yamila, que reservan turno.
- **Raúl y Marcelo:** se dejó afuera su recorrido por los afiches con QR (Raúl no los usa) y por el juego (Marcelo llega sin conocer las etapas anteriores), según el documento. Raúl conserva el nieto que le cuenta del juego.
- **Yamila:** ya no escanea los cuatro afiches; ve el afiche y la banda en el camino, lo comenta en el grupo y llega a la landing por el link.
- **Figma:** los SVG de `exportados/` salen de la web, no del Figma del mapa. Si la figura 9.1 tiene que salir de Figma, hay que dibujarla ahí.

## Archivos
`index.html` (web con las tres versiones), `exportados/*.svg` (claro y oscuro), `og.png` (preview; el anterior todavía mostraba el hackeo en vivo). Antes de publicar, actualizar el dominio de `canonical` y `og:*` si el repo nuevo tiene otro.
