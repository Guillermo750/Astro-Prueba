# Astro Ejemplo: Basics

## 🚀 Project Structure

Dentro de tu proyecto Astro, verás las siguientes carpetas y archivos:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Para obtener más información sobre la estructura de carpetas de un proyecto Astro, consulte [nuestra guía sobre la estructura de proyectos](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

Todos los comandos se ejecutan desde la raíz del proyecto, desde un terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala dependencias                            |
| `npm run dev`             | Inicia el servidor de desarrollo local en `localhost:4321`  |
| `npm run build`           | Construye tu sitio de producción en `./dist/`   |
| `npm run preview`         | Previsualiza tu construcción localmente, antes de desplegar      |
| `npm run astro ...`       | Ejecuta comandos CLI como `astro add`, `astro check` |
| `npm run astro -- --help` | Obtén ayuda usando Astro CLI                 |


## Instalación del Proyecto

Para crear nuestro proyecto ejecutamos este comando:
1. npm create astro@latest

1. Escribimos el nombre de nuestro proyecto
2. Le decimos que Nos instale las dependecias
3. Le decimos que si inicialize con Git

![image](https://github.com/user-attachments/assets/00784b39-d326-4ba6-84e8-3c0cb7ac5acb)

## Accedemos a nuestro Proyecto y arrancamos el Visual Studio Code ejecutando estos comandos
<img width="263" alt="captura 2 accedemos a la ruta y arrancamos el Visual Studio Code" src="https://github.com/user-attachments/assets/bfb54cc0-cfbe-4ac7-93dc-65069c6e31e0" />

## Podemos ver la estructura de nuestro Proyecto
<img width="748" alt="captura 3 vemos la estructura de nuestro proyecto" src="https://github.com/user-attachments/assets/10fe023b-b0cf-426d-b6e2-543d68f660fb" />

## Para instalar el `framework de tailwind CSS` a nuestro Proyecto ejecutamos este comando y le damos Sí a todo
<img width="605" alt="captura 4 añadir el framework tailwind a nuestro proyecto astro y darle Sí a todo" src="https://github.com/user-attachments/assets/dbf96bc5-2bea-4b98-a331-e5c584afbe16" />

Observamos que se nos creó una carpeta 'Styles' y dentro una archivo .CSS 'global.css'
Creando un 'h1' dentro del main del index podemos comprobar que el framwork tailwind CSS se instaló correctamente
<img width="791" alt="captura 5 vemos en nuestro proyecto que se nos creo una carpeta llamada estilos, un archivo global css y vemos código Tailwinds CSS añadiendose a un h1" src="https://github.com/user-attachments/assets/7325d445-57d2-4a02-b443-585247124196" />

## Ejecutamos este comando para arrancar nuestro programa
Accedemos a la ruta Local para ver la Web
<img width="324" alt="captura 6 arrancamos el programa ejecutando este comando" src="https://github.com/user-attachments/assets/bc2f3337-3570-4983-9760-9c81a8cd7b8d" />

## Ejecutamos estos dos comando para añadir el selector de idiomas al menú y que no los traduzca
<img width="424" alt="captura 7 instalar el paquete para la internacionalización en Astro e instalr i18next y arrobatypes(barra del 7)i18next como dependencias de desarrollo para que el menú también cambia de idioma" src="https://github.com/user-attachments/assets/3b4d8989-96fe-4759-8dfa-8224defcc0c0" />

## Creamos estos dos archivos en nuestro proyecto
<img width="199" alt="captura 8 creamos estos dos archivos en nuestro proyecto" src="https://github.com/user-attachments/assets/354aab0e-d4fc-408b-9a98-0066a7dc1527" />

## Dentro de este archivo `i18next-config.ts` añadimos este código
<img width="231" alt="captura 9 añadir este código al achivo 'i18next-config ts'i18next-config ts" src="https://github.com/user-attachments/assets/ba87ea57-3c78-4b07-9ef1-9b71b935821d" />

## Dentro de este archivo `i18next.d.ts` añadimos este código
<img width="209" alt="captura 10 añadir este código al achivo 'astro-i18next d ts'" src="https://github.com/user-attachments/assets/3c062084-0592-471a-832e-5d9db3096ad2" />

## Dentro de este archivo `astro.config.mjs` añadimos este código
<img width="321" alt="captura 11 añadir esto al archivo 'astro config mjs'" src="https://github.com/user-attachments/assets/415e8e82-898a-4d32-9190-e6d6ab7f9ff6" />

## Si nos da error en ìnitReactI18next`
![Captura 12 Si da error en lo marcado con rojo](https://github.com/user-attachments/assets/c7b47b41-6eec-4e42-b8d1-bbd038de9e85)

Ejecutamos estos dos comandos para corregirlo
<img width="484" alt="captura 12 1 ejecutamos estos comandos si el error no da en esta línea import { initReactI18next } from 'react-i18next';" src="https://github.com/user-attachments/assets/cf91db8a-98e8-4f56-bfea-5b08b9589eee" />

## Explicación de porque el archivo 'astro-i18next.d.ts' tiene que estar dentro de la carpeta src:
Es importante poner el archivo astro-i18next.d.ts dentro de la carpeta src porque esta carpeta es donde generalmente se almacenan los archivos de código fuente de tu proyecto. Al colocar el archivo de declaración de tipos dentro de la carpeta src, te aseguras de que TypeScript pueda encontrarlo y utilizarlo para proporcionar información de tipos para el módulo astro-i18next.

Además, al colocar el archivo de declaración de tipos dentro de la carpeta src, estás siguiendo una convención común para la organización de proyectos TypeScript, lo que facilita la comprensión y el mantenimiento del código.
