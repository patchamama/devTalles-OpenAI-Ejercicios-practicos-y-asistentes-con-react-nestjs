# devTalles: OpenAI. Ejercicios prácticos y asistentes con React + NestJS

Curso online [aquí](https://cursos.devtalles.com/courses/openai)

Reto final después de terminar el curso:
- [ ] Agregar funcionalidades para el uso de OpenAI tal como corrección de textos en inglés.
- [ ] Reprogramar el backend usando Deno y/o Burn
- [ ] Reprogramar el backend usando flask y/o Django DRF y/o FastAPI
- [ ] Reprogramar el frontend usando Astro y/o VueJS
- [ ] Reprogramar con Laravel / Lumen



## Sección 1: Introducción


[Instalaciones recomendadas](https://gist.github.com/Klerith/f0b6bf38f8d7103dec6079b7fea17e2f)
[Hoja de atajos de NestJS](https://github.com/Klerith/mas-talento/blob/main/nest/nest-cheatsheet.pdf)


## Sección 2: Frontend - Diseño y creación de la aplicación

### Temas puntuales de la sección

Esta sección es totalmente opcional, ya que no veremos nada de OpenAI aún, está destinada a la creación del cascarón inicial de nuestro frontend en React.

Puntualmente veremos:

- React Router Dom
- Diseño de Layout
- Rutas Hijas
- Redirecciones
- Tailwind
- React Markdown Component
- Diseño de chat
- Estructura del proyecto.

### Inicio del proyecto - ReactGPT

Crear el proyecto
```sh
npm create vite
cd react-gpt
npm install

# Correr la aplicación  para ver sí funciona
npm run dev
````

### Configurar TailwindCSS en react

Referencias
- https://tailwindcss.com/
- [Estilos globales](https://gist.github.com/Klerith/d02b770a277c4e6c8753ac02fd752837)


Visitar https://tailwindcss.com/docs/guides/vite y copiar comandos para instalar TailwindCSS:

```sh
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### Rutas y páginas

Referencias:
- https://reactrouter.com
- https://cdnjs.com/libraries/font-awesome
- [Gist - Arreglo de Rutas](https://gist.github.com/Klerith/2601fd211b014551f3934defdecf1c73)
