# Lenguaje de marcas · HTML, CSS y XML

Cuaderno de ejercicios básicos: una página web semántica, una hoja de estilos adaptable
y un catálogo XML con los ejercicios.

## Estructura

```text
index.html             Página principal
css/estilos.css         Presentación y adaptación a móviles
datos/ejercicios.xml    Catálogo de ejercicios
```

## Cómo verlo

Descarga el repositorio y abre `index.html` en tu navegador. No requiere instalar dependencias.
También puedes iniciar un servidor local con Python 3:

```bash
python -m http.server 8000
```

Abre http://localhost:8000. El enlace al XML permite consultar los datos; la página
HTML es estática y no genera su contenido a partir del XML.

## Conceptos practicados

- HTML: jerarquía de encabezados, secciones, listas, navegación y enlaces.
- CSS: variables, cuadrícula, media queries, foco visible y movimiento reducido.
- XML: declaración, raíz única, atributos y elementos anidados.

## Comprobación manual

1. Abre la página y prueba los enlaces de navegación.
2. Reduce el ancho de la ventana: las tres tarjetas deben pasar a una columna.
3. Usa Tab para recorrer los enlaces y comprobar el foco visible.
4. Abre `datos/ejercicios.xml` y comprueba los tres ejercicios.

Los ejercicios de programación están en [Java](https://github.com/Matias1443/Java).

## Historial

```bash
git log --graph --oneline --all
```
