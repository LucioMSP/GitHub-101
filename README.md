<!-- 
  <<< Author notes: Header of the course >>> 
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses Creative Commons Attribution 4.0 International.
-->
# GitHub-101
Curso básico para aprender a usar GitHub
---

<!-- 
  <<< Author notes: Start of the course >>> 
-->

<details id=0>
<summary><h2>¡Bienvenidxs!</h2></summary>

Estamos encantados de darles la bienvenida a este emocionante curso, donde aprenderán los fundamentos de GitHub y cómo aprovechar al máximo esta increíble plataforma de desarrollo colaborativo. GitHub se ha convertido en la herramienta de elección por millones de desarrolladores en todo el mundo, y este curso les brindará las habilidades necesarias para comenzar a utilizarlo de manera efectiva.

Durante este curso, exploraremos los conceptos básicos de GitHub, incluyendo cómo configurar su cuenta, crear y clonar repositorios, realizar cambios, colaborar con otros desarrolladores y mucho más. También les proporcionaremos consejos y buenas prácticas para garantizar una gestión eficiente de su flujo de trabajo.

Nuestro objetivo es ayudarles a familiarizarse con GitHub y demostrarles cómo puede mejorar su productividad, facilitar la colaboración en equipo y llevar su desarrollo de software al siguiente nivel. No importa si son principiantes en el mundo de la programación o si ya tienen experiencia con control de versiones, este curso está diseñado para adaptarse a todos los niveles de conocimiento.

Recuerden que el aprendizaje es un proceso continuo, y GitHub es una herramienta en constante evolución. Así que, estén abiertos a explorar, hacer preguntas y compartir ideas. Juntos, crearemos un entorno de aprendizaje enriquecedor y estimulante.

Estamos emocionados de acompañarles en esta aventura y esperamos que aprovechen al máximo este curso. 

¡Buena suerte y feliz codificación!

El equipo de GitHub 101

</details>

<!-- 
  <<< Author notes: Introduction >>> 
-->

<details id=1>
<summary><h2>Introducción</h2></summary>

**¿Qué es GitHub?**
<br>
GitHub es un servicio basado en la nube que aloja un sistema de control de versiones [(VCS)](https://es.wikipedia.org/wiki/VCS_(desambiguaci%C3%B3n)) llamado [Git](https://docs.github.com/es/get-started/using-git/about-git), en otras palabras es una plataforma de colaboración que utiliza Git para el control de versiones, es decir, se utiliza para compartir y contribuir al software de [código abierto](https://docs.github.com/es/get-started/quickstart/github-glossary#c%C3%B3digo-abierto).
<br>
📺 Vídeo: [¿Qué es GitHub?](https://youtu.be/DinilgacaWs)

**¿Qué es un repositorio?**
<br>
Un [repositorio](https://docs.github.com/es/get-started/quickstart/github-glossary#repository) es un proyecto que contiene todos los archivos del mismo, tales como imagenes, carpetas, entre otros tipos de archivos. Así como el historial de revisiones de cada uno de ellos. Aqui puedes debatir y administrar el trabajo de tu proyecto dentro.
<br>
📺 Video: [¿Qué es un repositorio?](https://youtu.be/6NOwXGqHUds)

**¿Qué es una rama?**
<br>
En GitHub, una [rama (branch en inglés)](https://docs.github.com/es/get-started/quickstart/github-glossary#branch) es una versión paralela de un repositorio que permite a los desarrolladores trabajar en distintos aspectos de un proyecto de forma aislada. Cuando se crea una rama, se copian todos los archivos y el historial de cambios del repositorio principal, y a partir de ahí se pueden realizar modificaciones sin afectar la rama principal (también conocida como rama "master" o "main").

Las ramas son útiles para varios propósitos, como desarrollar nuevas características, solucionar problemas, experimentar con cambios importantes o colaborar con otros desarrolladores. Cada rama puede tener su propio conjunto de cambios y contribuciones independientes del resto del proyecto. Esto permite un flujo de trabajo colaborativo y paralelo, ya que cada desarrollador puede trabajar en su propia rama sin interferir con el trabajo de los demás.
<br>
📺 Vídeo: [¿Qué son las ramas?](https://youtu.be/LL47l59Ld5I)

**¿Qué es un archivo README?**
<br>
Un archivo [README](https://docs.github.com/es/get-started/quickstart/github-glossary#archivo-l%C3%A9ame) en GitHub es una práctica común en la mayoría de los repositorios de código. README es una abreviatura de "read me" que significa "léeme" en inglés. Este archivo tiene la extensión ".md", lo que indica que está escrito en formato Markdown, un lenguaje de marcado ligero para formatear texto.

El README se utiliza para proporcionar información básica y relevante sobre el proyecto alojado en el repositorio de GitHub. Su objetivo es brindar a los visitantes y colaboradores una visión general del proyecto, instrucciones de instalación, documentación, ejemplos de uso y cualquier otra información que pueda ser útil.

El contenido de un archivo README puede variar según el proyecto, pero generalmente incluye los siguientes elementos:

- **Título y descripción**: Un breve resumen del proyecto que lo describe de manera concisa.
- **Requisitos**: Los requisitos previos necesarios para utilizar o contribuir al proyecto, como versiones de software o bibliotecas adicionales.
- **Instalación**: Instrucciones paso a paso sobre cómo instalar y configurar el proyecto.
- **Uso**: Cómo utilizar el proyecto, incluidos ejemplos de código o comandos.
- **Contribución**: Directrices para que otros contribuyan al proyecto, como pautas de estilo de código, estructura de directorios y procesos de solicitud de extracción.
- **Documentación adicional**: Enlaces a documentación adicional, como guías detalladas, tutoriales o ejemplos.
- **Licencia**: Información sobre la licencia del proyecto y los derechos de autor.

**¿Qué es un perfil README?**
<br>
Un perfil README es practicamente una introducción de quien eres, es decir, una mini biografia que se muestra en nuestro perfil de GitHub. Aquí podemos compartir información relveante hacia la comunidad en GitHub.com. GitHub muestra susodicho archivo en la parte superior de nuestra página de perfil. Para obtener más información, consulte "[Administrar el README de tu perfil](https://docs.github.com/es/enterprise-cloud@latest/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme#about-your-profile-readme)".

<br>
📺 Vídeo: [CREA tu Github README Profile paso a paso](https://www.youtube.com/live/1eEnboVooiY?feature=share)

 ![vgglProfileREADME](/images/vgglProfileREADME.jpeg)

</details>


<!-- 
  <<< Author notes: Inicio >>> 
-->

<details id=2>
<summary><h2>Inicio del curso</h2></summary>

</details>

<!-- 
  <<< Author notes: Actividad - Paso 1 >>> 
-->

<details id=3>
<summary><h2>Paso 1: Creando una rama</h2></summary>

</details>

<!-- 
  <<< Author notes: Actividad - Paso 2 >>> 
-->

<details id=4>
<summary><h2>Paso 2: Enviando un archivo/cambio</h2></summary>

</details>

<!-- 
  <<< Author notes: Actividad - Paso 3 >>> 
-->

<details id=5>
<summary><h2>Paso 3: Abrir una solicitud de incorporación de cambios</h2></summary>

</details>

<!-- 
  <<< Author notes: Actividad - Paso 4 >>> 
-->

<details id=6>
<summary><h2>Paso 4: Fusionando/Aceptando los cambios</h2></summary>

</details>

<!-- 
  <<< Author notes: Conclusión >>> 
-->

<details id=7>
<summary><h2>Termino del curso</h2></summary>

</details>

<!--
  <<< Author notes: Footer >>>
-->

---

- [Soporte de GitHub](https://support.github.com/)
- [Comunidad de GitHub](https://github.com/orgs/community/discussions)

