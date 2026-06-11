# 🎈 PANG! — Arcade Game

Un remake del clásico juego de arcade Pang (Buster Bros) en HTML5, con física realista, 10 niveles temáticos, soporte para 1-2 jugadores y controles táctiles en móvil.

## 🎮 Características

- **10 niveles progresivos** — Viaja por el mundo: Monte Fuji 🗻, Sídney 🦘, Atenas 🏛️, Barcelona 🏖️, París 🗼, Londres 🫖, Nueva York 🗽, El Cairo 🏜️, Kioto 🌸, Isla de Pascua 🗿
- **1-2 jugadores simultáneos** — Juega solo o desafía a un amigo en el mismo dispositivo
- **Física arcade auténtica** — Gravedad realista, rebotes elásticos, colisiones precisas
- **Arpón ondulado animado** — Cable serpenteante que se anima mientras disparas
- **Sistema de frutas de bonus** — Recoge frutas aleatorias (🍒 🍌 🍎 🍇 🍍) al reventar burbujas para multiplicar puntos
- **Soporte táctil completo** — Controles automáticos en móvil con botones deslizantes
- **Efectos visuales** — Partículas explosivas, textos de puntos flotantes, temblores dinámicos
- **Pausa y configuración dinámicas** — Presiona P para pausar (o el botón ⏸ en móvil)

## 🕹️ Controles

### Teclado (PC)
- **Jugador 1** (azul)
  - ◀ ▶ — Movimiento izquierda/derecha
  - ↑ / Enter — Disparar
- **Jugador 2** (verde)
  - A / D — Movimiento izquierda/derecha
  - W — Disparar
- **P** — Pausa

### Móvil
Aparecen botones táctiles automáticamente:
- **1 jugador** — Movimiento a la izquierda, disparo a la derecha
- **2 jugadores** — Cada uno en su lado de la pantalla
- **⏸** — Pausa (arriba a la derecha)

## 🎯 Cómo jugar

1. Elige 1 o 2 jugadores
2. Dispara arpones para reventar las burbujas
3. Las burbujas grandes se dividen en dos pequeñas al impactar
4. Las burbujas pequeñas valen más puntos
5. Evita que las burbujas te toquen (tienes 3 vidas)
6. Sobrevive a los 10 niveles para ganar
7. Recoge frutas para bonificaciones extras

**Bonus de nivel** — Ganas 500 puntos automáticos al completar cada nivel

## 📊 Tabla de frutas

| Fruta | Puntos | Rareza |
|-------|--------|--------|
| 🍒 Cerezas | 300 | ★★★★★ |
| 🍌 Plátano | 500 | ★★★★☆ |
| 🍎 Manzana | 800 | ★★★☆☆ |
| 🍇 Uvas | 1.200 | ★★☆☆☆ |
| 🍍 Piña | 2.000 | ★☆☆☆☆ |

## 📁 Instalación

Simplemente descarga `pang.html` y ábrelo en cualquier navegador moderno. No requiere instalación, dependencias ni servidor.

```bash
# O clónalo desde GitHub
git clone https://github.com/dierubo/custom-pang.git
cd custom-pang
# Abre pang.html en tu navegador
```

## 🛠️ Tecnología

- **HTML5 Canvas** — Renderizado gráfico
- **Vanilla JavaScript** — Sin dependencias externas
- **Responsive design** — Se adapta a cualquier pantalla
- **Touch API** — Soporte nativo de dispositivos táctiles

## 🎨 Características técnicas

- **Animaciones suaves** — 60 FPS (requestAnimationFrame)
- **Deteción de dispositivos** — Automáticamente muestra controles según el tipo de entrada
- **Física simulada** — Gravedad, velocidad angular, colisiones de círculos
- **Efectos de sonido** — (Próximamente: audio arcade retro)
- **Modo responsivo** — Funciona en desktop, tablet y móvil

## 📝 Cambios recientes

v1.2
- ✨ Arpón ondulado animado
- 🍎 Sistema de frutas de bonus
- 📊 Textos flotantes de puntos
- 🎯 Mejoras visuales

v1.1
- 📱 Soporte completo para móvil
- 🔄 Controles táctiles automáticos

v1.0
- 🎮 Mecánica arcade clásica
- 🌍 10 niveles temáticos
- 👥 Soporte 1-2 jugadores

## 🐛 Bugs conocidos

- En algunos navegadores antiguos, los estilos CSS variables podrían no renderizar correctamente

## 🚀 Mejoras futuras

- [ ] Power-ups (doble arpón, escudo, congelación)
- [ ] Temporizador de nivel con bonificación
- [ ] Tabla de puntuaciones (localStorage)
- [ ] Efectos de sonido retro
- [ ] Dificultad personalizable
- [ ] Modo infinito

## 📄 Licencia

Libre para usar, modificar y distribuir. Inspirado en el clásico Pang (Capcom, 1987).

---

**¿Problemas?** Abre un issue o contáctame. **¡Que disfrutes el juego!** 🎈

