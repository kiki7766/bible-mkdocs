# Historial de Lecturas Bíblica 2024

:musical_note:

:notes: 

:musical_note:

## Desglose de lecturas mensuales
!!! quote "Nota: Si los libros y/o capítulos son repetidos no seran contados como un libro/capítulo nuevo de lectura."


| Mes 2024      | Total de lecturas       | General - Total de lecturas       |
| :-----------: | :------------------------------------:| :------------------------------------:|
| [Enero](enero.md){.md-button}        | <font color=orange>Libros</font>: **2** <font color=red>Capítulos</font>: **2** <font color=lime>Versículos</font>: **15** | <font color=orange>Libros</font>: **2** <font color=red>Capítulos</font>: **2** <font color=lime>Versículos</font>: **15** |
| [Febrero](febrero.md){.md-button}       | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0** | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0** |
| [Marzo](marzo.md){.md-button} | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0** |
| [Abril](abril.md){.md-button}         | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  |
| [Mayo](mayo.md){.md-button}          | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**   | <font color=orange>Libros</font>: **10** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  |
| [Junio](junio.md){.md-button}         | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**   | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  |
| [Julio](julio.md){.md-button}         | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**    | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  |
| [Agosto](agosto.md){.md-button}        |  <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**   |  <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0** |
| [Septiembre](septiembre.md){.md-button}    |  <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**   | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0** |
| [Octubre](octubre.md){.md-button}       | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  |
| [Noviembre](noviembre.md){.md-button}     |<font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**  | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0** |
| [Diciembre](diciembre.md){.md-button}     | <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0** |  <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0** <font color=lime>Versículos</font>: **0**|
| Total de Lecturas :| <font color=orange>Libros</font>: **0** <font color=red>Capítulos</font>: **0**| <font color=lime>Versículos</font>: **0** |

## Gráfica de Lecturas Mensuales 2024

```vegalite
{
    "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
    "title": "Estatus de Lecturas Mensual 2024",
    "description": "A simple bar chart with random data.",
    "data": {"values": [
            {"versiculos": 15, "mes": "enero"}, {"versiculos": 0, "mes": "febrero"}, {"versiculos": 0, "mes": "marzo"}, {"versiculos": 0, "mes": "abril"}, {"versiculos": 0, "mes": "mayo"}, {"versiculos": 0, "mes": "junio"},{"versiculos": 0, "mes": "julio"}, {"versiculos": 0, "mes": "agosto"}, {"versiculos": 0, "mes": "septiembre"}, {"versiculos": 0, "mes": "octubre"}, {"versiculos": 0, "mes": "noviembre"}, {"versiculos": 0, "mes": "diciembre"}]},    
    "mark": {"type": "bar","cornerRadius":0},
    "transform": [{"calculate": "datum.mes", "as": "url"}],
    "encoding": {
        "x": {"field": "mes", "type": "nominal", "title": "Meses", "sort": ["Enero", "Febrero", "Marzo", "Abril", "Mayo", "Junio", "Julio", "Agosto", "Septiembre", "Octubre", "Noviembre", "Diciembre"]},
        "y": {"field": "versiculos", "type": "quantitative"},
        "color": {"field": "mes", "type": "nominal",  "title": "Legend", "sort": ["Enero", "Febrero", "Marzo", "Abril", "Mayo", "Junio", "Julio", "Agosto", "Septiembre", "Octubre", "Noviembre", "Diciembre"]},
        "tooltip": [{"field": "versiculos", "type": "quantitative"}, {"field": "mes", "type": "nominal"}],
        "href": {"field": "url", "type": "nominal"}
    }
}
```