# Historial de Lecturas Bíblica

:fontawesome-solid-gear: El propósito de las lecturas mensuales es para poder retarme y entender que planes Dios pudiese tener para mi durante este año y espero que sea también de gran bendición para sus vida.

:simple-hackster: Es la primera vez que utilizo mi conocimientos/destrezas para la obra de Dios. Seré totalmente honesta, se me ha complicado todo. Todo lo escribo en español pero en mi mente lo leo en inglés. Esto significa que tengo un problema de lenguaje. Jajaja 🤣

:fontawesome-solid-gear: En fin, esta página es para que se puedan dar cuenta que no leo todos los días pero me estare esforzando lo más posible para mantener esta plataforma activa y actualizada.

## Desglose de lecturas mensuales
!!! quote "Nota: Si los libros y/o capítulos son repetidos no seran contados como un libro/capítulo nuevo de lectura."


| Mes 2023      | Total de lecturas       | General - Total de lecturas       |
| :-----------: | :------------------------------------:| :------------------------------------:|
| [Enero](enero.md){.md-button}        | <font color=orange>Libros</font>: **4** <font color=red>Capítulos</font>: **4** <font color=lime>Versículos</font>: **50** | <font color=orange>Libros</font>: **4** <font color=red>Capítulos</font>: **4** <font color=lime>Versículos</font>: **50** |
| [Febrero](febrero.md){.md-button}       | <font color=orange>Libros</font>: **5** <font color=red>Capítulos</font>: **9** <font color=lime>Versículos</font>: **18** | <font color=orange>Libros</font>: **9** <font color=red>Capítulos</font>: **13** <font color=lime>Versículos</font>: **68** |
| [Marzo](marzo.md){.md-button} | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  | <font color=orange>Libros</font>: **9** <font color=red>Capítulos</font>: **13** <font color=lime>Versículos</font>: **68** |
| [Abril](abril.md){.md-button}         | <font color=orange>Libros</font>: **1** <font color=red>Capítulos</font>: **1** <font color=lime>Versículos</font>: **3**  | <font color=orange>Libros</font>: **10** <font color=red>Capítulos</font>: **14** <font color=lime>Versículos</font>: **71**  |
| [Mayo](mayo.md){.md-button}          | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**   | <font color=orange>Libros</font>: **10** <font color=red>Capítulos</font>: **14** <font color=lime>Versículos</font>: **71**  |
| [Junio](junio.md){.md-button}         | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**   | <font color=orange>Libros</font>: **10** <font color=red>Capítulos</font>: **14** <font color=lime>Versículos</font>: **71**  |
| [Julio](julio.md){.md-button}         | <font color=orange>Libros</font>: **1** <font color=red>Capítulos</font>: **1** <font color=lime>Versículos</font>: **9**    | <font color=orange>Libros</font>: **10** <font color=red>Capítulos</font>: **15** <font color=lime>Versículos</font>: **80**  |
| [Agosto](agosto.md){.md-button}        |  | |
| [Septiembre](septiembre.md){.md-button}    |  | |
| [Octubre](octubre.md){.md-button}       |  | |
| [Noviembre](noviembre.md){.md-button}     |  | |
| [Diciembre](diciembre.md){.md-button}     |  | |

## Gráfica de Lecturas Mensuales 2023

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "Estatus de Lecturas Mensual",
  "description": "A simple line chart with random data.",
  "data": {"values": [
            {"versiculos": 50, "mes": "enero"}, {"versiculos": 18, "mes": "febrero"}, {"versiculos": 0, "mes": "marzo"}, {"versiculos": 3, "mes": "abril"}, {"versiculos": 0, "mes": "mayo"}, {"versiculos": 0, "mes": "junio"},{"versiculos": 9, "mes": "julio"}, {"versiculos": 0, "mes": "agosto"}, {"versiculos": 0, "mes": "septiembre"}, {"versiculos": 0, "mes": "octubre"}, {"versiculos": 0, "mes": "noviembre"}, {"versiculos": 0, "mes": "diciembre"}]},
    "mark": {"type": "bar"},
    "transform": [{
    "calculate": "datum.mes", "as": "url"}],
    "encoding": {
        "x": {"field": "mes", "type": "nominal", "title": "Meses", "sort": ["enero", "febrero", "marzo", "abril", "mayo", "junio", "julio", "agosto", "septiembre", "octubre", "noviembre", "diciembre"]},
        "y": {"field": "versiculos", "type": "quantitative"},
        "color": {"field": "mes", "type": "nominal",  "title": "Legend", "sort": ["enero", "febrero", "marzo", "abril", "mayo",  "junio", "julio", "agosto", "septiembre", "octubre", "noviembre", "diciembre"]},
        "tooltip": {"field": "mes", "type": "nominal"},
        "href": {"field": "url", "type": "nominal"}
    }
}
```