# Tarjetas de vocabulario · GEDparaHispanos

Tarjetas interactivas para estudiar el vocabulario de las cuatro materias del GED. El estudiante ve un término, da la vuelta a la tarjeta para comprobar la definición y la coloca en la pila **Lo sé** o **No lo sé**. Al terminar puede repasar solo las tarjetas que no sabía.

Publicado en: <https://zhemaria.github.io/vocabulario/>

## Archivos

| Archivo | Contenido |
|---|---|
| `index.html` | El programa, uno solo para todas las materias. No hace falta tocarlo para añadir términos. |
| `matematicas.csv` | Vocabulario de Matemáticas |
| `lenguaje.csv` | Vocabulario de Artes del lenguaje |
| `ciencias.csv` | Vocabulario de Ciencias |
| `sociales.csv` | Vocabulario de Estudios sociales |

## Cómo añadir términos

1. Abra el `.csv` de la materia en Excel o en Google Sheets.
2. Cada fila es una tarjeta, con tres columnas:
   - **lista**: el tema al que pertenece el término, por ejemplo *2 · Datos, gráficas y cálculos científicos*.
   - **termino**: la palabra.
   - **definicion**: lo que significa.
3. Guarde el archivo como **CSV UTF-8** para conservar las tildes y la ñ.
4. Suba el archivo a este repositorio y reemplace el anterior.

Las filas que tienen el mismo nombre en la columna *lista* forman una lista. Si una materia tiene hasta tres listas, el estudiante las elige con botones; si tiene más, con un menú desplegable.

En las fórmulas, use símbolos comunes en lugar de notación LaTeX: × ÷ − ≤ ≥ ≠ √ π ° ² ³ ½ ¾.

## Direcciones para enlazar

| Para abrir… | Dirección |
|---|---|
| El menú de materias | `https://zhemaria.github.io/vocabulario/` |
| Toda una materia | `https://zhemaria.github.io/vocabulario/?materia=ciencias` |
| Una sola lista | `https://zhemaria.github.io/vocabulario/?materia=ciencias&lista=2` |

- Los valores de `materia` son: `matematicas`, `lenguaje`, `ciencias` y `sociales`.
- `lista` acepta el número del tema (`lista=2`), el nombre completo o solo su comienzo.
- Para los enlaces desde Google Sites, use `target="_blank"`.

## Accesibilidad (DUA)

- Se puede usar con teclado: **Espacio** da la vuelta a la tarjeta, **→** equivale a *Lo sé* y **←** a *No lo sé*.
- Tiene lectura en voz alta.
- Se puede elegir mostrar primero la definición.
- Los colores cumplen el contraste AA de WCAG.
- Todos los avisos aparecen dentro de la página.

## Contenido actual

| Materia | Listas | Términos |
|---|---|---|
| Matemáticas | 8 | 102 |
| Artes del lenguaje | 6 | 75 |
| Ciencias | 2 | 44 |
| Estudios sociales | 5 | 98 |

## Nota

El programa lee los `.csv` desde Internet. Por eso funciona en GitHub Pages, pero no si se abre `index.html` con doble clic en la computadora.

---

José M. Fernández, ABE/ASE Math Master Teacher, Harry S. Truman College — City Colleges of Chicago
Licencia [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)
