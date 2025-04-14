# Astro Ejemplo: Basics

Vídeo del Curso desde Cero de Astro
https://www.youtube.com/watch?v=RB5tR_nqUEw&t=2309s

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

![image](https://github.com/user-attachments/assets/0cf6c62b-1226-457e-a9c6-ace36df5be5b)

## Accedemos a nuestro Proyecto y arrancamos el Visual Studio Code ejecutando estos comandos
![image](https://github.com/user-attachments/assets/aeb5bfcc-5078-4e60-ac71-5debfa3ed174)

## Podemos ver la estructura de nuestro Proyecto
![image](https://github.com/user-attachments/assets/2fc03826-7f23-4c3b-8650-f71fec0bd403)

## Para instalar el `framework de tailwind CSS` a nuestro Proyecto ejecutamos este comando y le damos Sí a todo
![image](https://github.com/user-attachments/assets/f37b01a8-ba6c-4de7-a96b-dfd8cc45b177)

Observamos que se nos creó una carpeta 'Styles' y dentro un archivo llamdo 'global.css'
Creando un 'h1' dentro del main del index podemos comprobar que el framwork tailwind CSS se instaló correctamente
![image](https://github.com/user-attachments/assets/5b2d466b-6638-44dc-b077-52b535a4212f)

La guía oficial de Astro para integrar Tailwind CSS: 
https://docs.astro.build/en/guides/styling/#tailwind-css

## Ejecutamos este comando para arrancar nuestro programa
Accedemos a la ruta Local para ver la Web

![image](https://github.com/user-attachments/assets/6703246a-bdee-4a7f-a636-ba205db5f71a)



