# 🚀 Portafolio Web — Irving Poot

Portafolio personal desarrollado con **Astro** y **TypeScript**, diseñado para mostrar proyectos, habilidades y experiencia profesional de forma rápida y moderna.

---

## 🛠️ Tecnologías utilizadas

- [Astro](https://astro.build/) — Framework web de alto rendimiento
- [TypeScript](https://www.typescriptlang.org/) — Tipado estático
- [pnpm](https://pnpm.io/) — Gestor de paquetes rápido y eficiente

---

## 📁 Estructura del proyecto

```
/
├── public/
│   └── favicon.svg          # Activos estáticos públicos
├── src/
│   ├── assets/              # Imágenes y recursos del proyecto
│   ├── components/          # Componentes reutilizables (.astro)
│   ├── layouts/             # Plantillas de página base
│   └── pages/
│       └── index.astro      # Página principal del portafolio
├── astro.config.mjs         # Configuración de Astro
├── tsconfig.json            # Configuración de TypeScript
└── package.json
```

---

## ⚙️ Requisitos previos

- [Node.js](https://nodejs.org/) v18.14.1 o superior
- [pnpm](https://pnpm.io/installation) v8 o superior

---

## 🚀 Instalación y uso

Clona el repositorio e instala las dependencias:

```bash
git clone https://github.com/irvingpoot/portafolio-web.git
cd portafolio-web
pnpm install
```

### Comandos disponibles

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando             | Descripción                                              |
| ------------------- | -------------------------------------------------------- |
| `pnpm dev`          | Inicia el servidor de desarrollo en `localhost:4321`     |
| `pnpm build`        | Genera el sitio de producción en `./dist/`               |
| `pnpm preview`      | Previsualiza el build localmente antes de desplegar      |
| `pnpm astro ...`    | Ejecuta comandos del CLI de Astro (`add`, `check`, etc.) |

---

## 🌐 Despliegue

El sitio puede desplegarse en cualquier plataforma de hosting estático compatible con Astro:

- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
- [GitHub Pages](https://pages.github.com/)
- [Cloudflare Pages](https://pages.cloudflare.com/)

Para construir el sitio listo para producción:

```bash
pnpm build
```

Los archivos generados estarán en la carpeta `./dist/`.

---

## 📄 Licencia

Este proyecto es de uso personal. Siéntete libre de tomarlo como inspiración para tu propio portafolio.

---

## 🙋‍♂️ Contacto

Desarrollado por **Irving Poot** — [@irvingpoot](https://github.com/irvingpoot)
