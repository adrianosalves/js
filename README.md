# js


# INTRODUÇÃO

# Quer aprender a programar?

Quando você selecionar uma linha na transcrição, será direcionado à seção equivalente no vídeo
Você quer mergulhar no mundo da programação e não sabe por onde começar? 

Programar não é um bicho de sete cabeças. Também não é, necessariamente, uma coisa só para quem gosta de matemática. Programar é como aprender um novo idioma, que te abre portas para a criatividade, a produção de aplicativos ou sistemas e para o empreendedorismo de modo geral. 

Neste curso vamos explorar as ideias centrais e as noções básicas da programação necessárias para desenvolver código ou software para qualquer plataforma, em qualquer linguagem. Existem várias linguagens para uma ação e nesse curso vamos dar já o script, e também dar uma olhada no C, Ruby, Swift e Phyton. 

Vamos ver no que cada uma delas é boa e por que você escolheria uma sobre a outra, mas não vou tentar te tornar um expert em nenhuma delas, pelo contrário. Nesse curso vamos ver o que todas essas linguagens tem em comum. vamos falar sobre loops, condicionais, variáveis, memória... vamos entender como controlar a estrutura e os procedimentos de um programa, vamos também ver o que precisa saber sobre o que acontece por trás das cenas de um programa. Bem-vindo e vamos lá!

# O que deveria saber

O que eu tenho é uma lista de três coisas que não me importam. Não me importa se você nunca programou na vida, estamos começando do zero aqui; se você não tem ideia por onde começar a programar, esse curso é para você. 

Agora, se você já tem algumas noções de programação, ótimo. Talvez você já tenha escrito algumas linhas de código, lido alguns livros, aprendeu um pouco sozinho mas ainda não se sente totalmente confortável com os básicos; esse curso também é para você. Não me importa se você usa o MAC, PC ou Linux, não faz diferença nesse curso. 

Espero que você, pelo menos, saiba mexer no seu computador. Não me importo com a sua profissão, especialização ou idade. Já ensinei programação para engenheiros, professores de inglês, artistas e médicos; já tive alguns alunos com menos de 10 anos de idade e alunos bem além da idade de se aposentar. 

Algumas dicas para aproveitar o curso: não se preocupe em fazer tudo perfeito, entender tudo ou memorizar tudo de uma vez, se você tiver entendendo 80% das coisas, ótimo, siga em frente. Programação é um assunto denso mas muito interessante e recompensa quem pratica frequentemente, veja e reveja esse curso, mesmo que você tenha entendido tudo 100%, faça os exercícios novamente daqui a 3, 6 ou até mesmo daqui a um ano. 

E, não querendo ser óbvio, você pode sempre voltar esses vídeos, caso não tenha entendido algum conceito. Eu garanto que você vai encontrar um novo significado em algumas coisas e outras para prestar mais atenção. 

Saber programar é uma habilidade poderosa, não somente útil, boa para sua carreira e uma fonte de dinheiro, ela te capacita a criar. Objetivo desse curso é tornar você um criador de software, de programas e não somente um usuário. Vamos lá?

# Arquivos de Exercício

Se você quiser acompanhar tudo o que eu faço nesse curso, basta baixar o "Arquivo de Exercício.zip", eu já extraí os arquivos do zip, aqui nesse arquivo de exercício. 

E a gente vai ver quedentro dela está tudo organizado por capítulo. Dentro do capítulo, está organizado por vídeo e dentro do vídeo, eu tenho dois arquivos. O "container.html" é uma página na web que, por sua vez, aponta para nosso "script.js". Só por curiosidade, vamos ver que está dentro desse "container.html". 

Esse é o código fonte dessa página, veja que ele está apontando para o "script.js", e vamos dar uma olhada no que tem dentro desse arquivo. E aqui está o código fonte do script. Eu não espero que você entenda nada disso ainda mas, no final do curso, eu tenho certeza que você vai saber exatamente o que isso está fazendo. Vamos lá?

# OS CONCEITO BÁSICO DE PROGRAMAÇÃO:

# O que é programação?

O que exatamente é a programação? Você já deve ter ouvido algo como "um programa de computador é uma lista de instruções" Mas existe um pequeno problema: embora tecnicamente correta, essa definição é basicamente inútil. 

É a mesma coisa que eu dizer que o cérebro humano é 80% água, interessante mas que que eu faço com essa informação? Fica difícil de acreditar que um programa de computador complexo como o Photoshop foi feito simplesmente com uma lista de instruções, mas é exatamente isso. 

Todo programa de computador é uma lista de instruções, uma sequência de pequenos comandos individuais um depois do outro. Um programa pode ter uma lista de 5, 5.000 ou até mesmo 5 milhões de instruções. Cada instrução manda o computador fazer uma tarefa pequena e muito específica. 

A arte de programar é conseguir pegar uma idea e reduzir ela nesses passos individuais. A gente já faz isso todos os dias, vamos pegar um exemplo simples: como dar direções para o teu amigo, que não tem o GPS, para chegar na sua casa. 

Você nem pensa quando faz essa rota no seu dia a dia mas se você tem que explicar para alguém, você para e pensa um pouco, não é mesmo? Você precisa desmembrar a rota em suas partes individuais, então, você começa lá no início. Siga por 100m e vire a direita. Na Avenida Rebouças, vire a esquerda. Entre na segunda rua a direita e, no final da rua, a minha casa é azul. A sequência e precisão dessas informações é essencial. O que acontece se mudarmos a sequência? Vire a direita e siga por 1km te leva para um lugar bem diferente do que se eu disser siga por 1km e vire a direita. Ou seja, mesmo que só temos instruções muito básicas, como virar a direita, virar a esquerda e seguindo em frente, você pode mandar seu amigo para porta da padaria, em vez da porta sua casa, tudo isso com instruções simples, como as de virar a direita, e esquerda e seguir em frente. Você só vai precisar repetir isso muitas vezes. E é isso que é a programação, é dar direções para o computador, é separar uma tarefa complexa em pequenas partes individuais usando uma linguagem.

Agora, se você nunca programou, você deve estar se perguntando: "quais são essas instruções exatamente? O que que eu posso falar para o computador fazer? Certamente não é vire a direita, vire a esquerda, então, o que que são essas instruções?" Algumas delas são realmente muito básicas, como operações matemáticas, exibir uma letra na tela, verificar se o mouse foi clicado ou mudar a cor de um pixel individual na tela, por exemplo. Programar é como as direções para o teu amigo. Se você colocar instruções suficientes em sequência, você pode ir bem longe. Agora, no começo talvez seja difícil entender como os exemplos básicos que a gente vai ver podem se tornar em um programa complexo, como um jogo ou um aplicativo de celular. Esses programas, geralmente, foram feitos por centenas de programadores, escrevendo instruções por horas por dia, durante meses ou até anos. Em cima disso, temos o computador que processa as instruções em uma velocidade tão alta que conseguimos controlar a cor de cada um dos milhões de pixels na sua tela, 30 vezes por segundo. Com essa velocidade, dá para entender porque as suas instruções tem que estar certas. Imagine que o carro do seu amigo tenha só duas velocidades: 0 ou 5000km/h. De repente, vire a direita e siga por 1km fique ainda mais diferente do que siga por 1km e vire a direita. Os computadores farão exatamente tudo aquilo que você disser, portanto, de novo, as instruções tem que fazer sentido. 

Essas instruções, nas linguagens de programação, são chamadas de declarações. São como frases de palavras em inglês que em conjunto com pontuação, números, expressam um conceito, descrevem um item e direcionam a lógica do seu programa. 

A maioria dessas declarações são bem curtas, só algumas palavras. Agora, exatamente quais palavras, números ou pontuações que você usa depende da linguagem programação. 

Algumas linguagens exigem que você coloque um ; depois de cada declaração, como se fosse um ponto final. Outras não. 

Algumas linguagens são todas em letras maiúsculas, algumas são todas em minúsculas e outras não se importam. Entender as regras de cada linguagem é entender a sintaxe da linguagem de programação. Portanto, programação é a capacidade de pegar uma ideia da tua cabeça, separá-la em tarefas individuais e criar um passo a passo do que precisa acontecer para executar a sua ideia. 

A programação é saber escrever essas tarefas na linguagem de programação que você está usando, construindo as declarações na ordem correta e usando a sintaxe apropriada. Mas qual linguagem que eu devo usar? Bom, algumas vezes você escolhe a linguagem, outras vezes ela te escolhe; depende da necessidade do projeto.

# O que é linguagem?

Desde o início da computação, centenas de linguagens de programação foram criadas. Mas em qualquer dado momento, vamos ver que somente umas duas ou mais são realmente populares. 

E por popular eu quero dizer que é uma linguagem usada para fazer grande parte dos programas, por um número grande de programadores e existe uma comunidade ativa e um mercado de trabalho significativo. Com o passar dos anos, algumas delas aumentam e outras diminuem em popularidade. 

E, às vezes, novas linguagens são criadas, algumas são um grande sucesso mas a maioria não. Essa lista muda mas muda lentamente. 

A maioria dos programadores vai usar diversas linguagens ao longo de sua carreira, mas não se assuste com isso, pois uma vez que você aprendeu os básicos, aprender outras linguagens fica cada vez mais fácil. 

Mas você deve estar se perguntando: 

"por que existem tantas linguagens? 
Não estamos escrevendo instruções simples para o computador? 
Por que que não existe uma única linguagem de programação?" 

Bem, na verdade, essa linguagem existe mas não é nenhuma dessas que estamos falando. No cérebro de qualquer computador, desktop, laptop, servidor, celular, console de jogos, existe um chip, a CPU, a central de processamento único. 

Esse chip não entende nenhuma dessas linguagens, a única coisa que o chip entende é o machine language, ou código de máquina. Essas instruções são as que efetivamente são executadas diretamente no hardware do seu computador. A questão é: por que não escrevemos as instruções diretamente na linguagem de máquina? Bem, isso é praticamente impossível de se fazer. 

Além de ser em sequências de 1 e 0, são operações numéricas, instruções minúsculas que funcionam nas menores partes de memória do seu computador. Mesmo que você conseguisse escrever nessa linguagem, ela seria basicamente ilegível por qualquer outra pessoa. Essas instruções são exclusivas para um computador e não para o ser humano. 

Em cima disso, o código de máquina funciona no nível da CPU, então, cada modelo, marca de CPU tem uma linguagem diferente das outras. Ou seja, escrever um programa inteiro em código de máquina seria como cavar um túnel com uma colher de chá, é teoricamente possível mas levaria tanto tempo e seria tão tedioso que você nunca tentaria. Todas as linguagens de programação são, de fato, um meio termo. São linguagens inventadas e elas basicamente criam a ponte entre nós, seres humanos, e o hardware do computador. 

Algumas das linguagens, porém, tão bem mais próximas do código de máquina; o mais próximo é algo conhecido como Assembly Language, ou linguagem de montagem. E, em geral, quanto mais próximo a linguagem estiver do código de máquina mais difícil é de se escrever, além de ter que saber muito mais sobre o hardware que está rolando o programa. 

Isso é o que chamamos de uma linguagem de baixo nível. E na medida em que você se afasta da CPU, em direção às linguagens de alto nível, você se preocupa cada vez menos com hardware. Esses códigos, geralmente, é mais fácil de escrever e compartilhar, mesmo entre diferentes plataformas, mas pode ser mais lento na execução pois essas linguagens não são necessariamente otimizadas a uma CPU específica, por exemplo. Dito isso, hoje em dia, essas diferenças de velocidade são mínimas e, portanto, vamos nos concentrar nas linguagens de alto nível nesse curso. 

Agora, independente da linguagem que usamos para escrever nossas instruções, elas têm que ser convertidas em código de máquina antes que elas possam ser executadas. Agora, embora esse tal código de máquina pareça ser a peça mais importante do quebra-cabeça, não estamos interessados nela. Claro que precisamos saber como é que isso funciona mas programar, para gente, é lidar com código-fonte. O código-fonte é o que chamamos as declarações que escrevemos em alguma linguagem de alto nível. A gente escreve esse código-fonte que, em algum momento, ele vai ser traduzido em código de máquina para que ele possa ser executado no computador. Repare que quando eu digo que estou programando, eu estou escrevendo essas instruções, estou criando o código-fonte, tudo a mesma coisa. 

Então, para começar a escrever ou programar em qualquer uma dessas linguagens, precisamos entender três coisas: 

- como escrever esse código - literalmente, 
- aonde que a gente começa a digitar?-; a gente precisa entender como que esse código-fonte vai ser convertido em código de máquina e como que a gente executa esse código, 
- aonde que a gente roda esse programa. 

Parte disso depende da linguagem que a gente escolher, mas vamos começar vendo como realmente escrever essas declarações.

# O que é codigo fonte?

O código-fonte das linguagens de programação são escritos em texto puro e simples. Você pode usar o editor de texto que vem com o seu sistema operacional, como o Notepad no PC ou TextEdit no Mac, que fazem a mesma coisa: editam arquivos de texto simples. Eles funcionam para escrever para qualquer linguagem de programação, não é nada mágico sobre o código-fonte em si, é só texto. Sim, é texto simples, não é Rich Text ou texto com formatação. Por exemplo, esse é um editor de texto com um pouco de JavaScript; aqui, um outro com Perl, e esse outro com Ruby e aqui com Groovy. Sim, Groovy é uma linguagem de programação. Mas não se preocupe em tentar memorizar nada disso, é como ver extensões de arquivos diferentes, como o.js para JavaScript e.groovy para o Groovy, mas elas não tem nada de diferente que um arquivo de texto normal, .txt. O que você não quer é um processador de texto como o Word. Se você está escrevendo seu código-fonte em um programa que tem uma barra de formatação com opções de negrito, itálico, por exemplo, provavelmente você está no lugar errado. O código-fonte de linguagens de programação não precisam ter texto em negrito, sublinhado, itálico ou justificado. Agora, um programa não precisa ter muito mais do que isso. São programas considerados muito simples mas, tecnicamente falando, são programas completos, eles contém apenas uma instrução, uma instrução que exibe as palavras "Olá Mundo" na tela. Este aqui é um programa com apenas uma instrução, escrito em uma linguagem chamada Algol 68. Sim, 68 quer dizer 1968, o ano em que essa linguagem foi lançada. O Algol 68 não é uma linguagem que você precisará saber mas, por outro lado, talvez você queira conhecer o Python. E aqui está um programa com apenas uma instrução, escrito em Python 3, lançado em dezembro de 2008. E esse é um programa de uma instrução escrito em uma linguagem chamada Lua. E, sim, nesse caso específico, a declaração é exatamente igual nessas linguagens e, na verdade, em várias outras linguagens também. Muitas linguagens compartilham uma história comum, elas são bem mais parecidas do que diferentes. Agora, só porque as declarações são as mesmas nessas linguagens não significa que essas linguagens sejam idênticas. Agora, algumas linguagens precisam de um pouco mais que uma simples declaração para ser considerado um programa completo, muitas linguagens gostam de ter explicitados os pontos iniciais e finais do programa, por exemplo. Uma versão mais antiga do Algol, o Algol 60, foi escrita inteiramente em letras maiúsculas e exigia as palavras begin e end, início e fim, para marcar o início e o fim do programa. Idiomas como C e outras linguagens baseadas no C, como o C#, C++ e Java, requerem uma quantidade inicialmente intimidadora de {, [ e outras palavras-chaves esotéricas e estranhas para fazer com que algo muito simples, como exibir as palavras "Olá mundo" na tela. Agora, você se pergunta: "eu tenho que me lembrar de tudo isso para escrever um simples programa?" Na verdade, não. Não é porque é possível programar com editor de texto simples que essa seja a melhor maneira de você trabalhar; existem aplicativos que te ajudam a escrever o código-fonte e facilitam muito a sua vida. Para começar, temos alguns editores de texto para programadores, esses são editores de textos simples mas com alguns recursos extras. Existem vários assim que, inclusive, estão disponíveis em todas as plataformas, alguns são gratuitos e alguns são pagos. Mas, em geral, esses programas incluem algumas funcionalidades simples, como numeração de linhas e busca e substituição mais poderosas. Ele, geralmente, também tem codificação de cores mas repare que isso não é mesma coisa que formatação de texto; a codificação de cores acontece automaticamente e te ajuda a ler e reconhecer diferentes partes da linguagem. Além disso, esse programa geralmente também tem verificação de sintaxe, que é como a verificação ortográfica de um processador de texto. A verificação de sintaxe te mostra, por exemplo, quando algo está errado com seu código ao mesmo tempo que você está digitando. Alguns desses editores de texto dão suporte para várias linguagens além de rodar em múltiplas plataformas, como é o caso do Visual Studio Code da Microsoft. Outros são orientados para uma linguagem e plataforma específica, como o Xcode, usado para criar aplicativos para o ecossistema da Apple. Nesses casos, podemos chamar esses editores de texto de Ambientes de Desenvolvimento Integrados, ou IDS, Integrated Development Environment. As IDS são programas maiores que incluem um bom editor de texto para programadores mas geralmente tem, também, um monte de recurso para programação profissional. Mas nesse curso não vamos nos preocupar com as IDS, você vai usar um deles quando começar a se concentrar em uma área específica de programação. Ou seja, embora você não precise de um programa especial para escrever seu código no momento, você provavelmente vai acabar querendo um.



