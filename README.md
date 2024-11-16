# Proyecto React + TypeScript + Vite

Este proyecto es una aplicación web desarrollada en React y TypeScript, utilizando Vite como herramienta de construcción. Incluye componentes reutilizables, gestión de formularios y ejemplos prácticos de hooks de React como `useState` y `useEffect`.

## Requisitos previos

Asegúrate de tener instalados los siguientes programas antes de ejecutar el proyecto:

- [Node.js](https://nodejs.org/) (versión 16 o superior)
- [npm](https://www.npmjs.com/) o [yarn](https://yarnpkg.com/)

## Instalación

Sigue estos pasos para configurar y ejecutar el proyecto en tu máquina local:

1. **Clona este repositorio:**
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_PROYECTO>
   ```

2. **Instala las dependencias del proyecto:**
   Si usas `npm`:
   ```bash
   npm install
   ```
   Si usas `yarn`:
   ```bash
   yarn install
   ```

## Ejecución en modo desarrollo

Para iniciar el servidor de desarrollo, ejecuta:

```bash
npm run dev
```
o

```bash
yarn dev
```

Esto abrirá el proyecto en tu navegador predeterminado en `http://localhost:5173`.

## Construcción para producción

Para generar una versión optimizada para producción:

```bash
npm run build
```
o

```bash
yarn build
```

Los archivos optimizados estarán en la carpeta `dist`.

## Estructura del Proyecto

- **`index.html`:** Archivo principal HTML que incluye el punto de montaje `#root`.
- **`src/main.tsx`:** Archivo de entrada de la aplicación.
- **`src/components/`:** Contiene los diferentes componentes reutilizables:
  - `MiPrimerComponent.tsx`: Un ejemplo básico de un componente funcional con props.
  - `ComponentCounter.tsx`: Componente para manejar un contador.
  - `ComponentUseEffect.tsx`: Ejemplo del uso de `useEffect`.
  - `FormComponent.tsx`: Componente de formulario con gestión de estado.
  - `AppProduct/`: Subcarpeta con componentes relacionados con la gestión de productos.
- **`src/hooks/`:** Contiene hooks personalizados como `useForm`.

## Características del Proyecto

- **React + TypeScript:** Beneficios del tipado estático y las características avanzadas de React.
- **Gestión de estado:** Uso de hooks (`useState`, `useEffect`) para la lógica de los componentes.
- **Formularios dinámicos:** Hook personalizado `useForm` para manejar formularios.
- **Componentes modulares:** Estructura modular y reutilizable para facilitar la escalabilidad.

## Scripts Disponibles

- `dev`: Inicia el servidor de desarrollo.
- `build`: Construye la aplicación para producción.
- `preview`: Previsualiza la aplicación construida.

## Tecnologías utilizadas

- **React:** Biblioteca para construir interfaces de usuario.
- **TypeScript:** Lenguaje tipado para JavaScript.
- **Vite:** Herramienta rápida de construcción y desarrollo.
- **Bootstrap:** Estilización rápida y componentes responsivos.

## Personalización

Puedes habilitar o deshabilitar componentes comentados en `App.tsx` para personalizar la aplicación según tus necesidades.

## Autor

Especifica tu nombre o equipo aquí.

## Licencia

Este proyecto está bajo la licencia [MIT](./LICENSE).
