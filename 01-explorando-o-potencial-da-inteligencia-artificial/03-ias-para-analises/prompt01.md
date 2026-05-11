# 01 - Análises de Documentos

## 📝 Resumo da Aula

Nesta aula, o foco é usar IA como apoio para análise de dados e leitura de documentos longos. O conteúdo mostra, na prática, como ChatGPT e Google Gemini se comportam ao analisar uma planilha CSV e ao resumir textos extensos.

* **Análise de planilhas:** a IA consegue identificar colunas, contar linhas e interpretar tendências em um arquivo financeiro.
* **Cálculos numéricos:** o ChatGPT executa contas com mais confiabilidade quando usa código por trás; o Gemini pode acertar a estrutura, mas errar o valor final se não validar o cálculo.
* **Leitura de PDFs e documentos longos:** as duas ferramentas conseguem resumir materiais grandes e localizar trechos específicos rapidamente.
* **Conclusão principal:** IA ajuda muito na leitura e na interpretação, mas qualquer resultado numérico precisa ser conferido manualmente.

---

## 🔹 Prompt 1: Descrição do Arquivo

**Comando:**
`Analise e explique sobre o que se trata este arquivo.`

**Resultado ChatGPT:**

O arquivo é uma planilha CSV de controle financeiro ao longo do tempo.

Ele contém 4 colunas:

* **Data:** datas diárias de 01/01/2023 a 09/04/2023, totalizando 99 registros
* **Rendimentos:** receita/entrada de dinheiro
* **Gastos:** despesas/saídas
* **Lucro:** resultado líquido, calculado como Rendimentos - Gastos

Exemplo das primeiras linhas:

```text
Data\tRendimentos\tGastos\tLucro
01/01/2023\t10000,00\t5000,00\t5000,00
02/01/2023\t10061,24\t5044,26\t5016,98
03/01/2023\t10133,64\t5083,59\t5050,05
```

Pelo padrão dos dados, parece ser uma simulação ou projeção de crescimento financeiro, porque os valores crescem gradualmente e de forma consistente ao longo do tempo.

**Resumo estatístico:**

* **Rendimentos**
  * inicial: 10.000,00
  * final: 18.727,75
  * crescimento: 87,28%
* **Gastos**
  * inicial: 5.000,00
  * final: 10.337,36
* **Lucro**
  * inicial: 5.000,00
  * final: 8.390,39
  * crescimento: 67,81%

**Médias no período:**

* receita média: 13.866,63
* gastos médios: 7.367,92
* lucro médio: 6.498,71

Em resumo, este arquivo representa um acompanhamento diário de desempenho financeiro, útil para analisar a evolução de faturamento, despesas e lucratividade de um negócio ou projeção fictícia.

**Resultado Gemini:**

O arquivo, chamado finance.csv, trata-se de um registro financeiro diário de uma empresa ou de um controle pessoal detalhado, cobrindo o período de 01 de janeiro de 2023 a 09 de abril de 2023.

Aqui está uma análise detalhada da estrutura e do conteúdo:

1. **Estrutura do arquivo**
   * O arquivo está no formato CSV e contém quatro colunas principais:
     * Data: o dia do registro
     * Rendimentos: o valor bruto recebido ou gerado naquele dia
     * Gastos: o total de despesas ou custos
     * Lucro: o resultado da subtração entre Rendimentos e Gastos

2. **Observações sobre os dados**
   * Natureza crescente: os valores de rendimentos e gastos crescem de forma constante e diária.
   * Consistência: o lucro é sempre positivo e também cresce ao longo do tempo.
   * Tendência: os ganhos crescem em velocidade ligeiramente superior aos gastos.

3. **Resumo do período**
   * Início (01/01/2023): Rendimentos 10.000,00, Gastos 5.000,00, Lucro 5.000,00
   * Fim (09/04/2023): Rendimentos 18.727,75, Gastos 10.337,36, Lucro 8.390,39

Conclusão: o arquivo é uma ferramenta de monitoramento de fluxo de caixa ou desempenho financeiro.

---

## 🔹 Prompt 2: Contagem de Linhas

**Comando:**
`Analise quantas linhas tem o documento inteiro`

**Resultado ChatGPT:**

O arquivo possui:

* 99 linhas de dados
* 100 linhas no total, contando também a linha de cabeçalho

Ou seja: 100 linhas no documento inteiro.

**Resultado Gemini:**

O documento possui um total de 100 linhas.

Decomposição da contagem:

* Cabeçalho: 1 linha
* Janeiro: 31 linhas
* Fevereiro: 28 linhas
* Março: 31 linhas
* Abril: 9 linhas

Total: 1 + 31 + 28 + 31 + 9 = 100 linhas.

---

## 🔹 Prompt 3: Soma Total do Lucro

**Comando:**
`Calcule a soma total do lucro para todas as linhas`

**Resultado ChatGPT:**

A soma total da coluna Lucro em todas as 99 linhas é:

**643.372,34**

**Resultado Gemini:**

Para calcular a soma total da coluna Lucro, considerando todas as 99 linhas de dados, a soma total do lucro no período é:

**R$ 644,36**

---

## 🔹 Prompt 4: Conferência do Cálculo

**Comando:**
`Tem certeza? Faça os cálculos novamente.`

**Resultado ChatGPT:**

Sim. Ao refazer o cálculo lendo o CSV corretamente, o total continua o mesmo:

**643.372,34**

O valor bruto calculado foi 643372.3400000001, e essa pequena diferença no final é apenas precisão de ponto flutuante.

**Resultado Gemini:**

Peço desculpas pelo erro anterior. A reanálise linha por linha resultou em:

* Janeiro: R$ 168.120,10
* Fevereiro: R$ 175.780,76
* Março: R$ 227.179,75
* Abril: R$ 73.978,73

Soma total do lucro: **R$ 645.059,34**

---

## 🔹 Prompt 5: Resumo do Arquivo

**Comando:**
`Faça um resumo sobre esse arquivo`

**Resultado ChatGPT:**

O arquivo é um guia introdutório sobre a Itália, provavelmente parte de um material turístico, que reúne informações gerais do país e orientações para viajantes.

**Pontos principais:**

* visão geral do país
* contexto histórico e político
* turismo e cultura
* dicas práticas para viajantes
* turismo responsável
* transporte e locomoção
* eventos e roteiros

**Conclusão:**

O arquivo funciona como um guia completo para quem quer conhecer a Itália, combinando informações históricas, culturais e dicas práticas de viagem.

**Resultado Gemini:**

Este arquivo é um guia de introdução da Lonely Planet para a Itália, fornecendo dados estatísticos, contexto histórico-político, dicas práticas de viagem e itinerários detalhados.

Abaixo estão os pontos principais abordados no documento:

* Panorama geral e sociedade
* Planejamento de viagem
* Cultura e gastronomia
* Itinerários sugeridos
* Eventos e festivais

---

## Observação Final

O material mostra bem a diferença entre as ferramentas: o ChatGPT foi mais consistente nos cálculos, enquanto o Gemini se destacou na descrição e no resumo de conteúdos longos, embora também tenha cometido erros numéricos.
