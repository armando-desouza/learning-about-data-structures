<h1
    align="center"
>
    Algoritmos e Estruturas de Dados
</h1>

<p
    align="center"
>
    As estruturas de dados são formas de organizar e armazenar dados de forma eficiente. Elas definem como os dados são armazenados na memória, como podem ser acessados e quais operações podem ser realizadas sobre eles, permitem armazenar e manipular grandes volumes de dados de forma organizada e rápida, o que é crucial para área de engenharia de software de forma geral.
</p>

## Introdução

<p
    align="justify"
>
    As <strong>estruturas de dados</strong> são a espinha dorsal da organização e armazenamento de informações no universo da computação. Imagine um armário gigantesco com diferentes compartimentos, cada um projetado para armazenar um tipo específico de objeto: roupas, livros, rouças e outros. As estruturas de dados funcionam de maneira similar, organizando e gerenciando eficientemente os dados que alimentam nossos softwares e sistemas.
</p>
<p
    align="justify"
>
    O termo <i>"estrutura de dados"</i> surgiu na década de 1960, com a publicação do livro <strong>"Estruturas de Dados e Algoritmos"</strong> de <i>Donald Knuth</i>. Essa obra seminal consolidou a importância das estruturas de dados como base fundamental para a ciência da computação.
</p>
<p
    align="justify"
>
    Embora a história oficial atribua a Knuth a codificação do termo, a ideia por trás das estruturas de dados existe há séculos. Um dos primeiros exemplos é a <strong>lista</strong>, presente em antigas civilizações para registrar inventários e transações. Com o tempo, essa ideia evoluiu para formas mais complexas, como <strong>arrays</strong>, <strong>pilhas</strong>, <strong>filas</strong>, <strong>árvores</strong> e <strong>gráfos</strong>.
</p>
<p
    align="justify"
>
    As estruturas de dados permeiam nosso dia a dia digital, desde os aplicativos que utilizamos até os sistemas que gerenciam grandes infraestruturas. Vejamos alguns exemplos:
</p>

<ul
    align="justify"
>
    <li>
        <strong>Bancos de dados:</strong> armazenam e organizam infomações de clientes produtos e transações.
    </li>
    <li>
        <strong>Sistemas de processamento de imagens:</strong> manipulam e analisam imagens digitais, como fotos e vídeos.
    </li>
    <li>
        <strong>Algoritmos de busca:</strong> permitem encontrar rapidamente informações em grandes conjuntos de dados, como na internet.
    </li>
    <li>
        <strong>Compiladores de linguagem:</strong> traduzem código fonte em linguagem de máquina para que computadores possam executá-lo.
    </li>
    <li>
        <strong>Jogos:</strong> criam mundos virtuais interativos e simulam comportamentos realistas.
    </li>
</ul>

<p
    align="justify"
>
    Compreender as estruturas de dados é crucial para qualquer engenheiro de software que deseja desenvolver softwares robustos e eficientes. Através do estudo e da prática, é possível:
</p>

<ul
    align="justify"
>
    <li>
        Escolher a estrutura de dados ideal para cada problema, otimizando o desempenho do seu código.
    </li>
    <li>
        Implementar algoritmos complexos com mais clareza e eficiência. 
    </li>
    <li>
        Desenvolver aplicações escaláveis que lidam com grandes volumes de dados.
    </li>
</ul>

## Tipos de Estruturas de Dados

<p
    align="justify"
>
    Existem diversos tipos de estruturas de dados, cada uma com suas próprias características e aplicações. O mundo das estruturas de dados é vasto e fascinante, composto por diversas ferramentas que organizam e gerenciam informações de forma eficiente. Cada tipo possui características e aplicações únicas, permitindo que engenheiros de softwares resolvam problemas com criatividade e poder. Embora não seja possível listar todas as estruturas de dados existentes, podemos explorar as mais comuns e importantes:
</p>

<strong>1. ESTRUTURAS DE DADOS LINEARES.</strong>

<p
    align="justify"
>
    Estruturas de Dados Lineares são aquelas que organizam os elementos de forma hierárquica ou relacional, ou seja, em uma sequência lógica e ordenada, permitindo acesso não sequencial e relacionamentos complexos. Em outras palavras, cada elemento tem um predecessor e um sucessor, exceto o primeiro e o último elementos, respectivamente. Algumas das características mais comuns das estruturas de dados lineares são:
</p>

<ul
    align="justify"
>
    <li>
        <strong>Sequência:</strong> os elementos são dispostos em uma ordem linear, um após o outro.
    </li>
    <li>
        <strong>Acesso sequencial:</strong> para acessar um elemento, muitas vezes é necessário percorrer a estrutura desde o início.
    </li>
</ul>

<p
    align="justify"
>
    Alguns dos tipos mais comuns das estruturas de dados lineares são:
</p>

<ul
    align="justify"
>
    <li>
        <strong>Array (Vetor):</strong> armazenam uma coleção de elementos de tamanho fixo e do mesmo tipo, acessíveis por índices. Ideal para acesso rápido por índice e operações matemáticas.
    </li>
    <li>
        <strong>Lista ligada:</strong> armazenam elementos em nós iterligados por ponteiros. Permitem inserção e remoção eficientes em qualquer posição, mas acesso por índice pode ser mais lento.
    </li>
    <li>
        <strong>Pilha (stack):</strong> uma coleção que segue o princípio LIFO (Last In, First Out), onde o último elemento a entrar é o primeiro a sair. úteis para desfazer ações, gerenciar pilhas de chamadas e processar expressões matemáticas.
    </li>
    <li>
        <strong>Fila (queue):</strong> um coleção que segue o princípio FIFO (First In, First Out), ou seja, o primeira elemento a entrar é o primeiro a sair. Ideais para filas de espesra, bufferização de dados e processamento de tarefas em ordem.
    </li>
</ul>

<strong>2. ESTRUTURAS DE DADOS NÃO LINEARES.</strong>

<p
    align="justify"
>
    Estruturas de Dados Não Lineares são aquelas em que os elementos não estão organizados em uma sequência linear ou ordenada. Em vez disso, os elementos estão dispostos de forma que um único elemento pode estar conectado a vários outros elementos, formando uma estrutura hierárquica ou de rede. Algumas das características das estruturas de dados não lineares são:
</p>

<ul
    align="justify"
>
    <li>
        <strong>Hierarquia:</strong> os elementos podem ter um ou mais relacionamentos hierárquicos, como pais e filhos.
    </li>
    <li>
        <strong>Relacionamento de Rede:</strong> Os elementos podem estar interconectados de maneira complexa, semelhante a uma rede.
    </li>
</ul>

<p
    align="justify"
>
    Alguns dos tipos mais comuns das estruturas de dados não lineares são:
</p>

<ul
    align="justify"
>
    <li>
        <strong>Árvores:</strong> armazenam elementos em um hierarquia de nós, onde cada nó pode ter zero ou mais filhos. Úteis para representar estruturas hierárquicas, como árvores de diretórios, árvores de decisão e árvores de expressão.
    </li>
    <li>
        <strong>Grafos:</strong> armazenam elementos (vértices) e as conexões entre eles (arestas), que podem representar redes complexas como redes sociais, mapas de cidades, rotas de transporte e problemas de otimização.
    </li>
    <li>
        <strong>Tabelas Hash:</strong> estruturas que mapeiam chaves para valores em uma estrutura de dados hash, permitindo acesso rápido por chave. Úteis para implementação de dicionários, caches e bases de dados NoSQL.
    </li>
    <li>
        <strong>Conjuntos:</strong> armazenam coleções não ordenadas de elementos únicos, sem duplicatas. Ideais para verificar a presença de elementos, realizar uniões e intersecções de conjuntos e testar conjuntos disjuntos.
    </li>
</ul>

<strong>3. ESTRUTURAS DE DADOS AVANÇADAS.</strong>

<p
    align="justify"
>
    Estruturas de Dados Avançadas são blocos fundamentais na organização e manipulação de informações em algoritmos e programas. Elas permitem armazenar, acessar e gerenciar dados de maneira eficiente e adequada.
</p>
<p
    align="justify"
>
    Alguns dos tipos mais comuns das estruturas de dados avançadas são:
</p>

<ul
    align="justify"
>
    <li>
        <strong>Tries:</strong> árvores especializadas para armazenamento e busca eficiente de strings prefixadas. Úteis para autocompletar palavras, roteamento de pacotes e implementação de dicionários.
    </li>
    <li>
        <strong>Filas de Prioridade (Heaps):</strong> estruturas de dados baseadas em árvores que garantem que o elemento de maior ou menor valor esteja sempre na raiz. Ideais para implementação de filas de prioridade, algoritmos de ordenação, algoritmo de dijkstra e seleção de elementos
    </li>
    <li>
        <strong>Blocos de Memória:</strong> Gerenciam a alocação e desalocação de memória em blocos de tamanhos variáveis. Útes para ótimizar o uso da memória em aplicações que alocam e liberam memória com frequência.
    </li>
    <!-- <li>
        <strong>Partição Dinâmica:</strong> 
    </li> -->
</ul>