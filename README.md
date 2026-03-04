# Memento Mori

**Visualiza tu vida en semanas. Recuerda que vas a morir.**

> *"No es que tengamos poco tiempo, sino que perdemos mucho."* — Séneca

[**Ver en vivo**](https://gneironiar.github.io/memento_mori/)

---

## Qué es

Una página web que muestra tu vida entera como una grilla de cuadrados. Cada cuadrado es una semana. Los que ya viviste, los que te quedan, y el que estás viviendo ahora mismo.

Ingresás tu fecha de nacimiento, tu expectativa de vida, y la grilla te devuelve una imagen que dice más que mil palabras.

## Cómo funciona

- **Grilla semanal** (desktop): 48 columnas × 10 filas por década — cada celda es una semana
- **Grilla mensual** (mobile): 12 columnas × 10 filas por década — cada celda es un mes
- Las décadas se organizan lado a lado para ver toda tu vida en una sola pantalla
- El cuadrado naranja es **ahora**

### Paleta

| Color | Significado |
|-------|-------------|
| `#b8a882` | Semanas vividas |
| `#d4785a` | Esta semana |
| `#28272e` | Semanas por vivir |
| `#141418` | Fondo |

## Features

- Bilingüe (Español / English)
- Responsive: vista semanal en desktop, mensual en mobile
- Renderizado con Canvas (sin overflow, sin scroll)
- Sección de reflexiones compartidas entre todos los visitantes
- Nube de palabras generada en tiempo real
- Contador de almas que reflexionaron
- Share personalizado con tus stats a X, WhatsApp, LinkedIn, Facebook

## Stack

Un solo archivo HTML. Sin framework, sin build, sin dependencias locales.

- HTML + CSS + JavaScript vanilla
- Canvas API para la grilla
- Firebase Realtime Database para reflexiones compartidas
- GitHub Pages para hosting

## Ejecutar localmente

Abrí `index.html` en un navegador. Eso es todo.

Las reflexiones compartidas requieren conexión a internet (Firebase).

---

*Memento Mori — recuerda que vas a morir. Y mientras tanto, viví.*
