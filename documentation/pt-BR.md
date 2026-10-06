<!-- ELUCENIA technical documentation · escala-de-lawton · pt-BR · no clinical/professional/rights approval -->

# Escala de Lawton-Brody (AIVD)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escala-de-lawton)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Telefone

`tel`

- `a` — Usa por iniciativa própria (procura e disca números)
- `b` — Disca alguns números conhecidos
- `c` — Atende, mas não disca
- `d` — Não usa o telefone

### Compras

`compras`

- `a` — Faz todas as compras sozinho
- `b` — Faz sozinho só pequenas compras
- `c` — Precisa de acompanhante em qualquer compra
- `d` — Incapaz de fazer compras

### Preparo de refeições

`comida`

- `a` — Planeja, prepara e serve refeições adequadas sozinho
- `b` — Prepara se receber os ingredientes
- `c` — Aquece e serve refeições prontas, mas sem dieta adequada
- `d` — Precisa que preparem e sirvam as refeições

### Tarefas domésticas

`casa`

- `a` — Cuida da casa sozinho ou com ajuda ocasional em tarefas pesadas
- `b` — Faz tarefas leves (lavar louça, arrumar a cama)
- `c` — Faz tarefas leves, mas sem manter a limpeza adequada
- `d` — Precisa de ajuda em todas as tarefas
- `e` — Não participa de nenhuma tarefa doméstica

### Lavar roupa

`roupa`

- `a` — Lava toda a roupa pessoal
- `b` — Lava pequenas peças
- `c` — Toda a roupa é lavada por outros

### Transporte

`transp`

- `a` — Usa transporte público ou dirige sozinho
- `b` — Pega táxi ou aplicativo sozinho, mas não usa transporte público
- `c` — Usa transporte público quando acompanhado
- `d` — Só anda de táxi ou carro com ajuda de outra pessoa
- `e` — Não sai de casa

### Medicações

`remedio`

- `a` — Toma os remédios na dose e hora certas sozinho
- `b` — Toma se alguém separar as doses antes
- `c` — Incapaz de tomar os remédios sozinho

### Finanças

`dinheiro`

- `a` — Cuida das finanças sozinho
- `b` — Faz compras do dia a dia, mas precisa de ajuda com banco e grandes compras
- `c` — Incapaz de lidar com dinheiro

## Edição do método

Lawton Brody 1969:adaptação local 8 domínios 0–1, total 0–8 para ambossexos; não versão sexoespecífica original

## Fórmula documentada

Cada atividade recebe 1 ponto (independente) ou 0 (dependente), conforme o nível descrito:

Telefone: 1 nos três primeiros níveis.

Compras e preparo de refeições: 1 só no primeiro nível.

Tarefas domésticas: 1 em todos os níveis, exceto "não participa".

Lavar roupa: 1 nos dois primeiros níveis.

Transporte: 1 nos três primeiros níveis.

Medicações: 1 só no primeiro nível.

Finanças: 1 nos dois primeiros níveis.

Total de 0 (dependente) a 8 (independente).

## Limites e população

Esta versão de Lawton avalia oito atividades instrumentais e usa total de 0 a 8 para todos os gêneros, conforme a orientação HIGN de 2019; não aplica a antiga pontuação masculina de cinco itens. A orientação consultada não recomenda o instrumento para idosos institucionalizados. As respostas da pessoa ou de um informante descrevem função percebida e não demonstram execução real de cada tarefa; podem superestimar ou subestimar capacidade e não captar pequenas mudanças. Registre quem respondeu e o contexto da avaliação.

## Referências

- [Lawton MP, Brody EM. Assessment of older people: self-maintaining and instrumental activities of daily living. Gerontologist, 1969.](https://doi.org/10.1093/geront/9.3_Part_1.179)

- [HIGN,TryThis23,revised2019](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_23.pdf)

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

Independente nas atividades instrumentais


### 2

Dependência em 3 atividades: compras, medicações, finanças


### 3

Dependência em 6 atividades: compras, preparo de refeições, tarefas domésticas, lavar roupa, transporte, medicações

