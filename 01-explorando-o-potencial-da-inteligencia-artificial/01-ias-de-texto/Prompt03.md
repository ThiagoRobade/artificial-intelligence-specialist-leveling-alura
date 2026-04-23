# 03 - Lidando com Textos

## 📝 Resumo da Aula

A aula avança para tarefas de produtividade no dia a dia, focando na criação de e-mails padronizados e resumos de textos longos, destacando limites cruciais entre as ferramentas:

* **E-mails com Regras Rígidas:** Você pode colar uma lista de diretrizes estruturais para a IA seguir (ex: limite de caracteres no assunto, uso de emojis, bullet points, tom de voz específico, negrito em palavras-chave). Ambas as IAs (ChatGPT e Gemini) se saíram muito bem nessa tarefa.
* **Adaptabilidade Profissional:** Esse método de "regras" serve para qualquer área (marketing, advocacia, exatas). Basta criar o seu manual de tom de voz e pedir para a IA redigir o texto com base nele.
* **Resumo de Textos Longos:** A aula testa as IAs pedindo o resumo da transcrição completa de um podcast, usando separadores visuais (`-----`) para dividir o comando do texto.
* **O Limite do Gemini:** Ao colar o texto gigante, ficou claro que a versão gratuita do ChatGPT lida perfeitamente com grandes volumes de texto, enquanto a versão gratuita do Gemini tem um limite de caracteres menor no prompt. O Gemini cortou o texto pela metade e não conseguiu gerar o resumo, entregando uma resposta confusa.
* **Conclusão:** Ferramentas diferentes têm vantagens diferentes. O Gemini brilha nas buscas em tempo real, mas o ChatGPT (nas versões gratuitas testadas) ganha na capacidade de processar e resumir blocos massivos de texto.

---

## ✉️ Teste 1: Criação de E-mail com Regras

### Prompt Utilizado (ChatGPT e Gemini)

Crie um e-mail para um cliente seguindo as regras abaixo:

**Regras para Títulos:**
- Use títulos de até 42 caracteres
- Não use caixa alta
- Não use pontuação em excesso
- Personalize com o nome da pessoa
- Faça perguntas
- Use emojis

**Regras para o corpo do e-mail:**
- Escreva em primeira pessoa, use tom pessoal
- Use o nome da pessoa no início do e-mail
- Coloque o nome da pessoa antes de uma pergunta
- Use bullet points para organizar ideias
- Faça parágrafos curtos
- Dê um espaço entre uma frase e outra
- Coloque em negrito palavras que são importantes no texto
- Deixe a mensagem do botão de ação bem claro

**Tema do e-mail:**
O mesmo sobre o post acima sobre hotéis na Itália.

### 🤖 Resposta ChatGPT 1

> Oi, [Nome]! Tudo bem?
> 
> Eu tava pensando em você e numa coisa: que tal transformar sua próxima viagem pra **Roma** em algo realmente especial?
> 
> [Nome], você já imaginou ficar em um hotel incrível, com **sauna**, conforto e ainda perfeito pra ir com a família?
> 
> Eu separei algumas opções que valem MUITO a pena:
> 
> * **Hotéis modernos** com spa completo pra você relaxar de verdade
> * Lugares com **estrutura pra crianças**, sem estresse
> * Opções que equilibram **luxo e custo-benefício**
> * Localizações que facilitam explorar a cidade sem dor de cabeça
> 
> Sério, dá pra curtir Roma com tranquilidade e ainda aproveitar aquele descanso merecido no fim do dia.
> 
> E o melhor: você não precisa quebrar a cabeça procurando — já tá tudo praticamente resolvido.
> 
> [Nome], fala pra mim: você prefere algo mais **luxuoso** ou mais **prático e econômico**?
> 
> Seja qual for sua vibe, tem um hotel perfeito te esperando.
> 
> Agora é o momento de sair do plano e ir pra ação 👇
> 
> 👉 **Reserve agora seu hotel em Roma**
> 
> Não deixa pra depois… as melhores opções acabam rápido 😉
> 
> Abraço,  
> Seu parceiro de viagens ✈️

### 🤖 Resposta Google Gemini 1

> **Assunto:** Roma te espera, {{nome}}! 🏛️✨
> 
> Olá, {{nome}},
> 
> Espero que o seu dia esteja sendo incrível.
> 
> Estive organizando algumas opções de hospedagem em Roma e lembrei que você valoriza experiências que unem bem-estar e praticidade para a família.
> 
> {{nome}}, você já imaginou relaxar em uma sauna privativa após um dia explorando o Coliseu?
> 
> Selecionei alguns picos que são nota dez para o que você busca:
> 
> * **A.Roma Lifestyle:** Luxo moderno e spa de outro mundo.
> * **Villa Pamphili:** Sossego total ao lado do parque.
> * **Crowne Plaza:** Piscina interna braba e perto do Vaticano.
> * **The Building:** Estilo histórico com piscinas impecáveis.
> * **Golden Tulip Piram:** Localização estratégica e terraço irado.
> 
> Cada um desses lugares foi escolhido pensando no seu conforto e na diversão das crianças.
> 
> {{nome}}, qual desses estilos combina mais com a sua próxima viagem?
> 
> Estou à disposição para ajudar você a ajustar todos os detalhes e garantir que essa trip seja épica.
> 
> Abraços,  
> Thiago
> 
> **[RESERVAR MINHA ESTADA EM ROMA AGORA]**

---

## 📑 Teste 2: Resumo de Textos Longos

### Prompt Utilizado

Resuma a transcrição abaixo e me explique do que se trata:
`-----`

<details>
<summary><b>Clique aqui para visualizar a transcrição completa do Podcast</b></summary>

(Essa é a transcrição do episódio 21, Acessibilidade Web, tentando tornar nosso conteúdo mais acessível na internet! Um agradecimento à equipe de transcritores da Alura.

**Paulo:** Olá, ouvintes do Hipsters Ponto Tech! Eu sou Paulo Silveira.

Sábado, dia 3 de dezembro, foi uma data muito especial… Foi o dia da luta internacional da pessoa com deficiência e por isso, o papo de hoje será sobre acessibilidade – tanto na Web quando em aplicativos móveis. Porque hoje não é só um ponto fundamental para trazer socialmente todas as pessoas juntas, para que elas tenham acesso ao seu site ou a sua app, como também é um ponto vital para dar sobrevivência para sua empresa, para que ela alcance um público maior, um público consumidor e muito importante. Vamos para o podcast.
Hoje para conversar com a gente, tenho a presença do Reinaldo Ferraz, que é especialista em desenvolvimento web na W3C Brasil. Tudo bom com você, Reinaldo?

**Reinaldo:** Oi, pessoal. Primeiramente é um prazer estar com você aqui, falar de um tema tão importante, próximo dessa data tão especial.

**Paulo:** Junto com o Reinaldo, aqui presente no estúdio da Alura, tenho o Alexandre Costa que analista de desenvolvimento no Itaú. Tudo bom, Alexandre?

**Alexandre:** Opa, Paulo! Beleza? Boa tarde, pessoal. Uma data bem importante mesmo que não poderia passar em branco e realizando um sonho de estar aqui gravando um Hipster.

**Paulo:** [risos] Temos um fã aqui presente! Como essa conversa beira Web e mobile, a gente o nosso cohost, que você já conhece, que já tem sua própria musiquinha: o Sérgio Lopes. Tudo bom, Sérgio?

**Sérgio:** Oba, pessoal! Tudo bom?

**Paulo:** Eu queria começar o papo entendendo um pouco mais do que é acessibilidade. Pra não ficar muita indefinição, quero saber do Reinaldo, que trabalha nesse órgão que todo mundo já sonhou em trabalhar, o W3C, o que é acessibilidade na Web? Começando pela Web… Quais são os exemplos de um site que a gente pode dizer que é acessível, o que ele está resolvendo e pra quem?

**Reinaldo:** Poderíamos resumir a acessibilidade na Web como garantir que as pessoas com deficiência tenham acesso ao conteúdo na Web. Normalmente quando a gente trabalha a questão de sites acessíveis, falamos muito sobre barreiras de acesso. Então, um site que tem uma barreira de acesso, ele tem um problema sério de acessibilidade. Por exemplo, um site que você não consegue aumentar o tamanho das fontes, um site que as imagens não tem descrições adequada em textos alternativos, um site que você não consegue fazer um navegação viia teclado, um site que tem um contraste ruim entre o texto e o tom de fundo… Tudo isso seria considerado barreiras de acesso para pessoas com deficiência. Neste ponto, se você tem algum tipo de dificuldade, mesmo não tendo algum tipo de deficiência,  é bem provável que o seu site tenha alguma barreira séria de acessibilidade.

**Paulo:** Alexandre, hoje esse é um ponto importante para que o seu público seja ainda maior.

**Alexandre:** Com certeza. Se você pegar só no Brasil por exemplo, Paulo, são 6,5 milhões de pessoas com algum tipo de deficiência visual, só dentro do âmbito visual. Com todos os tipos de deficiência, chegamos a 45 milhões de pessoas, estamos falando de quase 1/5 da população brasileira. Não dá pra desperdiçar. Eu brinco muito que gostaria de fazer um app de $1 dólar para cada pessoa com deficiência. Já estava bom…

**Paulo:** É uma empresa de 1 milhão de dólares… O Reinaldo citou alguns exemplos de situações que não são muito acessíveis para um Web site, eu queria saber, começando pela pessoa com deficiência visual que acho que um caso um pouco mais fácil para as pessoas conseguirem imaginar. Quais sãos a técnicas que a gente deve seguir, qual é o guia principal que a sua página Web precisa ter, que recursos precisa ter para que uma pessoa com deficiência visual consiga utilizá-la da maneira adequada para ela.

**Reinaldo:** Acho até interessante pontuar esta questão, porque a pessoa com deficiência visual talvez seja uma que tenha um dos grandes impactos quando falamos de acesso à web… porque qualquer dispositivo, tanto computador, como o smartphone, ele é muito visual. Então, a gente se orienta pela visão. A deficiência visual costuma ser a mais utilizada para podermos verificar pontos específicos de acessibilidade com relação ao impacto. Existem diversas técnicas que estão disponíveis dentro da documentação do W3C, as WCAG, que acho que vale a pena deixar no comentários.

**Paulo:** Já estão nos links [risos].

**Reinaldo:** Que rápido! Como vocês são rápidos. [risos] [risadas no estúdio]

**Reinaldo:** Essa documentação diz como tornar o conteúdo acessível pra evitar que pessoas com deficiência tenham barreiras de acesso. Então, por exemplo, a descrição de imagens é importantíssima. Você declarar o atributo `alt` das suas imagens… Declarar o atributo `alt` funciona porque se uma pessoa estiver navegando com software leitor de tela, acho que o Alexandre pode explicar um pouco mais sobre a experiência dele, se a pessoa estiver navegando com o software e este atributo `alt` não estiver descrito, ele vai simplesmente ouvir o retorno do software sintetizador de voz como se ele fosse uma imagem. Sem uma descrição. E se essa imagem faz parte do contexto da página, ela deve conter uma descrição. A estrutura de cabeçalho da página é importantíssima, porque normalmente o usuário de tecnologia assistiva, que é como chamamos o usuário de leitor de tela ( o leitor de tela é um tipo de tecnologia assistiva), navega muito por atalho de teclado. Então, se eu pressionar a tecla H, eu navego por todos os cabeçalhos da minha página. Se eu pressionar a tecla 1, eu navego pelo cabeçalhos de nível 1. [Pressiono] 2, cabeçalho de nível 2, e por aí, vai… Então, se eu tiver estrutura de cabeçalho da minha página marcado de forma adequada, imagina que uma pessoa vai chegar na sua página, ela sabe que todos os tipos de notícia são cabeçalho de nível 2, então, é muito mais fácil para essa pessoa poder chegar nesse item da página.

**Paulo:** Estamos falando exatamente do que? “h1”, “h2”, “header”, “/header”?

**Sérgio:** Em HTML, são os famosos “h1”, “h2”, “h3”, a ideia é usar de uma maneira inteligente. Às vezes, quando o desenvolvedor vai fazer a página, muita gente pensa pega um design lá do Photoshop, por exemplo, que foi feito, e fala “isso aqui é um título, o título tem uma fonte grande, em negrito”. E às vezes, o cara implementa um “div” e implementa o título com o “div”, fica igualzinho o design, só que você perde o lado que o Reinaldo está falando, que é o lado semântico. É quando o leitor de tela vai olhar pra aquele código, ele não está interessado se o texto está grande ou está pequeno, do tamanho visual, a cor do texto, porque isso é totalmente irrelevante. O jeito dele saber que aquilo é um título, não é porque ele é uma fonte grande, é porque ele foi marcado como título e então são usadas essas tags que são super antigas (“h1”, “h2”) que existem no HTML há muito tempo, mas que muita gente usa errado. Ou deixa de usar.

**Reinaldo:** O Sérgio tocou num ponto extremamente importante que é a marcação semântica, na verdade, utilizar os elementos semânticos do HTML. Isso é importantíssimo para acessibilidade porque, como estamos falando de deficiência visual, você tem esses leitores de tela que já conseguem identificar grande parte dos elementos semânticos do HTML5. Então você consegue ir para blocos de conteúdo, ir para navegação, ir para áreas específicas da página utilizando esses elementos semânticos – a marcação de “header”, “nav”, “section” e por aí, vai. Eu só queria aproveitar e fazer um comentário interessante e aproveitar que estamos falando em um podcast que tem uma boa repercussão, e acho que isso é um discussão legal para se abrir, é a questão de múltiplos “h1” na página. Isso é um ponto que tem problema ainda com a acessibilidade, porque quando você utiliza múltiplos “h1” (vamos dizer, “h1” principal e depois, “h1” dentro de “section”, outro dentro de outra “section”) para um software leitor de tela, ele não consegue fazer a verificação de hierarquia entre esses “h1″s. Então, ele não sabe qual é “h1” principal, qual é o secundário. Ele vai chamar todos eles por “h1”. Então pra acessibilidade ele ainda é muito delicado para utilizar múltiplos “h1″s numa página.

**Paulo:** Vale lembrar que não só pra isso. Pra SEO, Google, o pessoal fala “se der, [use] um ‘h1’ só”.

**Alexandre:** Na verdade, não só um “h1”, mas você também não pular os “h”s. É você colocar “h1” para o seu título principal da página e os títulos secundários você colocar “h3” porque o tamanho da fonte está mais adequado. É muito comum.

**Paulo:** [risos] É a famosa preguiça do Front-End.

**Alexandre:** Exatamente… Então, a página ser semântica ajuda muito, principalmente, até colocando um adendo, temos que lembrar que o deficiente visual é bem impactado, mas as outras deficiências também. Porque à vezes, para determinada tecnologia, ele vai renderizar a página de uma forma só. Pensa que o leitor de tela, o que ele faz com a sua página? Não importa se ele tem, por exemplo, três colunas. Ele vai colocar aquilo como uma coisa sequêncial. Tanto é quando você chega para o deficiente visual e fala “o ícone à direita” ele fica maluco, porque para ele a página é um formulário contínuo.

[risos no estúdio]

**Alexandre:** Outra coisa importantíssima também, é uma coisa muito comum, eu quero que os meus links, [por exemplo] o link “comprar” ele tenha a aparência de um link, ele tenha a aparência de um botão. Então, você liga para o suporte técnico e fala “cara, eu não estou conseguindo comprar aqui no site”. “Senhor, clique no botão ‘comprar'”. Então, você vai lá no teclado, aperta B – que é o atalho para próximo botão – e o leitor de tela fala “não tem botão nessa página”. Você insiste no B e a pessoa vai lá, [clica em] “control + U” para verificar o código-fonte e verifica que é um link que tem um style “.btn” lá do Bootstrap.

[risos no estúdio]

**Alexandre:** Porque além das tags semânticas, a gente tem que lembrar de alguns outros atributos que um elemento tem que ter que a tecnologia assistiva usa. O primeiro dele é realmente a tag. A tag vai falar “isso aqui é um link, um “a”, então, é um link”. Então, ela tem um comportamento de link e eu consigo sobrepor isso. É a role, é o papel que esse elemento tem dentro da página. Isso indica para o leitor de tela, outros recursos assistivos como os navegadores que a pessoa tetraplégica usa aquele canudinho na boca pra navegar e outras tecnologias. Então, a role é importante porque ela diz para o leitor o que é aquilo e como eu interajo com aquele elemento. A segunda coisa é o estado daquele elemento, ele está ativo, ele está inativo, eu consigo interagir, ele está marcado? É um checkbox ou radio-button, ele está marcado ou desmarcado? Por último, e não menos importante, o valor. A caixa de texto, ela está preenchida, qual é o valor da caixa de texto? Tem um discussão muito boa, não é mesmo Reinaldo, em relação ao placeholder in text. Muita gente se confunde com o placeholder, acha que o placeholder substitui um label. Imagine que estou preenchendo um formulário e tem um placeholder colocando “999.999.999-99”, automaticamente você pensa “opa, isso aqui é o campo CPF”. Só que o leitor de tela não lê essa informação. E quando o campo ganha foco, ele fala “em branco”.

[risadas no estúdio]

**Alexandre:** “Eu preencho aqui, o quê? Com o nome da mãe ou do dono do site.

**Paulo:** Eu queria deixar claro, o Reinaldo deu um spoiler. A gente não falou lá na frente, mas o Alexandre fala com um certo conhecimento de causa. Ele é uma pessoa com deficiência visual, com cerca de 3% da visão. Está correto, Alexandre?

**Alexandre:** Isso mesmo. O que clinicamente… eu sou cego. Ainda tenho um resquício de luz, eu consigo saber se é de dia ou se é de noite, então, eu não me perco nos horários. Praticamente eu não consigo ler nada, eu não consigo usar o monitor, então eu passo o dia tanto no computador, como no celular, usando a tecla Assist View (leitores de tela).

*(Nota: O texto continua detalhando o uso de leitores de tela como VoiceOver, Jaws e NVDA, os desafios para desenvolvedores, a importância de focar em marcação correta, navegação via teclado para evitar atalhos que excluem usuários e encerra com recursos de validação automática e dicas valiosas de inclusão e documentação).*
</details>

### 🤖 Resposta ChatGPT 2

> 🧾 **Resumo da transcrição**
> 
> O episódio do podcast discute acessibilidade digital — como tornar sites e aplicativos utilizáveis por pessoas com deficiência (especialmente visual), mas também por qualquer usuário.
> 
> Os participantes explicam que acessibilidade significa remover barreiras que dificultam o uso de um site, como:
> * falta de descrição em imagens
> * impossibilidade de navegação por teclado
> * baixo contraste de cores
> * uso incorreto de HTML (ex: usar div em vez de button)
> 
> Eles destacam boas práticas técnicas, como:
> * usar HTML semântico (h1, button, label, etc.)
> * adicionar descrições (alt) em imagens
> * permitir navegação via teclado
> * estruturar corretamente títulos e formulários
> * não depender apenas de cor para transmitir informação
> 
> Também explicam o uso de leitores de tela (como NVDA, Jaws e VoiceOver), que permitem que pessoas cegas naveguem ouvindo o conteúdo.
> 
> Além disso, reforçam que:
> * acessibilidade melhora SEO e automação de testes
> * amplia o público (milhões de pessoas com deficiência)
> * é uma questão social e também legal no Brasil
> * beneficia todos os usuários, não só quem tem deficiência
> 
> 💡 **Do que se trata (explicação simples)**
> 
> Esse conteúdo é basicamente sobre como desenvolver tecnologia de forma inclusiva.
> 
> A ideia central é:
> **Um site acessível não é algo “extra” — é simplesmente um site bem feito.**
> 
> Ou seja:
> Quando você usa corretamente as tecnologias da web, organiza bem o conteúdo, e pensa em diferentes formas de interação (teclado, áudio, etc.), 👉 você cria uma experiência melhor para todo mundo — incluindo:
> * pessoas com deficiência permanente
> * pessoas com limitações temporárias (ex: braço machucado)
> * idosos
> * qualquer usuário em situações difíceis (ex: luz forte no celular, pressa, emergência)
> 
> 🎯 **Principais mensagens do episódio**
> * Acessibilidade é inclusão + oportunidade de negócio
> * Fazer acessível = seguir boas práticas básicas
> * Testar com teclado já revela muitos problemas
> * Tecnologia assistiva deve ser considerada desde o início do projeto
> * Não é só técnico — é também social e legal

### 🤖 Resposta Google Gemini 2

> Este é um resumo do episódio 21 do podcast Hipsters Ponto Tech, focado em Acessibilidade Web. O debate reúne especialistas para discutir como tornar a internet inclusiva para pessoas com deficiência (PCD) e por que isso é vital para qualquer negócio.
> 
> 💡 **O que é Acessibilidade Web?**
> De forma simples, é garantir que qualquer pessoa, independentemente de suas capacidades físicas ou sensoriais, consiga navegar, entender e interagir com um site ou aplicativo. O grupo destaca que acessibilidade não beneficia apenas PCDs, mas melhora a experiência de:
> * Pessoas idosas.
> * Pessoas em situações temporárias (braço quebrado, óculos perdido).
> * Pessoas em ambientes desfavoráveis (sol forte na tela do celular ou ruído excessivo).
> 
> **Principais Barreiras Citadas:**
> * Imagens sem descrição textual.
> * Navegação que depende exclusivamente do mouse (impossibilitando o uso de teclado).
> * Baixo contraste entre texto e fundo.
> * Falta de semântica no código (ex: usar um `<span>` com clique em vez de um `<button>`).
> 
> 🛠️ **Boas Práticas e Técnicas (O lado Técnico)**
> O episódio reforça que, para o desenvolvedor, acessibilidade é sinônimo de "fazer o código do jeito certo", respeitando os padrões da W3C.
> * **Semântica HTML:** Usar as tags corretas (`<h1>` para títulos, `<nav>` para menus, `<button>` para ações). Isso permite que leitores de tela entendam a estrutura da página.
> * **Atributo alt:** Essencial para descrever imagens. Se a imagem for apenas decorativa, deve-se usar `alt=""` (vazio) para que o leitor a ignore.
> * **Hierarquia de Cabeçalhos:** Não pular níveis (ir do h1 direto para o h3) apenas por estética, pois isso confunde a navegação por atalhos.
> * **Formulários:** Associar sempre o `<label>` ao `<input>` via ID. Isso amplia a área de clique e permite que o leitor de tela anuncie o que deve ser digitado.
> * **Navegação via Teclado:** Um site acessível deve ser totalmente operável usando apenas a tecla Tab e Enter.
> 
> 📈 **Os Argumentos para Convencer o "Chefe"**
> Se a questão social não for suficiente, os convidados listam motivos estratégicos:
> * **Alcance de Mercado:** No Brasil, cerca de 45 milhões de pessoas possuem algum tipo de deficiência. Ignorar acessibilidade é ignorar uma fatia enorme de consumidores.
> * **SEO (Google):** Robôs de busca leem o site de forma muito parecida com leitores de tela. Um site acessível (com bons alt e semântica) ranqueia melhor.
> * **Testes Automatizados:** Ferramentas de teste (como Selenium) usam os mesmos atributos de acessibilidade para identificar elementos.
> * **Legalidade:** Existe a Lei Brasileira de Inclusão (LBI), que torna obrigatória a acessibilidade em sites de empresas com representação no Brasil.
> 
> 🎧 **Tecnologias Assistivas**
> Alexandre Costa, que tem deficiência visual, explica como utiliza o computador através de Leitores de Tela:
> * **NVDA:** Gratuito e código aberto (muito recomendado para desenvolvedores testarem seus sites).
> * **Jaws:** Comercial e de alto custo.
> * **VoiceOver:** Nativo em dispositivos Apple (iOS e macOS).
> * **TalkBack:** Nativo no Android.
> 
> Ele menciona que usuários experientes ouvem o leitor em velocidades altíssimas (como um áudio de WhatsApp em 3x ou mais), o que exige que o código seja limpo e direto.
> 
> 🏁 **Conclusão**
> A mensagem final é: acessibilidade deve nascer com o projeto. Tentar "consertar" um site depois de pronto é mais caro e difícil. Quando o desenvolvedor usa o HTML para o que ele foi criado, a acessibilidade acontece naturalmente.
> 
> Você já tentou navegar no site em que trabalha usando apenas a tecla Tab para ver se consegue completar uma compra ou cadastro?