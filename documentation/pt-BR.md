<!-- ELUCENIA technical documentation · indice-de-tobin · pt-BR · no clinical/professional/rights approval -->

# Índice de Tobin (respiração rápida e superficial)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/indice-de-tobin)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Frequência respiratória espontânea

`fr`

irpm · intervalo: 1–80

### Volume corrente espontâneo

`vt`

mL · intervalo: 50–1500

## Edição do método

RSBI/Yang Tobin 1991:f/VT, VTlitros; sem confusão VTm L

## Fórmula documentada

f/VT = frequência respiratória (irpm) ÷ volume corrente (em litros).

## Limites e população

O RSBI foi estudado como preditor do resultado de tentativas de desmame ventilatório. O resultado depende de condições e técnica da medição e não confirma sozinho capacidade de proteção de via aérea ou segurança de extubação. Um índice favorável não equivale a sucesso garantido.

## Referências

- [Yang KL, Tobin MJ. A prospective study of indexes predicting the outcome of trials of weaning from mechanical ventilation. N Engl J Med, 1991.](https://doi.org/10.1056/NEJM199105233242101)

- [Boles JM et al. Weaning from mechanical ventilation. Eur Respir J, 2007.](https://doi.org/10.1183/09031936.00010206)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Abaixo de 105: favorece o sucesso do desmame


### 2

105 ou mais: prediz falha do desmame


### 3

105 ou mais: prediz falha do desmame

