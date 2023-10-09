---
title: Módulo 4
---

## Slides

[Avaliação Heurística](https://tiagomassoni.github.io/ihc-texts/modulo4/mod4aula1.pdf)

[Avaliação de Usuários](https://tiagomassoni.github.io/ihc-texts/modulo4/mod4aula2.pdf)

## Projeto: entrega

[Avaliação Heurística](https://tiagomassoni.github.io/ihc-texts/modulo4/projeto41.html)

[Avaliação de Usuarios](https://tiagomassoni.github.io/ihc-texts/modulo4/projeto42.html)

## Avaliação Heurística

Métodos de inspeção que não envolvem usuários são bastante usados, mesmo que pareça paradoxal.  Muitas organizações contratam consultores externos, com experiência em interação, para avaliar um sistema ou seus protótipos antes de serem lançados. A avaliação é feita com base no conhecimento prévio sobre usabilidade, comportamento e limitações cognitivas de usuários, contextos em que o sistema será usado, além dos tipos de atividades que serão desempenhadas. Exemplo mais clássico: avaliação heurística (nosso foco aqui na disciplina). Outro método bastante aplicado: *walk-through*, ou até análise de uso de aplicações já existentes. Por ora, vamos focar em *avaliação heurística*.
Às vezes, torna-se inviável conseguir usuários para avaliar UI\UX, em casos em que simplesmente não estão disponíveis, ou não há tempo para isso. Nesses casos, outros indíviduos, os **experts ou consultores de UX**, podem oferecer feedback. 
Vários métodos de inspeção de usabilidade foram desenvolvidos como alternativa ao teste de usabilidade com usuários, no início dos anos 90 - inspeções para qualidade de software em geral já eram populares na época. Uma vantagem de métodos desse tipo é que eles **podem ser utilizados a qualquer momento** no processo de desenvolvimento, em complemento, muitas vezes, aos testes de usuário.

Na **avaliação heurística**, consultores/pesquisadores, guiados por conjunto de princípios de usabilidade conhecidos como **heurísticas**, avaliam se elementos de UI, tais como caixas de diálogo, menus, estrutura de navegação, ajuda online, etc., estão em conformidade com esses princípios. Subjacentes a esses princípios fazem-se presentes diretrizes como consistência, memória, e clareza, ou seja, princípios básicos de usabilidade.

Diretrizes de avaliação heurística foram propostas por Jakob Nielsen e seus colegas entre 1990 e 1994, e posteriormente estendidas por outros pesquisadores para contextos específicos, como aplicações web. O conjunto de heurísticas original advém do estudo de 249 problemas de usabilidade, mais tarde revisados.

* Visibilidade de Status: O sistema deve sempre manter os usuários informados sobre o que está acontecendo, fornecendo feedback apropriado e dentro de um tempo razoável.
* Correspondência entre sistema e mundo real: O sistema deve falar a linguagem dos usuários, com palavras, frases e conceitos familiares ao usuário, em vez de termos orientados pelo sistema. Ele deve seguir convenções do mundo real, fazendo com que as informações apareçam em uma ordem natural e lógica.
* Controle de usuário e liberdade: Os usuários muitas vezes escolhem funções do sistema por engano e precisarão de uma saída de emergência claramente marcada para sair do estado indesejado sem precisar passar por um diálogo prolongado. O sistema deve suportar desfazer e refazer.
* Consistência e Padrões: Os usuários não devem se perguntar se diferentes palavras, situações ou ações significam a mesma coisa. O sistema deve seguir as convenções da plataforma.
* Prevenção de Erros: Em vez de apenas fornecer boas mensagens de erro, o sistema deve incorporar um design cuidadoso que evite que um problema ocorra em primeiro lugar. Elimine as condições propensas a erros ou verifique-as e apresente aos usuários uma opção de confirmação antes que eles se comprometam com a ação.
* Reconhecimento em Vez de Lembrança: Minimize a carga de memória do usuário tornando objetos, ações e opções visíveis. O usuário não deve precisar lembrar informações de uma parte do diálogo para outra. As instruções para usar o sistema devem ser visíveis ou facilmente recuperáveis sempre que apropriado.
* Flexibilidade e Eficiência de Uso: Aceleradores, invisíveis para o usuário iniciante, podem frequentemente acelerar a interação para o usuário experiente, de modo que o sistema possa atender tanto aos usuários inexperientes quanto aos experientes. Permita que os usuários personalizem ações frequentes.
* Design Estético e Minimalista: Os diálogos não devem conter informações irrelevantes ou raramente necessárias. Cada unidade adicional de informação em um diálogo concorre com as unidades relevantes de informação e diminui sua visibilidade relativa.
* Ajuda aos Usuários: Reconhecer, Diagnosticar e Recuperar de Erros As mensagens de erro devem ser expressas em linguagem clara (não códigos), indicar precisamente o problema e sugerir construtivamente uma solução.
* Ajuda e Documentação: Embora seja melhor se o sistema puder ser usado sem documentação, pode ser necessário fornecer ajuda e documentação. Qualquer informação desse tipo deve ser fácil de pesquisar, focada na tarefa do usuário, listar etapas concretas a serem realizadas e não ser muito extensa.

Pesquisadores e *designers* avaliam aspectos da UI em cima dessa checklist acima. Ao realizar a avaliação heurística, o pesquisador passa pela UI várias vezes, inspecionando os vários elementos e comparando-os com a lista. A cada iteração, problemas de usabilidade podem ser identificados, e formas de corrigir são propostas.

Uma avaliação heurística normalmente é quebrada em dois estágios. Primeiro, há uma sessão de **briefing**, em que os(as) especialistas ouvem explicações de contexto inicial, com os objetivos da avaliação. Depois há o período de **avaliação** propriamente dito, em que os(as) especialistas passam 1-2 horas inspecionando o produto de forma independente, usando as heurísticas como guia. Normalmente, ele(as) passam duas vezes pela UI: a primeira para dar uma ideia da interação e do escopo do sistema, e a segunda com foco em elementos específicos, para identificar problemas em potencial. Ao final, existe uma sessão de **debriefing**, na qual consultores se juntam para discutir seus achados com os designers para priorizar os problemas encontrados, dando sugestões de melhoria.


## Golden Rules

No meio dos anos 80, Ben Shneiderman também propôs um conjunto de diretrizes que são frequentemente usadas como heurística para avaliação, as **regras de ouro** (*eight golden rules*). São definidas assim, depois de uma revisão de 2016:

1. Reforce a consistência
2. Procure usabilidade universal
3. Ofereça feedback informativo
4. Projete diálogos que tragam conclusão
5. Previna erros
6. Permita fácil reversão de ações
7. Mantenha os usuários em controle
8. Reduza carga de memória de curta duração.


## Avaliação com Usuários

Ok, os protótipos foram construídos, já interativos, com ideias inspiradas em padrões de UI. Mesmo com todo esse cuidado, a interface pode incluir problemas de interação. Acaba que só temos como ver isso **avaliando**, vendo a interação funcionar, em uso. 

Neste módulo meu objetivo é apresentar os principais tipos de avaliação, enfatizando o método heurístico, com dois checklists considerados clássicos na área de *design* de interação. 

A avaliação é parte integrante do processo de *design*, envolvendo a coleta e a análise de dados sobre experiências de usuário **no momento em que interage com um artefato de design**, e.g., rascunhos de telas, protótipos, aplicativos, ou sistemas. O foco da avaliação aqui é a **usabilidade** do sistema e na **experiência** dos usuários enquanto utilizam o sistema. Avaliações são necessárias pois, infelizmente, é impossível prever que um conjunto de decisões de *design* vão funcionar bem para eles, mesmo que pessoas dentro da equipe concordem que aquelas são as melhores decisões. Avaliações têm o poder de "testar" o design, naquilo que interessa a nós aqui: a interação.

Existem vários métodos de avaliação, como você deve supor; nunca tem um só jeito de fazer algo, não é? Claro, depende do que a equipe de *design* quer dessa avaliação. Avaliações ocorrem em locais diferentes (laboratórios, local de trabalho, em contextos específicos), envolvem alvos diferentes (usuários, especialistas), e possuem precisão variável (heurísticas, métricas, experimentos). Pode ser algo que nem envolva usuários (modelagem de comportamento), até análise massiva de dados (experimentos A/B).

Para cada aplicação ou sistema, queremos saber algo diferente. Para um navegador web, queremos saber se os usuários consegue encontrar aquilo que procura na Web. Já para um sistema interativo de quiosque de um shopping, queremos verificar se o usuário consegue encontrar uma loja ou um serviço facilmente, através de navegação. E se for um jogo? Queremos manter os usuários jogando, certo? ;-)

Então, quando avaliar? Um produto totalmente novo, algo inovador, precisaria de avaliações muito mais frequentes, em estágios iniciais e intermediários, até para acompanhar se a continuidade do projeto se mantém viável. Para requisitos melhor estabelecidos, essa frequência poderia ser menor...mas a avaliação nunca pode ser negligenciada. Final do sprint, final de milestones...momentos críticos em que decisões importantes são tomadas, esses são os pontos mais favoráveis para avaliações. Deixar para o final é um risco absurdo - o famoso "está 90% pronto, só falta testar". 

A literatura da área chama de avaliação **formativa** aquela que é feita para assegurar, periodicamente, a conformidade dos resultados parciais com aquilo que se toma como requisito. Já a avaliação **somativa** é aquela feita para avaliar o sucesso de um produto final; ou seja, melhorias são o alvo. 



## Tipos de avaliação com Usuários

Vamos considerar aqui dois tipos de avaliação de interação.

* Ambiente controlado envolvendo usuários: normalmente dentro dos **laboratórios de usabilidade**, com testes de usabilidade e experimentos;

* Ambiente natural envolvendo usuários: produtos usados no trabalho, ou em ambientes públicos, como redes sociais;

Como sempre, vários pros e cons para cada um dos tipos. Estudos em laboratório revelam problemas de usabilidade, mas deixam escapar problemas de contexto de uso. Estudos em ambiente de usuário demonstram o uso diário do sistema, mas são custosos e difíceis de conduzir (imagine conseguir voluntários, dentro de uma rotina de trabalho?). Decidir o que fazer depende do que se quer no projeto, e quanto controle queremos ter sobre o processo de avaliação, além do que se tem para despender em um processo de avaliação. Quanto mais inovador é o sistema dentro do ambiente em que será usado, mais avaliação será necessária. 

### Ambientes controlados

Quando se juntam pessoas em laboratórios de usabilidade para avaliar um sistema, queremos determinar, de uma maneira mais genérica, se uma interface é usável. Investiga-se como **usuários típicos realizam tarefas típicas**. O que é típico aqui? Alguém do público-alvo do sistema, nas tarefas chave do sistema. 

Os pesquisadores aqui normalmente comparam o número de erros cometidos, e os tipos de erros. Podem marcar o tempo para a realização da tarefa. Normalmente se usa gravação de vídeo. Ou seja, tudo muito parecido do que já discutimos em prototipação, com a diferença de que aqui estamos trabalhando com sistemas completos, com o objetivo de avaliaçao do que foi realizado, enquanto que antes estávamos interessados em descobrir e esclarecer requisitos. 

Depois podem vir questionários ou entrevistas; esses dados podem ser complementados pela observação dos pesquisadores e designers. Daí podemos usar *think-aloud* e métodos similares de coleta de informações. Dados quantitativos e qualitativos são analisados de forma complementar para que, ao fim de tudo, possamos formar conclusoes acerca de como o sistema está de acordo com as necessidades dos usuários. Uma **especificação de usabilidade** pode ser produzido a partir do processo, um documento usado para avaliar futuras versões do sistema.



### Ambientes reais

Aqui avaliamos os produtos com usuários no qual onde eles deverão utilizar o produto. Um aplicativo de música? No trem, no ônibus, na sala de casa. Um aplicativo de caronas? Enquanto dirige, ou no meio da rua. Esses estudos ajudam a identificar oportunidades, estabelecer o contexto de uso e até facilitar a adoção da tecnologia. A dificuldade da equipe de *design* é se manter não-invasiva para não afetar a investigação, o que muitas vezes é impossível - é inevitável que uma pessoa, ao ser avaliada, se comporte de forma diferente do habitual. 


