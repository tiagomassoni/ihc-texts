---
title: Conceitos básicos
---

## Componentes de interface humano-computador

A proliferação dos avanços tecnológicos tem incentivado diferentes formas de pensar sobre o design de interação e a experiência do usuário (UX). Por exemplo, a entrada pode ocorrer por meio de mouse, touchpads, canetas, controles remotos, joysticks, leitores de RFID, gestos e até mesmo interações cérebro-computador. A saída é igualmente diversa, aparecendo na forma de interfaces gráficas, fala, realidades mistas, realidades aumentadas, interfaces tangíveis, computação vestível e muito mais.

Nossa conversa sobre interfaces quase sempre cai em *apps* ou *web*. Mas, além dessas, outros tipos foram desenvolvidos, e já fazem parte das nossas vidas, sem trégua: comando de voz, interfaces de toque, reconhecimento de gestos e as chamadas interfaces *multi-modais*. (Por exemplo, um assistente virtual como a Siri da Apple ou a Alexa da Amazon usa uma interface multimodal. Eles podem receber entrada de voz do usuário e fornecer saída não apenas em áudio, mas também por meio de respostas visuais em dispositivos com telas.)

Podemos entender um pouco dos componentes de interface através de uma reflexão histórica sobre a forma predominante de entrada de dados entre os profissionais de TI: a *linha de comando*. As interfaces antigas exigiam que o usuário digitasse comandos que geralmente eram abreviaturas (por exemplo, ls) no símbolo de prompt que aparecia na tela do computador, ao qual o sistema respondia (por exemplo, listando os arquivos atuais). Outra maneira de emitir comandos é pressionando certas combinações de teclas (como Shift+Alt+Ctrl). Alguns comandos também fazem parte fixa do teclado, como delete, enter e undo, enquanto outras teclas de função podem ser programadas pelo usuário como comandos específicos (por exemplo, F11 para comando de impressão).

As interfaces de linha de comando foram amplamente substituídas por interfaces gráficas que incorporavam comandos como menus, ícones, atalhos de teclado e comandos de texto pop-up/previsíveis como parte de um aplicativo. Mas ainda há vantagem em utilizar interfaces de linha de comando, quando os usuários as acham mais fáceis e rápidas de usar do que sistemas baseados em menus equivalentes. Os usuários também preferem interfaces de linha de comando para realizar certas operações como parte de um pacote de software complexo, como em ambientes CAD (como Rhino3D e AutoCAD) e repositórios Git, para permitir que designers especializados interajam rapidamente e com precisão com o software. 
Administradores de sistema, programadoras e usuários avançados frequentemente acham muito mais eficiente usar linguagens de comando como o PowerShell da Microsoft. Por exemplo, é muito mais fácil excluir 10.000 arquivos de uma vez usando um comando do que rolar por esse número de arquivos e destacar aqueles que precisam ser excluídos, não é mesmo?

## Princípios

Dois princípios norteiam o projeto de interfaces com o usuário: **usabilidade** e **acessibilidade**. Eles aparecerão a todo momento nas discussões desta disciplina.

### Usabilidade

Usabilidade confere a produtos interativos características desejáveis, como fáceis de aprender, efetividade de uso, além de serem satisfatórios na perspectiva do usuário. Um sistema *usável otimiza as interações* para a realização de atividades através de um sistema computacional. No livro de Rogers et al., o conceito de usabilidade é partido em seis objetivos:

* Efetividade 
* Eficiência
* Segurança
* Utilidade
* Facilidade de aprender
* Facilidade de memorizar

Alguns outros livros incluem objetivos além, como *desejabilidade* ou *uso prazeroso*, relacionados à necessidade do sistema atrair usuários e se sentirem satisfeitos com a experiência.

Uma forma interessante de avaliar usabilidade se dá através de uma série de perguntas. Essas perguntas acerca da usabilidade podem definir alvos dentro de um projeto de interação, servindo de guia para as atividades de pesquisa, prototipação, solução e avaliação no processo (veremos bem mais sobre isso). Resumo aqui abaixo um pouco mais de explicação sobre os conceitos, junto com perguntas padrão usadas para definir esses objetivos.

*Eficácia* é um objetivo geral e se refere a quão bom um produto é em fazer o que se espera dele. Pergunta: O sistema é capaz de permitir que as pessoas aprendam, realizem seu trabalho de maneira eficiente, acessem as informações de que precisam ou comprem os produtos que desejam?

*Eficiência* se refere ao modo como uma interface dá suporte aos usuários ao realizarem suas tarefas, com um número mínimo de passos. Pergunta: Depois que os usuários aprenderam a usar o sistema, eles conseguem fazê-lo de forma produtiva?

*Segurança* envolve proteger o usuário de condições perigosas ou indesejáveis. Pergunta: Quais tipos de erros são possíveis ao usar o sistema, e que medidas existem para permitir que o usuário consiga se recuperar desses erros?

*Utilidade* se refere ao tipo de funcionalidade que o sistema oferece, e como esta se adequa ao dia-a-dia de quem usa. Pergunta: O sistema oferece um conjunto apropriado de funções que habilitam os usuários a realizar suas tarefas da forma como eles querem ou precisam?

*Facilidade de aprender* liga-se à enorme necessidade de se usar um sistema rapidamente, sem ter que ler um manual de instruções. Pergunta: é possível para quem usa saber como fazer apenas ao explorar a interface e tentar certas ações? Quão difícil seria aprender um conjunto de funções desta forma?

*Facilidade de memorização* se refere à facilidade de lembrar de como usar um sistema, uma vez que seu uso foi compreendido. Pergunta: Qual o suporte dado pela interface para que o usuário lembre facilmente como realizar tarefas, principalmente para funções usadas esporadicamente?

No livro de Steve Krug (Não me faça pensar), o autor argumenta que todos esses objetivos poderiam ser substituídos por uma definição simples e única de usabilidade: "Uma pessoa na média (ou mesmo abaixo dela) será capaz de descobrir como usar o sistema para desempenhar algo sem obter ônus maiores que o bônus."


### Acessibilidade

## Outros conceitos importantes


### Design Centrado no Usuário (UCD)

Hoje, as equipes de desenvolvimento de software têm a noção de que, para atingir altos índices de usabilidade, é importante seguir as diretrizes de um _design centrado no usuário (UCD)_. Essa abordagem coloca o usuário como o foco principal de todo o processo de design. A ideia é entender as necessidades, expectativas e desejos dos usuários desde o início e criar soluções que atendam a essas demandas. Por exemplo, se a gente está desenvolvendo um aplicativo de música, a gente precisa entender os gostos musicais dos usuários, as funcionalidades que eles esperam encontrar e como eles gostariam de interagir com o aplicativo. A partir dessas informações, a gente cria um design que seja realmente útil e agradável para o público-alvo.

E olha só, uma das coisas legais do design centrado no usuário é que ele é _iterativo_. Isso significa que a gente faz testes, recebe feedback dos usuários e faz melhorias constantes ao longo do processo de design. Por exemplo, quando a gente lança um novo aplicativo de mensagens, a gente pede para os usuários experimentarem e nos contar o que eles acharam. Se eles tiverem dificuldades em encontrar os contatos ou enviar mensagens, a gente volta ao processo de design e faz ajustes para tornar a experiência mais fluída e intuitiva.


### UX

A **satisfação** do usuário está relacionada com a sensação de _prazer, contentamento e cumprimento de suas expectativas_ ao interagir com um sistema. Quando você usa o iFood, você quer que a experiência de ter uma refeição acontecendo de forma rápida, sem complicações com o pagamento ou com a entrega. E se ocorreu algo errado com a entrega, você quer ficar satisfeito com a forma como o problema será resolvido através do aplicativo.

O que influencia a nossa satisfação? Vários fatores entram em jogo, como a facilidade de uso do sistema, a eficiência na realização das tarefas, o design atraente e intuitivo, a clareza das informações apresentadas e até mesmo a confiabilidade do sistema. Tudo isso contribui para que a gente se sinta bem ao usar o sistema e tenha uma experiência positiva.

E quando falamos de **experiência do usuário** (UX), estamos falando de um conjunto de elementos que contribuem para uma experiência geral positiva. Além da satisfação, a UX envolve a usabilidade, a estética, as emoções despertadas e até mesmo o contexto em que a interação ocorre. No Spotify, ou em outros aplicativos de música, a interface agradável, os recursos personalizados, a possibilidade de descobrir novas músicas e até mesmo as playlists temáticas contribuem para uma experiência do usuário completa e envolvente. A gente se sente satisfeito ao usar o aplicativo, porque ele nos proporciona momentos de diversão, descoberta e conexão com a música.

Agora, como medir e avaliar a satisfação do usuário e a UX? Existem várias técnicas que podemos utilizar, como pesquisas de satisfação, questionários, entrevistas e até mesmo análise de dados de uso. Por exemplo, a gente pode enviar um questionário aos usuários de um aplicativo de streaming de vídeo, como a Netflix, perguntando sobre a qualidade do serviço, a facilidade de navegação, as sugestões de conteúdo e a satisfação geral. Essas informações nos ajudam a entender o que está funcionando bem e o que pode ser melhorado na experiência do usuário. Também podemos utilizar técnicas de teste de usabilidade, observando os usuários enquanto eles interagem com o sistema e coletando feedback em tempo real. Vamos falar mais sobre essas técnicas ao longo da disciplina.


### Affordance e restrições

**Affordances**! Vocês já ouviram falar disso? É um termo difícil de traduzir. Affordances são aquelas características das interfaces que nos dão dicas sobre como interagir e entender as funcionalidades.

Sabe quando você vê um botão em um aplicativo de música, como o Spotify, com uma seta apontando para a direita? Essa seta é uma affordance, ela nos diz que podemos clicar nesse botão para ir para a próxima música. É como se a interface estivesse nos mostrando uma pista de que ali tem uma funcionalidade que podemos usar. Outro exemplo é o gesto de deslizar o dedo na tela para rolar uma lista. Quando a gente faz esse gesto no Instagram, a gente entende que pode explorar mais conteúdo além do que está visível na tela. Essas são algumas formas de affordances que nos ajudam a entender como interagir com as interfaces.

As affordances precisam estar acompanhadas de **constraints**, que são como regras ou limitações que orientam o comportamento do usuário. Quando você está usando um aplicativo de edição de fotos, como o Snapseed, e tem uma opção de cortar a imagem, você vai ver uma caixa delimitando a área de corte. Essa caixa é uma constraint, ela nos mostra que só podemos cortar a imagem dentro dessa área específica. Assim, a interface nos guia e nos impede de fazer cortes indesejados. Outro exemplo são os botões que mudam de cor ou têm uma animação quando clicamos neles. Isso é uma constraint visual que nos mostra que o clique foi reconhecido e que a ação está em processo.


### Modelo conceitual

A gente tem coisas como **modelos mentais**, que são aquelas representações que a gente cria na nossa cabeça sobre como algo funciona. Pensa no Instagram, por exemplo. Quando você entra no aplicativo, você já sabe intuitivamente que pode rolar a tela pra baixo pra ver mais posts, né? Isso é um exemplo de como a interface foi projetada levando em conta os nossos modelos mentais. 

Podemos também pode usar esses conhecimentos de fatores humanos e psicologia cognitiva pra criar *interfaces específicas pra diferentes grupos de usuários*. Por exemplo, podemos considerar em interfaces adaptadas pra pessoas mais velhas, que podem ter dificuldade com leitura pequena ou botões muito pequenos. Ou então interfaces pensadas pra pessoas com deficiências motoras, que talvez prefiram usar comandos de voz ou gestos em vez de toques na tela. A ideia é criar interfaces que respeitem as habilidades e limitações de cada pessoa, pra que todo mundo possa aproveitar a tecnologia de forma plena e sem barreiras.

Na psicologia cognitiva, modelos mentais são definidos como construções internas manipuláveis de algum aspecto do mundo externo, permitindo que sejam feitas predições e inferências, muitas vezes através de analogias. 

Considerações para o design: 
* A grande diferença entre os modelos mentais desenvolvidos por usuários novatos e por experientes.
* As diferenças de modelos mentais entre indivíduos, segundo as funções por eles exercidas, de gestão ou de operação, por exemplo. Neste caso, são evidentes as diferenças nas representações mentais de quem opera um sistema assídua e frequentemente, de quem o faz de maneira esporádica ou intermitente;
* Os modelos mentais relativos a uma interface correspondem a um conjunto de conhecimentos semânticos (conceitos) e procedurais (procedimentos) que é particular a cada usuário;
* Os modelos mentais desenvolvidos por projetistas e por usuários se diferenciam grandemente.












