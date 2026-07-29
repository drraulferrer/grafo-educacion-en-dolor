# Grafo de conceptos · Educación en Dolor

**https://drraulferrer.github.io/grafo-educacion-en-dolor/**

Mapa estructural navegable de la base de conocimiento de
[educacionendolor.com](https://educacionendolor.com): un nodo por concepto
escrito, una arista por relación declarada entre conceptos.

## Qué contiene

Solo la **estructura**: identificador, título, dominio, módulo, etiquetas,
estado editorial y las relaciones entre conceptos (`requiere`, `modula`,
`contrasta_con`, `se_confunde_con`…).

## Qué NO contiene

El texto redactado de los conceptos —definiciones, resúmenes y explicaciones—
vive en el repositorio privado y no se publica hasta pasar revisión experta.

> Corpus en construcción y sin revisión externa. Este mapa es material de
> trabajo: **no es material de referencia clínica ni docente**.

## Cómo se actualiza

Nadie lo actualiza a mano. Cada cambio en la base de conocimiento privada
dispara una acción que recompila `index.html` y lo empuja aquí; GitHub Pages
lo sirve en minutos. El fichero es autocontenido: un solo HTML, sin CDN, sin
dependencias, sin analítica.

Generado por `build/grafo.py --publico` desde
`drraulferrer/educacion-en-dolor` (privado).

Contenido bajo CC BY-NC-SA 4.0.
