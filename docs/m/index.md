# Historial de Lecturas Bíblica

:fontawesome-solid-gear: El propósito de las lecturas mensuales es para poder retarme y entender que planes Dios pudiese tener para mi durante este año y espero que sea también de gran bendición para sus vida.

:simple-hackster: Es la primera vez que utilizo mi conocimientos/destrezas para la obra de Dios. Seré totalmente honesta, se me ha complicado todo. Todo lo escribo en español pero en mi mente lo leo en inglés. Esto significa que tengo un problema de lenguaje. Jajaja 🤣

:fontawesome-solid-gear: En fin, esta página es para que se puedan dar cuenta que no leo todos los días pero me estare esforzando lo más posible para mantener esta plataforma activa y actualizada.

## Desglose de lecturas mensuales
!!! quote "Nota: Si los libros y/o capítulos son repetidos no seran contados como un libro/capítulo nuevo de lectura."


| Mes 2023      | Total de lecturas       | General - Total de lecturas       |
| :-----------: | :------------------------------------:| :------------------------------------:|
| [Enero](ene.md){.md-button}        | <font color=orange>Libros</font>: **4** <font color=red>Capítulos</font>: **4** <font color=lime>Versículos</font>: **50** | <font color=orange>Libros</font>: **4** <font color=red>Capítulos</font>: **4** <font color=lime>Versículos</font>: **50** |
| [Febrero](feb.md){.md-button}       | <font color=orange>Libros</font>: **5** <font color=red>Capítulos</font>: **9** <font color=lime>Versículos</font>: **18** | <font color=orange>Libros</font>: **9** <font color=red>Capítulos</font>: **13** <font color=lime>Versículos</font>: **68** |
| [Marzo](mar.md){.md-button} | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  | <font color=orange>Libros</font>: **9** <font color=red>Capítulos</font>: **13** <font color=lime>Versículos</font>: **68** |
| [Abril](abr.md){.md-button}         | <font color=orange>Libros</font>: **1** <font color=red>Capítulos</font>: **1** <font color=lime>Versículos</font>: **3**  | <font color=orange>Libros</font>: **10** <font color=red>Capítulos</font>: **14** <font color=lime>Versículos</font>: **71**  |
| [Mayo](may.md){.md-button}          | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**   | <font color=orange>Libros</font>: **10** <font color=red>Capítulos</font>: **14** <font color=lime>Versículos</font>: **71**  |
| [Junio](jun.md){.md-button}         | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**   | <font color=orange>Libros</font>: **10** <font color=red>Capítulos</font>: **14** <font color=lime>Versículos</font>: **71**  |
| [Julio](jul.md){.md-button}         | <font color=orange>Libros</font>: **1** <font color=red>Capítulos</font>: **1** <font color=lime>Versículos</font>: **9**    | <font color=orange>Libros</font>: **10** <font color=red>Capítulos</font>: **15** <font color=lime>Versículos</font>: **80**  |
| [Agosto](ago.md){.md-button}        |  | |
| [Septiembre](sep.md){.md-button}    |  | |
| [Octubre](oct.md){.md-button}       |  | |
| [Noviembre](nov.md){.md-button}     |  | |
| [Diciembre](dic.md){.md-button}     |  | |

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "Estatus de Lecturas Mensual",
  "description": "A simple line chart with random data.",
  "mark": {"type": "bar", "tooltip": true},
  "data": {
      "values": [
      {"versiculos": 50, "mes": "Enero"}, {"versiculos": 18, "mes": "Febrero"}, {"versiculos": 0, "mes": "Marzo"},
      {"versiculos": 3, "mes": "Abril"}, {"versiculos": 0, "mes": "Mayo"}, {"versiculos": 0, "mes": "Junio"},
      {"versiculos": 9, "mes": "Julio"}, {"versiculos": 0, "mes": "Agosto"}, {"versiculos": 0, "mes": " Septiembre"}, {"versiculos": 0, "mes": "Octubre"}, {"versiculos": 0, "mes": "Noviembre"}, {"versiculos": 0, "mes": "Diciembre"}
      ]
  },"encoding": {
    "x": {"field": "mes", "type": "nominal", "title": "Meses",
        "sort": ["Enero", "Febrero", "Marzo", "Abril", "Mayo", "Junio", "Julio", "Agosto", "Septiembre", "Octubre", "Noviembre", "Diciembre"]},
    "y": {"field": "versiculos","type": "quantitative", "title": "Versículos"},
    "color": {"field": "mes", "type": "nominal", "title": "Legend", "sort": ["Enero", "Febrero", "Marzo", "Abril", "Mayo", "Junio", "Julio", "Agosto", "Septiembre", "Octubre", "Noviembre", "Diciembre"]}}
}
```
