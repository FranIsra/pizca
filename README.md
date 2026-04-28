# Pizca (Astro + Vanilla JS + esbuild-wasm)
Una herramienta web ultra rápida para la minificación de archivos JS y CSS, construida con Astro y ejecutada íntegramente en el cliente mediante WebAssembly.

[🔗 Ver Versión Web en GitHub Pages](https://franisra.github.io/pizca)

✨ Características

* Velocidad Extrema: Potenciado por esbuild-wasm, el minificador más rápido del ecosistema actual.

* Privacidad Total: El procesamiento ocurre 100% en tu navegador. Tu código nunca se envía a ningún servidor.

* Sin Dependencias de Node: Diseñado para funcionar como una aplicación web estática (SPA).

* Interfaz Minimalista: Enfocado en la productividad y la simplicidad.

## 🛠️ Tecnologías utilizadas

* Astro: Framework web para conseguir un rendimiento óptimo.

* esbuild-wasm: Motor de procesamiento compilado a WebAssembly.

* Vanilla JavaScript: Lógica de cliente pura para interactuar con el motor de minificación.

* GitHub Pages: Alojamiento gratuito y seguro para el despliegue.

## 🔒 Privacidad y Seguridad

* La seguridad es el pilar de esta herramienta. A diferencia de otros minificadores online que suben tu código a sus servidores:

* El navegador descarga el motor de esbuild desde un CDN seguro (jsDelivr).

* El código que pegas en la herramienta se procesa localmente en tu memoria RAM.

* Puedes incluso desconectar tu internet tras cargar la página y la herramienta seguirá funcionando.

## 🚀 Instalación y Desarrollo Local

Si deseas clonar este proyecto y ejecutarlo en tu máquina:

Clona el repositorio:

Bash

```text
gh repo clone FranIsra/pizca
```

Instala las dependencias:

Bash

```text
npm install
```

Bun

```text
bun install
```

Inicia el servidor de desarrollo:

Bash

```text
npm run dev
```

Bun

```text
bun run dev
```

Construye para producción:

Bash

```text
npm run build
```

Bun

```text
bun run build
```

## 📦 [Despliegue](https://docs.astro.build/es/guides/deploy/github/)

Este proyecto está configurado para desplegarse en GitHub Pages mediante GitHub Actions al hacer push a la rama main. Asegúrate de que tu archivo .github/workflows/deploy.yml este creado y astro.config.mjs tenga configurado el site y la base correctamente.

Creado con ❤️