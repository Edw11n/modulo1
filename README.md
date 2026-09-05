# Recetario

Aplicación web para buscar y ordenar recetas de cocina.

## Estructura del proyecto

```
.
├── index.html      # Página principal
├── css/style.css   # Estilos de la aplicación
├── js/app.js       # Lógica de la aplicación
└── README.md
```

## Características

- **Búsqueda de recetas**: campo de texto para filtrar recetas por nombre.
- **Ordenación**: permite ordenar las recetas por nombre o por tiempo de preparación.
- **Listado dinámico**: las recetas se renderizan en el elemento `main` de la página.

## Uso

1. Abre `index.html` en tu navegador.
2. Usa el campo **Buscar receta...** para filtrar por nombre.
3. Usa el desplegable **Ordenar...** para ordenar por nombre o por tiempo.

## Tecnologías

- HTML
- CSS
- JavaScript

## Estructura del HTML

- `<header>`: contiene el título, el campo de búsqueda (`#buscar`) y el selector de orden (`#orden`).
- `<main id="lista-recetas">`: contenedor donde se renderiza la lista de recetas.
