# Escritoras mexicanas en Wikidata

¿Dónde nacieron las escritoras mexicanas registradas en Wikidata?

**Visualización:** [ver en Tableau Public](PEGA_AQUI_TU_ENLACE)

## Resultados

- 935 escritoras después de depurar a un registro por persona.
- 757 tienen un estado de nacimiento identificado; 324 de ellas (42.8 %) nacieron en Ciudad de México.
- 115 no tienen un estado identificable y 63 nacieron fuera de México.
- 210 no tienen un artículo en español enlazado en Wikidata.

## Archivos

| Archivo | Contenido |
|---|---|
| `consulta.sparql` | Consulta usada en Wikidata Query Service |
| `datos_crudos_wikidata.csv` | Resultado original (1 de noviembre de 2026) |
| `limpieza.py` | Script de depuración y asignación de estados |
| `escritoras_mexicanas_wikidata.csv` | Datos finales usados en Tableau |

## Metodología

La consulta incluye mujeres con ciudadanía mexicana y ocupación de escritora, poeta, novelista, ensayista, dramaturga, cuentista o autora infantil.

La columna de estado de la consulta salió vacía, así que el estado se asignó a partir del lugar de nacimiento, con apoyo de IA y sin verificar cada caso contra fuentes externas. Puede haber errores; las correcciones son bienvenidas.

## Limitaciones

Los datos muestran quién está registrada en Wikidata, no a todas las escritoras que existen, ni explican por qué se concentran en la capital.

Autora: Mónica Villaseñor Sanromán
