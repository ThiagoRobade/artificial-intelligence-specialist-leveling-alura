# 02 - Descobrindo o Google Gemini - Prompts 🚀

Este repositório contém o resumo da aula sobre o Google Gemini, destacando suas diferenças práticas em relação ao ChatGPT e exemplos práticos de como a ferramenta reage aos mesmos comandos.

---

## 📝 Resumo da Aula

A aula explora o uso do Google Gemini aplicando os mesmos comandos testados anteriormente no ChatGPT, destacando as diferenças práticas entre as duas ferramentas:

* **Integração com a Internet:** O grande diferencial do Gemini é o acesso ao ecossistema do Google (como o Google Hotels). Ele consegue entregar dados reais e atualizados, incluindo preços, sugestões de datas e links diretos para reservas.
* **Dificuldade com Restrições (Alucinações/Erros):** A versão gratuita do Gemini pode falhar ao seguir regras de formatação. No teste, a IA ignorou o comando "não use listas", possivelmente porque os dados puxados do Google Hotels já vêm estruturados em formato de lista.
* **Comparação Prática:** O Gemini ganha pontos pela busca em tempo real e conexão com a web, mas o ChatGPT (na versão gratuita do teste) demonstrou ser mais "obediente" e preciso na formatação e redação do texto.
* **Dica de Ouro:** As IAs cometem erros e exigem revisão humana (o próprio Gemini exibe um aviso sobre isso). Se a ferramenta errar um detalhe visual, como criar uma lista indesejada, muitas vezes é mais rápido fazer o ajuste manual no texto do que tentar forçar a IA a corrigir.

---

## 🛠️ Exemplos de Prompts e Saídas

Abaixo estão os testes realizados durante a aula, utilizando os mesmos prompts do módulo anterior para fins de comparação.

### 🔹 Prompt 1: Criatividade (Poesia)

**Comando:**
`Escreva uma poesia sobre a Itália.`

**Resultado:**
> Sob o sol que doura as colinas da Toscana, a Itália se revela como um manuscrito aberto, onde cada ruela de pedra conta o segredo de um século passado. É um país que não se visita apenas com os pés, mas com a alma e o paladar.
> 
> Aqui está uma homenagem a essa terra de luz e mármore:
> 
> **O Despertar da Bota**
> Onde o azul do Tirreno abraça o Adriático,
> E o tempo caminha em passo lento e estático,
> Ergue-se a terra do mármore e do vinho,
> Feita de glória, de arte e de carinho.
> 
> Nas veias de Roma, o sangue dos césares pulsa,
> Entre ruínas que o destino não expulsa.
> O Coliseu guarda o eco de um grito antigo,
> Enquanto o Tibre corre, do passado, um amigo.
> 
> **A Dança das Cidades**
> Florença: Onde o pincel de Da Vinci ainda flutua,
> E a beleza de Vênus caminha na rua.
> 
> Veneza: Labirinto de águas, espelho de luz,
> Onde o silêncio do remo ao mistério conduz.
> 
> Nápoles: O caos que canta, o fogo do vulcão,
> Onde a vida explode em cada fatia de pão.
> 
> **O Aroma da Herança**
> Pelas estradas de ciprestes, o vento traz o odor,
> Do alecrim, da azeitona e do fruto de cor.
> É o dolce far niente, o prazer de existir,
> Entre um gole de vinho e um novo sorrir.
> 
> Do norte alpino ao sul que o sol incendeia,
> A Itália é uma ópera que nos corre na veia.
> Não é apenas um mapa, um destino ou lugar,
> É um estado de espírito que nos ensina a amar.
> 
> *"L'Italia è un sogno che continua a tornare per il resto della tua vita."*
> (A Itália é um sonho que continua voltando pelo resto da sua vida.)

---

### 🔹 Prompt 2: Informação Geral

**Comando:**
`Me escreva sobre hotéis em Roma.`

**Resultado:**
> Roma oferece uma vasta gama de opções de alojamento, desde hotéis de luxo em palácios históricos até pensões charmosas em bairros medievais. A escolha ideal depende muito do objetivo da viagem e do orçamento.
> 
> Aqui estão as principais zonas e tipos de hotéis para considerar:
> 
> **1. Centro Histórico (Panteão, Praça Navona e Campo de' Fiori)**
> É a zona mais procurada por quem quer fazer tudo a pé. Estará a poucos passos das principais atrações.
> * **Perfil:** Hotéis boutique e edifícios históricos.
> * **Vantagem:** Localização imbatível e atmosfera vibrante.
> * **Desvantagem:** Preços mais elevados e ruas que podem ser barulhentas à noite.
> 
> **2. Trastevere**
> O bairro mais boémio e pitoresco de Roma, do outro lado do rio Tibre.
> * **Perfil:** Hotéis de charme e pequenos alojamentos locais (Bed & Breakfast).
> * **Vantagem:** Excelente oferta gastronómica, vida noturna animada e ruas de paralelepípedos muito fotogénicas.
> * **Desvantagem:** Não tem metro por perto (depende de elétricos e autocarros).
> 
> **3. Via Veneto e Villa Borghese**
> Uma zona elegante, imortalizada pelo filme *La Dolce Vita*.
> * **Perfil:** Hotéis de 5 estrelas e grandes cadeias de luxo.
> * **Vantagem:** Segurança, tranquilidade e proximidade aos jardins da Villa Borghese. Ideal para quem procura sofisticação.
> * **Desvantagem:** Preços premium e subidas íngremes para chegar ao centro.
> 
> **4. Prati (Perto do Vaticano)**
> Um bairro mais residencial e organizado, muito popular entre famílias.
> * **Perfil:** Hotéis modernos e pensões com boa relação qualidade-preço.
> * **Vantagem:** Proximidade à Basílica de São Pedro e Museus do Vaticano, além de ótimas lojas para compras (Via Cola di Rienzo).
> * **Desvantagem:** Um pouco mais afastado das ruínas romanas (Coliseu/Fórum).
> 
> **5. Monti**
> O primeiro bairro de Roma, localizado entre o Coliseu e a Estação Termini.
> * **Perfil:** Hotéis de design, conceitos "hip" e alojamentos mais jovens.
> * **Vantagem:** Um ambiente artístico com muitas galerias, lojas vintage e bares de vinho, mantendo uma sensação de "bairro local".
> 
> **6. Termini (Estação Central)**
> A zona mais prática para quem viaja de comboio ou tem voos muito cedo.
> * **Perfil:** Grande concentração de hotéis económicos e grandes hotéis internacionais.
> * **Vantagem:** Melhores preços de Roma e excelentes ligações de transporte (metro, comboio e autocarros para o aeroporto).
> * **Desvantagem:** A zona imediata à volta da estação pode ser menos estética e requer maior atenção à segurança à noite.
> 
> **Dicas Úteis:**
> * **Taxa Turística:** Roma cobra uma taxa municipal por pessoa, por noite (geralmente entre 3€ e 7€, dependendo da categoria do hotel), que normalmente é paga em dinheiro no check-out.
> * **Ar Condicionado:** Se viajar no verão, confirme sempre se o hotel tem ar condicionado, pois muitos edifícios históricos têm restrições.
> * **Reservas:** É aconselhável reservar com bastante antecedência, especialmente se pretender visitar na Primavera ou no Outono, que são as épocas altas na cidade.

---

### 🔹 Prompt 3: Especificidade e Filtros

**Comando:**
`Me dê uma lista de 5 hotéis na cidade de Roma, na Itália. Eu quero hotéis que tenham sauna e que sejam amigáveis com crianças.`

**Resultado:**
> Aqui estão 5 opções de hotéis em Roma que oferecem spa (com sauna) e são adequados para famílias com crianças:
> 
> * **A.Roma Lifestyle Hotel:** Este hotel de 4 estrelas é muito bem avaliado e oferece um ambiente moderno. Conta com um spa completo, restaurante e é conhecido por ser uma excelente opção para quem busca conforto com a família, um pouco mais afastado da agitação do centro.
> * **Hotel Villa Pamphili Roma:** Localizado perto de um dos maiores parques de Roma, este hotel oferece spa com piscina e sauna. É uma escolha sofisticada que equilibra lazer para adultos e áreas adequadas para quem viaja com crianças.
> * **Crowne Plaza Rome - St. Peter's:** Situado próximo ao Vaticano, este hotel refinado possui spa com piscina interna e academia. Oferece uma boa infraestrutura para famílias, incluindo bares e restaurante no local.
> * **The Building Hotel:** Um hotel de luxo que se destaca pela sua arquitetura e comodidades, incluindo piscinas (coberta e externa), piano-bar e um spa completo. É uma opção elegante para quem deseja relaxar após explorar a cidade.
> * **Golden Tulip Rome Piram:** Uma opção mais tranquila e aconchegante, situada perto da estação Termini. Além do spa e sauna, oferece terraço com jardim e uma boa relação custo-benefício para famílias que desejam fácil acesso ao transporte público.
> 
> Lembre-se de verificar a disponibilidade e os serviços específicos para crianças no momento da reserva, pois as políticas podem variar.

---

### 🔹 Prompt 4: Ajuste de Formato e Tom (Intelectual)

**Comando:**
`Transforme isso em um post de blog. Eu quero um parágrafo para cada hotel, destacando os pontos positivos de cada um. Não use listas. Use palavras intelectuais. Finalize com uma chamada para que a pessoa reserve agora mesmo.`

**Resultado:**
> Roma, a Cidade Eterna, transcende a mera categoria de destino turístico para se consolidar como um epicentro de sofisticação e herança histórica, exigindo acomodações que espelhem tamanha magnitude. Ao selecionar o A.Roma Lifestyle Hotel, o viajante imerge em uma atmosfera de contemporaneidade e vanguarda, onde a excelência do serviço se harmoniza com um spa de padrão internacional, proporcionando um refúgio de serenidade urbana ideal para famílias que não abdicam do refinamento estético.
> 
> Para aqueles que buscam uma conexão intrínseca com a natureza sem negligenciar o luxo, o Hotel Villa Pamphili Roma apresenta-se como uma escolha providencial, situando-se nas adjacências de luxuriantes áreas verdes que conferem um respiro bucólico à jornada. Sua infraestrutura de bem-estar, ancorada em uma sauna revigorante e espaços meticulosamente planejados para o acolhimento infantil, estabelece um equilíbrio perfeito entre o repouso contemplativo e a conveniência funcional.
> 
> O Crowne Plaza Rome - St. Peter's evoca uma aura de distinção clássica, oferecendo uma proximidade privilegiada aos marcos sagrados da cidade e assegurando que cada detalhe da estada seja permeado por uma hospitalidade irrepreensível. A suntuosidade de seu complexo aquático e de suas instalações termais constitui um convite irrecusável ao relaxamento profundo, permitindo que adultos e crianças desfrutem de uma experiência de hospitalidade que é, simultaneamente, acolhedora e imponente.
> 
> No The Building Hotel, a arquitetura histórica dialoga com a modernidade em uma simbiose arquitetônica deslumbrante, transformando a hospedagem em uma extensão da própria exploração cultural romana. Este estabelecimento notabiliza-se por sua capacidade de oferecer um entretenimento sofisticado, como seu piano-bar e piscinas de design impecável, garantindo que o lazer em família seja envolto em uma camada extra de exclusividade e deleite sensorial.
> 
> Por fim, o Golden Tulip Rome Piram destaca-se como um bastião de elegância e praticidade, oferecendo um porto seguro de tranquilidade em uma localização estrategicamente central. Seu terraço ajardinado e as terapias de sua sauna providenciam um hiato necessário após as incursões pelas ruínas milenares, consolidando-se como uma opção de hospedagem que valoriza tanto a eficiência logística quanto o bem-estar integral dos seus hóspedes.
> 
> A imensidão cultural de Roma aguarda sua presença para revelar segredos que apenas a vivência presencial pode desvendar. Não postergue a oportunidade de vivenciar o ápice do conforto e da elegância italiana; assegure sua estada e reserve agora mesmo para transformar seu sonho europeu em uma realidade inesquecível.

---

### 🔹 Prompt 5: Ajuste de Formato e Tom (Informal/Gírias)

**Comando:**
`Reescreva o mesmo post, mas agora utilizando uma linguagem extremamente informal, com muitas gírias.`

**Resultado:**
> Fala, galera! Roma é outro nível, né? Mas pra viagem não virar perrengue, tu precisa de um pico responsa pra descançar a beleza. O A.Roma Lifestyle Hotel é puro luxo moderno, sem aquela vibe engravatada chata. O spa dos caras é brabo demais pra dar aquele relax, e o melhor é que eles acolhem a molecada com o maior carinho, então tu pode ficar de boa enquanto os pequenos se divertem.
> 
> Se tu quer mato e sossego sem sair da cidade, o Hotel Villa Pamphili Roma é a tua cara. O bagulho fica do lado de um parque gigante, então o ar é puro e a vibe é relax total. Tem sauna pra tu suar as mágoas e uma estrutura nota dez pros filhos não ficarem entediados, unindo o útil ao agradável naquele pique bem tranquilo.
> 
> O Crowne Plaza Rome - St. Peter's já chega chegando com aquela banca de hotel chique perto do Vaticano. Os caras não brincam em serviço: tem uma piscina interna que é um deboche de tão boa e um spa que vai te deixar renovado pra bater perna nas ruínas no dia seguinte. É aquele lugar que tu entra e já se sente o dono da rua, com tudo que a família tem direito.
> 
> Agora, se tu curte um visual que mistura o antigo com o novo de um jeito bem style, o The Building Hotel é o gabarito. O prédio é lindão, tem um piano-bar pra quem quer pagar de sofisticado e umas piscinas que rendem fotos pesadas pro feed. É o lugar certo pra quem quer ostentar conforto e ainda garantir que a criançada curta cada segundo da trip.
> 
> Pra fechar a lista, o Golden Tulip Rome Piram é o porto seguro perto da confusão da estação central. É aquele esquema: localização estratégica pra não perder tempo e um terraço irado pra trocar uma ideia no final do dia. A sauna deles é o xeque-mate pra fechar o dia com chave de ouro, tudo isso num clima bem família e sem frescura.
> 
> E aí, vai ficar moscando? Roma tá te chamando e esses hotéis lotam num piscar de olhos, hein! Brota lá e faz sua reserva agora mesmo pra garantir o seu lugar nesse paraíso!