# Bienvenid@s a mi blog :fontawesome-solid-blog:
## Lectura bíblica mensual :material-robot-happy:

En esta página encontrarás un diario de versículos leídos de la Santa Biblia.    

## Biblia Utilizada :fontawesome-solid-book-bible:

* `Reina-Valera (RVR 1960)` - Se utiliza esta versión de Biblia ya que es la más utilizada en lecturas bíblicas. 
* `Editorial Biblia - Biblia de Estudio (RVR 1960)` - Se utiliza la Biblia de estudio para obtener referencias y comentarios para entender la lectura o contexto del versículo bíblico.


## Enfoque de proyecto :material-folder-eye:

- El enfoque principal es instruir o informar líderes de utilizar formas para motivar a la lectura bíblica ya que muchas veces la lectura bíblica es compleja y se debe consultar con personas de conocimiento bíblico o utilizar referencias de acuerdo a conforme de las escritura y no a conveniencia del mismo/a.

## Updates/Actualizaciones :material-update:

- Durante cada día, semana, o mes, se estará actualizando con el versículo diario, semanal, o mensual correspondiente al mes.

## Licencias Utilizadas :material-license:
- MIT License :fontawesome-solid-scale-balanced:

## Comentarios o sugerencias :octicons-comment-discussion-24:

- Puedes escribirme a [peggy.gonzalez@upr.edu](mailto:peggy.gonzalez@upr.edu){target=_blank}
- También puedes escribirme a [hakunawonderland@gmail.com](mailto:hakunawonderland@gmail.com){target=_blank}

### Contribuciones :fontawesome-solid-people-group:

- Acepto a colaboradores o contribuidores que deseen ayudarme a expandir este proyecto para realizar o cumplir con la meta de leer lecturas bíblicas mensuales o semanales durante este año 2023. 

## [Gráfica de Lecturas Mensuales 2023](m-2023/index.md)

```vegalite
{
    "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
    "title": "Estatus de Lecturas Mensual",
    "description": "A simple bar chart with random data.",
    "data": {"values": [
            {"versiculos": 51, "mes": "Enero"}, {"versiculos": 18, "mes": "Febrero"}, {"versiculos": 0, "mes": "Marzo"}, {"versiculos": 3, "mes": "Abril"}, {"versiculos": 0, "mes": "Mayo"}, {"versiculos": 0, "mes": "Junio"},{"versiculos": 9, "mes": "Julio"}, {"versiculos": 0, "mes": "Agosto"}, {"versiculos": 0, "mes": "Septiembre"}, {"versiculos": 0, "mes": "Octubre"}, {"versiculos": 0, "mes": "Noviembre"}, {"versiculos": 0, "mes": "Diciembre"}]},     
    "mark": {"type": "bar"},
    "transform": [{"calculate": "'m-2023/' + datum.mes", "as": "url"}],
    "encoding": {
        "x": {"field": "mes", "type": "nominal", "title": "Meses", "sort": ["Enero", "Febrero", "Marzo", "Abril", "Mayo", "Junio", "Julio", "Agosto", "Septiembre", "Octubre", "Noviembre", "Diciembre"]},
        "y": {"field": "versiculos", "type": "quantitative"},
        "color": {"field": "mes", "type": "nominal",  "title": "Legend", "sort": ["Enero", "Febrero", "Marzo", "Abril", "Mayo", "Junio", "Julio", "Agosto", "Septiembre", "Octubre", "Noviembre", "Diciembre"]},
        "tooltip": [{"field": "versiculos", "type": "quantitative"}, {"field": "mes", "type": "nominal"}],
        "href": {"field": "url", "type": "nominal"}
    }
}
```
    