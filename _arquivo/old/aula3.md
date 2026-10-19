# Aula 3: Psicologia Cognitiva

Ao entendermos como nós pensamos, também poderemos construir interfaces que agradem a um número maior de usuários. A psicologia Cognitiva é o ramo da Psicologia que trata do modo como os indivíduos percebem, aprendem, lembram e representam as informações que a realidade fornece.  Estudos enfatizam *percepção, pensamento e memória*. 

Muitos dos problemas de interação originam-se da completa falta de compreensão dessa interação. A maioria dos projetos são realizados por engenheiros(as), especialistas na tecnologia mas limitados na sua compreensão sobre as pessoas. Ou seja, em geral pessoas que priorizam a lógica. Tendemos a projetar equipamentos que requerem que pessoas estejam totalmente alertas e atentas por horas, ou que lembrem processos arcaicos e confusos, mesmo que apenas usados esporadicamente. 

Colocamos pessoas em ambientes entediantes com nada para fazer por horas, até que repentinamente tenham que responder rápida e precisamente. Ou as colocamos em ambientes complexos, com alta carga de trabalho, onde são continuamente interrompidas enquanto precisam fazer várias tarefas simultâneas. No fim a gente se pergunta por que ocorrem falhas. Tendo que trabalhar oito horas por dia, com uma interface que não é agradável, como você chegará ao final do dia? As consequências de experiências negativas variam desde pequenos aborrecimentos a gigantescas frustrações. O usuário pode sentir-se diminuído perante os outros e se culpará por não conseguir interagir ou não entender o que todo mundo usa. 

Em outras interfaces de uso mais frequente e profissional, os aborrecimentos e as frustrações podem levar à ansiedade e ao estresse, devido à sequência de experiências negativas, da pressão pela obrigação do uso imposta pela chefia. Em casos mais agudos, o estresse não liberado pode levar a psicopatologias, em um processo pelo qual o usuário apresenta-se inicialmente irritado, deprimido, estúpido com os colegas, mais tarde sente-se perseguido, apresenta dores de cabeça constantes, cólicas abdominais. Em casos extremos, ele pode desenvolver ansiedade generalizada, comportamento compulsivo, crises de pânico.

Pergunte-se: será que os sistemas com os quais você interage na sua rotina podem estar causando esses sentimentos em você?

## Cognição

A cognição é o processo que toma lugar nas nossas mentes quando realizamos qualquer tipo de atividade: pensar, lembrar, aprender, fantasiar, tomar decisões, ver, ler, escrever e falar. 

Don Norman (Design do Dia a Dia) distingue dois modos gerais, ambos essenciais na nossa rotina: cognição **experiencial** e cognição **reflexiva**. O primeiro envolve um estado mental no qual percebemos, agimos e reagimos aos eventos ao nosso redor de maneira eficaz e *sem muito esforço* — dirigir automóveis, ler um livro, conversar, jogar videogame. Já o segundo modo inclui pensar, comparar e tomar decisões, promovendo novas ideias e *criatividade* — projetar, escrever, aprender. Os dois modos de cognição exigem tipos de suporte tecnológico distintos.

Outra forma recentemente popular de classificar cognição vem do Livro *Pensando Rápido e Devagar*, do economista Daniel Kahneman, de 2011. A cognição experiencial corresponde ao pensamento rápido, enquanto o pensamento lento corresponde à cognição reflexiva.

A diferença entre esses dois tipos de cognição fica escancarada ao se comparar a solução de duas operações aritméticas:

*2 + 2=*

*21 x 19=*

Se a primeira é respondida de forma experiencial, a segunda tende a ser respondida de forma reflexiva; bom, talvez nem tanto, porque usaríamos apenas a cognição experiencial para digitar essa segunda operação na calculadora do smartphone. A cognição experiencial inclui-se em processos como atenção, percepção e reconhecimento, memória, aprendizado e leitura, fala e audição, enquanto a cognição reflexiva é mais evidente em processos de resolução de problemas, planejamento, raciocínio e tomada de decisões. Quero, aqui, discutir um pouco como cada processo desses pode ter implicações do design de UI. 


## Processos Cognitivos

Os processos discutidos aqui são interdependentes: vários estão envolvidos em uma determinada atividade - raramente ocorrem isoladamente. Por exemplo, quando você está lendo esse texto, você *percebe* as letras e palavras, usa a *memória* para entender os conceitos, fazendom a *leitura* para encontrar o sentido das frases, talvez exercendo a *tomada de decisão* e a *resolução de problemas*.

### Atenção

Este processo envolve selecionar as coisas em que se concentrar, a partir de um conjunto de alternativas, permitindo o foco na informação que é relevante para o que você está fazendo. O sucesso desse processo depende de (1) o indivíduo ter os objetivos claros, e (2) o destaque da informação necessária no ambiente. 

Para (1), se alguém sabe do que precisa, este tenta casar esse objetivo com a informação disponível. Por exemplo, se você vai no portal UOL depois do jogo do seu time, seus olhos varrem a página procurando pelo escudo do clube e números destacados representando o placar. Por outro lado, se não há um objetivo predefinido, a navegação é mais importante. É só se ver em um restaurante em que você nunca esteve, escolhendo seu prato em um cardápio (hoje em dia, no QR Code, claro).

Para (2), é evidente que o jeito que a informação está mostrada tem grande influência na compreensão dessa informação. Organização, destaque, cores, tudo isso tem grande influência.

Outra questão importante é o efeito da necessidade moderna de sermos *multi-tarefa* no processo de atenção. Existem vários estudos científicos sobre o efeito de múltiplas tarefas simultâneas sobre memória e atenção; em geral, depende da natureza da tarefa e do quanto de atenção ela demanda. Diferenças individuais também são fatores. Você consegue escutar música enquanto estuda? E enquanto lava louça?

Mas resultados sugerem que várias tarefas dificultam o foco. E vivemos em um mundo em que nossa atenção está cada vez mais fragmentada, por vários motivos - o smartphone é o vilão mais citado. Um exemplo: estudantes que estavam interagindo com mensagens demoraram 50% mais tempo para ler e entender um texto, comparados com outros que estavam apenas lendo sem smartphone. Resultados de um mundo multi-tarefa incluem perder fio de raciocínio, cometer erros e necessidade de recomeçar. Os usuários de sistemas estão nesse contexto; design da interação deve levar isso em consideração.

Implicações da limitação de atenção para design de sistemas:
* Informação precisa ser destacada quando ela requer atenção em um dado momento;
* Para isso, usa-se animação, cores, ênfases, ordenação, sequenciamento de informação e espaçamento;
* Evita-se sobrepor muita informação em interfaces visuais - em vez de atenção, distração e irritação.
* Suporte à troca efetiva entre interfaces para multi-tarefa.

### Percepção

Entende-se percepção como a forma de adquirir informação via cinco sentidos (visão, audição, paladar, olfato e tato), transformando-a em experiências com objetos e eventos. Para o design da interação, é importante apresentar informação de forma que seja facilmente percebida da forma como foi projetada. Por exemplo, agrupar itens em conjunto e deixando espaços entre eles pode ajudar a perceber a estrutura da informação. 

Implicações para design de sistemas:
* Ícones e outras representações gráficas devem ser distinguíveis;
* Separadores óbvios e espaços em branco são efetivos em agrupar informação, facilitando identificação e localização;
* Sons devem ser distinguíveis entre si, remetendo a informação correta;
* Contraste de cores para correta identificação;
* Feedback de toque pode ser usado em vários contextos, no entanto devem ser diferenciável.

### Memória

Memória é lembrar de vários tipos de conhecimento, permitindo alguma ação: saber onde está determinado comando no menu, ou saber os comandos Git na linha de comando. Somos afetados pela sobrecarga de informação; nosso cérebro coloca em ação algum mecanismo de filtro para decidir que informação processar e memorizar. Ainda assim, esse filtro acaba falhando - vivenciamos isso quando esquecemos nossa senha do banco no caixa eletrônico, com 10 pessoas na fila esperando por você.

De forma bastante rudimentar, podemos entender o processo como dependente da atenção e da percepção. Quanto mais prestamos atenção em algo, o quanto mais o processarmos em termos de raciocínio, comparando-o com outros conhecimentos, mais provável será nos lembrarmos disso.

Cada vez mais, tendemos a depender da internet e do Smarphone como "apoios cognitivos", algo como uma extensão da mente. Todo mundo hoje tem algum tipo de "sistema de informação pessoal", através de ferramentas de informação. Qual é o seu?

Implicações para design de sistemas:
* Redução da carga cognitiva ao evitar procedimentos longos e complicados;
* A priorização do *reconhecimento* à necessidade de *lembrança*, usando padrões de interação, menus, ícones familiares;
* É bom sempre oferecer modos variados de identificar objetos digitais (cores, nomes, tags, ícones, folders).


### Aprendizado

Bastante relacionado com a memória, aprendizado define a acumulação de habilidades e conhecimento. Sem a memória não há aprendizado, e talvez possamos dizer que sem aprendizado também há pouca memória. Na psicologia cognitiva, o aprendizado acontece de duas formas: incidental ou intencional, de nomes autoexplicativos. No primeiro caso, reconhecimento de rostos, ruas e objetos. Já no segundo, assunto de uma prova, ou a habilidade de cozinhar. Este é bem mais difícil, por isso desenvolvedores de software não podem assumir que usuários vão facilmente  aprender a usar um aplicativo que requer esforço consciente significativo. 

Além disso, as pessoas preferem aprender usando qualquer coisa a ler manuais. Interfaces devem ter o papel de fomentar o aprendizado ativo, dando suporte à interação exploratória e sem medo de cometer erros. Dá pra imaginar sistemas sem Control+Z?

Implicações para design de sistemas:
* Interfaces devem encorajar a exploração;
* Interfaces devem restringir e guiar usuários a selecionar ações apropriadas quando aprendem.


### Ler, ouvir e falar

São as três formas de processamento de linguagem; no entanto, a facilidade com que pessoas as exercem depende do indivíduo, da tarefa e do contexto. Muitas pessoas estão impossibilitadas de ouvir, por isso só podem ler, ou o oposto. Uma interface pode ser baseada em sons, no entanto o sistema poderia ser acessado por um computador com a saída de som quebrada. 

Outros aspectos a considerar: a linguagem escrita é permanente, enquanto o áudio é transiente; reler é fácil, reescutar pode não ser possível. Ler pode ser mais rápido que falar ou ouvir, apesar de que ouvir requer um esforço cognitivo menor. 

Implicações para design de sistemas:
* Menus e recomendações em áudio precisam ser usados de forma limitada;
* É necessário dar a opção de aumentar textos na tela, de uma forma fácil, sem modificar a formatação geral.

### Resolução de problemas, planejamento, raciocínio e tomada de decisão

Aqui incluem-se pensar sobre o que você deve fazer, quais são as opções disponíveis, e quais são as consequências de cada ação. Em geral envolve processos conscientes (cognição reflexiva), discussão (até com você mesmo), e o uso de artefatos adicionais (caneta, mapas, livros, papel).

Teorias mais antigas sobre a tomada de decisão professavam que isso normalmente inclui pesar todos os custos e benefícios das diferentes opções. Empiricamente, a psicologia cognitiva tem mostrado que as pessoas tendem a usar heurísticas simples para decidir - nossa mente evoluiu para tomar decisões rápidas e "suficientemente boas", ignorando boa parte da informação disponível e confiando em algumas poucas pistas. Por exemplo, num supermercado, fazemos julgamentos de compra baseados em marcas reconhecidas ou pelo empacotamento vistoso, sem olhar qualquer outra informação. 

No design, por isso torna-se crítico evidenciar informações chave. Melhor que oferecer muitas informações é projetar intervenções tecnológicas que oferecem pouca informação, da melhor forma, facilitando as decisões positivas. 

Implicações para design de sistemas:
* Oferecer informação e ajuda fáceis de acessar;
* Empregar funções simples e memoráveis para dar suporte à tomada rápida de decisões;
* O usuário deve ter como definir suas próprias preferências e critérios;


## Teorias

Designers e pesquisadores UI/UX acumularam uma riqueza de experiências que acabaram se organizando na forma de um *corpo de conhecimento*, empacotado na forma de teorias. Com elas, podemos aplicar seus preceitos e definir diretrizes com o potencial de se encaixar nas mais variadas situações de interação. 

Teorias tentam explicar e até prever situações na prática, baseadas em conhecimento acerca dos seres humanos e sua psicologia cognitiva. Tipos de teoria são definidos comumente em UI/UX:
* descritivas, estabelecendo terminologias para objetos e ações;
* explicativas, descrevendo sequências de eventos e, quando possível, causa e efeito;
* prescritivas, dando designers diretrizes claras para suas escolhas;
* preditivas, habilitando designers a comparar designs propostos em relação a tempo de execução, taxas de erro e níveis de confiança.

Um exemplo:  é sabido que, se usuários estão tentando achar a demonstração de um pacote de software, um link com o texto "Download Demo" é uma ótima indicação. Essa é uma aplicação da teoria de *Information Scent*, amplamente conhecida por designers web na arquitetura de informações para um site web.

Pode ser bastante difícil digerir a teoria pura, já que a terminologia e a forma de pensar da teoria pode ser desencorajadora para quem não estiver familiarizado. E essa familiarização exigiria um tempo proibitivo na prática. Pesquisadores em IHC tornam então essa teoria mais acessível, traduzindo-a em **conceitos e princípios de design** e **métodos de avaliação**, aplicáveis diretamente, com o objetivo de enfatizar a usabilidade dos sistemas. 


### Um exemplo: Lei de Fitts 

Interfaces modernas nos fazem apontar o tempo todo. Com setas, com dedo, com canetas e outros dispositivos. Pois, por incrível que pareça, existe uma fórmula matemática, conhecida como Lei de Fitts, que define precisamente o grau de dificuldade de completar tarefas que envolvem apontamentos.

Lei: O tempo para atingir um alvo na tela é uma função da distância para ele e o tamanho do alvo. 

Esse conhecimento matemático é usado por designers UI/UX para definir o tamanho e a posição relativa de objetos em uma tela. A Lei de certa forma explica a precisão da ação, já que o tamanho e a distância podem predizer o número de vezes que você vai clicar no lugar errado. Por ela, quanto maior é o objeto, o tempo para selecionar é menor; ao mesmo tempo, o tempo para selecionar diminui se a distância que o usuário precisa deslocar o apontador diminuir. 

## Modelos Mentais

Modelos mentais podem ser usados para refletir e analisar o comportamento dos usuários em relação a produtos tecnológicos. Quanto mais alguém aprende sobre um produto e sobre como ele funciona, melhor se desenvolve seu modelo mental. Veja por exemplo, como as pessoas lidam com poblemas na redes wi-fi, comparando a abordagem de um engenheiro de redes com um indivíduo que só sabe usar o Facebook e o WhatsApp. O primeiro tem um modelo mental muito próximo do real, já que ele entende o modelo usado pelos projetistas da tecnologia wi-fi. Já o segundo sofre para entender por que o sinal aumenta ou diminui, ou por que ele precisa mudar de rede, ou por que o sinal do vizinho pode interferir no dele.

Na psicologia cognitiva, modelos mentais são definidos como construções internas manipuláveis de algum aspecto do mundo externo, permitindo que sejam feitas predições e inferências, muitas vezes através de analogias. 

Considerações para o design: 
* A grande diferença entre os modelos mentais desenvolvidos por usuários novatos e por experientes.
* As diferenças de modelos mentais entre indivíduos, segundo as funções por eles exercidas, de gestão ou de operação, por exemplo. Neste caso, são evidentes as diferenças nas representações mentais de quem opera um sistema assídua e frequentemente, de quem o faz de maneira esporádica ou intermitente;
* Os modelos mentais relativos a uma interface correspondem a um conjunto de conhecimentos semânticos (conceitos) e procedurais (procedimentos) que é particular a cada usuário;
* Os modelos mentais desenvolvidos por projetistas e por usuários se diferenciam grandemente.










