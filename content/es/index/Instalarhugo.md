+++
title = 'Instalar Hugo'
date = 2023-09-19T10:47:50+02:00 
draft = false
weight = 20
+++

# 1. ¿Que es hugo?

Hugo es un generador de sitios estáticos. Uno de los más populares y el más rápido que podemos encontrar en la actualidad. Es una herramienta que permite construir sitios web de una manera sencilla, apoyándonos en las tecnologías más modernas para el desarrollo.

# 2. Link de Hugo

{{<highlight lineNos="false" lineNoStart="1" type="py">}}
    https://themes.gohugo.io/
{{</highlight>}}

# 3. Instalación de Hugo

Instalamos hugo desde terminal:
{{<highlight lineNos="true" lineNoStart="1" type="py">}}
 sudo snap install hugo
{{</highlight>}}


Creamos una carpeta llamada hugo y entramos en ella:
{{<highlight lineNos="true" lineNoStart="2" type="py">}}
 mkdir hugo
 cd hugo
{{</highlight>}}


Elegimos el tema de la página en hugo themes: 
{{% button href="https://themes.gohugo.io/" style="blue" %}}Hugo Themes{{% /button %}}


Desde la terminal de la carpeta hugo, creamos un nuevo proyecto y nos colocamos en la carpeta themes del proyecto: 
{{<highlight lineNos="true" lineNoStart="4" type="py">}}
 hugo new site "nombre_proyecto"
 cd "nombre_proyecto"
 cd themes
{{</highlight>}}


Clonamos con el git clone el tema que hemos elegido, en mi caso Relearn:
{{<highlight lineNos="true" lineNoStart="7" type="py">}}
 git clone https://github.com/McShelby/hugo-theme-relearn.git
{{</highlight>}}


Salimos de la carpeta de themes e iniciamos el servidor hugo: 
{{<highlight lineNos="true" lineNoStart="8" type="py">}}
 cd ..
 hugo server 
{{</highlight>}}