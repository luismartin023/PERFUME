<div align="center">

# AS Fragrance — Tienda Online y Juego

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Sin backend](https://img.shields.io/badge/Backend-No%20requerido-1E7A3C?style=flat-square)
![Hecho en RD](https://img.shields.io/badge/Hecho%20en-Rep%C3%BAblica%20Dominicana%20%F0%9F%87%A9%F0%9F%87%B4-CE1126?style=flat-square)

Proyecto web de **AS Fragrance**: tienda de perfumes, rankings *top tier*
y **Perfume Fighter**, un juego arcade de peleas con 18 personajes.

</div>

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
