---
title: Limitações cognitivas
css: '/assets/css/custom-styles.css'
---

Imagine-se criando um aplicativo de entrega de comida. Se você compreende que as pessoas têm habilidades diferentes, como pessoas com deficiências visuais ou motoras, a gente pode criar uma interface que seja acessível pra todo mundo. É possível considerar opções de contraste, tamanhos de fonte ajustáveis e até mesmo leitores de tela que leiam o conteúdo pro usuário. Assim, a gente garante que todos possam usar o aplicativo de forma fácil e inclusiva.
Quando a gente fala de fatores humanos, estamos falando de como as _características e habilidades das pessoas influenciam a interação com os computadores_.

A psicologia Cognitiva é o ramo da Psicologia que trata do modo como os indivíduos percebem, aprendem, lembram e representam as informações que a realidade fornece. Estudos enfatizam _percepção, pensamento e memória_.
A cognição é o processo que toma lugar nas nossas mentes quando realizamos qualquer tipo de atividade: pensar, lembrar, aprender, fantasiar, tomar decisões, ver, ler, escrever e falar.

Vamos discutir aqui alguns processos cognitivos. Vários estão envolvidos em uma determinada atividade - raramente ocorrem isoladamente. Por exemplo, quando você está lendo esse texto, você _percebe_ as letras e palavras, usa a _memória_ para entender os conceitos, fazendom a _leitura_ para encontrar o sentido das frases, talvez exercendo a _tomada de decisão_ e a _resolução de problemas_.

**Atenção**

Este processo envolve selecionar as coisas em que se concentrar, a partir de um conjunto de alternativas, permitindo o foco na informação que é relevante para o que você está fazendo. O sucesso desse processo depende de (1) o indivíduo ter os objetivos claros, e (2) o destaque da informação necessária no ambiente.

Para (1), se alguém sabe do que precisa, este tenta casar esse objetivo com a informação disponível. Por exemplo, se você vai no portal UOL depois do jogo do seu time, seus olhos varrem a página procurando pelo escudo do clube e números destacados representando o placar. Por outro lado, se não há um objetivo predefinido, a navegação é mais importante. É só se ver em um restaurante em que você nunca esteve, escolhendo seu prato em um cardápio (hoje em dia, no QR Code, claro).

Para (2), é evidente que o jeito que a informação está mostrada tem grande influência na compreensão dessa informação. Organização, destaque, cores, tudo isso tem grande influência.

Outra questão importante é o efeito da necessidade moderna de sermos _multi-tarefa_ no processo de atenção. Existem vários estudos científicos sobre o efeito de múltiplas tarefas simultâneas sobre memória e atenção; em geral, depende da natureza da tarefa e do quanto de atenção ela demanda. Diferenças individuais também são fatores. Você consegue escutar música enquanto estuda? E enquanto lava louça?

Mas resultados sugerem que várias tarefas dificultam o foco. E vivemos em um mundo em que nossa atenção está cada vez mais fragmentada, por vários motivos - o smartphone é o vilão mais citado. Um exemplo: estudantes que estavam interagindo com mensagens demoraram 50% mais tempo para ler e entender um texto, comparados com outros que estavam apenas lendo sem smartphone. Resultados de um mundo multi-tarefa incluem perder fio de raciocínio, cometer erros e necessidade de recomeçar. Os usuários de sistemas estão nesse contexto; design da interação deve levar isso em consideração.

Implicações da limitação de atenção para design de sistemas:

- Informação precisa ser destacada quando ela requer atenção em um dado momento;
- Para isso, usa-se animação, cores, ênfases, ordenação, sequenciamento de informação e espaçamento;
- Evita-se sobrepor muita informação em interfaces visuais - em vez de atenção, distração e irritação.
- Suporte à troca efetiva entre interfaces para multi-tarefa.

**Percepção**

Entende-se percepção como a forma de adquirir informação via cinco sentidos (visão, audição, paladar, olfato e tato), transformando-a em experiências com objetos e eventos. Para o design da interação, é importante apresentar informação de forma que seja facilmente percebida da forma como foi projetada. Por exemplo, agrupar itens em conjunto e deixando espaços entre eles pode ajudar a perceber a estrutura da informação.

Implicações para design de sistemas:

- Ícones e outras representações gráficas devem ser distinguíveis;
- Separadores óbvios e espaços em branco são efetivos em agrupar informação, facilitando identificação e localização;
- Sons devem ser distinguíveis entre si, remetendo a informação correta;
- Contraste de cores para correta identificação;
- Feedback de toque pode ser usado em vários contextos, no entanto devem ser diferenciável.

**Memória**

Memória é lembrar de vários tipos de conhecimento, permitindo alguma ação: saber onde está determinado comando no menu, ou saber os comandos Git na linha de comando. Somos afetados pela sobrecarga de informação; nosso cérebro coloca em ação algum mecanismo de filtro para decidir que informação processar e memorizar. Ainda assim, esse filtro acaba falhando - vivenciamos isso quando esquecemos nossa senha do banco no caixa eletrônico, com 10 pessoas na fila esperando por você.

De forma bastante rudimentar, podemos entender o processo como dependente da atenção e da percepção. Quanto mais prestamos atenção em algo, o quanto mais o processarmos em termos de raciocínio, comparando-o com outros conhecimentos, mais provável será nos lembrarmos disso.

Cada vez mais, tendemos a depender da internet e do Smarphone como "apoios cognitivos", algo como uma extensão da mente. Todo mundo hoje tem algum tipo de "sistema de informação pessoal", através de ferramentas de informação. Qual é o seu?

Implicações para design de sistemas:

- Redução da carga cognitiva ao evitar procedimentos longos e complicados;
- A priorização do _reconhecimento_ à necessidade de _lembrança_, usando padrões de interação, menus, ícones familiares;
- É bom sempre oferecer modos variados de identificar objetos digitais (cores, nomes, tags, ícones, folders).

**Aprendizado**

Bastante relacionado com a memória, aprendizado define a acumulação de habilidades e conhecimento. Sem a memória não há aprendizado, e talvez possamos dizer que sem aprendizado também há pouca memória. Na psicologia cognitiva, o aprendizado acontece de duas formas: incidental ou intencional, de nomes autoexplicativos. No primeiro caso, reconhecimento de rostos, ruas e objetos. Já no segundo, assunto de uma prova, ou a habilidade de cozinhar. Este é bem mais difícil, por isso desenvolvedores de software não podem assumir que usuários vão facilmente aprender a usar um aplicativo que requer esforço consciente significativo.

Além disso, as pessoas preferem aprender usando qualquer coisa a ler manuais. Interfaces devem ter o papel de fomentar o aprendizado ativo, dando suporte à interação exploratória e sem medo de cometer erros. Dá pra imaginar sistemas sem Control+Z?

Implicações para design de sistemas:

- Interfaces devem encorajar a exploração;
- Interfaces devem restringir e guiar usuários a selecionar ações apropriadas quando aprendem.

**Ler, ouvir e falar**

São as três formas de processamento de linguagem; no entanto, a facilidade com que pessoas as exercem depende do indivíduo, da tarefa e do contexto. Muitas pessoas estão impossibilitadas de ouvir, por isso só podem ler, ou o oposto. Uma interface pode ser baseada em sons, no entanto o sistema poderia ser acessado por um computador com a saída de som quebrada.

Outros aspectos a considerar: a linguagem escrita é permanente, enquanto o áudio é transiente; reler é fácil, reescutar pode não ser possível. Ler pode ser mais rápido que falar ou ouvir, apesar de que ouvir requer um esforço cognitivo menor.

Implicações para design de sistemas:

- Menus e recomendações em áudio precisam ser usados de forma limitada;
- É necessário dar a opção de aumentar textos na tela, de uma forma fácil, sem modificar a formatação geral.

**Resolução de problemas, planejamento, raciocínio e tomada de decisão**

Aqui incluem-se pensar sobre o que você deve fazer, quais são as opções disponíveis, e quais são as consequências de cada ação. Em geral envolve processos conscientes (cognição reflexiva), discussão (até com você mesmo), e o uso de artefatos adicionais (caneta, mapas, livros, papel).

Teorias mais antigas sobre a tomada de decisão professavam que isso normalmente inclui pesar todos os custos e benefícios das diferentes opções. Empiricamente, a psicologia cognitiva tem mostrado que as pessoas tendem a usar heurísticas simples para decidir - nossa mente evoluiu para tomar decisões rápidas e "suficientemente boas", ignorando boa parte da informação disponível e confiando em algumas poucas pistas. Por exemplo, num supermercado, fazemos julgamentos de compra baseados em marcas reconhecidas ou pelo empacotamento vistoso, sem olhar qualquer outra informação.

No design, por isso torna-se crítico evidenciar informações chave. Melhor que oferecer muitas informações é projetar intervenções tecnológicas que oferecem pouca informação, da melhor forma, facilitando as decisões positivas.

Implicações para design de sistemas:

- Oferecer informação e ajuda fáceis de acessar;
- Empregar funções simples e memoráveis para dar suporte à tomada rápida de decisões;
- O usuário deve ter como definir suas próprias preferências e critérios;
