# 🚀 El Impostor Multiplayer - Master Project Plan & Architecture

## 📋 Resumen Ejecutivo
Versión web moderna, interactiva y multiplataforma del juego social de deducción "El Impostor", diseñada con un **estilo auténtico de videojuego de simulación táctica espacial (HUD de Nave Espacial / estilo Among Us/Subterfuge)** tal como se observa en la referencia visual. Elimina completamente la apariencia de "plantilla web hecha con IA" para ofrecer una interfaz sólida, profesional, con paneles de mando robustos, botones táctiles de videojuego y distribución óptima en PC y móviles.

---

## 🎨 Dirección de Arte & Estilo Videojuego Espacial (Tactical HUD)
- **Concepto Visual ("Consola de la Nave")**:
  - Paneles de control sólidos en azul espacial profundo (`#0b1424`, `#101d31`, `#152640`) con bordes delineados de 1.5px a 2px (`#213d62`, `#2b5080`) y cabeceras redondeadas tipo cabina.
  - Botonera táctil estilo juego:
    - **Acciones Primarias**: Turquesa / Menta eléctrico (`#00e5a3` / `#00d2b4`) con texto oscuro y relieve táctil.
    - **Suspenso / Alerta / Omisión**: Naranja mandarina vibrante (`#ff8c32` / `#f97316`) para el rol de Impostor, botón Saltar (Skip) y avisos de emergencia.
    - **Consola Secundaria**: Azul marino pizarra con reborde cian.
- **Top Game Bar (Barra de Juego Superior)**:
  - Logotipo `IMPOSTOR` con tipografía bold de videojuego.
  - Indicador de estado y tarjeta de perfil del jugador a la derecha (Avatar, Apodo, Estado de conexión).
  - Pestañas/Navegación limpia integrada (`JUGAR`, `SALA`, `REGLAS`).
- **Tablero de Estado de Tripulación (Player Status)**:
  - Lista de tripulantes organizada verticalmente con círculos de avatar, checkmarks de verificación y badges de estado.
- **Reloj de Reunión y Fases**:
  - Indicador claro: `GAME PHASE: DISCUSIÓN / PISTAS` en naranja/ámbar, cronómetro digital grande en recuadro centrado.

---

## 🎯 Requerimientos y Estado de Desarrollo

### 1. 🚀 Estilo Videojuego Espacial (Tactical Game HUD)
- [x] Sustituir el aspecto de "tarjeta genérica de IA" por una interfaz de videojuego de consola de nave espacial.
- [x] Paleta de colores oficial de la referencia: Turquesa menta (`#00e5a3`), Naranja mandarina (`#ff8c32`), Azul espacial (`#0b1424` - `#162740`).
- [x] Barra superior de juego (Logotipo `IMPOSTOR`, chip de perfil, botón de salida discreto).
- [x] Paneles de mando con bordes sólidos y esquinas redondeadas tipo cabina.
- [x] Botones de videojuego con peso visual, relieves y respuesta al pulsar.

### 2. 🖥️ Layout Responsivo PC / Móvil
- [x] Pantalla completa con distribución de terminal en PC (Panel de Misión a la izquierda, Consola de acceso a la derecha).
- [x] Panel de "PLAYER STATUS" integrado para el lobby y la partida.
- [x] Votación con tarjetas de tripulantes, botón de Votar (Turquesa) y Saltar Voto (Naranja).

### 3. 🚪 Navegación y Modal Inmersivo
- [x] Botón único de salida en la barra superior.
- [x] Modal custom temático de expulsión/desconexión de la nave.

### 4. 🎮 Mecánica de Juego y Flujo de Rondas
- [x] Selección aleatoria de jugador inicial.
- [x] Turnos de pistas individuales con confirmación "READY / LISTO".
- [x] Ronda 1: Recopilación de testimonios.
- [x] Ronda 2 en adelante: Votación de sospechosos.
- [x] Hold-to-Reveal secreto con escáner biométrico.
- [x] Alternancia animada de pestañas superiores (`PLAY` vs `REGLAS`) con memoria de retorno.
- [x] Transición limpia de rondas sin atascos en pantalla de resultados (ver `Fix.md`).
- [x] Atajos de teclado `Enter` y auto-conexión con 4 dígitos.
