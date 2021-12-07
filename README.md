# js


# MODULO 1: INTRODUÇÃO

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

# MODULO 1: OS CONCEITO BÁSICO DE PROGRAMAÇÃO:

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

# O que é compilado e interpretado?

Precisamos converter o nosso código fonte em código de máquina,de alguma maneira antes que ele possa ser executado pelo computador. E há basicamente duas maneiras de se fazer isso: 

- uma é chamada compilar o código fonte;
- e a outra é chamada de interpretar o código fonte. 
 
Felizmente,isso não é uma decisão com a qual você precisa se preocupar nesse momento, a maioria das linguagens caem naturalmente em um, ou outro, mas vale a pena saber quais são as diferenças. 

# Com as linguagens compilada

o código fonte que você escreve precisa ser compiladospara ser executado diretamente no sistema operacional ou no processador. Arquivos .exe, e por exemplo são compilados e rodam sem a necessidade de qualquer outro aplicativo, 

# linguagens interpretadas 

precisam de um aplicativo para interpretar o código fonte,para depois rodar. Um exemplo disso é o arquivo.html, um arquivo.php, que precisam de um browser, um navegador de internet pra rodar o programa. 

Vamos começar com um exemplo simples, você escreve um programa no seu computador e quer que eu execute ele no meu..., 

# usando uma linguagem compilada...

você escreve seu código fonte, passa ele para um outro programa,chamado "compilador ",que lê o seu código fonte, cria um arquivo separado com o código de máquina, você me dá esse arquivo e eu executo ele. 

Esse resultado final geralmente é chamado de um arquivo executável, ou simplesmente executável, pois posso executá-lo diretamente, perceba que eu posso apenas executar o seu programa, você mantém o seu código fonte e eu nunca vejo ele. 

Por outro lado, usando uma ...

# linguagem interpretada..,

você não precisa compilar o seu código fonte antes de me mandar, você simplesmente me dá uma cópia de todo o seu código fonte, e para executar o seu programa, eu preciso de algo no meu computador que vai interpretar o seu código fonte. Veja que um interpretador é diferente de um compilador de código, ele faz a leitura do código em tempo real. 

O interpretador passa pelo seu código fonte linha por linha e o processo sai na hora, ele não salva esse processamento como um arquivo separado de código de máquina, sabia que você já viu linguagens interpretadas, provavelmente várias vezes? Se você já abriu uma página web que contém JavaScript, que é o caso da grande maioria dos sites, você já viu um interpretador em ação. Esse JavaScript já foi baixado da web para o seu computador, juntamente com vários outros arquivos como o HTML e imagens, e o seu browser então interpreta esse JavaScript, para que ele possa executar esse código. 

Mas, qual que é melhor? Bom, cada um tem seus pontos positivos e pontos negativos, vamos começar com os benefícios do...

# código compilado: 

depois de compilado, seu código fonte está pronto para ser executado, você pode enviá-lo para 100, 1000 ou 100000 pessoas diferentes e pronto. E como ele pode ser otimizado para uma CPU específica, ele é potencialmente mais rápido, você não precisa enviar seu código fonte para todos, que também pode ser uma coisa boa. No entanto as desvantagens são: que se eu compilar ele em um pc, ele não vai rodar num Mac e vice-versa. O código fonte geralmente precisa de ser compilado separadamente para cada tipo de CPU, mesmo que seja dentro da mesma plataforma, esse é um passo extra que você precisa tomar, toda vez que quiser testar o seu programa. 

Agora, com o...

# código interpretado:

um dos maiores benefícios é que realmente não importa que tipo de máquina que está do outro lado, porque não fornecemos o código de máquina, nós apenas enviamos o código fonte e deixamos que o outro lado cuide dele. Por isso pode ser mais portátil, mais flexível e roda em múltiplas plataformas, também é um pouco mais fácil de se testar, porque você simplesmente escreve seu código fonte e o executa, deixando que o intérprete se encarregue de convertê-lo em código de máquina, não há um compilador no meio. Outra vantagem é que o código interpretado pode ser mais fácil de depurar, ou debugar quando as coisas dão errado, pois você sempre tem acesso direto a todo o código fonte. Por outro lado, tem alguns aspectos negativos: quem quiser executar esse programa, precisa ter o intérprete para essa linguagem em seu computador, ele também pode ser um pouco mais lento. Você precisa interpretar o código-fonte toda vez que o programa é executado, o código fonte também é efetivamente público, qualquer um pode ver como que você escreveu seu programa. 

Agora, como temos coisas boas tanto nas linguagens compiladas quanto nas linguagens interpretadas, temos uma terceira maneira de fazer as coisas, que é com um pouco de cada um. 

Pra começar, compilamos nosso código fonte só até um determinado ponto, é o que chamamos de uma linguagem intermediária, isso nos coloca o mais próximo possível do código de máquina, mas mantemos o código fonte portátil entre diferentes plataformas. 

Você então distribui esse código na linguagem intermediária, envia para as pessoas que precisam executá-lo e ao executar o código, o último passo é dado para chegar ao nível do código de máquina, isso geralmente é chamado de "Compilação just-in-time", ou na hora certa. 

Essa linguagem intermediária também atende pelo nome "Byte Code", a questão é: quanto disso acontece na sua máquina e quanto disso acontece na minha? Teoricamente, qualquer uma das linguagens de programação pode usar um desses métodos, mas geralmente cada linguagem utiliza um ou outro, 

por exemplo:

"C", "C++", "Swift" são linguagens compiladas, então eles requerem um compilador, e esse compilador pode ser baixado gratuitamente e muitas vezes já são integrados no ambiente de desenvolvimento, agora linguagens como: "PHP", "JavaScript", e a maioria das linguagens com a palavra Script no final, são interpretadas. 

Linguagens como: 

"Java", "C#", "VB.NET", "Python", usam essa abordagem híbrida ou intermediária, o fato de uma linguagem ser compilada, interpretada ou estar no meio do caminho, raramente é motivo principal para ser escolhida, mas pode ser algo que você leve em conta na hora de decidir qual linguagem usar. 

# Se a prioridade absoluta de seu programa for velocidade...
máxima em tempo de execução e para uma única plataforma, você provavelmente vai decidir por uma linguagem compilada,...

# se o seu maior interesse for executar facilmente seu código em várias plataformas...,
é provável que você vá decidir por uma linguagem interpretada, e se você for criar um webside dinâmico, ou como o nosso caso, aprender os básicos da programação, você vai usar uma linguagem interpretada. 

De novo, a tarefa ou o programa final, vai determinar se você vai usar uma linguagem "compilada", "interpretada", ou uma linguagem "híbrida".

# Teste do Capitulo:

Pergunta 2 de 7
# Todos os computadores utilizam o __

- C++

- código binário

- Java

- código de máquina (x)
Correta
Todas as linguagens de programação são eventualmente transformadas em código de máquina.

Pergunta 2 de 7
# Quanto mais próxima uma linguagem de programação for do código de máquina, mais difícil é de escrever.

- VERDADEIRO (x)
Correta
Quanto mais próxima uma linguagem de programação for do código de máquina, mais difícil é de escrever.

- FALSO

Pergunta 3 de 7
# O código fonte de todas as linguagens de programação é escrito usando _

- Evernote

- texto simples(x)
Correta
O código fonte de todas as linguagens de programação é escrito usando texto simples.

- texto com formatação

- NotePad

Pergunta 4 de 7
# O que é verdadeiro sobre as linguagens de programação de alto nível? 

- Você se preocupa menos com o hardware e o código fonte é mais legível
Correta (x)
Você se preocupa menos com o hardware e o código fonte é mais legível.

- O código é mais difícil de escrever do que o código de linguagens de baixo nível.

- Você precisa comprar programas adicionais para poder treinar. 

- Você precisa saber muito sobre o hardwared.

Pergunta 5 de 7
# Verificação de __ te informa se algo está errado no seu código enquanto você digita.

- ortografia

- terminologia

- sintaxe (x)
Correta
Verificação de sintaxe te informa se algo está errado no seu código enquanto você digita.

- estrutura
- 
Pergunta 6 de 7
# Código interpretado tem a seguinte desvantagem: 

- o código fonte é público - qualquer um consegue ver.

- precisa ser interpretado separadamente para cada tipo de CPU. (x)
Correta
O fato do código fonte precisar ser interpretado separadamente para cada tipo de CPU não é uma desvantagem, mas sim o que possibilita ele rodar em diferentes máquinas.

- qualquer pessoa que tiver o interpretador consegue rodar o código.

- o código pode rodar mais lentamente pois ele tem de ser interpretado cada vez que ele roda.

Pergunta 7 de 7
O JavaScript…

- é uma linguagem interpretada.(x)
Correta
O JavaScript  é uma linguagem interpretada.


- é usada para criar aplicativos para o desktop.

- é a mesma coisa que o Java.

- é baseado no ActionScript.

# MODULO 2: SINTAXE FUNDAMENTAL

# Por que usar o JavaScrip?

Nesse curso vamos usar o JavaScript como a nossa linguagem de programação, existem várias outras linguagens que poderíamos usar, mas com o JavaScript você não precisa instalar nada no seu computador, além de rodar em qualquer plataforma. 

- É uma linguagem amigável para iniciantes e 
- sem grandes limitações, 
- ela é popular e relevante, 
- além de ser fácil para explorar os conceitos básicos da programação, 
- foi inventado para criar e manipular páginas web. 

Isso significa que o JavaScript é uma linguagem:

- especializada e intencionalmente limitada, 
- a gente não usaria o JavaScript para escrever um aplicativo de desktop, ou um aplicativo para o seu celular, por exemplo. 

Em vez a gente usaria uma linguagem compilada, como: C++, o Java, C# ou Swift. Embora eles tenham nomes parecidos, 

- o Java e o JavaScript são linguagens completamente diferentes, e não são relacionadas de nenhuma maneira significativa. 
- Embora o JavaScript seja uma linguagem de programação, ele também é chamado de uma linguagem de "scripting",...
 
linguagens de scripting são linguagens de programação mais limitadas e embutidas em algum outro programa,... 

- o JavaScript funciona somente dentro de um outro aplicativo, o seu browser. 

Independente de qual você use, o Internet Explorer, o Microsoft Edge, o Safari, Firefox, Chrome ou Opera, todos eles têm um interpretador de JavaScript dentro deles, o JavaScript portanto, como na maioria das linguagens de script...

- é uma linguagem "interpretada". 
- Não precisamos manualmente compilar o código fonte em código de máquina,...
- isso será feito automaticamente pelo browser...
 
quando ele for executado dentro de uma página web. 

# Por que usar o JavaScrip? > Como funciona? 

.Compilação automática > Sistem Operacional > Browser (Navegador)> Pagina Web(HTML) > JavaScript (Codigo Fonte).

- 1. O sistema operacional roda o browser, 
- 2. o browser por sua vez abre uma página web, 
- 3. e em seguida chama e roda o nosso Javascript. 

Um detalhe muito importante é que JavaScript é uma linguagem que diferencia entre maiúsculas e minúsculas, para você que é novo na programação, não tem como enfatizar o suficiente de quanto isso é importante. 

Vamos analisar essas duas linhas de código JavaScript aqui como exemplo, 

document.getElementById("exemplo").style.display = "none";

document.getElementByID("exemplo").style.display = "none";

...não se preocupe com o que essas linhas fazem efetivamente, apenas saiba que uma delas está certa e a outra está errada. Temos aqui a palavra "Id", com o d minúsculo, e a outra com D maiúsculo. 

Esse é o nível de detalhe entre maiúscula e minúsculo que devemos prestar atenção quando usamos a grande maioria das linguagens, mesmo que você tiver usando uma linguagem que não diferencia entre maiúsculas e minúsculas, é recomendado que você entre no hábito de prestar muita atenção nisso, pois uma dessas funções vai funcionar e a outra não. 

Vamos então dar uma olhada no Javascript, de novo, não se preocupe agora com o que cada linha faz, quando vemos qualquer linguagem em programação com chaves, linhas terminando com ponto e vírgula e alguns outros detalhes que vamos explorar em breve, podemos deduzir que estamos lidando com uma linguagem que foi influenciada pela linguagem de programação chamada: "C". O "C" existe desde o início dos anos 70 e influenciou aparência de muitas linguagens mais populares que usamos hoje em dia.

Alguns até compartilham o nome: C++ e o C#, e outros como o Swift não. Outro exemplo é o Java, o Java é uma linguagem com estilo do C,assim como Actionscript e o Javascript, e conhecer uma linguagem do estilos C, facilita muito quando for aprender outras linguagens de programação. 

# Por que usar o JavaScrip? > Conclusão: 

JavaScript é uma linguagem que diferencia entre maiúsculas e minúsculas, é uma linguagem interpretada, baseada no C, altamente relevante e muito amigável para iniciantes.

# Introdução ao primeiro programa

Para criar uma página web, a gente não precisa se preocupar com sites, servidores, imagens ou outros arquivos. 

- A gente só precisa de uma única página web simples. Um arquivo HTML, cujo único motivo de existir é chamar nosso JavaScript e fazer ele rodar. 

Eu crio uma pasta com dois arquivos de texto simples...

- container.html
- script.js

...um para o HTML e outro para o Javascript, não importa a primeira parte do nome, o importante é o ponto HTML, a extensão do arquivo. 

A extensão indica para o sistema operacional, qual o programa deve ser usado quando a gente abrir esse arquivo, no caso do ponto HTML, o sistema operacional abre o browser padrão do seu computador, seja ele qual for. 

No arquivo "Container. html" temos uma página web, em HTML, mas muito simples. 

<html>
  <head>
        <meta charset="UTF-8">
  </head>
  <body>
    <p>Uma página simples de internet</p>
    <scritp src="script.js"></script>
  </body>
</html>

Eu não quero entrar em detalhes, mas basicamente existem essas demarcações que indicam ao browser aonde começam e onde terminam os blocos de informação, eles informam que deve ser exibido na tela e chama o nosso código fonte. 

o HTML, na verdade é um tipo de código bem diferente,...

- e não é uma linguagem de programação, 
- é uma linguagem de marcar app ou de marcação. A própria sigla diz isso: Hyper Text Markup Language; linguagem de marcação de hipertexto. 
- Descreve a página web
 
Agora isso pode soar como um detalhe extremo, mas há uma diferença muito grande. 

O HTML escreve uma página web, a sua estrutura, o título, o cabeçalho, imagens, parágrafo e textos, infelizmente a gente não tem tempo suficiente nesse curso para entrar nos detalhes do HTML. 

Eu só vou mostrar por que que a gente precisa desse arquivo, e é por causa desta linha aqui: 

<script src="script.js"></script>

É assim que indicamos ao browser, aonde está o nosso código fonte em Javascript, no arquivo chamado script.js, que é onde fica o nosso código fonte, nele temos a nossa primeira instrução, o clássico: 

alert("Ola mundo!");

olá mundo, sempre usado quando estamos aprendendo uma nova linguagem de programação. O browser vai ler essa linha e encontrar a palavra alert, alerta; que é um comando do Javascript, que exibe um alerta com um texto para o usuário, aí temos os parênteses, que criam um contêiner para o texto, que tem o seu próprio contêiner: as aspas. Enfim, vamos ver isso na prática.

# O primeiro programa na prática

Abrir a pasta do exercicios 'Capitulo_2/02_03' vamos encontrar os seguintes arquivos: container.html, script.js

Abre os arquivos e analise o codigo!
Faça alteração apenas na linha 'aler("Olá mundo!"); .Altere a expressão "Olá mundo"! e atualize seu codigo e veja as alterações em tempo real.

# Requisitando informações

todo tip











