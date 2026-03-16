---
layout: home
title: Blog Equipo 18
---

Este blog ha sido creado como parte de la práctica de **HMIS 2026**, con el objetivo de aprender a trabajar de forma colaborativa utilizando **GitHub Flow**, **Jekyll** y herramientas modernas de desarrollo web.

## Sobre el proyecto 💻

Somos el **Equipo 18** y estamos desarrollando un blog estático para documentar nuestro trabajo en la asignatura.  
Durante esta práctica iremos publicando entradas sobre el progreso del proyecto, configuración del entorno, uso de Git y despliegue del sitio.

## Últimas entradas 📝

{% raw %}{% for post in site.posts limit:5 %}{% endraw %}
### [{% raw %}{{ post.title }}{% endraw %}]({% raw %}{{ post.url | relative_url }}{% endraw %})
**Fecha:** {% raw %}{{ post.date | date: "%d/%m/%Y" }}{% endraw %}  
**Autor:** {% raw %}{{ post.author }}{% endraw %}

{% raw %}{{ post.excerpt }}{% endraw %}
{% raw %}{% endfor %}{% endraw %}

## Miembros del equipo 👥

- [Página del equipo]({{ "/equipo/" | relative_url }})
- [Perfil de Diogo]({{ "/diogo/" | relative_url }})
- [Perfil de Julián]({{ "/julian/" | relative_url }})

## Contacto 📩

- [Ir al formulario de contacto]({{ "/contacto/" | relative_url }})

## Herramientas utilizadas 🛠️

- Git
- GitHub
- GitHub Flow
- Jekyll
- Visual Studio Code