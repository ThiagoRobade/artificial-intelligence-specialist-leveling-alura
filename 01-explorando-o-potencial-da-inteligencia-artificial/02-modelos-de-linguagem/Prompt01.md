# 02 - Como funcionam os Grandes Modelos de Linguagem (LLMs)

## 📝 Resumo da Aula

Esta aula mergulha nos bastidores da Inteligência Artificial para explicar a mecânica por trás do ChatGPT e do Gemini:

* **Processamento de Linguagem Natural (NLP):** é a área da IA focada em fazer as máquinas entenderem e reproduzirem a linguagem humana. Isso permite que você se comunique com o computador usando textos comuns, sem precisar de códigos de programação.
* **O “Autocompletar” superpoderoso:** na prática, um LLM funciona calculando a probabilidade estatística da próxima palavra. Quando você escreve um comando, a IA não “pensa” como um humano, mas calcula matematicamente qual palavra faz mais sentido vir a seguir, encadeando termo por termo.
* **Treinamento e padrões:** para fazer essas previsões com precisão, os modelos são treinados com volumes colossais de dados da internet. Eles aprendem regras gramaticais e o sentido das palavras em diferentes idiomas.
* **Memória contextual:** o grande trunfo que popularizou essas ferramentas foi a capacidade de manter o contexto em formato de chat. A IA lembra do que foi dito nas mensagens anteriores da mesma janela, permitindo continuar a conversa naturalmente sem repetir tudo de novo.

---

## 🔹 Prompt 1: Continuação de Frases

**Comando:**
`Vamos simular como funciona o ChatGPT. Para cada frase que eu escrever no prompt, você deve listar as 5 palavras com maior probabilidade que você usaria para completá-la, junto com a probabilidade de cada uma delas. Combinado? Apenas as palavras e probabilidades, sem mais nada.`

**Entrada:**
`Eu gosto de`

**Resposta ChatGPT:**
> comer — 0,18
> viajar — 0,15
> aprender — 0,12
> assistir — 0,10
> ler — 0,09

**Entrada:**
`Eu gosto de chocolate`

**Resposta ChatGPT:**
> ao — 0,22
> e — 0,18
> porque — 0,14
> mas — 0,11
> com — 0,09

**Entrada:**
`Eu gosto de chocolate porque`

**Resposta ChatGPT:**
> é — 0,24
> tem — 0,18
> gosto — 0,14
> me — 0,11
> ele — 0,09

---

## 🔹 Prompt 2: Fórmula do Excel

**Comando:**
`Qual é o nome da fórmula de Excel para encontrar o maior número em uma lista de números? Responda apenas com o nome da fórmula.`

**Resposta ChatGPT:**
> MÁXIMO

**Comando:**
`Me dê um exemplo dessa fórmula.`

**Resposta:**
> =MÁXIMO(A1:A10)


