<!-- ELUCENIA technical documentation · indice-de-tobin · es · no clinical/professional/rights approval -->

# Índice de Tobin (respiración rápida y superficial)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/indice-de-tobin)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Frecuencia respiratoria espontánea

`fr`

respiraciones/min · intervalo: 1–80

### Volumen corriente espontáneo

`vt`

mL · intervalo: 50–1500

## Edición del método

RSBI/Yang–Tobin 1991: f/VT, VT en litros; no confundir con mL

## Fórmula documentada

f/VT = frecuencia respiratoria (resp/min) ÷ volumen corriente (litros).

## Límites y población

El RSBI se estudió como predictor del resultado de intentos de destete ventilatorio. El resultado depende de las condiciones y la técnica de medición y no confirma por sí solo la capacidad de proteger la vía aérea ni la seguridad de la extubación. Un índice favorable no equivale a éxito garantizado.

## Referencias

- [Yang KL, Tobin MJ. A prospective study of indexes predicting the outcome of trials of weaning from mechanical ventilation. N Engl J Med, 1991.](https://doi.org/10.1056/NEJM199105233242101)

- [Boles JM et al. Weaning from mechanical ventilation. Eur Respir J, 2007.](https://doi.org/10.1183/09031936.00010206)

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
