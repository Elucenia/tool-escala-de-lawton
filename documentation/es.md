<!-- ELUCENIA technical documentation · escala-de-lawton · es · no clinical/professional/rights approval -->

# Escala de Lawton-Brody (AIVD)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escala-de-lawton)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Teléfono

`tel`

- `a` — Usa el teléfono por iniciativa propia (busca y marca números)
- `b` — Marca algunos números conocidos
- `c` — Contesta, pero no marca
- `d` — No usa el teléfono

### Compras

`compras`

- `a` — Hace todas las compras sin ayuda
- `b` — Hace sin ayuda solo compras pequeñas
- `c` — Necesita acompañante para cualquier compra
- `d` — No puede hacer compras

### Preparación de comidas

`comida`

- `a` — Planifica, prepara y sirve comidas adecuadas sin ayuda
- `b` — Prepara las comidas si recibe los ingredientes
- `c` — Calienta y sirve comidas preparadas, pero sin una dieta adecuada
- `d` — Necesita que le preparen y sirvan las comidas

### Tareas domésticas

`casa`

- `a` — Cuida de la casa sin ayuda o con ayuda ocasional para tareas pesadas
- `b` — Hace tareas ligeras (lavar platos, hacer la cama)
- `c` — Hace tareas ligeras, pero no mantiene una limpieza adecuada
- `d` — Necesita ayuda en todas las tareas
- `e` — No participa en ninguna tarea doméstica

### Lavar la ropa

`roupa`

- `a` — Lava toda su ropa personal
- `b` — Lava prendas pequeñas
- `c` — Toda la ropa la lavan otras personas

### Transporte

`transp`

- `a` — Usa transporte público o conduce sin ayuda
- `b` — Usa taxi o una aplicación de transporte solo, pero no transporte público
- `c` — Usa transporte público si va acompañado
- `d` — Solo viaja en taxi o coche con ayuda de otra persona
- `e` — No sale de casa

### Medicamentos

`remedio`

- `a` — Toma los medicamentos sin ayuda en la dosis y el horario correctos
- `b` — Toma los medicamentos si alguien prepara antes las dosis
- `c` — No puede tomar los medicamentos sin ayuda

### Finanzas

`dinheiro`

- `a` — Gestiona las finanzas solo
- `b` — Hace compras cotidianas, pero necesita ayuda con operaciones bancarias y compras importantes
- `c` — No puede manejar dinero

## Edición del método

Lawton–Brody 1969: adaptación local 8 dominios 0–1, total 0–8 para ambos sexos; no la versión original por sexo

## Fórmula documentada

Cada actividad puntúa 1 (independiente) o 0 (dependiente) según el nivel:

Teléfono: 1 en los tres primeros.

Compras y comidas: 1 solo en el primero.

Casa: 1 en todos salvo “no participa”.

Ropa: 1 en los dos primeros.

Transporte: 1 en los tres primeros.

Medicación: 1 solo en el primero.

Finanzas: 1 en los dos primeros.

Total 0 (dependiente) a 8 (independiente).

## Límites y población

Esta versión de Lawton evalúa ocho actividades instrumentales y utiliza un total de 0 a 8 para todos los géneros, conforme a la orientación HIGN de 2019; no aplica la antigua puntuación masculina de cinco ítems. La orientación consultada no recomienda el instrumento para personas mayores institucionalizadas. Las respuestas de la persona o de un informante describen la función percibida y no demuestran la ejecución real de cada tarea; pueden sobreestimar o subestimar la capacidad y no detectar pequeños cambios. Registre quién respondió y el contexto de la evaluación.

## Referencias

- [Lawton MP, Brody EM. Assessment of older people: self-maintaining and instrumental activities of daily living. Gerontologist, 1969.](https://doi.org/10.1093/geront/9.3_Part_1.179)

- [HIGN,TryThis23,revised2019](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_23.pdf)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
