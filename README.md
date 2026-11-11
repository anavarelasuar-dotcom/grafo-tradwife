# Grafo de coocurrencias del corpus tradwife

Material complementario del capítulo «La tendencia tradwife en las redes sociales o cómo el neoliberalismo hace emerger los roles tradicionales de las mujeres», de [autoría], en *Discurso, léxico y género: representaciones de la mujer y el feminismo en España (siglos XX–XXI)* (Dykinson, [año]).

**Grafo interactivo:** https://anavarelasuar-dotcom.github.io/grafo-tradwife/

Vistas directas por subcorpus:

- Global: https://anavarelasuar-dotcom.github.io/grafo-tradwife/#global
- España: https://anavarelasuar-dotcom.github.io/grafo-tradwife/#espana
- Latinoamérica: https://anavarelasuar-dotcom.github.io/grafo-tradwife/#latinoamerica
- España sin RoRo: https://anavarelasuar-dotcom.github.io/grafo-tradwife/#espana-sin-roro
- Vídeos explícitos: https://anavarelasuar-dotcom.github.io/grafo-tradwife/#explicito
- Vídeos implícitos: https://anavarelasuar-dotcom.github.io/grafo-tradwife/#implicito

## Corpus

51 vídeos de TikTok de 26 creadoras (29 de España y 22 de Latinoamérica), publicados entre octubre de 2021 y febrero de 2026, con unas 16.000 palabras de transcripción, segmentadas en 1.002 oraciones. El corpus procede del TFG de Candela Fernández Fariñas (Universidade de Vigo). Las transcripciones no se incluyen en este repositorio.

## Método

- Unidad: la oración. Formas sin lematizar.
- Se conservan sustantivos, nombres propios, adjetivos y verbos (sin auxiliares).
- Nueve nodos de categoría sustituyen a las palabras que agrupan: HOMBRE_PAREJA, CREADORA, ALIMENTO, TAREA, TIEMPO, HIJOS, PROVISIÓN, CUERPO y AUDIENCIA. La asignación de formas y de referentes (clíticos y palabras ambiguas) se revisó a mano.
- Dos palabras se conectan si están a una o dos posiciones dentro de la oración: peso 2 si son contiguas y 1 si hay una palabra entre medias.
- Métricas: grado, grado ponderado, intermediación y comunidades de Louvain.

## Archivos

| Archivo | Contenido |
| --- | --- |
| `index.html` | Visor interactivo. Funciona en el navegador sin instalar nada, también sin conexión. |
| `tradwife_*.gexf` | Los seis grafos en formato GEXF, para Gephi o Gephi Lite. |
| `Resultados_grafo_tradwife.xlsx` | Métricas, matrices entre nodos, vecinos y adjetivos de cada nodo, nodos y aristas. |

## Herramientas

Python, spaCy 3.8.18 (es_core_news_md 3.8.0), NetworkX 3.7, graphology 0.25.4, ForceAtlas2 0.10.1 y sigma.js 2.4.0.

## Cómo citar

[Completar con la referencia y el DOI de Zenodo.]

## Licencia

[Completar, por ejemplo CC BY 4.0.]
