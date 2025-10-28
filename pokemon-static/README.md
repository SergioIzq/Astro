#  pokedex-astro 
![Logo de Pokémon](https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/25.png)

Una aplicación web visual para explorar el mundo Pokémon, construida con Astro, Tailwind CSS y la PokeAPI. Este es mi segundo proyecto desarrollado con Astro.

[Proyecto desplegado](https://pokedex.sergioizq.es)

---

## 📖 Sobre este proyecto

Este proyecto es una **Pokédex** que permite a los usuarios explorar información sobre distintos Pokémon de una manera visual, sencilla y rápida. La aplicación consume datos de la [PokeAPI](https://pokeapi.co/) para mostrar listados y detalles de cada criatura.

El objetivo principal fue practicar la integración de APIs, el manejo de datos dinámicos y la construcción de una interfaz limpia y funcional utilizando tecnologías modernas.

### ✨ Características

* Listado de Pokémon con scroll infinito (o paginación, ¡depende de cómo lo hayas implementado!).
* Página de detalle para cada Pokémon (estadísticas, tipos, habilidades, etc.).
* Diseño 100% responsive.
* Interfaz rápida gracias al renderizado estático de Astro.

---

## 🛠️ Tecnologías Utilizadas

El stack principal del proyecto es:

* **[Astro](https://astro.build/)**: Framework web para construir sitios rápidos. Usado para el renderizado estático y la componentización.
* **[Tailwind CSS](https://tailwindcss.com/)**: Framework de CSS utility-first para un diseño moderno y responsive.
* **[PokeAPI](https://pokeapi.co/)**: La API REST gratuita de donde se obtienen todos los datos de los Pokémon.

---

## 🎯 Aprendizajes

Durante el desarrollo de este proyecto, los principales puntos de aprendizaje fueron:

* **Consumo de APIs**: Practicar `fetch` para obtener datos de una API externa.
* **Renderizado Dinámico en Astro**: Creación de páginas dinámicas (por ejemplo, `[id].astro` o `[pokemon].astro`) a partir de los datos de la API.
* **Componentes Reutilizables**: Creación de componentes (como `PokemonCard.astro`) para mantener el código limpio y escalable.
* **Manejo de Layouts**: Uso de `MainLayout.astro` para una estructura de página consistente.
* **Estilado con Tailwind**: Afianzar conocimientos en Tailwind CSS para crear interfaces complejas y atractivas.

---

## 🚀 Cómo empezar

Si quieres ejecutar este proyecto en tu máquina local, sigue estos pasos:

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/SergioIzq/Astro](https://github.com/SergioIzq/Astro)
    cd pokemon-static
    ```

2.  **Instala las dependencias:**
    ```bash
    npm install
    # o pnpm install, yarn install
    ```

3.  **Ejecuta el servidor de desarrollo:**
    ```bash
    npm run dev
    ```

4.  Abre `http://localhost:4321` en tu navegador para ver el proyecto.

---

## 👨‍💻 Autor

* **Sergio Izquierdo**
* GitHub: `[@SergioIzq](https://github.com/SergioIzq)`
* LinkedIn: `[Sergio Izquierdo](https://linkedin.com/in/sergioizquierdomoreno)`