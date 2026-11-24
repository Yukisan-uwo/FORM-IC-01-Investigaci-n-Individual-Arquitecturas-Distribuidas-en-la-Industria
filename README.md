# FORM-IC-01 - Arquitecturas Distribuidas en la Industria

**Estudiante:** Mario Zambrano  
**Asignatura:** Aplicaciones Distribuidas  
**Nivel:** Séptimo A  

## Descripción

Investigación sobre la arquitectura orientada a eventos (EDA) en DoorDash, específicamente en su plataforma Iguazu, que utiliza Apache Kafka y Apache Flink. Se analizan sus beneficios, desafíos y posible aplicación al SGRA.

## Archivos

- `main.tex`: archivo principal del informe.
- `referencias.bib`: referencias bibliográficas.
- `secciones/`: contenido del documento.
- `evidencias/`: capturas de la fuente consultada.
- `main.pdf`: informe compilado.
- `BITACORA.md`: registro de actividades.

## Compilación

Se utilizó pdfLaTeX y Biber para las referencias en formato IEEE.

Se requiere MiKTeX o TeX Live con los paquetes babel (español), newtx, geometry, microtype, setspace, graphicx, booktabs, float, tabularx, titlesec, csquotes, biblatex, biblatex-ieee e hyperref.

Desde la raíz del repositorio ejecutar:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El documento generado se encuentra en [main.pdf](main.pdf).

## Fuente principal

https://careersatdoordash.com/blog/building-scalable-real-time-event-processing-with-kafka-and-flink/
