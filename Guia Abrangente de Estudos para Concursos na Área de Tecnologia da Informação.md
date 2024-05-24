---


---

<h3 id="manual-completo-para-concurso-da-caixa---técnico-bancário-novo-em-tecnologia-da-informação">Manual Completo para Concurso da Caixa - Técnico Bancário Novo em Tecnologia da Informação</h3>
<h4 id="introdução">Introdução</h4>
<p>Este manual é destinado a candidatos que estão se preparando para o concurso da Caixa Econômica Federal para o cargo de Técnico Bancário Novo na área de Tecnologia da Informação. Ele abrange todos os tópicos do edital, explicados de forma clara e objetiva, com exemplos práticos e códigos, para ajudar você a se preparar da melhor maneira possível.</p>
<hr>
<h3 id="sumário">Sumário</h3>
<ol>
<li>Engenharia de Software</li>
<li>Estrutura de Dados e Algoritmos</li>
<li>Linguagens de Programação</li>
<li>Desenvolvimento de Software para a Web</li>
<li>Teste de Software (Qualidade)</li>
<li>Bancos de Dados</li>
<li>Agilidade</li>
<li>Organização e Arquitetura de Computadores</li>
<li>Sistemas Operacionais</li>
<li>Arquiteturas de Software</li>
<li>Gerência de Configuração</li>
<li>Portais Corporativos</li>
<li>Qualidade de Software</li>
<li>Conceitos de Arquitetura de Referência</li>
<li>Gestão e Governança de TI</li>
<li>Conhecimentos e Comportamentos Digitais</li>
</ol>
<hr>
<h3 id="engenharia-de-software">1. Engenharia de Software</h3>
<p><strong>1.1 Processos de Software</strong></p>
<p><strong>Processo Unificado (UP)</strong></p>
<ul>
<li><strong>Conceitos Gerais</strong>: O Processo Unificado é um framework de desenvolvimento de software iterativo e incremental. Isso significa que o software é desenvolvido em pequenas partes, chamadas de iterações, e cada parte vai sendo melhorada ao longo do tempo.</li>
<li><strong>Disciplinas</strong>: As disciplinas do UP incluem:
<ul>
<li><strong>Modelagem de Negócios</strong>: Entender o contexto e os processos de negócios.</li>
<li><strong>Requisitos</strong>: Coletar e definir o que o software deve fazer.</li>
<li><strong>Análise e Design</strong>: Criar a arquitetura e o design do software.</li>
<li><strong>Implementação</strong>: Codificar o software.</li>
<li><strong>Teste</strong>: Verificar se o software funciona corretamente.</li>
<li><strong>Implantação</strong>: Colocar o software em produção.</li>
<li><strong>Gestão de Configuração e Mudança</strong>: Controlar as mudanças no software.</li>
<li><strong>Gestão de Projeto</strong>: Planejar e acompanhar o projeto.</li>
<li><strong>Ambiente</strong>: Preparar o ambiente de desenvolvimento.</li>
</ul>
</li>
</ul>
<p><strong>Fases do UP</strong>:</p>
<ul>
<li><strong>Concepção</strong>: Definir a visão do projeto e sua viabilidade.</li>
<li><strong>Elaboração</strong>: Detalhar a arquitetura do sistema.</li>
<li><strong>Construção</strong>: Desenvolver o produto.</li>
<li><strong>Transição</strong>: Entregar o produto ao usuário final.</li>
</ul>
<p><strong>Exemplo Prático</strong>:<br>
Imagine que você está desenvolvendo um sistema de gestão para uma biblioteca. Na fase de concepção, você define que o sistema deve permitir a gestão de livros e empréstimos. Na fase de elaboração, você cria a arquitetura do sistema, definindo os componentes necessários, como o banco de dados para armazenar as informações dos livros e dos usuários. Na fase de construção, você desenvolve o código para essas funcionalidades. Na fase de transição, você instala o sistema na biblioteca e treina os funcionários para usá-lo.</p>
<p><strong>UX (User Experience)</strong></p>
<ul>
<li><strong>Definição</strong>: User Experience (UX) é a experiência que um usuário tem ao interagir com um produto ou sistema. Um bom design de UX torna o sistema fácil de usar e agradável.</li>
<li><strong>Princípios de UX</strong>:
<ul>
<li><strong>Utilidade</strong>: O sistema deve ser útil.</li>
<li><strong>Usabilidade</strong>: O sistema deve ser fácil de usar.</li>
<li><strong>Acessibilidade</strong>: O sistema deve ser acessível a todos os usuários, incluindo aqueles com deficiências.</li>
<li><strong>Estética</strong>: O sistema deve ser visualmente agradável.</li>
<li><strong>Design Centrado no Usuário</strong>: O design deve focar nas necessidades dos usuários.</li>
</ul>
</li>
</ul>
<hr>
<h3 id="estrutura-de-dados-e-algoritmos">2. Estrutura de Dados e Algoritmos</h3>
<p><strong>2.1 Tipos de Busca e Ordenação</strong></p>
<p><strong>Busca Sequencial</strong></p>
<ul>
<li><strong>Definição</strong>: Na busca sequencial, você percorre uma lista elemento por elemento até encontrar o valor desejado.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">busca_sequencial</span><span class="token punctuation">(</span>lista<span class="token punctuation">,</span> valor<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">for</span> i <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span><span class="token builtin">len</span><span class="token punctuation">(</span>lista<span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">if</span> lista<span class="token punctuation">[</span>i<span class="token punctuation">]</span> <span class="token operator">==</span> valor<span class="token punctuation">:</span>
            <span class="token keyword">return</span> i
    <span class="token keyword">return</span> <span class="token operator">-</span><span class="token number">1</span>

lista <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">,</span> <span class="token number">7</span><span class="token punctuation">,</span> <span class="token number">9</span><span class="token punctuation">]</span>
valor <span class="token operator">=</span> <span class="token number">5</span>
resultado <span class="token operator">=</span> busca_sequencial<span class="token punctuation">(</span>lista<span class="token punctuation">,</span> valor<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>f<span class="token string">"Valor encontrado na posição: {resultado}"</span><span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, a função <code>busca_sequencial</code> percorre a lista e retorna a posição do valor 5.</p>
<p><strong>Busca Binária</strong></p>
<ul>
<li><strong>Definição</strong>: A busca binária funciona em listas ordenadas e divide repetidamente o intervalo de busca pela metade até encontrar o valor.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">busca_binaria</span><span class="token punctuation">(</span>lista<span class="token punctuation">,</span> valor<span class="token punctuation">)</span><span class="token punctuation">:</span>
    esquerda<span class="token punctuation">,</span> direita <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">,</span> <span class="token builtin">len</span><span class="token punctuation">(</span>lista<span class="token punctuation">)</span> <span class="token operator">-</span> <span class="token number">1</span>
    <span class="token keyword">while</span> esquerda <span class="token operator">&lt;=</span> direita<span class="token punctuation">:</span>
        meio <span class="token operator">=</span> <span class="token punctuation">(</span>esquerda <span class="token operator">+</span> direita<span class="token punctuation">)</span> <span class="token operator">//</span> <span class="token number">2</span>
        <span class="token keyword">if</span> lista<span class="token punctuation">[</span>meio<span class="token punctuation">]</span> <span class="token operator">==</span> valor<span class="token punctuation">:</span>
            <span class="token keyword">return</span> meio
        <span class="token keyword">elif</span> lista<span class="token punctuation">[</span>meio<span class="token punctuation">]</span> <span class="token operator">&lt;</span> valor<span class="token punctuation">:</span>
            esquerda <span class="token operator">=</span> meio <span class="token operator">+</span> <span class="token number">1</span>
        <span class="token keyword">else</span><span class="token punctuation">:</span>
            direita <span class="token operator">=</span> meio <span class="token operator">-</span> <span class="token number">1</span>
    <span class="token keyword">return</span> <span class="token operator">-</span><span class="token number">1</span>

lista <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">,</span> <span class="token number">7</span><span class="token punctuation">,</span> <span class="token number">9</span><span class="token punctuation">]</span>
valor <span class="token operator">=</span> <span class="token number">5</span>
resultado <span class="token operator">=</span> busca_binaria<span class="token punctuation">(</span>lista<span class="token punctuation">,</span> valor<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>f<span class="token string">"Valor encontrado na posição: {resultado}"</span><span class="token punctuation">)</span>
</code></pre>
<p>Aqui, a função <code>busca_binaria</code> retorna a posição do valor 5 na lista ordenada.</p>
<p><strong>2.2 Métodos de Ordenação</strong></p>
<p><strong>Bubble Sort</strong></p>
<ul>
<li><strong>Definição</strong>: O Bubble Sort ordena a lista, trocando elementos adjacentes que estão na ordem errada.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">bubble_sort</span><span class="token punctuation">(</span>lista<span class="token punctuation">)</span><span class="token punctuation">:</span>
    n <span class="token operator">=</span> <span class="token builtin">len</span><span class="token punctuation">(</span>lista<span class="token punctuation">)</span>
    <span class="token keyword">for</span> i <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">for</span> j <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span><span class="token number">0</span><span class="token punctuation">,</span> n<span class="token operator">-</span>i<span class="token number">-1</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
            <span class="token keyword">if</span> lista<span class="token punctuation">[</span>j<span class="token punctuation">]</span> <span class="token operator">&gt;</span> lista<span class="token punctuation">[</span>j<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">]</span><span class="token punctuation">:</span>
                lista<span class="token punctuation">[</span>j<span class="token punctuation">]</span><span class="token punctuation">,</span> lista<span class="token punctuation">[</span>j<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">]</span> <span class="token operator">=</span> lista<span class="token punctuation">[</span>j<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">]</span><span class="token punctuation">,</span> lista<span class="token punctuation">[</span>j<span class="token punctuation">]</span>

lista <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">64</span><span class="token punctuation">,</span> <span class="token number">34</span><span class="token punctuation">,</span> <span class="token number">25</span><span class="token punctuation">,</span> <span class="token number">12</span><span class="token punctuation">,</span> <span class="token number">22</span><span class="token punctuation">,</span> <span class="token number">11</span><span class="token punctuation">,</span> <span class="token number">90</span><span class="token punctuation">]</span>
bubble_sort<span class="token punctuation">(</span>lista<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Lista ordenada:"</span><span class="token punctuation">,</span> lista<span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, <code>bubble_sort</code> ordena a lista em ordem crescente.</p>
<p><strong>Selection Sort</strong></p>
<ul>
<li><strong>Definição</strong>: O Selection Sort encontra repetidamente o menor elemento e o move para a posição correta.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">selection_sort</span><span class="token punctuation">(</span>lista<span class="token punctuation">)</span><span class="token punctuation">:</span>
    n <span class="token operator">=</span> <span class="token builtin">len</span><span class="token punctuation">(</span>lista<span class="token punctuation">)</span>
    <span class="token keyword">for</span> i <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
        min_idx <span class="token operator">=</span> i
        <span class="token keyword">for</span> j <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span>i<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">,</span> n<span class="token punctuation">)</span><span class="token punctuation">:</span>
            <span class="token keyword">if</span> lista<span class="token punctuation">[</span>j<span class="token punctuation">]</span> <span class="token operator">&lt;</span> lista<span class="token punctuation">[</span>min_idx<span class="token punctuation">]</span><span class="token punctuation">:</span>
                min_idx <span class="token operator">=</span> j
        lista<span class="token punctuation">[</span>i<span class="token punctuation">]</span><span class="token punctuation">,</span> lista<span class="token punctuation">[</span>min_idx<span class="token punctuation">]</span> <span class="token operator">=</span> lista<span class="token punctuation">[</span>min_idx<span class="token punctuation">]</span><span class="token punctuation">,</span> lista<span class="token punctuation">[</span>i<span class="token punctuation">]</span>

lista <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">64</span><span class="token punctuation">,</span> <span class="token number">25</span><span class="token punctuation">,</span> <span class="token number">12</span><span class="token punctuation">,</span> <span class="token number">22</span><span class="token punctuation">,</span> <span class="token number">11</span><span class="token punctuation">]</span>
selection_sort<span class="token punctuation">(</span>lista<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Lista ordenada:"</span><span class="token punctuation">,</span> lista<span class="token punctuation">)</span>
</code></pre>
<p>Aqui, <code>selection_sort</code> ordena a lista.</p>
<p><strong>Insertion Sort</strong></p>
<ul>
<li><strong>Definição</strong>: O Insertion Sort constrói uma lista ordenada, inserindo um elemento de cada vez na posição correta.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">insertion_sort</span><span class="token punctuation">(</span>lista<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">for</span> i <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token builtin">len</span><span class="token punctuation">(</span>lista<span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
        chave <span class="token operator">=</span> lista<span class="token punctuation">[</span>i<span class="token punctuation">]</span>
        j <span class="token operator">=</span> i <span class="token operator">-</span> <span class="token number">1</span>
        <span class="token keyword">while</span> j <span class="token operator">&gt;=</span> <span class="token number">0</span> <span class="token operator">and</span> chave <span class="token operator">&lt;</span> lista<span class="token punctuation">[</span>j<span class="token punctuation">]</span><span class="token punctuation">:</span>
            lista<span class="token punctuation">[</span>j <span class="token operator">+</span> <span class="token number">1</span><span class="token punctuation">]</span> <span class="token operator">=</span> lista<span class="token punctuation">[</span>j<span class="token punctuation">]</span>
            j <span class="token operator">-=</span> <span class="token number">1</span>
        lista<span class="token punctuation">[</span>j <span class="token operator">+</span> <span class="token number">1</span><span class="token punctuation">]</span> <span class="token operator">=</span> chave

lista <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">12</span><span class="token punctuation">,</span> <span class="token number">11</span><span class="token punctuation">,</span> <span class="token number">13</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">,</span> <span class="token number">6</span><span class="token punctuation">]</span>
insertion_sort<span class="token punctuation">(</span>lista<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Lista ordenada:"</span><span class="token punctuation">,</span> lista<span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, <code>insertion_sort</code> organiza a lista.</p>
<p><strong>2.3 Estruturas de Dados</strong></p>
<p><strong>Lista Encadeada</strong></p>
<ul>
<li><strong>Definição</strong>: Uma lista encadeada é uma estrutura de dados linear, onde cada elemento aponta para o próximo.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">class</span> <span class="token class-name">No</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">__init__</span><span class="token punctuation">(</span>self<span class="token punctuation">,</span> dado<span class="token operator">=</span><span class="token boolean">None</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>dado <span class="token operator">=</span> dado
        self<span class="token punctuation">.</span>proximo <span class="token operator">=</span> <span class="token boolean">None</span>

<span class="token keyword">class</span> <span class="token class-name">ListaEncadeada</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">__init__</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>cabeca <span class="token operator">=</span> <span class="token boolean">None</span>

    <span class="token keyword">def</span> <span class="token function">inserir</span><span class="token punctuation">(</span>self<span class="token punctuation">,</span> novo_dado<span class="token punctuation">)</span><span class="token punctuation">:</span>
        novo_no <span class="token operator">=</span> No<span class="token punctuation">(</span>novo_dado<span class="token punctuation">)</span>
        novo_no<span class="token punctuation">.</span>proximo <span class="token operator">=</span> self<span class="token punctuation">.</span>cabeca
        self<span class="token punctuation">.</span>cabeca <span class="token operator">=</span> novo_no

    <span class="token keyword">def</span> <span class="token function">exibir</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        no_atual <span class="token operator">=</span> self<span class="token punctuation">.</span>cabeca
        <span class="token keyword">while</span> no_atual<span class="token punctuation">:</span>
            <span class="token keyword">print</span><span class="token punctuation">(</span>no_atual<span class="token punctuation">.</span>dado<span class="token punctuation">,</span> end<span class="token operator">=</span><span class="token string">" -&gt; "</span><span class="token punctuation">)</span>
            no_atual <span class="token operator">=</span> no_atual<span class="token punctuation">.</span>proximo
        <span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"None"</span><span class="token punctuation">)</span>

lista <span class="token operator">=</span> ListaEncadeada<span class="token punctuation">(</span><span class="token punctuation">)</span>
lista<span class="token punctuation">.</span>inserir<span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">)</span>
lista<span class="token punctuation">.</span>inserir<span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">)</span>
lista<span class="token punctuation">.</span>inserir<span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">)</span>
lista<span class="token punctuation">.</span>exibir<span class="token punctuation">(</span><span class="token punctuation">)</span>
</code></pre>
<p>Este exemplo demonstra como criar e exibir uma lista encadeada simples.</p>
<p><strong>Pilha (Stack)</strong></p>
<ul>
<li><strong>Definição</strong>: Uma pilha é uma estrutura LIFO (Last In, First Out), onde o último elemento inserido é o primeiro a ser removido.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">class</span> <span class="token class-name">Pilha</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">__init__</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>itens <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token punctuation">]</span>

    <span class="token keyword">def</span> <span class="token function">esta_vazia</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">return</span> <span class="token builtin">len</span><span class="token punctuation">(</span>self<span class="token punctuation">.</span>itens<span class="token punctuation">)</span> <span class="token operator">==</span> <span class="token number">0</span>

    <span class="token keyword">def</span> <span class="token function">push</span><span class="token punctuation">(</span>self<span class="token punctuation">,</span> item<span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>itens<span class="token punctuation">.</span>append<span class="token punctuation">(</span>item<span class="token punctuation">)</span>

    <span class="token keyword">def</span> <span class="token function">pop</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">if</span> <span class="token operator">not</span> self<span class="token punctuation">.</span>esta_vazia<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
            <span class="token keyword">return</span> self<span class="token punctuation">.</span>itens<span class="token punctuation">.</span>pop<span class="token punctuation">(</span><span class="token punctuation">)</span>

    <span class="token keyword">def</span> <span class="token function">topo</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">if</span> <span class="token operator">not</span> self<span class="token punctuation">.</span>esta_vazia<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
            <span class="token keyword">return</span> self<span class="token punctuation">.</span>itens<span class="token punctuation">[</span><span class="token operator">-</span><span class="token number">1</span><span class="token punctuation">]</span>

pilha <span class="token operator">=</span> Pilha<span class="token punctuation">(</span><span class="token punctuation">)</span>
pilha<span class="token punctuation">.</span>push<span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">)</span>
pilha

<span class="token punctuation">.</span>push<span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">)</span>
pilha<span class="token punctuation">.</span>push<span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Topo da pilha:"</span><span class="token punctuation">,</span> pilha<span class="token punctuation">.</span>topo<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Removido:"</span><span class="token punctuation">,</span> pilha<span class="token punctuation">.</span>pop<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Topo da pilha:"</span><span class="token punctuation">,</span> pilha<span class="token punctuation">.</span>topo<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, <code>Pilha</code> demonstra operações básicas de uma pilha.</p>
<p><strong>Fila (Queue)</strong></p>
<ul>
<li><strong>Definição</strong>: Uma fila é uma estrutura FIFO (First In, First Out), onde o primeiro elemento inserido é o primeiro a ser removido.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">class</span> <span class="token class-name">Fila</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">__init__</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>itens <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token punctuation">]</span>

    <span class="token keyword">def</span> <span class="token function">esta_vazia</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">return</span> <span class="token builtin">len</span><span class="token punctuation">(</span>self<span class="token punctuation">.</span>itens<span class="token punctuation">)</span> <span class="token operator">==</span> <span class="token number">0</span>

    <span class="token keyword">def</span> <span class="token function">enqueue</span><span class="token punctuation">(</span>self<span class="token punctuation">,</span> item<span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>itens<span class="token punctuation">.</span>append<span class="token punctuation">(</span>item<span class="token punctuation">)</span>

    <span class="token keyword">def</span> <span class="token function">dequeue</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">if</span> <span class="token operator">not</span> self<span class="token punctuation">.</span>esta_vazia<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
            <span class="token keyword">return</span> self<span class="token punctuation">.</span>itens<span class="token punctuation">.</span>pop<span class="token punctuation">(</span><span class="token number">0</span><span class="token punctuation">)</span>

    <span class="token keyword">def</span> <span class="token function">frente</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">if</span> <span class="token operator">not</span> self<span class="token punctuation">.</span>esta_vazia<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
            <span class="token keyword">return</span> self<span class="token punctuation">.</span>itens<span class="token punctuation">[</span><span class="token number">0</span><span class="token punctuation">]</span>

fila <span class="token operator">=</span> Fila<span class="token punctuation">(</span><span class="token punctuation">)</span>
fila<span class="token punctuation">.</span>enqueue<span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">)</span>
fila<span class="token punctuation">.</span>enqueue<span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">)</span>
fila<span class="token punctuation">.</span>enqueue<span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Frente da fila:"</span><span class="token punctuation">,</span> fila<span class="token punctuation">.</span>frente<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Removido:"</span><span class="token punctuation">,</span> fila<span class="token punctuation">.</span>dequeue<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Frente da fila:"</span><span class="token punctuation">,</span> fila<span class="token punctuation">.</span>frente<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<p>Aqui, <code>Fila</code> demonstra as operações básicas de uma fila.</p>
<p><strong>Árvore Binária</strong></p>
<ul>
<li><strong>Definição</strong>: Uma árvore binária é uma estrutura hierárquica onde cada nó tem, no máximo, dois filhos.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">class</span> <span class="token class-name">No</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">__init__</span><span class="token punctuation">(</span>self<span class="token punctuation">,</span> chave<span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>esquerda <span class="token operator">=</span> <span class="token boolean">None</span>
        self<span class="token punctuation">.</span>direita <span class="token operator">=</span> <span class="token boolean">None</span>
        self<span class="token punctuation">.</span>chave <span class="token operator">=</span> chave

<span class="token keyword">def</span> <span class="token function">inserir</span><span class="token punctuation">(</span>raiz<span class="token punctuation">,</span> chave<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">if</span> raiz <span class="token keyword">is</span> <span class="token boolean">None</span><span class="token punctuation">:</span>
        <span class="token keyword">return</span> No<span class="token punctuation">(</span>chave<span class="token punctuation">)</span>
    <span class="token keyword">else</span><span class="token punctuation">:</span>
        <span class="token keyword">if</span> chave <span class="token operator">&lt;</span> raiz<span class="token punctuation">.</span>chave<span class="token punctuation">:</span>
            raiz<span class="token punctuation">.</span>esquerda <span class="token operator">=</span> inserir<span class="token punctuation">(</span>raiz<span class="token punctuation">.</span>esquerda<span class="token punctuation">,</span> chave<span class="token punctuation">)</span>
        <span class="token keyword">else</span><span class="token punctuation">:</span>
            raiz<span class="token punctuation">.</span>direita <span class="token operator">=</span> inserir<span class="token punctuation">(</span>raiz<span class="token punctuation">.</span>direita<span class="token punctuation">,</span> chave<span class="token punctuation">)</span>
    <span class="token keyword">return</span> raiz

<span class="token keyword">def</span> <span class="token function">em_ordem</span><span class="token punctuation">(</span>raiz<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">if</span> raiz<span class="token punctuation">:</span>
        em_ordem<span class="token punctuation">(</span>raiz<span class="token punctuation">.</span>esquerda<span class="token punctuation">)</span>
        <span class="token keyword">print</span><span class="token punctuation">(</span>raiz<span class="token punctuation">.</span>chave<span class="token punctuation">,</span> end<span class="token operator">=</span><span class="token string">" -&gt; "</span><span class="token punctuation">)</span>
        em_ordem<span class="token punctuation">(</span>raiz<span class="token punctuation">.</span>direita<span class="token punctuation">)</span>

raiz <span class="token operator">=</span> No<span class="token punctuation">(</span><span class="token number">50</span><span class="token punctuation">)</span>
raiz <span class="token operator">=</span> inserir<span class="token punctuation">(</span>raiz<span class="token punctuation">,</span> <span class="token number">30</span><span class="token punctuation">)</span>
raiz <span class="token operator">=</span> inserir<span class="token punctuation">(</span>raiz<span class="token punctuation">,</span> <span class="token number">20</span><span class="token punctuation">)</span>
raiz <span class="token operator">=</span> inserir<span class="token punctuation">(</span>raiz<span class="token punctuation">,</span> <span class="token number">40</span><span class="token punctuation">)</span>
raiz <span class="token operator">=</span> inserir<span class="token punctuation">(</span>raiz<span class="token punctuation">,</span> <span class="token number">70</span><span class="token punctuation">)</span>
raiz <span class="token operator">=</span> inserir<span class="token punctuation">(</span>raiz<span class="token punctuation">,</span> <span class="token number">60</span><span class="token punctuation">)</span>
raiz <span class="token operator">=</span> inserir<span class="token punctuation">(</span>raiz<span class="token punctuation">,</span> <span class="token number">80</span><span class="token punctuation">)</span>

<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Em ordem traversal:"</span><span class="token punctuation">)</span>
em_ordem<span class="token punctuation">(</span>raiz<span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, uma árvore binária é criada e percorrida em ordem.</p>
<hr>
<h3 id="linguagens-de-programação">3. Linguagens de Programação</h3>
<p><strong>3.1 Tipos de Linguagens</strong></p>
<p><strong>Linguagens Orientadas a Objeto</strong></p>
<ul>
<li><strong>Java</strong>: Uma linguagem de programação popular para desenvolvimento web e mobile.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-java"><code class="prism  language-java"><span class="token keyword">public</span> <span class="token keyword">class</span> <span class="token class-name">ExemploJava</span> <span class="token punctuation">{</span>
    <span class="token keyword">public</span> <span class="token keyword">static</span> <span class="token keyword">void</span> <span class="token function">main</span><span class="token punctuation">(</span>String<span class="token punctuation">[</span><span class="token punctuation">]</span> args<span class="token punctuation">)</span> <span class="token punctuation">{</span>
        System<span class="token punctuation">.</span>out<span class="token punctuation">.</span><span class="token function">println</span><span class="token punctuation">(</span><span class="token string">"Hello, World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Neste exemplo, um simples programa Java imprime “Hello, World!”.</p>
<p><strong>C#</strong>: Utilizada principalmente na plataforma .NET.</p>
<ul>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-csharp"><code class="prism  language-csharp"><span class="token keyword">using</span> System<span class="token punctuation">;</span>

<span class="token keyword">class</span> <span class="token class-name">ExemploCSharp</span> <span class="token punctuation">{</span>
    <span class="token keyword">static</span> <span class="token keyword">void</span> <span class="token function">Main</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
        Console<span class="token punctuation">.</span><span class="token function">WriteLine</span><span class="token punctuation">(</span><span class="token string">"Hello, World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Aqui, um programa C# que imprime “Hello, World!”.</p>
<p><strong>Linguagens Procedurais</strong></p>
<ul>
<li><strong>C</strong>: Uma linguagem eficiente para programação de sistemas.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-c"><code class="prism  language-c"><span class="token macro property">#<span class="token directive keyword">include</span> <span class="token string">&lt;stdio.h&gt;</span></span>

<span class="token keyword">int</span> <span class="token function">main</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token function">printf</span><span class="token punctuation">(</span><span class="token string">"Hello, World!\n"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">return</span> <span class="token number">0</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Este exemplo em C imprime “Hello, World!”.</p>
<p><strong>3.2 Ferramentas e Bibliotecas</strong></p>
<p><strong>Java SE, JEE, Microprofile</strong></p>
<ul>
<li><strong>Java SE</strong>: Plataforma Java Standard Edition para aplicações desktop.</li>
<li><strong>Java EE</strong>: Plataforma Java Enterprise Edition para aplicações web.</li>
<li><strong>Microprofile</strong>: APIs para microserviços em Java.</li>
</ul>
<p><strong>Python Bibliotecas</strong></p>
<ul>
<li><strong>Pandas</strong>: Biblioteca para manipulação de dados.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> pandas <span class="token keyword">as</span> pd

data <span class="token operator">=</span> <span class="token punctuation">{</span>
    <span class="token string">'Nome'</span><span class="token punctuation">:</span> <span class="token punctuation">[</span><span class="token string">'Ana'</span><span class="token punctuation">,</span> <span class="token string">'Bruno'</span><span class="token punctuation">,</span> <span class="token string">'Carla'</span><span class="token punctuation">]</span><span class="token punctuation">,</span>
    <span class="token string">'Idade'</span><span class="token punctuation">:</span> <span class="token punctuation">[</span><span class="token number">23</span><span class="token punctuation">,</span> <span class="token number">35</span><span class="token punctuation">,</span> <span class="token number">42</span><span class="token punctuation">]</span>
<span class="token punctuation">}</span>
df <span class="token operator">=</span> pd<span class="token punctuation">.</span>DataFrame<span class="token punctuation">(</span>data<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>df<span class="token punctuation">)</span>
</code></pre>
<p>Este exemplo cria um DataFrame com Pandas.</p>
<ul>
<li><strong>NumPy</strong>: Biblioteca para computação científica.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> numpy <span class="token keyword">as</span> np

array <span class="token operator">=</span> np<span class="token punctuation">.</span>array<span class="token punctuation">(</span><span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">4</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>array<span class="token punctuation">)</span>
</code></pre>
<p>Aqui, um array NumPy é criado e impresso.</p>
<ul>
<li><strong>SciPy</strong>: Biblioteca para matemática e ciência.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> scipy <span class="token keyword">import</span> stats

data <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">4</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">,</span> <span class="token number">6</span><span class="token punctuation">,</span> <span class="token number">7</span><span class="token punctuation">,</span> <span class="token number">8</span><span class="token punctuation">,</span> <span class="token number">9</span><span class="token punctuation">,</span> <span class="token number">10</span><span class="token punctuation">]</span>
mean <span class="token operator">=</span> stats<span class="token punctuation">.</span>tmean<span class="token punctuation">(</span>data<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Mean:"</span><span class="token punctuation">,</span> mean<span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, a média dos dados é calculada usando SciPy.</p>
<ul>
<li><strong>Matplotlib</strong>: Biblioteca de plotagem 2D.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> matplotlib<span class="token punctuation">.</span>pyplot <span class="token keyword">as</span> plt

x <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">4</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">]</span>
y <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">,</span> <span class="token number">7</span><span class="token punctuation">,</span> <span class="token number">11</span><span class="token punctuation">]</span>

plt<span class="token punctuation">.</span>plot<span class="token punctuation">(</span>x<span class="token punctuation">,</span> y<span class="token punctuation">)</span>
plt<span class="token punctuation">.</span>xlabel<span class="token punctuation">(</span><span class="token string">'x'</span><span class="token punctuation">)</span>
plt<span class="token punctuation">.</span>ylabel<span class="token punctuation">(</span><span class="token string">'y'</span><span class="token punctuation">)</span>
plt<span class="token punctuation">.</span>title<span class="token punctuation">(</span><span class="token string">'Exemplo de Gráfico'</span><span class="token punctuation">)</span>
plt<span class="token punctuation">.</span>show<span class="token punctuation">(</span><span class="token punctuation">)</span>
</code></pre>
<p>Este exemplo cria um gráfico simples com Matplotlib.</p>
<ul>
<li><strong>TensorFlow, PyTorch</strong>: Bibliotecas para aprendizado de máquina.</li>
<li><strong>Exemplo Prático com TensorFlow</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> tensorflow <span class="token keyword">as</span> tf

x <span class="token operator">=</span> tf<span class="token punctuation">.</span>constant<span class="token punctuation">(</span><span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
y <span class="token operator">=</span> tf<span class="token punctuation">.</span>constant<span class="token punctuation">(</span><span class="token punctuation">[</span><span class="token number">4</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">,</span> <span class="token number">6</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
result <span class="token operator">=</span> tf<span class="token punctuation">.</span>add<span class="token punctuation">(</span>x<span class="token punctuation">,</span> y<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>result<span class="token punctuation">)</span>
</code></pre>
<p>Aqui, TensorFlow é usado para somar dois arrays.</p>
<ul>
<li><strong>Scikit-learn</strong>: Biblioteca para aprendizado de máquina e mineração de dados.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> sklearn<span class="token punctuation">.</span>linear_model <span class="token keyword">import</span> LinearRegression
<span class="token keyword">import</span> numpy <span class="token keyword">as</span> np

x <span class="token operator">=</span> np<span class="token punctuation">.</span>array<span class="token punctuation">(</span><span class="token punctuation">[</span><span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">]</span><span class="token punctuation">,</span> <span class="token punctuation">[</span><span class="token number">2</span><span class="token punctuation">]</span><span class="token punctuation">,</span> <span class="token punctuation">[</span><span class="token number">3</span><span class="token punctuation">]</span><span class="token punctuation">,</span> <span class="token punctuation">[</span><span class="token number">4</span><span class="token punctuation">]</span><span class="token punctuation">,</span> <span class="token punctuation">[</span><span class="token number">5</span><span class="token punctuation">]</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
y <span class="token operator">=</span> np<span class="token punctuation">.</span>array<span class="token punctuation">(</span><span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">,</span> <span class="token number">7</span><span class="token punctuation">,</span> <span class="token number">9</span><span class="token punctuation">]</span><span class="token punctuation">)</span>

model <span class="token operator">=</span> LinearRegression<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">.</span>fit<span class="token punctuation">(</span>x<span class="token punctuation">,</span> y<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Coeficiente:"</span><span class="token punctuation">,</span> model<span class="token punctuation">.</span>coef_<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Intercepto:"</span><span class="token punctuation">,</span> model<span class="token punctuation">.</span>intercept_<span class="token punctuation">)</span>
</code></pre>
<p>Este exemplo ajusta um modelo de regressão linear usando Scikit-learn.</p>
<hr>
<h3 id="desenvolvimento-de-software-para-a-web">4. Desenvolvimento de Software para a Web</h3>
<p><strong>4.1 Tecnologias Web</strong></p>
<p><strong>Sistemas Distribuídos e Microsserviços</strong></p>
<ul>
<li><strong>Definição</strong>: Sistemas compostos por múltiplos serviços independentes que se comunicam por meio de APIs.</li>
<li><strong>Vantagens</strong>: Escalabilidade, flexibilidade e resiliência.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> flask <span class="token keyword">import</span> Flask<span class="token punctuation">,</span> jsonify

app <span class="token operator">=</span> Flask<span class="token punctuation">(</span>__name__<span class="token punctuation">)</span>

@app<span class="token punctuation">.</span>route<span class="token punctuation">(</span><span class="token string">'/api/dados'</span><span class="token punctuation">,</span> methods<span class="token operator">=</span><span class="token punctuation">[</span><span class="token string">'GET'</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
<span class="token keyword">def</span> <span class="token function">get_dados</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
    dados <span class="token operator">=</span> <span class="token punctuation">{</span><span class="token string">'chave'</span><span class="token punctuation">:</span> <span class="token string">'valor'</span><span class="token punctuation">}</span>
    <span class="token keyword">return</span> jsonify<span class="token punctuation">(</span>dados<span class="token punctuation">)</span>

<span class="token keyword">if</span> __name__ <span class="token operator">==</span> <span class="token string">'__main__'</span><span class="token punctuation">:</span>
    app<span class="token punctuation">.</span>run<span class="token punctuation">(</span>debug<span class="token operator">=</span><span class="token boolean">True</span><span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, um simples serviço web é criado usando Flask, um microframework para Python.</p>
<p><strong>Padrões REST, SOAP</strong></p>
<ul>
<li><strong>REST (Representational State Transfer)</strong>: Usa HTTP e CRUD (Create, Read, Update, Delete).</li>
<li><strong>SOAP (Simple Object Access Protocol)</strong>: Usa XML para troca de informações estruturadas.</li>
<li><strong>Exemplo Prático REST</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> flask <span class="token keyword">import</span> Flask<span class="token punctuation">,</span> jsonify<span class="token punctuation">,</span> request

app <span class="token operator">=</span> Flask<span class="token punctuation">(</span>__name__<span class="token punctuation">)</span>
dados <span class="token operator">=</span> <span class="token punctuation">{</span><span class="token punctuation">}</span>

@app<span class="token punctuation">.</span>route<span class="token punctuation">(</span><span class="token string">'/api/dados/&lt;chave&gt;'</span><span class="token punctuation">,</span> methods<span class="token operator">=</span><span class="token punctuation">[</span><span class="token string">'GET'</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
<span class="token keyword">def</span> <span class="token function">get_dado</span><span class="token punctuation">(</span>chave<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> jsonify<span class="token punctuation">(</span><span class="token punctuation">{</span>chave<span class="token punctuation">:</span> dados<span class="token punctuation">.</span>get<span class="token punctuation">(</span>chave<span class="token punctuation">,</span> <span class="token string">'Não encontrado'</span><span class="token punctuation">)</span><span class="token punctuation">}</span><span class="token punctuation">)</span>

@app<span class="token punctuation">.</span>route<span class="token punctuation">(</span><span class="token string">'/api/dados/&lt;chave&gt;'</span><span class="token punctuation">,</span> methods<span class="token operator">=</span><span class="token punctuation">[</span><span class="token string">'POST'</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
<span class="token keyword">def</span> <span class="token function">add_dado</span><span class="token punctuation">(</span>chave<span class="token punctuation">)</span><span class="token punctuation">:</span>
    valor <span class="token operator">=</span> request<span class="token punctuation">.</span>json<span class="token punctuation">[</span><span class="token string">'valor'</span><span class="token punctuation">]</span>
    dados<span class="token punctuation">[</span>chave<span class="token punctuation">]</span> <span class="token operator">=</span> valor
    <span class="token keyword">return</span> jsonify<span class="token punctuation">(</span><span class="token punctuation">{</span>chave<span class="token punctuation">:</span> valor<span class="token punctuation">}</span><span class="token punctuation">)</span>

<span class="token keyword">if</span> __name__ <span class="token operator">==</span> <span class="token string">'__main__'</span><span class="token punctuation">:</span>
    app<span class="token punctuation">.</span>run<span class="token punctuation">(</span>debug<span class="token operator">=</span><span class="token boolean">True</span><span class="token punctuation">)</span>
</code></pre>
<p>Aqui, um serviço REST simples é criado com Flask.</p>
<p><strong>HTML, XML, JSON</strong></p>
<ul>
<li><strong>HTML (HyperText Markup Language)</strong>: Linguagem de marcação usada para criar páginas web.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-html"><code class="prism  language-html"><span class="token doctype">&lt;!DOCTYPE html&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>html</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>head</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>title</span><span class="token punctuation">&gt;</span></span>Exemplo HTML<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>title</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>head</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>body</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>Hello, World!<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>html</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>Este exemplo cria uma página HTML básica.</p>
<ul>
<li><strong>XML (eXtensible Markup Language)</strong>: Linguagem de marcação usada para transportar e armazenar dados.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-xml"><code class="prism  language-xml"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>livro</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>titulo</span><span class="token punctuation">&gt;</span></span>Exemplo de XML<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>titulo</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>autor</span><span class="token punctuation">&gt;</span></span>Autor Exemplo<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>autor</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>livro</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>Este exemplo cria um documento XML simples.</p>
<ul>
<li><strong>JSON (JavaScript Object Notation)</strong>: Formato leve de troca de dados.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-json"><code class="prism  language-json"><span class="token punctuation">{</span>
    <span class="token string">"nome"</span><span class="token punctuation">:</span> <span class="token string">"Ana"</span><span class="token punctuation">,</span>
    <span class="token string">"idade"</span><span class="token punctuation">:</span> <span class="token number">23</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Aqui, um documento JSON simples é mostrado.</p>
<hr>
<h3 id="teste-de-software-qualidade">5. Teste de Software (Qualidade)</h3>
<p><strong>5.1 Controle de Qualidade</strong></p>
<p><strong>Técnicas de Teste</strong></p>
<ul>
<li>**Teste</li>
</ul>
<p>de Unidade**: Verifica a menor parte testável do software.</p>
<ul>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> unittest

<span class="token keyword">def</span> <span class="token function">soma</span><span class="token punctuation">(</span>a<span class="token punctuation">,</span> b<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> a <span class="token operator">+</span> b

<span class="token keyword">class</span> <span class="token class-name">TestSoma</span><span class="token punctuation">(</span>unittest<span class="token punctuation">.</span>TestCase<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">test_soma</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>assertEqual<span class="token punctuation">(</span>soma<span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">)</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">)</span>

<span class="token keyword">if</span> __name__ <span class="token operator">==</span> <span class="token string">'__main__'</span><span class="token punctuation">:</span>
    unittest<span class="token punctuation">.</span>main<span class="token punctuation">(</span><span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, um teste de unidade para a função <code>soma</code> é criado usando <code>unittest</code>.</p>
<p><strong>Teste de Integração</strong>: Verifica a interação entre módulos.</p>
<ul>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> unittest

<span class="token keyword">class</span> <span class="token class-name">BancoDeDados</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">conectar</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">return</span> <span class="token string">"Conectado ao banco de dados"</span>

<span class="token keyword">class</span> <span class="token class-name">TestBancoDeDados</span><span class="token punctuation">(</span>unittest<span class="token punctuation">.</span>TestCase<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">test_conexao</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        bd <span class="token operator">=</span> BancoDeDados<span class="token punctuation">(</span><span class="token punctuation">)</span>
        self<span class="token punctuation">.</span>assertEqual<span class="token punctuation">(</span>bd<span class="token punctuation">.</span>conectar<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">,</span> <span class="token string">"Conectado ao banco de dados"</span><span class="token punctuation">)</span>

<span class="token keyword">if</span> __name__ <span class="token operator">==</span> <span class="token string">'__main__'</span><span class="token punctuation">:</span>
    unittest<span class="token punctuation">.</span>main<span class="token punctuation">(</span><span class="token punctuation">)</span>
</code></pre>
<p>Aqui, um teste de integração é realizado para verificar a conexão ao banco de dados.</p>
<p><strong>Teste de Sistema</strong>: Verifica o sistema completo.</p>
<ul>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> unittest

<span class="token keyword">def</span> <span class="token function">sistema</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> <span class="token string">"Sistema funcionando corretamente"</span>

<span class="token keyword">class</span> <span class="token class-name">TestSistema</span><span class="token punctuation">(</span>unittest<span class="token punctuation">.</span>TestCase<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">test_sistema</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>assertEqual<span class="token punctuation">(</span>sistema<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">,</span> <span class="token string">"Sistema funcionando corretamente"</span><span class="token punctuation">)</span>

<span class="token keyword">if</span> __name__ <span class="token operator">==</span> <span class="token string">'__main__'</span><span class="token punctuation">:</span>
    unittest<span class="token punctuation">.</span>main<span class="token punctuation">(</span><span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, um teste de sistema simples é criado.</p>
<p><strong>Teste de Aceitação</strong>: Verifica se o sistema atende aos requisitos.</p>
<ul>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> unittest

<span class="token keyword">def</span> <span class="token function">aceitar_requisitos</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> <span class="token string">"Requisitos aceitos"</span>

<span class="token keyword">class</span> <span class="token class-name">TestAceitacao</span><span class="token punctuation">(</span>unittest<span class="token punctuation">.</span>TestCase<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">test_aceitacao</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>assertEqual<span class="token punctuation">(</span>aceitar_requisitos<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">,</span> <span class="token string">"Requisitos aceitos"</span><span class="token punctuation">)</span>

<span class="token keyword">if</span> __name__ <span class="token operator">==</span> <span class="token string">'__main__'</span><span class="token punctuation">:</span>
    unittest<span class="token punctuation">.</span>main<span class="token punctuation">(</span><span class="token punctuation">)</span>
</code></pre>
<p>Aqui, um teste de aceitação é realizado para verificar os requisitos do sistema.</p>
<p><strong>Teste de Regressão</strong>: Garante que novas mudanças não introduzam erros.</p>
<ul>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> unittest

<span class="token keyword">def</span> <span class="token function">funcao_antiga</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> <span class="token string">"Funciona corretamente"</span>

<span class="token keyword">class</span> <span class="token class-name">TestRegressao</span><span class="token punctuation">(</span>unittest<span class="token punctuation">.</span>TestCase<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">def</span> <span class="token function">test_funcao_antiga</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        self<span class="token punctuation">.</span>assertEqual<span class="token punctuation">(</span>funcao_antiga<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">,</span> <span class="token string">"Funciona corretamente"</span><span class="token punctuation">)</span>

<span class="token keyword">if</span> __name__ <span class="token operator">==</span> <span class="token string">'__main__'</span><span class="token punctuation">:</span>
    unittest<span class="token punctuation">.</span>main<span class="token punctuation">(</span><span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, um teste de regressão é criado para verificar uma função existente.</p>
<p><strong>5.2 Automação de Testes</strong></p>
<p><strong>Selenium</strong>: Ferrenter code hereamenta para automação de navegadores web.</p>
<ul>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> selenium <span class="token keyword">import</span> webdriver

driver <span class="token operator">=</span> webdriver<span class="token punctuation">.</span>Chrome<span class="token punctuation">(</span><span class="token punctuation">)</span>
driver<span class="token punctuation">.</span>get<span class="token punctuation">(</span><span class="token string">"http://www.google.com"</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>driver<span class="token punctuation">.</span>title<span class="token punctuation">)</span>
driver<span class="token punctuation">.</span>quit<span class="token punctuation">(</span><span class="token punctuation">)</span>
</code></pre>
<p>Aqui, Selenium é usado para abrir o Google e imprimir o título da página.</p>
<p><strong>Jenkins</strong>: Ferramenta de integração contínua.</p>
<ul>
<li><strong>Configuração Básica</strong>:
<ul>
<li><strong>Instalação</strong>: Baixe e instale Jenkins em seu servidor.</li>
<li><strong>Pipeline</strong>: Crie um pipeline para executar testes automatizados.</li>
</ul>
</li>
</ul>
<p><strong>JUnit</strong>: Framework para testes de unidade em Java.</p>
<ul>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-java"><code class="prism  language-java"><span class="token keyword">import</span> <span class="token keyword">static</span> org<span class="token punctuation">.</span>junit<span class="token punctuation">.</span>Assert<span class="token punctuation">.</span>assertEquals<span class="token punctuation">;</span>
<span class="token keyword">import</span> org<span class="token punctuation">.</span>junit<span class="token punctuation">.</span>Test<span class="token punctuation">;</span>

<span class="token keyword">public</span> <span class="token keyword">class</span> <span class="token class-name">ExemploJUnit</span> <span class="token punctuation">{</span>
    <span class="token annotation punctuation">@Test</span>
    <span class="token keyword">public</span> <span class="token keyword">void</span> <span class="token function">testSoma</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
        <span class="token function">assertEquals</span><span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">1</span> <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Este exemplo mostra um teste de unidade em Java usando JUnit.</p>
<hr>
<h3 id="bancos-de-dados">6. Bancos de Dados</h3>
<p><strong>6.1 Modelagem de Dados</strong></p>
<p><strong>Modelo Entidade-Relacionamento (ER)</strong></p>
<ul>
<li><strong>Definição</strong>: Representação gráfica de entidades e seus relacionamentos.</li>
<li><strong>Exemplo Prático</strong>:<br>
Imagine um modelo ER para uma biblioteca:</li>
<li><strong>Entidades</strong>: Livro, Autor, Empréstimo.</li>
<li><strong>Relacionamentos</strong>: Livro-Escrito por-Autor, Empréstimo-Contém-Livro.</li>
</ul>
<p><strong>6.2 SQL (Structured Query Language)</strong></p>
<p><strong>Comandos SQL</strong></p>
<ul>
<li><strong>CREATE TABLE</strong>: Cria uma nova tabela.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-sql"><code class="prism  language-sql"><span class="token keyword">CREATE</span> <span class="token keyword">TABLE</span> Alunos <span class="token punctuation">(</span>
    ID <span class="token keyword">INT</span> <span class="token keyword">PRIMARY</span> <span class="token keyword">KEY</span><span class="token punctuation">,</span>
    Nome <span class="token keyword">VARCHAR</span><span class="token punctuation">(</span><span class="token number">100</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
    Idade <span class="token keyword">INT</span>
<span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Este comando cria uma tabela <code>Alunos</code> com colunas <code>ID</code>, <code>Nome</code> e <code>Idade</code>.</p>
<ul>
<li><strong>INSERT INTO</strong>: Insere novos registros.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-sql"><code class="prism  language-sql"><span class="token keyword">INSERT</span> <span class="token keyword">INTO</span> Alunos <span class="token punctuation">(</span>ID<span class="token punctuation">,</span> Nome<span class="token punctuation">,</span> Idade<span class="token punctuation">)</span> <span class="token keyword">VALUES</span> <span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token string">'Ana'</span><span class="token punctuation">,</span> <span class="token number">23</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Este comando insere um novo registro na tabela <code>Alunos</code>.</p>
<ul>
<li><strong>SELECT</strong>: Consulta dados.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-sql"><code class="prism  language-sql"><span class="token keyword">SELECT</span> <span class="token operator">*</span> <span class="token keyword">FROM</span> Alunos<span class="token punctuation">;</span>
</code></pre>
<p>Este comando seleciona todos os registros da tabela <code>Alunos</code>.</p>
<ul>
<li><strong>UPDATE</strong>: Atualiza registros existentes.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-sql"><code class="prism  language-sql"><span class="token keyword">UPDATE</span> Alunos <span class="token keyword">SET</span> Idade <span class="token operator">=</span> <span class="token number">24</span> <span class="token keyword">WHERE</span> ID <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span>
</code></pre>
<p>Este comando atualiza a idade do aluno com <code>ID</code> 1 para 24.</p>
<ul>
<li><strong>DELETE</strong>: Remove registros.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-sql"><code class="prism  language-sql"><span class="token keyword">DELETE</span> <span class="token keyword">FROM</span> Alunos <span class="token keyword">WHERE</span> ID <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span>
</code></pre>
<p>Este comando remove o registro do aluno com <code>ID</code> 1.</p>
<p><strong>6.3 NoSQL</strong></p>
<p><strong>MongoDB</strong></p>
<ul>
<li><strong>Definição</strong>: Um banco de dados NoSQL orientado a documentos.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> pymongo <span class="token keyword">import</span> MongoClient

client <span class="token operator">=</span> MongoClient<span class="token punctuation">(</span><span class="token string">'localhost'</span><span class="token punctuation">,</span> <span class="token number">27017</span><span class="token punctuation">)</span>
db <span class="token operator">=</span> client<span class="token punctuation">[</span><span class="token string">'biblioteca'</span><span class="token punctuation">]</span>
colecao <span class="token operator">=</span> db<span class="token punctuation">[</span><span class="token string">'livros'</span><span class="token punctuation">]</span>
livro <span class="token operator">=</span> <span class="token punctuation">{</span><span class="token string">"titulo"</span><span class="token punctuation">:</span> <span class="token string">"Exemplo de MongoDB"</span><span class="token punctuation">,</span> <span class="token string">"autor"</span><span class="token punctuation">:</span> <span class="token string">"Autor Exemplo"</span><span class="token punctuation">}</span>
colecao<span class="token punctuation">.</span>insert_one<span class="token punctuation">(</span>livro<span class="token punctuation">)</span>
</code></pre>
<p>Neste exemplo, um documento é inserido em uma coleção MongoDB.</p>
<p><strong>Redis</strong></p>
<ul>
<li><strong>Definição</strong>: Um banco de dados em memória, chave-valor.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> redis

r <span class="token operator">=</span> redis<span class="token punctuation">.</span>Redis<span class="token punctuation">(</span>host<span class="token operator">=</span><span class="token string">'localhost'</span><span class="token punctuation">,</span> port<span class="token operator">=</span><span class="token number">6379</span><span class="token punctuation">,</span> db<span class="token operator">=</span><span class="token number">0</span><span class="token punctuation">)</span>
r<span class="token punctuation">.</span><span class="token builtin">set</span><span class="token punctuation">(</span><span class="token string">'chave'</span><span class="token punctuation">,</span> <span class="token string">'valor'</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>r<span class="token punctuation">.</span>get<span class="token punctuation">(</span><span class="token string">'chave'</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<p>Aqui, um valor é armazenado e recuperado usando Redis.</p>
<p><strong>Cassandra</strong></p>
<ul>
<li><strong>Definição</strong>: Um banco de dados distribuído, orientado a colunas.</li>
<li><strong>Exemplo Prático</strong>:</li>
</ul>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> cassandra<span class="token punctuation">.</span>cluster <span class="token keyword">import</span> Cluster

cluster <span class="token operator">=</span> Cluster<span class="token punctuation">(</span><span class="token punctuation">[</span><span class="token string">'127.0.0.1'</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
session <span class="token operator">=</span> cluster<span class="token punctuation">.</span>connect<span class="token punctuation">(</span><span class="token punctuation">)</span>
session<span class="token punctuation">.</span>execute<span class="token punctuation">(</span><span class="token string">"CREATE KEYSPACE IF NOT EXISTS exemplo WITH replication = {'class': 'SimpleStrategy', 'replication_factor': '1'}"</span><span class="token punctuation">)</span>
session<span class="token punctuation">.</span>execute<span class="token punctuation">(</span><span class="token string">"CREATE TABLE IF NOT EXISTS exemplo.livros (id UUID PRIMARY KEY, titulo text, autor text)"</span><span class="token punctuation">)</span>
</code></pre>
<p>Este exemplo cria um keyspace e uma tabela em Cassandra.</p>
<hr>
<h3 id="agilidade">7. Agilidade</h3>
<p><strong>7.1 Métodos Ágeis</strong></p>
<p><strong>Scrum</strong></p>
<ul>
<li><strong>Definição</strong>: Um framework ágil para gerenciamento de projetos.</li>
<li><strong>Papéis</strong>: Product Owner, Scrum Master, Time de Desenvolvimento.</li>
<li><strong>Eventos</strong>: Sprint, Planejamento da Sprint, Daily Scrum, Revisão da Sprint, Retrospectiva da Sprint.</li>
<li><strong>Artefatos</strong>: Product Backlog, Sprint Backlog, Incremento.</li>
</ul>
<p><strong>Exemplo Prático</strong>:<br>
Imagine um projeto de desenvolvimento de um site. O Product Owner prioriza as funcionalidades no Product Backlog. Durante o Planejamento da Sprint, o time escolhe as tarefas para a Sprint. Diariamente, o time se reúne para a Daily Scrum, discutindo o progresso e os impedimentos. No final da Sprint, o time apresenta o Incremento na Revisão da Sprint e discute melhorias na Retrospectiva.</p>
<p><strong>Kanban</strong></p>
<ul>
<li><strong>Definição</strong>: Método ágil para gerenciar o trabalho com foco na visualização do fluxo de trabalho.</li>
<li><strong>Componentes</strong>: Quadro Kanban, Cartões Kanban, Colunas (A Fazer, Em Progresso, Concluído).</li>
</ul>
<p><strong>Exemplo Prático</strong>:<br>
Imagine um quadro Kanban para o mesmo projeto de desenvolvimento de um site. As tarefas são movidas entre as colunas, do “A Fazer” para “Em Progresso” e finalmente para “Concluído”, visualizando o fluxo de trabalho e identificando gargalos.</p>
<hr>
<h3 id="organização-e-arquitetura-de-computadores">8. Organização e Arquitetura de Computadores</h3>
<p><strong>8.1 Arquitetura de Computadores</strong></p>
<p><strong>Conceitos Básicos</strong></p>
<ul>
<li><strong>CPU (Unidade Central de Processamento)</strong>: O cérebro do computador, responsável por executar instruções.</li>
<li><strong>Memória RAM (Random Access Memory)</strong>: Memória de acesso rápido usada para armazenar dados temporários.</li>
<li><strong>Memória ROM (Read-Only Memory)</strong>: Memória de acesso somente leitura, usada para armazenar firmware.</li>
<li><strong>Armazenamento</strong>: Dispositivos como HDDs e SSDs usados para armazenar dados permanentemente.</li>
</ul>
<p><strong>Componentes de um Computador</strong></p>
<ul>
<li><strong>Processador</strong>: Realiza operações aritméticas e lógicas.</li>
<li><strong>Placa-mãe</strong>: Conecta todos os componentes do computador.</li>
<li><strong>Memória</strong>: Armazena dados e instruções temporariamente.</li>
<li><strong>Dispositivos de Entrada/Saída</strong>: Incluem teclado, mouse, monitor, impressora.</li>
</ul>
<p><strong>Exemplo Prático</strong>:<br>
Imagine montar um computador. Você precisa de um processador para executar as instruções, memória RAM para armazenar dados temporários, uma placa-mãe para conectar todos os componentes e dispositivos de entrada/saída para interagir com o computador.</p>
<p>**8.</p>
<p>2 Sistemas de Numeração**</p>
<p><strong>Binário, Decimal, Hexadecimal</strong></p>
<ul>
<li><strong>Binário</strong>: Base 2, usa 0 e 1.</li>
<li><strong>Decimal</strong>: Base 10, usa 0-9.</li>
<li><strong>Hexadecimal</strong>: Base 16, usa 0-9 e A-F.</li>
</ul>
<p><strong>Conversões</strong></p>
<ul>
<li><strong>Binário para Decimal</strong>:
<ul>
<li><strong>Exemplo</strong>: <code>1010</code> (binário) = <code>10</code> (decimal)</li>
</ul>
</li>
<li><strong>Decimal para Binário</strong>:
<ul>
<li><strong>Exemplo</strong>: <code>10</code> (decimal) = <code>1010</code> (binário)</li>
</ul>
</li>
<li><strong>Decimal para Hexadecimal</strong>:
<ul>
<li><strong>Exemplo</strong>: <code>255</code> (decimal) = <code>FF</code> (hexadecimal)</li>
</ul>
</li>
<li><strong>Hexadecimal para Decimal</strong>:
<ul>
<li><strong>Exemplo</strong>: <code>FF</code> (hexadecimal) = <code>255</code> (decimal)</li>
</ul>
</li>
</ul>
<p><strong>Exemplo Prático</strong>:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">binario_para_decimal</span><span class="token punctuation">(</span>binario<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> <span class="token builtin">int</span><span class="token punctuation">(</span>binario<span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">)</span>

<span class="token keyword">def</span> <span class="token function">decimal_para_binario</span><span class="token punctuation">(</span>decimal<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> <span class="token builtin">bin</span><span class="token punctuation">(</span>decimal<span class="token punctuation">)</span><span class="token punctuation">[</span><span class="token number">2</span><span class="token punctuation">:</span><span class="token punctuation">]</span>

<span class="token keyword">print</span><span class="token punctuation">(</span>binario_para_decimal<span class="token punctuation">(</span><span class="token string">'1010'</span><span class="token punctuation">)</span><span class="token punctuation">)</span>  <span class="token comment"># Saída: 10</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>decimal_para_binario<span class="token punctuation">(</span><span class="token number">10</span><span class="token punctuation">)</span><span class="token punctuation">)</span>      <span class="token comment"># Saída: 1010</span>
</code></pre>
<p>Neste exemplo, funções Python convertem entre binário e decimal.</p>
<p><strong>8.3 Processadores e Memória</strong></p>
<p><strong>Ciclo de Instrução</strong></p>
<ul>
<li><strong>Fase de Busca</strong>: A CPU busca a próxima instrução da memória.</li>
<li><strong>Fase de Decodificação</strong>: A CPU decodifica a instrução.</li>
<li><strong>Fase de Execução</strong>: A CPU executa a instrução.</li>
</ul>
<p><strong>Exemplo Prático</strong>:<br>
Imagine a CPU executando um programa. Ela busca a instrução <code>ADD A, B</code> da memória, decodifica para entender que precisa somar os valores nos registradores <code>A</code> e <code>B</code>, e executa a soma, armazenando o resultado em <code>A</code>.</p>
<hr>
<h3 id="conclusão">Conclusão</h3>
<p>Este guia fornece uma visão abrangente dos tópicos abordados na Prova de Avaliação de Conhecimentos para o Técnico Superior Profissional de Informática no concurso público em Portugal. Com exemplos práticos, esperamos que ajude no estudo e preparação para a prova. Boa sorte!</p>

