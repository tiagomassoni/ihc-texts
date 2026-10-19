# Aula 6: Padrões de Projeto de UI

Os padrões de UI são as formas mais comuns como pensar e se comportar ao se relacionar com interfaces de software. Mesmo que cada indivíduo seja único, pessoas em geral se comportam de forma previsível. Designers estudam visitas em sites e usuários por anos; cientistas cognitivos e outros pesquisadores passam muito tempo tentando entender as pessoas. Os princípios e os padrões são resultado de todo esse conhecimento.

Um site como exemplo de catalogação desses padrões: [http://ui-patterns.com](http://ui-patterns.com).

## Layouts (Cap 4)

Vamos começar essa breve visão geral dos padrões com elementos de layout, a forma particular como elementos são arranjados na UI. Cada elemento pode ser *informacional, funcional, de enquadramento ou decorativo*. A disposição desses elementos ajuda a guiar e informar usuários sobre a importância relativa de informação e funções. 

Normalmente ouvimos falar do termo interface *limpa*. Um layout limpo segue princípios de hierarquia da informação visual, fluxo visual, alinhamento, além de seguir princípios *Gestalt*. 

O conteúdo mais importante deve se destacar mais, e o menos importante deve ficar menos proeminente. Uma boa hierarquia visual nos fornece, instantaneamente:
* a importância relativa dos elementos de tela;
* os relacionamentos entre eles;
* o que fazer em seguida.

Na figura abaixo, é possível perceber qual informação é mais importante, nas duas telas? A maioria das pessoas acha o exemplo B mais fácil de entender, já que os elementos, o tamanho relativo e a proporção entre eles implica sua importância e guia o leitor ao que realmente importa. Em B, podemos dizer que há uma *hierarquia visual* ausente em A.

![aula7/t1.png](aula7/t1.png)

O que faz os elementos tornarem-se importantes?
* Tamanho
* Posição
* Densidade: quanto mais denso, melhor para ler, em geral
* Cores de fundo
* Ritmo: espaços entre elementos, grades de elementos
* Alinhamento

### Princípios Gestalt

*Gestalt* é o alemão para "forma", conceito esse da teoria psicológica dos anos 1920s; traz regras que descrevem como humanos percebem objetos visuais. Isso tudo ajuda a definir propriedades de layout que acabam sendo naturais em sistemas visuais.

**Proximidade.** Quando objetos são colocados juntos, quem os visualiza associa um com outro. Por isso elementos relacionados devem ser agrupados visualmente.

**Similaridade.** Itens similares em tamanho, formato ou cor são percebidos com relacionados. 

**Continuidade.** Nossos olhos naturalmente seguem as linhas percebidos e as curvas formadas pelo alinhamento de outros elementos.

**Fechamento (Closure).** Nosso cérebro naturalmente "fecha" linhas para criar formas simples fechadas, mesmo se essas linhas não forem explicitamente fechadas. Exemplos abaixo:

![aula7/t2.png](aula7/t2.png)

Esses princípios são normalmente usados em combinação. Continuidade e fechamento juntos justificam o alinhamento de elementos, por exemplo.

### Principais padrões

Muitos padrões de UI para layout podem ser encontrados em catálogos ou sites ([http://ui-patterns.com](http://ui-patterns.com)). Aqui vou fazer um rápido resumo do que prescrevem os principais.

Em geral, dentro de uma aplicação, todos os modelos de tela/página compartilham características em comum mantendo um estilo e layout consistente. A tarefa a ser desempenho em um determinado momento localiza-se no centro, em ênfase, enquanto que conteúdo secundário se localiza em painéis periféricos menores.

Itens de conteúdo muito similares, como resultados de busca, são bem arranjados em *grids* ou matrizes, onde cada item segue um modelo comum, e o peso visual de cada um deve ser similar. 

![aula7/t3.png](aula7/t3.png)

Para grupos de conteúdo distintos, seções de conteúdo são separadas, com um título visualmente forte em cada.

![aula7/t4.png](aula7/t4.png)


## Estilo Visual e Estética

Design visual (*look-and-feel*) pode fazer um produto digital se destacar. A linguagem visual usada simboliza uma mensagem que acaba sendo importante para a usabilidade do produto. *Looking good matters*.

A mais pura beleza digital é a combinação da forma física com a função desejada, funcionando juntos, em harmonia. No design de software, não é suficiente que cada pixel seja perfeito, pois deve combinar com utilidade, compreensão e prazer de uso.

O que faz um bom design visual? Em geral é um conjunto de propriedades: composição, cores, tipografia, legibilidade, evocação de sensações, e imagens. 

Por exemplo, a figura abaixo traz telas que  evocam sensações diferentes, ainda que contenham os mesmos elementos visuais. 

![aula7/t5.png](aula7/t5.png)

Há uma quantidade enorme de padrões relacionados a cada propriedade de design visual. Só para cores, já existe um corpo razoável de conhecimento que pode ser aplicado ao design.

Por exemplo, sugere-se sempre colocar cores frontais escuras sobre cores de fundo claras, e vice-versa (designers testam isso visualizando como escala de cinza em ferramentas como Photoshop). Ou ainda, quando verde ou vermelho indicam alguma distinção, é bom reforçar essa distinção com alguma forma diferente ou texto - cerca de 10% dos homens e 1% das mulheres apresentam alguma forma de daltonismo.

Adicionalmente, é bom evitar algumas combinações de cor. Por exemplo, texto azul brilhante num fundo vermelho cansa os olhos, pois são cores *complementares*, estando localizadas em lados opostos na chamada roda das cores (abaixo).

![aula7/t6.png](aula7/t6.png)

Quando estamos falando de computadores, tablets ou smartphones, o fundo escuro tem sido uma opção disseminada, para poupar visão e até energia. Outras questões relacionadas a cores: Cores quentes ou frias, contraste baixo (mais relaxante) ou alto (maior tensão/força), muito ou pouco saturado.

## Recebendo Entrada

Já tem uns 30 anos que usamos formulários para entrada de dados em sistemas de informação, e isso é um bom motivo para acharmos que não há muito o que fazer nessa seara, em termos de design. Somos meio que direcionados pelos frameworks de *front-end* a usar seus elementos "de prateleira". 


Ainda assim, muitas dúvidas aparecem, e podem fazer diferença na usabilidade. Considere um simples formulário para cadastrar um endereço. Falhas de design podem arruinar a experiência do usuário: quais campos são obrigatórios? Devo começar pelo CEP? Abreviações são ok? E se eu escrever em outro idioma? Existe um mapa para eu escolher? Por que o sistema não lembra do endereço que eu cadastrei aqui mês passado?

Alguns princípios no design de formulários:
* Fazer formulários simples e curtos, percebendo o tempo que será gasto neles;
* Minimizar quantidade de elementos de entrada: por exemplo, precisa mesmo selecionar a bandeira, já que os dois primeiros inteiros identifica a operadora do cartão;
* Minimizar elementos visuais não-essenciais;
* Agrupar e colocar título em seções de elementos de formulário quando for possível e apropriado;
* Usar alinhamento para o fluxo vertical da visão;
* Indicar claramente obrigatórios e opcionais
* Aceitar variações no formato, como no caso de datas e endereços.
* Prevenção de erros e validação o mais rápido possível na interação.

