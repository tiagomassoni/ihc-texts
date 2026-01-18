---
title: Padrões de Projeto de Interação
---

Os padrões de UI são as formas mais comuns como pensar e se comportar ao se relacionar com interfaces de software. Mesmo que cada indivíduo seja único, pessoas em geral se comportam de forma previsível, por isso padrões podem ser observados e reutilizados. Designers estudam visitas em sites e usuários por anos; cientistas cognitivos e outros pesquisadores passam muito tempo tentando entender as pessoas. Os princípios e os padrões são resultado de todo esse conhecimento. Muitos padrões de UI podem ser encontrados em catálogos ou sites ([http://ui-patterns.com](http://ui-patterns.com)). Usaremos aqui como referência o seguinte livro texto:

**Designing Interfaces: Patterns for Effective Interaction Design**.
Jenifer Tidwell et al. Terceira Edição.
O'Reilly.
Link: [https://www.oreilly.com/library/view/designing-interfaces-3rd/9781492051954/]


# Básico

## O que é UI Design?

O Design de Interface do Usuário (UI Design) refere-se aos elementos visuais de um produto digital. Ele foca principalmente na aparência e no estilo, e não na experiência completa (como o UX Design). Você pode pensar nele como a "superfície" de um produto digital.

Uma ótima interface de usuário deve ser utilizável (usável) e encantadora. Além de funcional, a interface deve ser agradável e prazerosa de usar. A interface mais simples possível é aquela que ajuda o usuário a resolver seu problema com esforço mínimo.

## Telas

Todo UI Design é colocado em uma tela (smartphone, laptop, tablet ou smartwatch). Cada tela tem sua própria resolução, geralmente expressa em pixels (px). Abaixo podemos ver as resoluções de tela de um iPhone e de um Macbook de 13 polegadas. Essas resoluções são as que vemos na vida real. No entanto, designers não criam UIs para essas dimensões, mas usam resoluções simplificadas, chamadas de pontos (pt), para cuja conversão vemos logo abaixo.

![t6.png](t6.png)
![t7.png](t7.png)

Projetar em pontos é uma simplificação estratégica. Se um designer tentasse projetar um aplicativo para um iPhone X usando sua resolução real de $1125x2436$ px, o processo seria extremamente detalhado e lento. 
Ao utilizar a resolução em pontos, que para o mesmo aparelho é de $375x812$ pt, o designer trabalha em uma escala reduzida que é muito mais fácil de gerenciar. A principal vantagem dessa simplificação é tornar o design mais fácil e rápido. 

Trabalhar com números menores permite que o designer se concentre na proporção e na hierarquia dos elementos sem se perder na contagem de milhares de pixels individuais. As ferramentas de design modernas já trazem essas resoluções em pontos como predefinições (presets), eliminando a necessidade de memorizar cada valor. Essa abordagem garante que a proporção da tela (*aspect ratio*) seja mantida, permitindo que o design seja escalado corretamente para a resolução real do dispositivo mais tarde.

O bom é que tudo o que é criado na interface — como retângulos, ovais e textos — é um *objeto vetorial*. Isso significa que, independentemente de projetarmos em uma escala menor (pontos), o design pode ser redimensionado para a tela real de alta densidade de pixels sem qualquer perda de qualidade.

## Objetos

Enquanto a tela é nosso *canvas*, o design em si é feito de muitos elementos diferentes. Todo objeto é uma forma vetorial e pode ser redimensionado sem perder qualidade. Essencialmente, UI Design é posicionar formas (retângulos, ovais, texto) na tela.

Aqui vão algumas propriedades dos Objetos

* Tamanho (Width e Height): Todo elemento tem largura (W) e altura (H) expressas em pontos.
* Posição (X e Y): O valor X indica a distância da borda esquerda e o valor Y a distância da borda superior.
* Rotação: Os valores variam de 0 a 360 graus.
* Preenchimento (Fill): Pode ser cor, gradiente ou imagem
* Borda (Border/Stroke): Existem três tipos: interna (most frequent), centralizada e externa.
* Raio da Borda (Border Radius): Define o quão arredondados são os cantos. Usar 0 pt é raro; cantos arredondados dão uma sensação mais amigável.
* Sombras (Shadows): Funcionam como uma camada separada e possuem valores de X, Y, Blur e Opacidade.
* Desfoque (Blur): Pode ser Layer Blur (desfoca o próprio elemento) ou Background Blur (desfoca o que está por baixo do elemento).


# Navegação

Padrões de navegação lidam com o desafio de deixar claro a usuários em que local do sistema eles se encontram, mostrando como sair de um local e chegar em outro. Parece fácil, não é? Na verdade, tarefa gigantesca para designers. O melhor sistema de navegação é aquele que não é percebido. Deixar o que é importante sempre à mão, tirando do foco aquilo que é menos importante, mantendo uma distância curta para chegar a qualquer lugar.

Nesse ponto, alguns conceitos. _Signposts_ são elementos que ajudam os usuários a ter noção de seu ambiente. Coisas como título de página e janela, logos, abas, e indicações de seleção, além de indicadores de progresso, _breadcrumbs_, e barras de rolagem. O pessoal de UX usa também o termo _Wayfinding_ para indicar a ação da usuária em encontrar algo; para facilitar tal processo, esperamos do sistema algumas qualidades:

- Boa sinalização;
- Indicações claras, padronizadas;
- Mapas.

Os padrões de navegação tentam promover certas boas práticas gerais. Vamos a elas:

- Separar o projeto de navegação do projeto visual: priorize a forma da usuária navegar, depois disso pense na estética, respeitando as decisões iniciais;
- Carga Cognitiva: Novas páginas adicionam carga cognitiva, a tal "mudança de contexto". As decisões que a usuária deve tomar em cada uma precisam ser padronizadas.

Os padrões de **navegação** versam sobre vários aspectos de navegação: estrutura geral, determinação do status, determinação de onde ir, e formas de chegar lá eficientemente. No livro texto, páginas 129 a 208.

- Clear Entry Points
- Menu Page
- Pyramid
- Modal Panel
- Deep Links
- Escape Hatch
- Fat Menus
- Sitemap Footer \* Sign-In Tools
- Progress Indicator
- Breadcrumbs
- Annotated Scroll Bar

# Grid e Layout

O layout determina o jeito como os elementos (componentes) estão dispostos. Cada elemento pode ser _informacional, funcional, de enquadramento ou decorativo_. A disposição desses elementos ajuda a guiar e informar usuários sobre a importância relativa de informação e funções. Normalmente ouvimos falar do termo interface _limpa_. Um layout limpo segue princípios de hierarquia da informação visual, fluxo visual, alinhamento, além de seguir princípios _Gestalt_.

O conteúdo mais importante deve se destacar mais, e o menos importante deve ficar menos proeminente. Uma boa hierarquia visual nos fornece, instantaneamente:

- a importância relativa dos elementos de tela;
- os relacionamentos entre eles;
- o que fazer em seguida.

Na figura abaixo, é possível perceber qual informação é mais importante, nas duas telas? A maioria das pessoas acha o exemplo B mais fácil de entender, já que os elementos, o tamanho relativo e a proporção entre eles implica sua importância e guia o leitor ao que realmente importa. Em B, podemos dizer que há uma _hierarquia visual_ ausente em A.

![t2.png](t2.png)

O que faz os elementos tornarem-se importantes?

- Tamanho
- Posição
- Densidade: quanto mais denso, melhor para ler, em geral
- Cores de fundo
- Ritmo: espaços entre elementos, grades de elementos
- Alinhamento

## Grids

Um *grid* (grade) é um conjunto de linhas horizontais e verticais, que dividem a tela em colunas e linhas. São importantes porque fornecem estrutura a uma página ou aplicação, assegurando espaçamento consistente entre os elementos. 

Colunas são as seções verticais do grid; quanto mais colunas, mais flexível é o grid. A maoria dos designs utilizam 12 colunas.

![t8.png](t8.png)

Já as linhas são as seções horizontais, mas são usadas raramente em design para a web, por exemplo. Os grids são mais baseados nas colunas mesmo, em geral. Mais importantes são os *gutters* (calhas) são os espaços vazios que dividem as colunas e as linhas dentro de um grid de design. Determinam a densidade do conteúdo: quanto menor a largura da calha, mais apertado e denso o conteúdo parecerá na tela. Em interfaces web, é comum utilizar valores como 12pt, 14pt, 16pt ou 20pt para as calhas, garantindo que haja um respiro adequado entre os elementos.

![t9.png](t9.png)
*Gutters*

Outros conceitos importantes são *margem* e *módulos*. Estes são os pontos de encontro entre colunas e linhas.

![t10.png](t10.png)
![t11.png](t11.png)

Não existem muitos tipos de grid em Design UI, mas também não há um formato universal. Podemos ver abaixo os tipos mais usados.

O *tipo fluido* apresenta colunas que mudam a largura baseado na largura da tela, enquanto a margem e a calha permanecem fixas. Este é o tipo de grid perfeito para o design de interfaces *responsivas*, em que o tamanho do conteúdo muda com o tamanho da tela.

![t12.png](t12.png)

Por outro lado, o *grid fixo* tem um imutável para colunas e calhas, com a variação das margens apenas. Funciona bem para telas em que os componentes devem manter seu tamanho, independente do que acontecer.

![t13.png](t13.png)

As ferramentas já fazem este cálculo para nós -- como é o caso do Figma -- mas vale a pena discutir o cálculo de tamanho de colunas e calhas. No design para web, é comum utilizar calhas com valores entre 12pt e 20pt para manter uma estrutura consistente. Por exemplo, ao configurar um grid de 12 colunas em uma tela de 1440pt de largura, você pode definir margens de 160pt e calhas de 20pt; nesse cenário, o espaço total das calhas (11 calhas de 20pt cada) será subtraído da largura total para ajudar a determinar o tamanho exato de cada coluna. O cálculo matemático seria: primeiro, subtraia as duas margens (1440 - 320 = 1120) e, em seguida, as 11 calhas (1120 - 220 = 900); ao dividir o restante pelas 12 colunas (900/12), você descobre que cada coluna deve ter exatamente 75pt de largura.

Uma técnica bastante usada é a do *grid de 8 pontos*.
A ideia baseia-se no princípio de utilizar múltiplos de 8 (como 8, 16, 24, 32, etc.) para definir as dimensões de elementos, margens, preenchimentos (paddings) e o espaçamento entre componentes em uma interface. 
A escolha do número 8 justifica-se pelo fato de que a grande maioria das resoluções de tela atuais é divisível por 8, o que garante que o design seja escalado de forma consistente e evite o aparecimento de meios pixels, resultando em uma interface mais nítida e organizada em diferentes dispositivos.

![t14.png](t14.png)

Ao implementar este sistema, a designer pode optar por dois caminhos: o *Hard Grid* ou o *Soft Grid*. No Hard Grid, todos os elementos devem seguir estritamente os incrementos de 8pt e "encaixar" em um padrão de grade visível, o que pode ser bastante rígido. Já o Soft Grid, que é a abordagem preferida por muitos profissionais, foca apenas em medir o espaçamento entre os elementos utilizando a escala de 8pt, oferecendo maior flexibilidade sem sacrificar a consistência visual e a harmonia do layout.

Pensando em texto agora. É bom tentar alinhar na linha de base (*baseline*) sobre a primeira linha de texto. Assim, independente do tamanho da fonte, o texto estará bem alinhado.

![t15.png](t15.png)


## Princípios Gestalt

_Gestalt_ é o alemão para "forma", conceito esse da teoria psicológica dos anos 1920s; traz regras que descrevem como humanos percebem objetos visuais. Isso tudo ajuda a definir propriedades de layout que acabam sendo naturais em sistemas visuais.

**Proximidade.** Quando objetos são colocados juntos, quem os visualiza associa um com outro. Por isso elementos relacionados devem ser agrupados visualmente.

**Similaridade.** Itens similares em tamanho, formato ou cor são percebidos com relacionados.

**Continuidade.** Nossos olhos naturalmente seguem as linhas percebidos e as curvas formadas pelo alinhamento de outros elementos.

**Fechamento (Closure).** Nosso cérebro naturalmente "fecha" linhas para criar formas simples fechadas, mesmo se essas linhas não forem explicitamente fechadas. Exemplos abaixo:

![t3.png](t3.png)

Esses princípios são normalmente usados em combinação. Continuidade e fechamento juntos justificam o alinhamento de elementos, por exemplo.

Os padrões de design para layout definem modos específicos para dispor os componentes na interface. Eles articulam a hierarquia visual de páginas ou telas inteiras (Páginas 209 a 254).

- Visual Framework
- Center Stage
- Grid of Equals
- Module Tabs
- Accordion
- Collapsible Panels
- Movable Panels

# Estilo Visual e Estética

Design visual (_look-and-feel_) pode fazer um produto digital se destacar. A linguagem visual usada simboliza uma mensagem que acaba sendo importante para a usabilidade do produto. _Looking good matters_.
A mais pura beleza digital é a combinação da forma física com a função desejada, funcionando juntos, em harmonia. No design de software, não é suficiente que cada pixel seja perfeito, pois deve combinar com utilidade, compreensão e prazer de uso.

O que faz um bom design visual? Em geral é um conjunto de propriedades: composição, cores, tipografia, legibilidade, evocação de sensações, e imagens.
Por exemplo, a figura abaixo traz telas que evocam sensações diferentes, ainda que contenham os mesmos elementos visuais.

![t4.png](t4.png)

Há uma quantidade enorme de padrões relacionados a cada propriedade de design visual. Só para cores, já existe um corpo razoável de conhecimento que pode ser aplicado ao design.

Para criar designs visualmente atraentes, é importante compreender os princípios de _teoria das cores, tipografia, layout e hierarquia visual_. 

## Cores

A teoria das cores nos ajuda a escolher combinações de cores que transmitam a mensagem certa e evocam as emoções desejadas. Por exemplo, para um aplicativo de saúde e bem-estar, cores calmas e naturais podem ser mais adequadas do que cores vibrantes e intensas.

Por exemplo, sugere-se sempre colocar cores frontais escuras sobre cores de fundo claras, e vice-versa (designers testam isso visualizando como escala de cinza em ferramentas como Photoshop). Ou ainda, quando verde ou vermelho indicam alguma distinção, é bom reforçar essa distinção com alguma forma diferente ou texto - cerca de 10% dos homens e 1% das mulheres apresentam alguma forma de daltonismo.

Adicionalmente, é bom evitar algumas combinações de cor. Por exemplo, texto azul brilhante num fundo vermelho cansa os olhos, pois são cores _complementares_, estando localizadas em lados opostos na chamada roda das cores (abaixo).

![t5.png](t5.png)

Quando estamos falando de computadores, tablets ou smartphones, o fundo escuro tem sido uma opção disseminada, para poupar visão e até energia. Outras questões relacionadas a cores: cores quentes ou frias, contraste baixo (mais relaxante) ou alto (maior tensão/força), muito ou pouco saturado.

## Hieraquia

Além disso, a disposição dos elementos na interface é fundamental para criar uma experiência coerente. A hierarquia visual nos ajuda a guiar os olhos do usuário, destacando informações importantes e organizando o conteúdo de forma lógica. Por exemplo, um aplicativo de notícias pode usar tamanhos maiores de fonte e cores vivas para manchetes, enquanto o texto do corpo utiliza uma fonte mais simples.

## Fontes

A tipografia também é crucial: escolher fontes legíveis e que se alinhem à identidade do aplicativo é essencial para uma boa legibilidade. 
A tipografia é definida como a arte e a técnica de organizar tipos para tornar a linguagem escrita legível, compreensível e visualmente atraente quando exibida em uma interface. Envolve a seleção cuidadosa de fontes e famílias tipográficas que comuniquem a mensagem de forma eficaz, respeitando regras de anatomia do tipo, espaçamento e hierarquia para garantir que o conteúdo seja o foco principal sem causar distrações.

*Typeface* (Família Tipográfica) é o design visual das letras, números e símbolos que compartilham um estilo comum. É o conceito criativo e artístico; por exemplo, Inter, Roboto ou Helvetica são typefaces. Já a fonte é a variação específica de peso, largura ou estilo dentro dessa família. É o arquivo ou o formato que você utiliza para aplicar o design. Por exemplo, Inter Bold Italic tamanho 16pt é uma fonte. Seguindo a analogia, a fonte é um "membro" específico da família.

A figura abaixo traz (em inglês) os conceitos básicos relacionados ao trabalho com texto. A não em casos muito específicos, designers não vão criar novas famílias tipográficas para um projeto -- esses conceitos são mais importantes para entender as escolhas de fontes que devem ser feitas.

![t16.png](t16.png)

A *baseline* (linha de base) é a linha invisível onde a maioria das letras se apoia ; a *cap height* (altura da caixa alta) mede a altura das letras maiúsculas a partir da linha de base; a *x-height* (altura de x) refere-se à altura das letras minúsculas (excluindo hastes), já o *ascender* (ascendente) é a parte da letra minúscula que sobe acima da altura de x (como no "h" ou "d").O *descender* (descendente) é a parte que desce abaixo da linha de base (como no "p" ou "g").

O *line height* (altura da linha) é o espaço vertical entre as linhas de texto, medido de uma linha de base (baseline) até a próxima. Para garantir uma boa legibilidade, sugere-se que a altura da linha deve ser maior que a altura dos caracteres (*cap height* mais  ascendentes), permitindo que o olhar do usuário deslize facilmente entre as frases sem se perder. Uma regra prática comum é definir o line height entre 140% e 160% do tamanho da fonte. Por exemplo, se você estiver usando uma fonte de 16pt, uma altura de linha de 24pt (150%) costuma criar um equilíbrio ideal, evitando que as ascendentes de uma linha encostem nas descendentes da linha superior e garantindo que o bloco de texto não pareça muito denso ou muito disperso.

Para a escolha de famílias tipográficas, existem duas categorias bem comuns: serifa ou sem serifa. Esta última é normalmente o padrão, e mais comum. As famílias serifa acabam não sendo a escolha principal, a não ser que se adequem à marca do produto. Famílias *script*, *caligraphy* ou *handwritten* são difíceis de ler e nunca são usadas como escolha principal.

Há poucas dicas no sentido de escolher a família tipográfica. Duas dicas: usar famílias escaláveis, que são bem lidas em tamanhos variados, ou mesmo extremos. Aqui, a criatividade e a experiência dos designers, a partir de pesquisa, são imprescindíveis. Adicionalmente, os designer utilizam apenas uma família tipográfica em um projeto, variando na ênfase e no tamanho, apenas.

Uma técnica usada para a escolha de tamanhos de fonte, a partir do tamanho base, é a aplicação da chamada proporção dourada (*golden ratio*): 1,618. Ela age como multiplicador para criar uma escala tipográfica harmônica. O processo começa com a definição de um tamanho base para o texto do corpo (como 16pt) e, a partir dele, multiplica-se ou divide-se esse valor por 1,618 para encontrar os tamanhos dos títulos e subtítulos. Embora essa técnica gere proporções matematicamente equilibradas, ela pode ser problemática, pois frequentemente cria lacunas muito grandes entre os tamanhos (pulando, por exemplo, de 16pt diretamente para 26pt), o que pode exigir ajustes manuais para incluir tamanhos intermediários necessários à interface.

Existe a chamada escala manual, que começa com a escolha de um tamanho base e avança através de incrementos fixos: utiliza-se a soma ou subtração de 2pt para tamanhos próximos ao corpo do texto (criando variações como 10, 12, 14, 16, 18 e 20pt) e, para tamanhos maiores destinados a cabeçalhos onde o detalhe fino é menos necessário, utiliza-se incrementos de 4pt ou até 8pt. 

Podemos listar algumas dicas relacionadas à escolha das variações de fonte para estabelecer hierarquia visual:

* Ao combinar um título com um texto de corpo, a recomendação é pular um ou dois pesos para garantir contraste suficiente. Por exemplo, se o texto do corpo for Regular, use Bold para o título, evitando combinações muito próximas como Regular e Medium, que podem parecer inconsistentes.

* Geralmente, tamanhos de fonte maiores suportam pesos mais altos (como Bold), enquanto tamanhos menores funcionam melhor com pesos menores. Um exemplo de escala seria usar 12pt com peso Regular e 20pt com peso Bold.

* Deve-se evitar o uso de pesos muito leves (Light) para textos pequenos, pois isso prejudica significativamente a leitura. Para esses casos, o peso Regular é o mínimo recomendado.

* É possível aumentar o espaçamento entre letras (letter spacing) em textos todo em maiúsculas para melhorar a legibilidade, especialmente quando se usa pesos mais pesados.

Os *rags* referem-se às bordas irregulares formadas quando as linhas de um bloco de texto terminam em pontos diferentes devido ao comprimento variável das palavras. O salto visual excessivo entre uma linha longa e uma muito curta exige mais esforço dos olhos do usuário, prejudicando o ritmo da leitura. 

![t18.png](t18.png)

Algumas dicas para lidar com esse problema incluem:

* Priorize o alinhamento à esquerda: É a escolha mais segura para a leitura ocidental, pois mantém o ponto de partida de cada linha consistente.

* Evite textos centralizados para blocos longos: O alinhamento centralizado cria "rags" em ambos os lados, tornando a leitura cansativa em textos extensos.

* Controle o comprimento da linha: Uma linha ideal deve ter entre 50 a 60 caracteres; linhas muito longas ou curtas demais acentuam os problemas de *rags* e dificultam a legibilidade.

* Ajuste manual quando possível: Em elementos fixos como banners, você pode ajustar o texto para suavizar a transição entre as linhas, embora em plataformas dinâmicas isso nem sempre seja possível.

Os sistemas de design escolhidos para o projeto normalmente possuem padrões a serem utilizados.

![t17.png](t17.png)


# Recebendo Entrada

Já tem uns 30 anos que usamos formulários para entrada de dados em sistemas de informação, e isso é um bom motivo para acharmos que não há muito o que fazer nessa seara, em termos de design. Somos meio que direcionados pelos frameworks de _front-end_ a usar seus elementos "de prateleira".

Ainda assim, muitas dúvidas aparecem, e podem fazer diferença na usabilidade. Considere um simples formulário para cadastrar um endereço. Falhas de design podem arruinar a experiência do usuário: quais campos são obrigatórios? Devo começar pelo CEP? Abreviações são ok? E se eu escrever em outro idioma? Existe um mapa para eu escolher? Por que o sistema não lembra do endereço que eu cadastrei aqui mês passado?

Alguns princípios no design de formulários (mais detalhes nas páginas 471 a 532):

- Fazer formulários simples e curtos, percebendo o tempo que será gasto neles;
- Minimizar quantidade de elementos de entrada: por exemplo, precisa mesmo selecionar a bandeira, já que os dois primeiros inteiros identifica a operadora do cartão;
- Minimizar elementos visuais não-essenciais;
- Agrupar e colocar título em seções de elementos de formulário quando for possível e apropriado;
- Usar alinhamento para o fluxo vertical da visão;
- Indicar claramente obrigatórios e opcionais
- Aceitar variações no formato, como no caso de datas e endereços.
- Prevenção de erros e validação o mais rápido possível na interação.

# Referências

Designing Interfaces: Patterns for Effective Interaction Design. Jenifer Tidwell et al. Terceira Edição. O'Reilly.
Link: [https://www.oreilly.com/library/view/designing-interfaces-3rd/9781492051954/]

