<p align="center">
  <a href="https://github.com/BrandonGS22b/Front/blob/main/reacttutorial/react.png" target="blank"><img src="https://github.com/BrandonGS22b/Front/blob/main/reacttutorial/react.png" width="200" alt="React Logo" /></a>
</p>


<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%"><!-- se agrega estilo css line en rgb-->

<h3>Como empezar un proyecto en react</h3>
<a>Primero vamos abrir una ventana en cmd ya sea en el "escritorio" y ejecutamos los siguientes comandos</a>

```bash

npm create vite@latest  mi-nameproyect

```
<a>automaticamente se nos creara una carpera en el escritorio que es el proyecto </a>


<h3>Instalamos las dependencias del proyecto</h3>
<a>cuando ya estemos dentro del proyecto en visualStudio code vamos a la terminal del shell y aplicamos los siguientes comandos </a>
<b>

```bash

npm install

```
<a>Instalamos TailwindCss</a>

```bash

npm i -D tailwindcss postcss autoprefixer

```

<a>Instalamos el prefijo automatico</a>

```bash

npx tailwindcss init -p

```
<a>la estructura de nuestro proyecto quedaria de la siguiente manera:</a>

![image](https://github.com/BrandonGS22b/Front/blob/main/reacttutorial/estructura1.png)


<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%"><!-- se agrega estilo css line en rgb-->


<a>En el siguiente archivo vamos a escribir:</a>
<a>App.jsx</a>

```bash
export default function app(){
  return(
    <h1 className=" text-3x1 font blond underline ">
      Hello world!
    </h1>
  )
}

```
<a>Index.css</a>

```bash
@tailwind base;
@tailwind conponents;
@tailwind utilities;

```
<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%"><!-- se agrega estilo css line en rgb-->
<h3>Ejecutamos el proyecto o compilamos</h3>
<a>en la terminar o shell ponemos el siguiente comando</a>

```bash
npm run dev

```
<a>en la consola nos saldra lo siguiente</a>

![image](https://github.com/BrandonGS22b/Front/blob/main/reacttutorial/consola.png)

<a>Abrimos el link y para abrir la pagina del servicio</a>

![image](https://github.com/BrandonGS22b/Front/blob/main/reacttutorial/resutado.png)








