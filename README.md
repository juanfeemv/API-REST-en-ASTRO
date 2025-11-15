# Proyecto Astro: Consumo de API de Recetas

## Descripción

Este proyecto consiste en una aplicación web desarrollada con **Astro** que consume datos de la API pública [TheMealDB](https://www.themealdb.com/api.php) para mostrar recetas de cocina de todo el mundo. El objetivo principal fue practicar la integración de **APIs externas**, renderizado dinámico de datos y diseño de interfaces web responsivas.

El usuario puede:

- Ver una **rejilla de recetas** con nombre, imagen, categoría, área y etiquetas.
- **Filtrar recetas en tiempo real** mediante un input de búsqueda.
- Abrir un **modal** con la información completa de cada receta, incluyendo ingredientes e instrucciones.
- Disfrutar de una experiencia **responsiva**, funcional en escritorio y dispositivos móviles.

---

## Tecnologías utilizadas

- **Astro**: framework para construir páginas web rápidas y escalables.
- **HTML5** y **CSS3**: para estructura y diseño visual.
- **JavaScript**: manejo de lógica del filtro, modal y consumo de API.
- **TheMealDB API**: fuente de datos de recetas públicas.
- **Fonts**: 'Inter' para texto y 'Playfair Display' para títulos.

---

## Funcionalidades

- **Consumo de API**: se obtienen todas las recetas disponibles usando `fetch` en paralelo para cada letra del abecedario.
- **Filtrado en tiempo real**: búsqueda de recetas por nombre.
- **Modal interactivo**: muestra ingredientes e instrucciones al hacer clic en una tarjeta.
- **Responsivo**: la interfaz se adapta a móviles y tablets.
- **Manejo de errores**: si la API falla o devuelve resultados vacíos, se muestra un mensaje al usuario.

---

