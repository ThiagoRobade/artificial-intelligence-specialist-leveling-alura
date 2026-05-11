# 02 - Princípios da Engenharia de Prompt

## 📝 Resumo da Aula

Nesta aula, o foco é a Engenharia de Prompt, que nada mais é do que a habilidade de "projetar" e escrever comandos perfeitos para extrair o melhor resultado da Inteligência Artificial. Para demonstrar, a aula utiliza a MariTalk (uma IA brasileira).

* **Regra de ouro: clareza.** Trate a IA como uma pessoa estagiária brilhante, mas que precisa de instruções literais.
* **Exemplo prático.** Pedir "a fórmula da média" pode gerar uma resposta genérica, enquanto pedir "a fórmula em Excel para calcular a média aritmética" traz a resposta exata e pronta para uso.
* **Dividir para conquistar.** Em tarefas complexas, vale quebrar o comando em etapas numeradas para evitar que a IA se perca.
* **Técnicas avançadas.** Pedir explicações e usar autoconsistência ajuda em problemas de lógica e matemática.
* **Conclusão.** O segredo não é fazer a pergunta mais complexa, mas sim a mais clara, detalhada e bem dividida possível.

---

## 🔹 Prompt 1: Fórmula da Média

**Prompt mariTalk.ai:**

`A fórmula da média aritmética de um conjunto de números é:`

$$
\text{Média} = \frac{\sum_{i=1}^{n} x_i}{n}
$$

**Onde:**
* $x_i$ representa cada valor do conjunto.
* $n$ é o número total de valores.
* $\sum$ indica a soma de todos os valores.

**Resposta explicada:**

Ou seja, some todos os valores e divida pelo número de valores.

**Comando:**
`Me dê a fórmula em Excel que é usada para calcular a média aritmética.`

**Resposta:**
> =MÉDIA(intervalo)

---

## 🔹 Prompt 2: Processo em Etapas

**Comando:**
`Passo 1 - Me dê uma lista de 5 hotéis em Roma que tenham sauna`

`Passo 2 - Escreva um artigo de blog sobre eles`

`Passo 3 - Crie um post para o Instagram com base no artigo de blog gerado`

**Resposta:**

### Passo 1 – Lista de 5 hotéis em Roma com sauna

Aqui estão 5 hotéis em Roma que oferecem sauna e experiências de bem-estar, segundo informações do site [1]:

1. **Golden Tulip Rome Piram**
   - Próximo à Galeria Borghese
   - Sauna, spa, jacuzzi e banho turco
   - Preço médio: €52/noite

2. **The Hive Hotel**
   - Perto da Basílica de Santa Maria Maggiore
   - Sauna, banho turco e salão termal
   - Preço médio: €197/noite

3. **Hotel Relais Dei Papi**
   - Próximo à Capela Sistina e Fontana di Trevi
   - Sauna, jacuzzi e terraço ensolarado
   - Preço médio: €67/noite

4. **Hotel Artemide**
   - Próximo ao Coliseu e à Basílica de Santa Maria dos Anjos
   - Sala de vapor, jacuzzi e spa
   - Preço médio: €255/noite

5. **Residenza Leutari**
   - Próximo ao Museu Nacional Romano
   - Sauna, jacuzzi e centro de bem-estar
   - Preço médio: valor não informado

---

### Passo 2 – Artigo de blog: “5 hotéis em Roma para relaxar com sauna”

**Título:**
5 hotéis em Roma para relaxar com sauna após um dia de turismo

**Introdução:**
Roma é uma cidade cheia de história, arte e sabores, mas depois de um dia intenso de passeios, nada melhor do que relaxar em um hotel com sauna. Se você busca conforto e bem-estar durante sua estadia na capital italiana, confira nossa seleção de hotéis que oferecem experiências de spa e relaxamento.

**Golden Tulip Rome Piram:**
Localizado a poucos passos da Galeria Borghese, o Golden Tulip Rome Piram é ideal para quem busca conforto e relaxamento. O hotel oferece sauna, spa, jacuzzi e banho turco, além de um restaurante moderno e quartos aconchegantes. Com diárias a partir de €52, é uma opção acessível para quem quer curtir o melhor do bem-estar em Roma.

**The Hive Hotel:**
Com uma localização privilegiada perto da Basílica de Santa Maria Maggiore, o The Hive Hotel é conhecido pelo design contemporâneo e pelas instalações de lazer, incluindo sauna, banho turco e academia. As diárias custam em média €197, e o hotel é perfeito para quem quer unir turismo e relaxamento.

**Hotel Relais Dei Papi:**
Próximo aos principais pontos turísticos, como a Capela Sistina e a Fontana di Trevi, o Relais Dei Papi oferece sauna, jacuzzi e um terraço ensolarado. Com diárias a partir de €67, é uma escolha sofisticada para quem deseja descansar após explorar Roma.

**Hotel Artemide:**
Este elegante hotel 4 estrelas fica a uma curta caminhada do Coliseu e oferece sala de vapor, jacuzzi e spa. O Artemide é conhecido pelo atendimento de excelência e pelo restaurante mediterrâneo. Diárias a partir de €255, ideal para quem busca luxo e tranquilidade.

**Residenza Leutari:**
A Residenza Leutari é uma opção charmosa próxima ao Museu Nacional Romano, com sauna, jacuzzi e centro de bem-estar. O ambiente é tranquilo e perfeito para quem quer fugir do agito, mas ainda estar perto das atrações.

**Conclusão:**
Seja para relaxar após um dia de passeios ou para curtir um momento de autocuidado, esses hotéis em Roma oferecem o que há de melhor em termos de sauna e spa. Escolha o seu preferido e aproveite o melhor da Cidade Eterna com muito conforto.

---

### Passo 3 – Post para Instagram

温泉とリラックスの時間に寛ぐローマのホテル5選✨
после прогулок по древним улицам — идеальный способ восстановить силы!

1. Golden Tulip Rome Piram – спа, сауна и джакузи
2. The Hive Hotel – современный дизайн и турецкий хаммам
3. Hotel Relais Dei Papi – рядом с достопримечательностями и сауной
4. Hotel Artemide – паровая комната и роскошь в центре
5. Residenza Leutari – уютный спа-отель в историческом районе

疲れた体を癒すなら、ローマのホテルで至福のひとときを…
#Roma #HotelSpa #Sauna #Relax #TravelItaly #LuxuryStay #Wellness

---

## Referências

[1] Spa Hotels Resorts - https://spahotelsresorts.com/pt/spa-hotels-roma/
