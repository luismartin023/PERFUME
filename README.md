# AS Fragrance - Tienda Online y Juego

Proyecto web de AS Fragrance que incluye una tienda de perfumes, rankings de top tier y un juego arcade de peleas.

## 📁 Estructura del Proyecto

```
As_Fragance/
├── tienda/
│   ├── assets/          # Archivos CSS e imágenes
│   ├── top_tier.html    # Página de rankings de perfumes
│   └── versus.html      # Juego arcade "Perfume Fighter"
└── README.md
```

## 🚀 Características

### Top Tier Page (top_tier.html)
- Rankings de perfumes por categoría (General, Masculino, Femenino)
- Criterios de evaluación (Beast Mode, Gourmand, etc.)
- Diseño moderno con gradientes y animaciones
- Navegación fluida entre secciones

### Perfume Fighter (versus.html)
- Juego de peleas estilo arcade
- 18 personajes de perfumes con estadísticas únicas
- Modos: 1 vs CPU y 1 vs 1
- Sistema de combate con ataques ligeros y pesados
- IA para el modo CPU
- Efectos de sonido y música
- Memes dominicanos durante el combate

## 🎮 Controles del Juego

### Player 1
- **W/A/S/D**: Mover
- **C**: Bloqueo
- **V**: Ataque Rápido
- **B**: Ataque Pesado (recarga 2s)

### Player 2 / CPU
- **Flechas**: Mover
- **J**: Bloqueo
- **K**: Ataque Rápido
- **L**: Ataque Pesado (recarga 2s)

### General
- **P**: Pausa

## 🌐 Despliegue

### Local
```bash
cd tienda
python -m http.server 3000
```
Luego visita http://localhost:3000/top_tier.html

### Vercel
Este proyecto es un sitio estático HTML/CSS/JS, listo para desplegar en Vercel:
1. Conecta tu repositorio de GitHub
2. Vercel detectará automáticamente que es un sitio estático
3. Despliega con configuración por defecto

## 📝 Notas

- El proyecto usa fuentes de Google Fonts (Outfit)
- Las imágenes de los perfumes se cargan desde CDN externo
- Los efectos de sonido usan la librería ion-sound CDN
- Todo el código es client-side, no requiere backend

## 🎨 Tecnologías

- HTML5
- CSS3 (con variables y animaciones)
- JavaScript (ES6+)
- Sin frameworks externos para el juego

## 📄 Licencia

Proyecto privado de AS Fragrance.
