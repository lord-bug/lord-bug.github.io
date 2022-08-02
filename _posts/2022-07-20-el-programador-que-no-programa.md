---
title: El programador que no programa
author: lord-bug
categories: [Programacion,Tecnología]
tags: [jekyll,programacion,tecnologia,blog]
---

# El motivo por el que uso Jekyll
1. [Antecedentes](#antecedentes)
2. [Jekyll](#jekyll)
3. [Cacharreando](#cacharreando)
4. [Conclusiones](#conclusiones)

## Antecedentes

No todos los programadores sabemos de todo.

Muchas veces tiendo a comparar nuestro oficio con la medicina, en cuanto a especialización se refiere. ¿Tu crees que un traumatologo sabría hacer un transplante de corazón?

Pues lo mismo los programadores. Yo llevo toda mi vida trabajando en el Backend de las cosas. ¿que pasa cuando uno de nosotros necesita una página web?

Pues una de dos: o te haces un bootcamp de desarrollador web full stack tope chachi guai (gratuito o no), lo cual lleva su tiempo, o utilizas algo prefabricado. Algún día daré mi opinión sobre esto de ser Full Stack y las modas.

<p style="text-align:center;">
    <img src="https://lord-bug.github.io/assets/img/2022-07-21/full-stack-meme.jpg" width="420">
</p>

## Jekyll

Cuando me planteé la creación de este blog, quería algo que fuera sencillo, minimalista y sobre todo, fácil de mantener y de hostear, por lo que descubrí los blogs estáticos, cuyo contenido era actualizado mediante ficheros en lenguaje [Markdown](https://www.markdownguide.org/).

Realmente pensaba que había descubierto algo perfecto, dado que eliminaba de un plumazo bastantes problemas (buscar hosting con BBDD, los tiempos de carga...), hasta que empecé a ver tutoriales y me di cuenta que había que controlar de tecnologías como [React](https://es.reactjs.org/) o [NextJs](https://nextjs.org/) para llevar esto a cabo.

A pesar de todo, tenía las mismas ganas de tener un blogspot o un wordpress que de sentarme encima de un cactus, por lo que adapté mi búsqueda un poco y encontré mi Santo Grial, [Jekyll](https://jekyllrb.com/).

<p style="text-align:center;">
    <img src="https://lord-bug.github.io/assets/img/2022-07-21/holy-grail-jekyll.jpg">
</p>

Jekyll es un generador de webs estáticas, ideal para crear blogs o portafolios con el mínimo esfuerzo. Está basado en Ruby, aunque no es necesario saber este lenguaje para ponerlo en funcionamiento (yo no tengo ni idea de Ruby).

Acepta plugins y sobre todo, temas hechos por la comunidad, por lo que tampoco tienes porqué saber nada de HTML y CSS (aunque para incrustar según qué código, te vendría muy bien alguna noción básica. Nada que no se pueda googlear).

¿Y para hostear? Pues nada mejor ni más fácil que usar Github Pages. El sistema está preparado para ello y (dependiendo del tema que uses), te bastará con hacer un push de tus cambios en Github, que el se encargará solito de publicar las actualizaciones.

## Cacharreando

No voy a darmelas de experto en este tema. Os voy a hacer un favor mucho mayor, que es dejaros el vídeo que yo mismo usé para instalarlo todo.

<p style="text-align:center">
    <a href="https://youtu.be/F8iOU1ci19Q" style="text-decoration:none">
        <img src="https://img.youtube.com/vi/F8iOU1ci19Q/hqdefault.jpg">
    </a>
</p>

Os recomiendo seguir los pasos al pie de la letra, al menos si queréis usar el tema que hemos usado el creador del video y yo. Tengo la enorme suerte de que el empleado en el tutorial es el que más me gusta de todos los que vi disponibles.

Hay varios factores a tener en cuenta:
* Recomiendo usar Linux, o bien de manera nativa o bien mediante WSL en Windows 10/11 (es mi caso).
* Haz caso cuando dicen que tienes que nombrar el repositorio como lo tienes que llamar, es vital. Yo fuí de listo y tuve que empezar todo desde cero porque se me rompió todo a la hora de publicar.
* Si usas WSL como yo, te recomiendo usar un IDE con entorno gráfico como VSCode, más que nada porque si vas a usar imágenes u otros recursos, podrás arrastrarlos a las carpetas directamente desde tu sistema Windows, y así se pegaran en tu sistema Linux sin hacer muchos malabares.

## Conclusiones

Si estás leyendo este artículo, significa que, en líneas generales, estoy contento con este sistema de blogging. No es que sea un sistema perfecto, pero si que puedes tener algo bastante decente con pocos conocimientos y empleando, según tu nivel, una cantidad de tiempo razonable.

Jekyll tiene cosas malas, por supuesto, como por ejemplo el hecho de que incrustar videos de Youtube es bastante cutre, o que te arriesgas como yo a tener un blog que se parece a muchisimos otros debido al uso de temas prefabricados.

Pero si eres de esa gente que antepone el contenido al contenedor, tienes prisa por expresarte o realmente el desarrollo full stack no es para ti, te lo recomiendo.

Lord Bug.

