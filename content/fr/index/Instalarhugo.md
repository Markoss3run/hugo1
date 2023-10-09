+++
title = 'Instalar Hugo'
date = 2023-09-19T10:47:50+02:00 
draft = false
weight = 20
+++

# 1. Qu'est-ce que Hugo ?

Hugo est un générateur de sites statiques. Il est l'un des plus populaires et les plus rapides que l'on puisse trouver actuellement. C'est un outil qui permet de construire des sites web de manière simple en utilisant les technologies les plus modernes pour le développement.

# 2. Lien vers Hugo

{{<highlight lineNos="false" lineNoStart="1" type="py">}}
    https://themes.gohugo.io/
{{</highlight>}}

# 3. Installation de Hugo

Nous installons Hugo depuis le terminal :
{{<highlight lineNos="true" lineNoStart="1" type="py">}}
 sudo snap install hugo
{{</highlight>}}


Nous créons un dossier appelé "hugo" et y accédons :
{{<highlight lineNos="true" lineNoStart="2" type="py">}}
 mkdir hugo
 cd hugo
{{</highlight>}}


Nous choisissons le thème de la page sur Hugo Themes :
{{% button href="https://themes.gohugo.io/" style="blue" %}}Hugo Themes{{% /button %}}


Depuis le terminal du dossier "hugo", nous créons un nouveau projet et accédons au dossier "themes" du projet :
{{<highlight lineNos="true" lineNoStart="4" type="py">}}
 hugo new site "nombre_proyecto"
 cd "nombre_proyecto"
 cd themes
{{</highlight>}}


Nous clonons le thème que nous avons choisi en utilisant "git clone", dans mon cas "Relearn" :
{{<highlight lineNos="true" lineNoStart="7" type="py">}}
 git clone https://github.com/McShelby/hugo-theme-relearn.git
{{</highlight>}}


Nous quittons le dossier "themes" et lançons le serveur Hugo :
{{<highlight lineNos="true" lineNoStart="8" type="py">}}
 cd ..
 hugo server 
{{</highlight>}}