# BrainHack

## 🛠️ Ejecución Local

Para ejecutar este proyecto en tu máquina local, sigue estos pasos:

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/BrainHack.git
   cd BrainHack
   ```

2. **Instala las dependencias:**
   ```bash
   deno install
   ```

3. **Ejecuta el servidor de desarrollo:**
   ```bash
   deno run dev
   ```

El proyecto estará disponible en `http://localhost:4321/BrainHack`

## 🚀 Estructura del Proyecto

Dentro de tu proyecto Astro, verás las siguientes carpetas y archivos:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro busca archivos `.astro` o `.md` en el directorio `src/pages/`. Cada página se expone como una
ruta basada en su nombre de archivo.

No hay nada especial sobre `src/components/`, pero ahí es donde nos gusta colocar cualquier
componente de Astro/React/Vue/Svelte/Preact.

Cualquier recurso estático, como imágenes, puede colocarse en el directorio `public/`.

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                | Acción                                           |
| :--------------------- | :----------------------------------------------- |
| `deno install`         | Instala las dependencias                         |
| `deno dev`             | Inicia el servidor de desarrollo local en `localhost:4321` |
| `deno build`           | Construye tu sitio de producción en `./dist/`    |
| `deno preview`         | Previsualiza tu construcción localmente, antes del despliegue |
| `deno astro ...`       | Ejecuta comandos CLI como `astro add`, `astro check` |
| `deno astro -- --help` | Obtiene ayuda usando la CLI de Astro            |
| `deno run npm:shadcn@latest add <componente>` | Agrega componentes de shadcn/ui |

## 📚 Tecnologías Usadas

Este proyecto utiliza las siguientes tecnologías principales:

| Tecnología | Descripción | Documentación |
| :--------- | :---------- | :------------ |
| **React** | Biblioteca de JavaScript para construir interfaces de usuario | [Documentación](https://react.dev/) |
| **Astro** | Framework web moderno para construir sitios web rápidos y centrados en el contenido | [Documentación](https://docs.astro.build/) |
| **Tailwind CSS** | Framework de CSS utilitario para diseño rápido y personalizable | [Documentación](https://tailwindcss.com/docs) |
| **shadcn/ui** | Biblioteca de componentes reutilizables construida con Radix UI y Tailwind CSS | [Documentación](https://ui.shadcn.com/) |
| **Radix UI** | Biblioteca de componentes primitivos de bajo nivel para crear sistemas de diseño de alta calidad | [Documentación](https://www.radix-ui.com/) |

