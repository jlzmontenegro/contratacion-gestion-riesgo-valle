# Contratación · Secretaría de Gestión del Riesgo de Desastres · Valle del Cauca

Tablero interactivo de la contratación de la Secretaría de Gestión del Riesgo de Desastres de la Gobernación del Valle del Cauca, desde el 1 de enero de 2024, con una sección dedicada a lo contratado después del sismo del 10 de agosto de 2026.

**Ver el tablero:** https://jlzmontenegro.github.io/contratacion-gestion-riesgo-valle/

## Qué incluye

- Sección del sismo: contratos firmados desde el 10-ago-2026, su relación con el evento, comparación con periodos de igual duración y lo que la Gobernación contrató por el sismo en otras dependencias.
- Gráficos interactivos que se leen por valor contratado, por número de contratos o en porcentaje: categorías de gasto, top 15 de contratistas, estado actual, tipo de contrato, modalidad y año.
- Filtros que se combinan (varios valores por filtro) y gráficos que filtran al hacer clic.
- Tabla con columnas a elección, orden por cualquier columna, enlace a cada contrato en SECOP y exportación a CSV y PDF.

## Datos

- **Contratos:** SECOP Integrado (`rpmr-utcd`) en datos.gov.co, filtrado por el nombre exacto de la entidad. El dataset de contratos de SECOP II (`jbjy-vk9h`) está truncado a 1.000 filas desde septiembre de 2026.
- **Procesos:** SECOP II (`p6dx-8zbt`), para la justificación de la modalidad y el código UNSPSC.
- Se excluyen los contratos en Borrador o Cancelado y se deja una sola fila por contrato.
- La página consulta la API al abrirse y se actualiza sola; si no hay conexión usa `datos.js`.

Las cifras del sismo son un piso: la urgencia manifiesta permite contratar antes de publicar en SECOP.
