+++
title = 'Shortcodes'
date = 2023-09-19T10:47:50+02:00 
draft = false
weight = 20
+++

### Descargas
{{<highlight lineNos="false" lineNoStart="0" type="py">}}
    En este apartado podremos adjuntar documento para que cualquier usuario los pueda descargar.
{{</highlight>}}
{{% attachments sort="asc" /%}}


### Color
{{<highlight lineNos="false" lineNoStart="0" type="py">}}
    En este apartado podremos adjuntar como un tipo de etiqueta donde podemos poner lo que queramos.
{{</highlight>}}
{{% badge style="info" %}}New{{% /badge %}}

### Botones
{{<highlight lineNos="false" lineNoStart="0" type="py">}}
    En este apartado podremos adjuntar botones para que el usuario clique y le lleve al sitio web que nosotros hayamos creado.
{{</highlight>}}
{{% button href="https://gohugo.io/" style="blue" %}}Get Hugo{{% /button %}}


### Expand
{{<highlight lineNos="false" lineNoStart="0" type="py">}}
    En este apartado podremos adjuntar un apartado con un texto que se abre y se cierra, para que no ocupe la pantalla.
{{</highlight>}}
{{% expand title="Leer más..." open="true" %}}Expande un nuevo texto{{% /expand %}}


### Iconos
{{<highlight lineNos="false" lineNoStart="0" type="py">}}
    En este apartado podremos adjuntar cualquier tipo de icono a nuestra página.
{{</highlight>}}
Triángulo de advertencia {{% icon icon="exclamation-triangle" %}}
Corazón {{% icon heart %}} 


### Formulas matemáticas
{{<highlight lineNos="false" lineNoStart="0" type="py">}}
    En este apartado podremos adjuntar la formula matemática que nosotros queramos con una serie de variables.
{{</highlight>}}
{{< math align="center" >}}
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
{{< /math >}}

### Diagramas
{{<highlight lineNos="false" lineNoStart="0" type="py">}}
    En este apartado podremos diseñar cualquier serie de diagramas.
{{</highlight>}}
{{< mermaid align="center" zoom="true" >}}
---
title: Example Diagram
---
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{<strong>Decision</strong>}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}

### Avisos
{{<highlight lineNos="false" lineNoStart="0" type="py">}}
    En este apartado podremos adjuntar un aviso en la pantalla y podemos cambiarle el color y poner lo que queramos.
{{</highlight>}}
{{% notice style="warning" title="Para que sirve" icon="skull-crossbones" %}}
Sirve para poner avisos.
{{% /notice %}}


### Pestaña
{{% tab title="c" %}}
```c
printf("Hello World!");
```
{{% /tab %}}

### Pestañas
{{< tabs title="hello." >}}
{{% tab title="py" %}}
```python
print("Hello World!")
```
{{% /tab %}}
{{% tab title="sh" %}}
```bash
echo "Hello World!"
```
{{% /tab %}}
{{% tab title="c" %}}
```c
printf"Hello World!");
```
{{% /tab %}}
{{< /tabs >}}