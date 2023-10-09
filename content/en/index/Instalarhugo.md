+++
title = 'Instalar Hugo'
date = 2023-09-19T10:47:50+02:00 
draft = false
weight = 20
+++

# 1. ¿Que es hugo?

Hugo is a static site generator. It's one of the most popular and fastest ones available today. It's a tool that allows you to build websites in a straightforward way, leveraging the latest technologies for development.

# 2. Link de Hugo

{{<highlight lineNos="false" lineNoStart="1" type="py">}}
    https://themes.gohugo.io/
{{</highlight>}}

# 3. Instalación de Hugo

We install Hugo from the terminal:  
{{<highlight lineNos="true" lineNoStart="1" type="py">}}
 sudo snap install hugo
{{</highlight>}}


Create a folder called 'hugo' and navigate into it:
{{<highlight lineNos="true" lineNoStart="2" type="py">}}
 mkdir hugo
 cd hugo
{{</highlight>}}


Choose the theme for your Hugo page at 'hugo themes':
{{% button href="https://themes.gohugo.io/" style="blue" %}}Hugo Themes{{% /button %}}


From the terminal inside the 'hugo' folder, create a new project and navigate to the project's 'themes' folder:
{{<highlight lineNos="true" lineNoStart="4" type="py">}}
 hugo new site "nombre_proyecto"
 cd "nombre_proyecto"
 cd themes
{{</highlight>}}


Clone the theme you've chosen using git clone, in my case 'Relearn':
{{<highlight lineNos="true" lineNoStart="7" type="py">}}
 git clone https://github.com/McShelby/hugo-theme-relearn.git
{{</highlight>}}


Exit the 'themes' folder and start the Hugo server:
{{<highlight lineNos="true" lineNoStart="8" type="py">}}
 cd ..
 hugo server 
{{</highlight>}}