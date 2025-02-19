---
id: release_notes.md
summary: Notas de lançamento do Milvus
title: Notas de lançamento
---
<h1 id="Release-Notes" class="common-anchor-header">Notas de lançamento<button data-href="#Release-Notes" class="anchor-icon" translate="no">
      <svg translate="no"
        aria-hidden="true"
        focusable="false"
        height="20"
        version="1.1"
        viewBox="0 0 16 16"
        width="16"
      >
        <path
          fill="#0092E4"
          fill-rule="evenodd"
          d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"
        ></path>
      </svg>
    </button></h1><p>Descubra o que há de novo no Milvus! Esta página resume as novas funcionalidades, melhorias, problemas conhecidos e correcções de erros em cada versão. Pode encontrar as notas de lançamento para cada versão lançada após a v2.4.0 nesta secção. Sugerimos que visite regularmente esta página para se informar sobre as actualizações.</p>
<h2 id="v249" class="common-anchor-header">v2.4.9<button data-href="#v249" class="anchor-icon" translate="no">
      <svg translate="no"
        aria-hidden="true"
        focusable="false"
        height="20"
        version="1.1"
        viewBox="0 0 16 16"
        width="16"
      >
        <path
          fill="#0092E4"
          fill-rule="evenodd"
          d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"
        ></path>
      </svg>
    </button></h2><p>Data de lançamento: 20 de agosto de 2024</p>
<table>
<thead>
<tr><th>Versão do Milvus</th><th>Versão do Python SDK</th><th>Versão do Java SDK</th><th>Versão do SDK do Node.js</th></tr>
</thead>
<tbody>
<tr><td>2.4.9</td><td>2.4.5</td><td>2.4.3</td><td>2.4.4</td></tr>
</tbody>
</table>
<p>O Milvus v2.4.9 resolve um problema crítico que poderia retornar resultados inferiores ao limite (topk) em alguns casos de canto e inclui várias melhorias importantes para melhorar o desempenho e a usabilidade da plataforma.</p>
<h3 id="Critical-fixes" class="common-anchor-header">Correcções críticas</h3><ul>
<li>Excluído o segmento l0 do snapshot legível<a href="https://github.com/milvus-io/milvus/pull/35510">(#35510</a>).</li>
</ul>
<h3 id="Improvements" class="common-anchor-header">Melhorias</h3><ul>
<li>Removida a criação duplicada de ajudante de esquema no proxy<a href="https://github.com/milvus-io/milvus/pull/35502">(#35502</a>).</li>
<li>Adicionado suporte para compilação do Milvus no Ubuntu 20.04<a href="https://github.com/milvus-io/milvus/pull/35457">(#35457</a>).</li>
<li>Optimizado o uso de bloqueios e evitado o double flush do escritor de buffer de clustering<a href="https://github.com/milvus-io/milvus/pull/35490">(#35490</a>).</li>
<li>Removido o log inválido<a href="https://github.com/milvus-io/milvus/pull/35473">(#35473</a>).</li>
<li>Adicionado um documento de guia de utilizador de compactação de clustering<a href="https://github.com/milvus-io/milvus/pull/35428">(#35428</a>).</li>
<li>Adicionado suporte para campos dinâmicos no auxiliar de esquema<a href="https://github.com/milvus-io/milvus/pull/35469">(#35469</a>).</li>
<li>Adicionada a secção msgchannel no YAML gerado<a href="https://github.com/milvus-io/milvus/pull/35466">(#35466</a>).</li>
</ul>
<h2 id="v248" class="common-anchor-header">v2.4.8<button data-href="#v248" class="anchor-icon" translate="no">
      <svg translate="no"
        aria-hidden="true"
        focusable="false"
        height="20"
        version="1.1"
        viewBox="0 0 16 16"
        width="16"
      >
        <path
          fill="#0092E4"
          fill-rule="evenodd"
          d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"
        ></path>
      </svg>
    </button></h2><p>Data de lançamento: 14 de agosto de 2024</p>
<table>
<thead>
<tr><th>Versão do Milvus</th><th>Versão do Python SDK</th><th>Versão do Java SDK</th><th>Versão do SDK do Node.js</th></tr>
</thead>
<tbody>
<tr><td>2.4.8</td><td>2.4.5</td><td>2.4.3</td><td>2.4.4</td></tr>
</tbody>
</table>
<p>O Milvus 2.4.8 introduziu várias melhorias significativas no desempenho e na estabilidade do sistema. A caraterística mais notável foi a implementação da compactação de clustering, um mecanismo que melhora a eficiência da pesquisa e consulta redistribuindo dados em grandes colecções com base numa chave de clustering designada, reduzindo a quantidade de dados digitalizados. A compactação também foi desacoplada do DataNode do fragmento, permitindo que qualquer DataNode execute a compactação de forma independente, o que melhorou a tolerância a falhas, a estabilidade, o desempenho e a escalabilidade. Além disso, a interface entre os componentes Go e C++ foi refatorada para usar chamadas CGO assíncronas, resolvendo problemas como timeouts de sessão, enquanto várias outras otimizações de desempenho foram feitas com base na criação de perfis. As dependências da aplicação também foram actualizadas para resolver vulnerabilidades de segurança conhecidas. Além disso, esta versão também inclui várias optimizações de desempenho e correcções de erros críticos.</p>
<h3 id="Features" class="common-anchor-header">Caraterísticas</h3><ul>
<li>Implementação da compactação de clustering, permitindo que os dados sejam redistribuídos com base numa chave de clustering designada para melhorar a eficiência da consulta<a href="https://github.com/milvus-io/milvus/pull/34326">(#34326</a>),<a href="https://github.com/milvus-io/milvus/pull/34363">(#34363</a>).</li>
</ul>
<h3 id="Improvements" class="common-anchor-header">Melhorias</h3><ul>
<li>Implementadas capacidades de pesquisa e recuperação assíncronas no CGO.<a href="https://github.com/milvus-io/milvus/pull/34200">(#34200</a>)</li>
<li>Separado o processo de compactação do Shard DataNode para melhorar a modularidade do sistema.<a href="https://github.com/milvus-io/milvus/pull/34157">(#34157</a>)</li>
<li>Adicionado suporte para pooling de clientes no QueryNode dentro do proxy/delegator para melhorar o desempenho.<a href="https://github.com/milvus-io/milvus/pull/35195">(#35195</a>)</li>
<li>Sonic integrado para minimizar a sobrecarga da CPU durante o marshaling e unmarshaling JSON nos manipuladores Gin e RestfulV1.<a href="https://github.com/milvus-io/milvus/pull/35018">(#35018</a>)</li>
<li>Introduzido um cache na memória para otimizar a recuperação de resultados de autenticação.<a href="https://github.com/milvus-io/milvus/pull/35272">(#35272</a>)</li>
<li>Modificado o tipo de métrica padrão para autoindexação. [<a href="https://github.com/milvus-io/milvus/pull/34277">#34277</a>, <a href="https://github.com/milvus-io/milvus/pull/34479">#34479</a>]</li>
<li>Refactorizado o formato de memória em tempo de execução para colunas variáveis, levando à redução da utilização de memória.<a href="https://github.com/milvus-io/milvus/pull/34367">[#34367</a>, <a href="https://github.com/milvus-io/milvus/pull/35012">#35012</a>, <a href="https://github.com/milvus-io/milvus/pull/35041">#35041</a>]</li>
<li>Processos de compactação refatorados para permitir o armazenamento de dados persistentes.<a href="https://github.com/milvus-io/milvus/pull/34268">(#34268</a>)</li>
<li>Ativado o suporte de ficheiros memory-mapped para segmentos crescentes, melhorando a gestão da memória.<a href="https://github.com/milvus-io/milvus/pull/34110">(#34110</a>)</li>
<li>Registos de acesso melhorados, adicionando suporte a API RESTful, níveis de consistência de registo e distinção entre erros do sistema e do utilizador.<a href="https://github.com/milvus-io/milvus/pull/34295">[#34295</a>, <a href="https://github.com/milvus-io/milvus/pull/34352">#34352</a>, <a href="https://github.com/milvus-io/milvus/pull/34396">#34396</a>]</li>
<li>Utilizado o novo parâmetro <code translate="no">range_search_k</code> no Knowhere para acelerar as pesquisas de intervalo.<a href="https://github.com/milvus-io/milvus/pull/34709">(#34709</a>)</li>
<li>Aplicados filtros Bloom bloqueados para aumentar a velocidade de construção e consulta de filtros.<a href="https://github.com/milvus-io/milvus/pull/34377">[#34377</a>, <a href="https://github.com/milvus-io/milvus/pull/34922">#34922</a>]</li>
<li>Melhorias na utilização da memória:<ul>
<li>Espaço pré-alocado para os buffers de inserção do DataNode.<a href="https://github.com/milvus-io/milvus/pull/34205">(#34205</a>)</li>
<li>Pré-alocado <code translate="no">FieldData</code> para operações Reduce.<a href="https://github.com/milvus-io/milvus/pull/34254">(#34254</a>)</li>
<li>Registos libertados no codec de eliminação para evitar fugas de memória.<a href="https://github.com/milvus-io/milvus/pull/34506">(#34506</a>)</li>
<li>Controlado o nível de concorrência do gestor de ficheiros do disco durante o carregamento de ficheiros.<a href="https://github.com/milvus-io/milvus/pull/35282">(#35282</a>)</li>
<li>Optimizada a lógica de recolha de lixo em tempo de execução do Go para libertação atempada de memória.<a href="https://github.com/milvus-io/milvus/pull/34950">(#34950</a>)</li>
<li>Implementada uma nova política de selagem para segmentos crescentes.<a href="https://github.com/milvus-io/milvus/pull/34779">(#34779</a>)</li>
</ul></li>
<li>Melhorias no DataCoord:<ul>
<li>Reduzida a utilização da CPU.<a href="https://github.com/milvus-io/milvus/pull/34231">[#34231</a>, <a href="https://github.com/milvus-io/milvus/pull/34309">#34309</a>]</li>
<li>Implementada uma lógica de saída de recolha de lixo mais rápida.<a href="https://github.com/milvus-io/milvus/pull/35051">(#35051</a>)</li>
<li>Melhoria dos algoritmos de agendamento dos nós de trabalho.<a href="https://github.com/milvus-io/milvus/pull/34382">(#34382</a>)</li>
<li>Algoritmo de controlo de tamanho de segmento melhorado especificamente para operações de importação.<a href="https://github.com/milvus-io/milvus/pull/35149">(#35149</a>)</li>
</ul></li>
<li>Melhorias no algoritmo de balanceamento de carga:<ul>
<li>Reduzido o fator de sobrecarga de memória no delegador.<a href="https://github.com/milvus-io/milvus/pull/35164">(#35164</a>)</li>
<li>Atribuído um tamanho de memória fixo para o delegador.<a href="https://github.com/milvus-io/milvus/pull/34600">(#34600</a>)</li>
<li>Evitada a atribuição excessiva de segmentos e canais para novos nós de consulta.<a href="https://github.com/milvus-io/milvus/pull/34245">(#34245</a>)</li>
<li>Reduzido o número de tarefas por ciclo de agendamento pelo Coordenador de Consultas, aumentando a frequência de agendamento.<a href="https://github.com/milvus-io/milvus/pull/34987">(#34987</a>)</li>
<li>Melhoria do algoritmo de equilíbrio de canais no DataNode.<a href="https://github.com/milvus-io/milvus/pull/35033">(#35033</a>)</li>
</ul></li>
<li>Métricas do sistema expandidas: Adicionadas novas métricas em vários componentes para monitorizar aspectos específicos, incluindo:<ul>
<li>Estado de escrita forçada de negação.<a href="https://github.com/milvus-io/milvus/pull/34989">(#34989</a>)</li>
<li>Latência da fila.<a href="https://github.com/milvus-io/milvus/pull/34788">(#34788</a>)</li>
<li>Quota de disco.<a href="https://github.com/milvus-io/milvus/pull/35306">(#35306</a>)</li>
<li>Tempo de execução da tarefa.<a href="https://github.com/milvus-io/milvus/pull/35141">(#35141</a>)</li>
<li>Tamanho do binlog.<a href="https://github.com/milvus-io/milvus/pull/35235">(#35235</a>)</li>
<li>Taxa de inserção.<a href="https://github.com/milvus-io/milvus/pull/35188">(#35188</a>)</li>
<li>Nível de água alto da memória.<a href="https://github.com/milvus-io/milvus/pull/35188">(#35188</a>)</li>
<li>Métricas da API RESTful.<a href="https://github.com/milvus-io/milvus/pull/35083">(#35083</a>)</li>
<li>Latência de pesquisa.<a href="https://github.com/milvus-io/milvus/pull/34783">(#34783</a>)</li>
</ul></li>
</ul>
<h3 id="Changes" class="common-anchor-header">Alterações</h3><ul>
<li><p>Para utilizadores de código aberto, esta versão altera os tipos de métricas no AutoIndex para <code translate="no">FloatVector</code> e <code translate="no">BinaryVector</code> para <code translate="no">Cosine</code> e <code translate="no">Hamming</code>, respetivamente.</p></li>
<li><p><strong>Versões corrigidas de dependências de terceiros</strong>:</p>
<ul>
<li>Este lançamento introduz versões fixas para certas bibliotecas de dependência de terceiros, melhorando significativamente a gestão da cadeia de fornecimento de software da Milvus.</li>
<li>Ao isolar o projeto das alterações a montante, protege as construções diárias de potenciais interrupções.</li>
<li>A atualização assegura a estabilidade ao alojar exclusivamente pacotes validados C++ de terceiros no JFrog Cloud e ao utilizar as Revisões de Receitas Conan (RREV).</li>
<li>Esta abordagem atenua o risco de quebra de alterações de atualizações no ConanCenter.</li>
<li>Os desenvolvedores que usam o Ubuntu 22.04 se beneficiarão imediatamente dessas alterações. No entanto, os programadores de outros sistemas operativos poderão ter de atualizar a sua versão do <code translate="no">glibc</code> para evitar problemas de compatibilidade.</li>
</ul></li>
</ul>
<h3 id="Critical-bug-fixes" class="common-anchor-header">Correções de erros críticos</h3><ul>
<li>Corrigido um problema em que os dados de exclusão eram perdidos devido à omissão de segmentos durante a compactação L0.<a href="https://github.com/milvus-io/milvus/pull/33980">[#33980</a>, <a href="https://github.com/milvus-io/milvus/pull/34363">#34363</a>]</li>
<li>Corrigido um problema em que as mensagens de eliminação não eram encaminhadas devido ao tratamento incorreto do âmbito dos dados.<a href="https://github.com/milvus-io/milvus/pull/35313">(#35313</a>)</li>
<li>Resolvida uma exceção SIGBUS que ocorria devido à utilização incorrecta de <code translate="no">mmap</code>.<a href="https://github.com/milvus-io/milvus/pull/34455">[#34455</a>, <a href="https://github.com/milvus-io/milvus/pull/34530">#34530</a>]</li>
<li>Corrigidos os crashes causados por expressões de pesquisa ilegais.<a href="https://github.com/milvus-io/milvus/pull/35307">(#35307</a>)</li>
<li>Corrigido um problema em que o DataNode watch falhava devido a uma definição incorrecta de tempo limite no contexto do watch.<a href="https://github.com/milvus-io/milvus/pull/35017">(#35017</a>)</li>
</ul>
<h3 id="Bug-fixes" class="common-anchor-header">Correcções de erros</h3><ul>
<li>Resolvidas vulnerabilidades de segurança através da atualização de certas dependências.<a href="https://github.com/milvus-io/milvus/pull/33927">[#33927</a>, <a href="https://github.com/milvus-io/milvus/pull/34693">#34693</a>]</li>
<li>Corrigido um erro de análise despoletado por expressões excessivamente longas.<a href="https://github.com/milvus-io/milvus/pull/34957">(#34957</a>)</li>
<li>Resolvida uma fuga de memória que ocorria durante a análise do plano de consulta.<a href="https://github.com/milvus-io/milvus/pull/34932">(#34932</a>)</li>
<li>Corrigido um problema onde as modificações do nível de registo dinâmico não estavam a ter efeito.<a href="https://github.com/milvus-io/milvus/pull/34777">(#34777</a>)</li>
<li>Resolvido um problema onde o grupo por consultas em dados crescentes falhava devido a offsets de segmento não inicializados.<a href="https://github.com/milvus-io/milvus/pull/34750">(#34750</a>)</li>
<li>Corrigida a definição dos parâmetros de pesquisa ao utilizar o iterador Knowhere.<a href="https://github.com/milvus-io/milvus/pull/34732">(#34732</a>)</li>
<li>Revisto a lógica para verificar o estado da carga da partição.<a href="https://github.com/milvus-io/milvus/pull/34305">(#34305</a>)</li>
<li>Corrigido um problema em que as actualizações da cache de privilégios falhavam devido a erros de pedidos não tratados.<a href="https://github.com/milvus-io/milvus/pull/34697">(#34697</a>)</li>
<li>Resolvida uma falha na recuperação da coleção carregada após o reinício do QueryCoord.<a href="https://github.com/milvus-io/milvus/pull/35211">(#35211</a>)</li>
<li>Corrigido um problema de idempotência de carga, removendo a validação desnecessária de parâmetros de índice.<a href="https://github.com/milvus-io/milvus/pull/35179">(#35179</a>)</li>
<li>Assegurado que o <code translate="no">compressBinlog</code> é executado para permitir que o <code translate="no">reloadFromKV</code> preencha corretamente o <code translate="no">logID</code> do binlog após o DataCoord reiniciar.<a href="https://github.com/milvus-io/milvus/pull/34062">(#34062</a>)</li>
<li>Foi corrigido um problema em que os metadados da coleção não eram removidos após a recolha de lixo no DataCoord.<a href="https://github.com/milvus-io/milvus/pull/34884">(#34884</a>)</li>
<li>Resolvido um vazamento de memória no SegmentManager dentro do DataCoord, removendo os segmentos de descarga gerados através de importações.<a href="https://github.com/milvus-io/milvus/pull/34651">(#34651</a>)</li>
<li>Corrigido um problema de pânico quando a compactação era desactivada e uma coleção era abandonada.<a href="https://github.com/milvus-io/milvus/pull/34206">(#34206</a>)</li>
<li>Foi corrigido um problema de falta de memória no DataNode, melhorando o algoritmo de estimativa de uso de memória.<a href="https://github.com/milvus-io/milvus/pull/34203">(#34203</a>)</li>
<li>Prevenido o uso de memória quando vários pedidos de recuperação de vetor atingem uma falha de cache, implementando singleflight para cache de pedaços.<a href="https://github.com/milvus-io/milvus/pull/34283">(#34283</a>)</li>
<li>Capturado <code translate="no">ErrKeyNotFound</code> durante operações CAS (Compare and Swap) na configuração.<a href="https://github.com/milvus-io/milvus/pull/34489">(#34489</a>)</li>
<li>Corrigido um problema em que as actualizações de configuração falhavam devido à utilização errada do valor formatado numa operação CAS.<a href="https://github.com/milvus-io/milvus/pull/34373">(#34373</a>)</li>
</ul>
<h3 id="Miscellaneous" class="common-anchor-header">Diversos</h3><ul>
<li>Adicionado suporte para o exportador HTTP OTLP, melhorando a observabilidade e as capacidades de monitorização. [<a href="https://github.com/milvus-io/milvus/pull/35073">#35073</a>, <a href="https://github.com/milvus-io/milvus/pull/35299">#35299</a>]</li>
<li>Funcionalidade da base de dados melhorada através da introdução de propriedades como "max collections" e "disk quota", que podem agora ser modificadas dinamicamente.<a href="https://github.com/milvus-io/milvus/pull/34511">[#34511</a>, <a href="https://github.com/milvus-io/milvus/pull/34386">#34386</a>]</li>
<li>Adicionadas capacidades de rastreio para processos de compactação L0 no DataNode para melhorar o diagnóstico e a monitorização.<a href="https://github.com/milvus-io/milvus/pull/33898">(#33898</a>)</li>
<li>Introduzida a configuração de quotas para o número de entradas de segmentos L0 por coleção, permitindo um melhor controlo sobre as taxas de eliminação através da aplicação de contrapressão.<a href="https://github.com/milvus-io/milvus/pull/34837">(#34837</a>)</li>
<li>Estendido o mecanismo de limitação de taxa para operações de inserção para também cobrir operações de upsert, garantindo um desempenho consistente sob alta carga.<a href="https://github.com/milvus-io/milvus/pull/34616">(#34616</a>)</li>
<li>Implementado um grupo CGO dinâmico para chamadas CGO proxy, optimizando a utilização de recursos e o desempenho.<a href="https://github.com/milvus-io/milvus/pull/34842">(#34842</a>)</li>
<li>Activada a opção de compilação DiskAnn para os sistemas operativos Ubuntu, Rocky e Amazon, melhorando a compatibilidade e o desempenho nestas plataformas.<a href="https://github.com/milvus-io/milvus/pull/34244">(#34244</a>)</li>
<li>Atualizado o Conan para a versão 1.64.1, assegurando a compatibilidade com as últimas funcionalidades e melhorias.<a href="https://github.com/milvus-io/milvus/pull/35216">(#35216</a>)</li>
<li>Atualizado o Knowhere para a versão 2.3.7, trazendo melhorias de desempenho e novas funcionalidades.<a href="https://github.com/milvus-io/milvus/pull/34709">(#34709</a>)</li>
<li>Corrigida a revisão de pacotes específicos de terceiros para garantir compilações consistentes e reduzir o risco de alterações inesperadas.<a href="https://github.com/milvus-io/milvus/pull/35316">(#35316</a>)</li>
</ul>
<h2 id="v246" class="common-anchor-header">v2.4.6<button data-href="#v246" class="anchor-icon" translate="no">
      <svg translate="no"
        aria-hidden="true"
        focusable="false"
        height="20"
        version="1.1"
        viewBox="0 0 16 16"
        width="16"
      >
        <path
          fill="#0092E4"
          fill-rule="evenodd"
          d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"
        ></path>
      </svg>
    </button></h2><p>Data de lançamento: 16 de julho de 2024</p>
<table>
<thead>
<tr><th>Versão do Milvus</th><th>Versão do Python SDK</th><th>Versão do Java SDK</th><th>Versão do SDK do Node.js</th></tr>
</thead>
<tbody>
<tr><td>2.4.6</td><td>2.4.4</td><td>2.4.2</td><td>2.4.4</td></tr>
</tbody>
</table>
<p>O Milvus v2.4.6 é uma versão de correção de erros que resolve problemas críticos como panics, fugas de memória e perda de dados durante as eliminações. Também introduz várias optimizações, incluindo melhorias nas métricas de monitorização, atualização da versão Go para 1.21 e melhoria da experiência do utilizador para consultas RESTful count(*).</p>
<h3 id="Improvements" class="common-anchor-header">Melhorias</h3><ul>
<li>Melhorada a facilidade de utilização das consultas RESTful API<a href="https://github.com/milvus-io/milvus/pull/34444">(#34444</a>).</li>
<li>Atualizada a versão Go de 1.20 para 1.21<a href="https://github.com/milvus-io/milvus/pull/33940">(#33940</a>).</li>
<li>Otimizado o balde de métrica de histograma para uma granularidade mais fina no balde<a href="https://github.com/milvus-io/milvus/pull/34592">(#34592</a>).</li>
<li>Atualizada a versão de dependência do Pulsar de 2.8.2 para 2.9.5. É recomendado atualizar o Pulsar para 2.9.5 desde o Milvus 2.4.6.</li>
</ul>
<h3 id="Bug-fixes" class="common-anchor-header">Correções de erros</h3><ul>
<li>Corrigido um problema onde a API GetReplicas retornava um status nulo<a href="https://github.com/milvus-io/milvus/pull/34019">(#34019</a>).</li>
<li>Corrigido um problema em que as consultas podiam retornar registos apagados<a href="https://github.com/milvus-io/milvus/pull/34502">(#34502</a>).</li>
<li>Foi resolvido um problema em que o IndexNode ficava preso durante a paragem devido a um controlo de tempo de vida incorreto<a href="https://github.com/milvus-io/milvus/pull/34559">(#34559</a>).</li>
<li>Corrigida uma fuga de memória de objectos oracle de chave primária quando um trabalhador está offline<a href="https://github.com/milvus-io/milvus/pull/34020">(#34020</a>).</li>
<li>Corrigido o ChannelManagerImplV2 para notificar o Node correto, abordando questões de captura de parâmetros no encerramento do loop<a href="https://github.com/milvus-io/milvus/pull/34004">(#34004</a>).</li>
<li>Corrigida uma corrida de dados de leitura-escrita em ImportTask segmentsInfo implementando uma cópia profunda<a href="https://github.com/milvus-io/milvus/pull/34126">(#34126</a>).</li>
<li>Corrigida a informação de versão para a opção de configuração "legacyVersionWithoutRPCWatch" para evitar erros durante actualizações contínuas<a href="https://github.com/milvus-io/milvus/pull/34185">(#34185</a>).</li>
<li>Corrigida a métrica para o número de partições carregadas<a href="https://github.com/milvus-io/milvus/pull/34195">(#34195</a>).</li>
<li>Passou a configuração <code translate="no">otlpSecure</code> ao configurar o rastreio segcore<a href="https://github.com/milvus-io/milvus/pull/34210">(#34210</a>).</li>
<li>Corrigido um problema em que as propriedades do DataCoord eram substituídas por engano<a href="https://github.com/milvus-io/milvus/pull/34240">(#34240</a>).</li>
<li>Resolvido um problema de perda de dados causado pela fusão errónea de dois fluxos de mensagens recentemente criados<a href="https://github.com/milvus-io/milvus/pull/34563">(#34563</a>).</li>
<li>Resolvido um pânico causado pelo msgstream tentando consumir um pchannel inválido<a href="https://github.com/milvus-io/milvus/pull/34230">(#34230</a>).</li>
<li>Resolvido um problema onde as importações podiam gerar ficheiros órfãos<a href="https://github.com/milvus-io/milvus/pull/34071">(#34071</a>).</li>
<li>Corrigido resultados de consulta incompletos devido a chaves primárias duplicadas num segmento<a href="https://github.com/milvus-io/milvus/pull/34302">(#34302</a>).</li>
<li>Resolvido um problema de falta de segmentos selados na compactação L0<a href="https://github.com/milvus-io/milvus/pull/34566">(#34566</a>).</li>
<li>Corrigido o problema de dados sujos no meta channel-cp gerado após a recolha de lixo<a href="https://github.com/milvus-io/milvus/pull/34609">(#34609</a>).</li>
<li>Corrigida a métrica onde database_num era 0 depois de reiniciar o RootCoord<a href="https://github.com/milvus-io/milvus/pull/34010">(#34010</a>).</li>
<li>Corrigido um vazamento de memória no SegmentManager no DataCoord, removendo os segmentos de descarga gerados através da importação<a href="https://github.com/milvus-io/milvus/pull/34652">(#34652</a>).</li>
<li>Assegurado que o compressBinlog preenche o logID dos binlogs após o DataCoord reiniciar, assegurando o recarregamento correto do KV<a href="https://github.com/milvus-io/milvus/pull/34064">(#34064</a>).</li>
</ul>
<h2 id="v245" class="common-anchor-header">v2.4.5<button data-href="#v245" class="anchor-icon" translate="no">
      <svg translate="no"
        aria-hidden="true"
        focusable="false"
        height="20"
        version="1.1"
        viewBox="0 0 16 16"
        width="16"
      >
        <path
          fill="#0092E4"
          fill-rule="evenodd"
          d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"
        ></path>
      </svg>
    </button></h2><p>Data de lançamento: 18 de junho de 2024</p>
<table>
<thead>
<tr><th>Versão do Milvus</th><th>Versão do Python SDK</th><th>Versão do Java SDK</th><th>Versão do SDK do Node.js</th></tr>
</thead>
<tbody>
<tr><td>2.4.5</td><td>2.4.4</td><td>2.4.1</td><td>2.4.3</td></tr>
</tbody>
</table>
<p>O lançamento do Milvus 2.4.5 introduz várias melhorias e correcções de erros para melhorar o desempenho, a estabilidade e a funcionalidade. O Milvus 2.4.5 simplifica a pesquisa de vetores esparsos, float16 e bfloat16 com auto-indexação, acelera pesquisas, exclusões e compactações com otimizações do filtro Bloom e aborda o gerenciamento de dados através de tempos de carregamento mais rápidos e suporte a importação de segmentos L0. Ele também introduz o índice HNSW esparso para pesquisa eficiente de dados esparsos de alta dimensão, aprimora a API RESTful com suporte a vetor flutuante esparso e corrige bugs críticos para melhor estabilidade.</p>
<h3 id="New-Features" class="common-anchor-header">Novos recursos</h3><ul>
<li>Adicionado suporte rbac para descrever/alterar a API da base de dados<a href="https://github.com/milvus-io/milvus/pull/33804">(#33804</a>)</li>
<li>Suporte para a construção do índice HNSW para vectores esparsos<a href="https://github.com/milvus-io/milvus/pull/33653">(#33653</a>, <a href="https://github.com/milvus-io/milvus/pull/33662">#33662</a>)</li>
<li>Suporte à construção do índice de disco para vetor binário<a href="https://github.com/milvus-io/milvus/pull/33575">(#33575</a>)</li>
<li>Suporte para o tipo de vetor esparso em RESTful v2<a href="https://github.com/milvus-io/milvus/pull/33555">(#33555</a>)</li>
<li>Adicionada a api RESTful /management/stop para parar um componente<a href="https://github.com/milvus-io/milvus/pull/33799">(#33799</a>)</li>
</ul>
<h3 id="Improvements" class="common-anchor-header">Melhorias</h3><ul>
<li>Definir o valor predefinido de maxPartitionNum para 1024<a href="https://github.com/milvus-io/milvus/pull/33950">(#33950</a>)</li>
<li>Ativado para forçar a reinicialização da ligação por erro indisponível<a href="https://github.com/milvus-io/milvus/pull/33910">(#33910</a>)</li>
<li>Ativado o limitador de taxa de descarga do nível de coleção<a href="https://github.com/milvus-io/milvus/pull/33864">(#33864</a>)</li>
<li>Executada a aplicação do filtro bloom em paralelo para acelerar a previsão de segmentos<a href="https://github.com/milvus-io/milvus/pull/33793">(#33793</a>)</li>
<li>Utilizada a biblioteca fastjson para desmarcar o log de eliminação para acelerar o json.Unmarshal<a href="https://github.com/milvus-io/milvus/pull/33802">(#33802</a>)</li>
<li>Usado BatchPkExist para reduzir o custo da chamada da função bloom filter<a href="https://github.com/milvus-io/milvus/pull/33752">(#33752</a>)</li>
<li>Acelerou o carregamento de pequenas colecções<a href="https://github.com/milvus-io/milvus/pull/33746">(#33746</a>)</li>
<li>Suportada a importação de dados de eliminação para o segmento L0 (<a href="https://github.com/milvus-io/milvus/pull/33712">#33712</a>)</li>
<li>Saltou tarefas de compactação de marca para ser timeouted para evitar a execução da mesma tarefa uma e outra vez<a href="https://github.com/milvus-io/milvus/pull/33833">(#33833</a>)</li>
<li>Tratados os vectores float16 e bfloat16 como sendo iguais ao BinaryVector na inserção em massa numpy (<a href="https://github.com/milvus-io/milvus/pull/33788">#33788</a>)</li>
<li>Adicionado o sinalizador includeCurrentMsg para o método seek<a href="https://github.com/milvus-io/milvus/pull/33743">(#33743</a>)</li>
<li>Adicionado mergeInterval, targetBufSize, maxTolerantLag do msgdispatcher às configurações<a href="https://github.com/milvus-io/milvus/pull/33680">(#33680</a>)</li>
<li>Melhorado o GetVectorByID do vetor esparso<a href="https://github.com/milvus-io/milvus/pull/33652">(#33652</a>)</li>
<li>Removida a StringPrimarykey para reduzir a cópia desnecessária e o custo da chamada de função (<a href="https://github.com/milvus-io/milvus/pull/33649">#33649</a>)</li>
<li>Adicionado mapeamento autoindex para tipo de dados binário/esparso<a href="https://github.com/milvus-io/milvus/pull/33625">(#33625</a>)</li>
<li>Optimizada alguma cache para reduzir a utilização de memória<a href="https://github.com/milvus-io/milvus/pull/33560">(#33560</a>)</li>
<li>Interface de execução abstrata para tarefas de importação/preimportação (<a href="https://github.com/milvus-io/milvus/pull/33607">#33607</a>)</li>
<li>Usado map pk para timestamp na inserção de buffer para reduzir as causas de bf<a href="https://github.com/milvus-io/milvus/pull/33582">(#33582</a>)</li>
<li>Evitou meta operações redundantes de importação (<a href="https://github.com/milvus-io/milvus/pull/33519">#33519</a>)</li>
<li>Melhorar os logs registando melhor a informação da quota do disco, adicionando a bandeira UseDefaultConsistency, removendo logs desnecessários<a href="https://github.com/milvus-io/milvus/pull/33597">(#33597</a>, <a href="https://github.com/milvus-io/milvus/pull/33644">#33644</a>, <a href="https://github.com/milvus-io/milvus/pull/33670">#33670</a>)</li>
</ul>
<h3 id="Bug-fixes" class="common-anchor-header">Correcções de erros</h3><ul>
<li>Corrigido um bug que queryHook não conseguia reconhecer o tipo de vetor<a href="https://github.com/milvus-io/milvus/pull/33911">(#33911</a>)</li>
<li>Prevenido o uso capturado da variável de iteração partitionID<a href="https://github.com/milvus-io/milvus/pull/33970">(#33970</a>)</li>
<li>Corrigido um bug que podia fazer com que o Milvus não conseguisse criar AutoIndex em vectores binários e esparsos<a href="https://github.com/milvus-io/milvus/pull/33867">(#33867</a>)</li>
<li>Corrigido um erro que podia fazer com que o indexnode tentasse novamente criar um índice em parâmetros de índice inválidos de todos os vectores (<a href="https://github.com/milvus-io/milvus/pull/33878">#33878</a>)</li>
<li>Corrigido o bug que quando cargas e lançamentos acontecem simultaneamente podem travar o Servidor<a href="https://github.com/milvus-io/milvus/pull/33699">(#33699</a>)</li>
<li>Melhoria da consistência da cache para valores de configuração<a href="https://github.com/milvus-io/milvus/pull/33797">(#33797</a>)</li>
<li>Prevenida a possível perda de dados durante a eliminação<a href="https://github.com/milvus-io/milvus/pull/33821">(#33821</a>)</li>
<li>Assegurado que o campo DroppedAt (provável registo de data e hora da eliminação) é definido após a eliminação de colecções<a href="https://github.com/milvus-io/milvus/pull/33767">(#33767</a>)</li>
<li>Corrigido um problema que poderia ter feito com que o Milvus tratasse incorretamente os tamanhos dos dados do vetor binário<a href="https://github.com/milvus-io/milvus/pull/33751">(#33751</a>)</li>
<li>Evitado que as credenciais sensíveis do Kafka fossem registadas em texto simples<a href="https://github.com/milvus-io/milvus/pull/33694">(#33694</a>, <a href="https://github.com/milvus-io/milvus/pull/33747">#33747</a>)</li>
<li>Assegurado que o Milvus pode importar corretamente dados com múltiplos campos vectoriais.<a href="https://github.com/milvus-io/milvus/pull/33724">(#33724</a>)</li>
<li>Melhorada a fiabilidade da importação, verificando se existe um trabalho de importação antes de iniciar.<a href="https://github.com/milvus-io/milvus/pull/33673">(#33673</a>)</li>
<li>Melhorado o manuseamento do índice HNSW esparso (funcionalidade interna)<a href="https://github.com/milvus-io/milvus/pull/33714">(#33714</a>)</li>
<li>Memória vetorial limpa para evitar fugas de memória<a href="https://github.com/milvus-io/milvus/pull/33708">(#33708</a>)</li>
<li>Assegurado um aquecimento assíncrono mais suave, corrigindo um problema de bloqueio de estado.<a href="https://github.com/milvus-io/milvus/pull/33687">(#33687</a>)</li>
<li>Resolvido um erro que poderia ter causado resultados em falta em iteradores de consulta.<a href="https://github.com/milvus-io/milvus/pull/33506">(#33506</a>)</li>
<li>Corrigido um erro que poderia causar o tamanho do segmento de importação não ser uniforme (<a href="https://github.com/milvus-io/milvus/pull/33634">#33634</a>)</li>
<li>Corrigido o tratamento incorreto do tamanho dos dados para bf16, fp16, e tipos de vetor binário<a href="https://github.com/milvus-io/milvus/pull/33488">(#33488</a>)</li>
<li>Estabilidade melhorada através da resolução de potenciais problemas com o compactador L0<a href="https://github.com/milvus-io/milvus/pull/33564">(#33564</a>)</li>
<li>Assegurado que as actualizações de configuração dinâmica são reflectidas corretamente na cache.<a href="https://github.com/milvus-io/milvus/pull/33590">(#33590</a>)</li>
<li>Melhorada a precisão da métrica RootCoordQuotaStates (<a href="https://github.com/milvus-io/milvus/pull/33601">#33601</a>)</li>
<li>Garantido o relatório exato do número de entidades carregadas na métrica<a href="https://github.com/milvus-io/milvus/pull/33522">(#33522</a>)</li>
<li>Fornecida informação mais completa nos registos de exceção. <a href="https://github.com/milvus-io/milvus/pull/33396">(#33396</a>)</li>
<li>Optimizado o pipeline de consulta, removendo o verificador de grupo desnecessário<a href="https://github.com/milvus-io/milvus/pull/33485">(#33485</a>)</li>
<li>Utilizado o caminho de armazenamento local para uma verificação mais precisa da capacidade do disco no nó de índice.<a href="https://github.com/milvus-io/milvus/pull/33505">(#33505</a>)</li>
<li>Corrigido o facto de hasMoreResult poder devolver falso quando o número de acertos é maior que o limite<a href="https://github.com/milvus-io/milvus/pull/33642">(#33642</a>)</li>
<li>Atraso no carregamento do bf no delegador para evitar que o bfs seja carregado repetidamente quando o trabalhador não tem mais memória<a href="https://github.com/milvus-io/milvus/pull/33650">(#33650</a>) - Corrigido um bug que queryHook não conseguia reconhecer o tipo de vetor<a href="https://github.com/milvus-io/milvus/pull/33911">(#33911</a>)</li>
<li>Prevenido o uso capturado da variável de iteração partitionID<a href="https://github.com/milvus-io/milvus/pull/33970">(#33970</a>)</li>
<li>Corrigido um bug que pode fazer com que o Milvus não consiga criar AutoIndex em vectores binários e esparsos<a href="https://github.com/milvus-io/milvus/pull/33867">(#33867</a>)</li>
<li>Corrigido um erro que podia fazer com que o indexnode tentasse novamente criar um índice em parâmetros de índice inválidos de todos os vectores (<a href="https://github.com/milvus-io/milvus/pull/33878">#33878</a>)</li>
<li>Corrigido o bug que quando cargas e lançamentos acontecem simultaneamente podem travar o Servidor<a href="https://github.com/milvus-io/milvus/pull/33699">(#33699</a>)</li>
<li>Melhoria da consistência da cache para valores de configuração<a href="https://github.com/milvus-io/milvus/pull/33797">(#33797</a>)</li>
<li>Prevenida a possível perda de dados durante a eliminação<a href="https://github.com/milvus-io/milvus/pull/33821">(#33821</a>)</li>
<li>Assegurado que o campo DroppedAt (provável registo de data e hora da eliminação) é definido após a eliminação de colecções<a href="https://github.com/milvus-io/milvus/pull/33767">(#33767</a>)</li>
<li>Corrigido um problema que poderia ter feito com que o Milvus tratasse incorretamente os tamanhos dos dados do vetor binário<a href="https://github.com/milvus-io/milvus/pull/33751">(#33751</a>)</li>
<li>Evitado que as credenciais sensíveis do Kafka fossem registadas em texto simples<a href="https://github.com/milvus-io/milvus/pull/33694">(#33694</a>, <a href="https://github.com/milvus-io/milvus/pull/33747">#33747</a>)</li>
<li>Assegurado que o Milvus pode importar corretamente dados com múltiplos campos vectoriais.<a href="https://github.com/milvus-io/milvus/pull/33724">(#33724</a>)</li>
<li>Melhorada a fiabilidade da importação, verificando se existe um trabalho de importação antes de iniciar.<a href="https://github.com/milvus-io/milvus/pull/33673">(#33673</a>)</li>
<li>Melhorado o manuseamento do índice HNSW esparso (funcionalidade interna)<a href="https://github.com/milvus-io/milvus/pull/33714">(#33714</a>)</li>
<li>Memória vetorial limpa para evitar fugas de memória<a href="https://github.com/milvus-io/milvus/pull/33708">(#33708</a>)</li>
<li>Assegurado um aquecimento assíncrono mais suave, corrigindo um problema de bloqueio de estado.<a href="https://github.com/milvus-io/milvus/pull/33687">(#33687</a>)</li>
<li>Resolvido um erro que poderia ter causado resultados em falta em iteradores de consulta.<a href="https://github.com/milvus-io/milvus/pull/33506">(#33506</a>)</li>
<li>Corrigido um erro que poderia causar o tamanho do segmento de importação não ser uniforme (<a href="https://github.com/milvus-io/milvus/pull/33634">#33634</a>)</li>
<li>Corrigido o tratamento incorreto do tamanho dos dados para bf16, fp16, e tipos de vetor binário<a href="https://github.com/milvus-io/milvus/pull/33488">(#33488</a>)</li>
<li>Estabilidade melhorada através da resolução de potenciais problemas com o compactador L0<a href="https://github.com/milvus-io/milvus/pull/33564">(#33564</a>)</li>
<li>Assegurado que as actualizações de configuração dinâmica são reflectidas corretamente na cache.<a href="https://github.com/milvus-io/milvus/pull/33590">(#33590</a>)</li>
<li>Melhorada a precisão da métrica RootCoordQuotaStates (<a href="https://github.com/milvus-io/milvus/pull/33601">#33601</a>)</li>
<li>Garantido o relatório exato do número de entidades carregadas na métrica<a href="https://github.com/milvus-io/milvus/pull/33522">(#33522</a>)</li>
<li>Fornecida informação mais completa nos registos de exceção. <a href="https://github.com/milvus-io/milvus/pull/33396">(#33396</a>)</li>
<li>Optimizado o pipeline de consulta, removendo o verificador de grupo desnecessário<a href="https://github.com/milvus-io/milvus/pull/33485">(#33485</a>)</li>
<li>Utilizado o caminho de armazenamento local para uma verificação mais precisa da capacidade do disco no nó de índice.<a href="https://github.com/milvus-io/milvus/pull/33505">(#33505</a>)</li>
<li>Corrigido o facto de hasMoreResult poder devolver falso quando o número de acertos é maior que o limite<a href="https://github.com/milvus-io/milvus/pull/33642">(#33642</a>)</li>
<li>Atraso no carregamento do bf no delegador para evitar que o bfs seja carregado repetidamente quando o trabalhador não tem mais memória<a href="https://github.com/milvus-io/milvus/pull/33650">(#33650</a>)</li>
</ul>
<h2 id="v244" class="common-anchor-header">v2.4.4<button data-href="#v244" class="anchor-icon" translate="no">
      <svg translate="no"
        aria-hidden="true"
        focusable="false"
        height="20"
        version="1.1"
        viewBox="0 0 16 16"
        width="16"
      >
        <path
          fill="#0092E4"
          fill-rule="evenodd"
          d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"
        ></path>
      </svg>
    </button></h2><p>Data de lançamento: 31 de maio de 2024</p>
<table>
<thead>
<tr><th>Versão do Milvus</th><th>Versão Python SDK</th><th>Versão do Java SDK</th><th>Versão do SDK do Node.js</th></tr>
</thead>
<tbody>
<tr><td>2.4.4</td><td>2.4.3</td><td>2.4.1</td><td>2.4.2</td></tr>
</tbody>
</table>
<p>O Milvus v2.4.4 inclui várias correcções de erros críticos e melhorias destinadas a melhorar o desempenho e a estabilidade. Em particular, resolvemos <strong>um problema crítico em que os registos de estatísticas de inserção em massa eram incorretamente recolhidos</strong>, afectando potencialmente a integridade dos dados. <strong>Recomendamos vivamente que todos os utilizadores da versão 2.4 actualizem para esta versão para beneficiarem destas correcções.</strong></p>
<p><strong>Se estiver a utilizar a inserção em massa, actualize para a v2.4.4 o mais rapidamente possível para garantir a integridade dos dados.</strong></p>
<h3 id="Critical-bug-fixes" class="common-anchor-header">Correcções de erros críticos</h3><ul>
<li>Preenchimento do ID do registo de estatísticas e validação da sua correção<a href="https://github.com/milvus-io/milvus/pull/33478">(#33478</a>)</li>
</ul>
<h3 id="Improvements" class="common-anchor-header">Melhorias</h3><ul>
<li>Conjunto de bits atualizado para ARM SVE<a href="https://github.com/milvus-io/milvus/pull/33440">(#33440</a>)</li>
<li>Activada a compilação Milvus com GCC-13<a href="https://github.com/milvus-io/milvus/pull/33441">(#33441</a>)</li>
</ul>
<h3 id="Bug-fixes" class="common-anchor-header">Correcções de erros</h3><ul>
<li>Mostrava colecções vazias quando todos os privilégios eram concedidos<a href="https://github.com/milvus-io/milvus/pull/33454">(#33454</a>)</li>
<li>Assegurado que o CMake descarrega e instala para a plataforma atual, não apenas x86_64<a href="https://github.com/milvus-io/milvus/pull/33439">(#33439</a>)</li>
</ul>
<h2 id="v243" class="common-anchor-header">v2.4.3<button data-href="#v243" class="anchor-icon" translate="no">
      <svg translate="no"
        aria-hidden="true"
        focusable="false"
        height="20"
        version="1.1"
        viewBox="0 0 16 16"
        width="16"
      >
        <path
          fill="#0092E4"
          fill-rule="evenodd"
          d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"
        ></path>
      </svg>
    </button></h2><p>Data de lançamento: 29 de maio de 2024</p>
<table>
<thead>
<tr><th>Versão do Milvus</th><th>Versão do Python SDK</th><th>Versão do Java SDK</th><th>Versão do SDK do Node.js</th></tr>
</thead>
<tbody>
<tr><td>2.4.3</td><td>2.4.3</td><td>2.4.1</td><td>2.4.2</td></tr>
</tbody>
</table>
<p>A versão 2.4.3 do Milvus introduziu uma série de funcionalidades, melhorias e correcções de erros para aumentar o desempenho e a fiabilidade. Melhorias notáveis incluíram suporte para inserção em massa de vetor float esparso e aceleração otimizada de filtro bloom. As melhorias abrangeram várias áreas, desde atualizações de configuração dinâmica até otimização do uso de memória. As correcções de erros abordaram questões críticas como cenários de pânico e garantiram operações de sistema mais suaves. Esta versão sublinhou o compromisso contínuo da Milvus em melhorar a funcionalidade, otimizar o desempenho e fornecer uma experiência de utilizador robusta.</p>
<h3 id="Features" class="common-anchor-header">Caraterísticas</h3><ul>
<li>Suporte para inserção em massa de vetor de flutuação esparsa para binlog/json/parquet<a href="https://github.com/milvus-io/milvus/pull/32649">(#32649</a>)</li>
</ul>
<h3 id="Improvements" class="common-anchor-header">Melhorias</h3><ul>
<li>Implementação do canal de observação Datacoord/node baseado em RPC<a href="https://github.com/milvus-io/milvus/pull/32036">(#32036</a>)</li>
<li>Filtro bloom optimizado para acelerar a filtragem de eliminação<a href="https://github.com/milvus-io/milvus/pull/32642">(#32642</a>, <a href="https://github.com/milvus-io/milvus/pull/33329">#33329</a>, <a href="https://github.com/milvus-io/milvus/pull/33284">#33284</a>)</li>
<li>Carregamento de dados brutos via mmap se o índice escalar não tiver dados brutos<a href="https://github.com/milvus-io/milvus/pull/33317">(#33317</a>)</li>
<li>Sincronizada a configuração do milvus para milvus.yaml<a href="https://github.com/milvus-io/milvus/pull/33322">(#33322</a>, <a href="https://github.com/milvus-io/milvus/pull/32920">#32920</a>, <a href="https://github.com/milvus-io/milvus/pull/32857">#32857</a>, <a href="https://github.com/milvus-io/milvus/pull/32946">#32946</a>)</li>
<li>Actualizada a versão do knowhere<a href="https://github.com/milvus-io/milvus/pull/33310">(#33310</a>, <a href="https://github.com/milvus-io/milvus/pull/32931">#32931</a>, <a href="https://github.com/milvus-io/milvus/pull/33043">#33043</a>)</li>
<li>Activada a atualização dinâmica da política do balancer no QueryCoord<a href="https://github.com/milvus-io/milvus/pull/33272">(#33272</a>)</li>
<li>Usado um logger pré-construído no buffer de escrita para minimizar a alocação de logger<a href="https://github.com/milvus-io/milvus/pull/33304">(#33304</a>)</li>
<li>Verificação de parâmetros melhorada<a href="https://github.com/milvus-io/milvus/pull/32777">(#32777</a>, <a href="https://github.com/milvus-io/milvus/pull/33271">#33271</a>, <a href="https://github.com/milvus-io/milvus/pull/33218">#33218</a>)</li>
<li>Adicionado um parâmetro para ignorar IDs de mensagens incorrectas no ponto de verificação<a href="https://github.com/milvus-io/milvus/pull/33249">(#33249</a>)</li>
<li>Adicionada configuração para controlar o tratamento de falhas de inicialização para plugins<a href="https://github.com/milvus-io/milvus/pull/32680">(#32680</a>)</li>
<li>Adicionada uma configuração de consistência de cálculo de pontuação para o knowhere<a href="https://github.com/milvus-io/milvus/pull/32997">(#32997</a>)</li>
<li>Introduzida uma opção de configuração para controlar a inicialização das permissões de função pública<a href="https://github.com/milvus-io/milvus/pull/33174">(#33174</a>)</li>
<li>Optimizada a utilização de memória ao ler campos<a href="https://github.com/milvus-io/milvus/pull/33196">(#33196</a>)</li>
<li>Implementação refinada do Channel Manager v2<a href="https://github.com/milvus-io/milvus/pull/33172">(#33172</a>, <a href="https://github.com/milvus-io/milvus/pull/33121">#33121</a>, <a href="https://github.com/milvus-io/milvus/pull/33014">#33014</a>)</li>
<li>Adicionada funcionalidade para controlar o tamanho dos dados na memória para o binlog<a href="https://github.com/milvus-io/milvus/pull/33025">(#33025</a>)</li>
<li>Adicionada métrica para o tamanho dos ficheiros de índice de segmentos<a href="https://github.com/milvus-io/milvus/pull/32979">(#32979</a>, <a href="https://github.com/milvus-io/milvus/pull/33305">#33305</a>)</li>
<li>Substituído o Delete por DeletePartialMatch para remover métricas<a href="https://github.com/milvus-io/milvus/pull/33029">(#33029</a>)</li>
<li>Obteve o tamanho dos dados relacionados de acordo com o tipo de segmento<a href="https://github.com/milvus-io/milvus/pull/33017">(#33017</a>)</li>
<li>Limpada a informação do nó do canal na meta store<a href="https://github.com/milvus-io/milvus/pull/32988">(#32988</a>)</li>
<li>Removido o rootcoord do datanode broker<a href="https://github.com/milvus-io/milvus/pull/32818">(#32818</a>)</li>
<li>Ativado o upload em lote<a href="https://github.com/milvus-io/milvus/pull/32788">(#32788</a>)</li>
<li>Alterado o número de partição predefinido para 16 quando se usa a chave de partição<a href="https://github.com/milvus-io/milvus/pull/32950">(#32950</a>)</li>
<li>Melhorado o desempenho de redução em consultas top-k muito grandes<a href="https://github.com/milvus-io/milvus/pull/32871">(#32871</a>)</li>
<li>Utilizada a capacidade de TestLocations para acelerar a escrita e compactação<a href="https://github.com/milvus-io/milvus/pull/32948">(#32948</a>)</li>
<li>Optimizado o pool de analisadores de planos para evitar reciclagem desnecessária<a href="https://github.com/milvus-io/milvus/pull/32869">(#32869</a>)</li>
<li>Velocidade de carregamento melhorada<a href="https://github.com/milvus-io/milvus/pull/32898">(#32898</a>)</li>
<li>Utilizado o nível de consistência padrão da coleção para restv2<a href="https://github.com/milvus-io/milvus/pull/32956">(#32956</a>)</li>
<li>Adicionada resposta de custo para o resto da API<a href="https://github.com/milvus-io/milvus/pull/32620">(#32620</a>)</li>
<li>Activada a política de equilíbrio exclusiva do canal<a href="https://github.com/milvus-io/milvus/pull/32911">(#32911</a>)</li>
<li>Exposta a API describedatabase em proxy<a href="https://github.com/milvus-io/milvus/pull/32732">(#32732</a>)</li>
<li>Utilizado o mapeamento coll2replica ao obter RG por coleção<a href="https://github.com/milvus-io/milvus/pull/32892">(#32892</a>)</li>
<li>Adicionado mais tracing para pesquisa e consulta<a href="https://github.com/milvus-io/milvus/pull/32734">(#32734</a>)</li>
<li>Suportada configuração dinâmica para rastreio de opentelemetria<a href="https://github.com/milvus-io/milvus/pull/32169">(#32169</a>)</li>
<li>Evitada a iteração sobre os resultados do canal ao atualizar o leaderview<a href="https://github.com/milvus-io/milvus/pull/32887">(#32887</a>)</li>
<li>Optimizado o tratamento de offsets de vetor para parquet<a href="https://github.com/milvus-io/milvus/pull/32822">(#32822</a>)</li>
<li>Melhorada a filtragem do segmento datacoord com recolha<a href="https://github.com/milvus-io/milvus/pull/32831">(#32831</a>)</li>
<li>Ajustado o nível e frequência do registo<a href="https://github.com/milvus-io/milvus/pull/33042">(#33042</a>, <a href="https://github.com/milvus-io/milvus/pull/32838">#32838</a>, <a href="https://github.com/milvus-io/milvus/pull/33337">#33337</a>)</li>
<li>Ativado o equilíbrio de paragem após o equilíbrio ter sido suspenso<a href="https://github.com/milvus-io/milvus/pull/32812">(#32812</a>)</li>
<li>Actualizada a cache do líder do fragmento quando a localização do líder foi alterada<a href="https://github.com/milvus-io/milvus/pull/32470">(#32470</a>)</li>
<li>Removido API e campo obsoletos<a href="https://github.com/milvus-io/milvus/pull/32808">(#32808</a>, <a href="https://github.com/milvus-io/milvus/pull/32704">#32704</a>)</li>
<li>Adicionado metautil.channel para converter string compare para int<a href="https://github.com/milvus-io/milvus/pull/32749">(#32749</a>)</li>
<li>Adicionada informação de tipo para mensagem de erro do escritor de carga útil e registo quando o querynode encontrou uma nova coleção<a href="https://github.com/milvus-io/milvus/pull/32522">(#32522</a>)</li>
<li>Verificado o número da partição ao criar uma coleção com chave de partição<a href="https://github.com/milvus-io/milvus/pull/32670">(#32670</a>)</li>
<li>Removido o segmento l0 legado se o watch falhar<a href="https://github.com/milvus-io/milvus/pull/32725">(#32725</a>)</li>
<li>Melhoria na impressão do tipo de pedido<a href="https://github.com/milvus-io/milvus/pull/33319">(#33319</a>)</li>
<li>Verificado que os dados do campo do array eram nulos antes de obter o tipo<a href="https://github.com/milvus-io/milvus/pull/33311">(#33311</a>)</li>
<li>Devolvido erro quando a operação de arranque do nó Delete/AddNode falhava<a href="https://github.com/milvus-io/milvus/pull/33258">(#33258</a>)</li>
<li>Permitiu que o ID do servidor do datanode fosse atualizado<a href="https://github.com/milvus-io/milvus/pull/31597">(#31597</a>)</li>
<li>Limpeza unificada das métricas do querynode no lançamento da coleção<a href="https://github.com/milvus-io/milvus/pull/32805">(#32805</a>)</li>
<li>Corrigida a versão incorrecta da configuração do índice automático escalar<a href="https://github.com/milvus-io/milvus/pull/32795">(#32795</a>)</li>
<li>Verificação de parâmetros de índice refinada para criar/alterar índice<a href="https://github.com/milvus-io/milvus/pull/32712">(#32712</a>)</li>
<li>Removida a recuperação redundante de réplicas<a href="https://github.com/milvus-io/milvus/pull/32985">(#32985</a>)</li>
<li>Activada a meta tabela de canais para escrever mais de 200k segmentos<a href="https://github.com/milvus-io/milvus/pull/33300">(#33300</a>)</li>
</ul>
<h3 id="Bug-fixes" class="common-anchor-header">Correcções de erros</h3><ul>
<li>Corrigido o pânico quando a base de dados não existia no intercetor de limite de taxa<a href="https://github.com/milvus-io/milvus/pull/33308">(#33308</a>)</li>
<li>Corrigida a falha na recolha de métricas do quotacenter devido a parâmetros incorrectos<a href="https://github.com/milvus-io/milvus/pull/33399">(#33399</a>)</li>
<li>Corrigido o pânico se o processactivestandby devolvesse um erro<a href="https://github.com/milvus-io/milvus/pull/33372">(#33372</a>)</li>
<li>Corrigido o truncamento do resultado da pesquisa em restful v2 quando nq &gt; 1<a href="https://github.com/milvus-io/milvus/pull/33363">(#33363</a>)</li>
<li>Adicionado campo de nome de base de dados para operações de função em restful v2<a href="https://github.com/milvus-io/milvus/pull/33291">(#33291</a>)</li>
<li>Corrigido o limite de taxa global que não funcionava<a href="https://github.com/milvus-io/milvus/pull/33336">(#33336</a>)</li>
<li>Corrigido o pânico causado pela falha na construção do índice<a href="https://github.com/milvus-io/milvus/pull/33314">(#33314</a>)</li>
<li>Adicionada validação para vetor esparso no segcore para garantir a legalidade<a href="https://github.com/milvus-io/milvus/pull/33312">(#33312</a>)</li>
<li>Removida a tarefa do syncmgr após a conclusão da tarefa<a href="https://github.com/milvus-io/milvus/pull/33303">(#33303</a>)</li>
<li>Corrigida a falha de filtragem da chave de partição durante a importação de dados<a href="https://github.com/milvus-io/milvus/pull/33277">(#33277</a>)</li>
<li>Corrigida a incapacidade de gerar traceID ao usar o exportador noop<a href="https://github.com/milvus-io/milvus/pull/33208">(#33208</a>)</li>
<li>Melhorada a recuperação dos resultados da consulta<a href="https://github.com/milvus-io/milvus/pull/33179">(#33179</a>)</li>
<li>Marcado o ponto de verificação do canal descartado para evitar a fuga de métricas de atraso do ponto de verificação<a href="https://github.com/milvus-io/milvus/pull/33201">(#33201</a>)</li>
<li>Corrigido o nó de consulta a ficar preso durante a paragem do progresso<a href="https://github.com/milvus-io/milvus/pull/33154">(#33154</a>)</li>
<li>Corrigido segmentos em falta na resposta de descarga<a href="https://github.com/milvus-io/milvus/pull/33061">(#33061</a>)</li>
<li>Tornada a operação de submissão idempotente<a href="https://github.com/milvus-io/milvus/pull/33053">(#33053</a>)</li>
<li>Atribuída nova fatia para cada lote no leitor de streaming<a href="https://github.com/milvus-io/milvus/pull/33360">(#33360</a>)</li>
<li>Limpou o nó offline do grupo de recursos após o reinício do QueryCoord<a href="https://github.com/milvus-io/milvus/pull/33233">(#33233</a>)</li>
<li>Removido compactador l0 em completedCompactor<a href="https://github.com/milvus-io/milvus/pull/33216">(#33216</a>)</li>
<li>Redefinido o valor da quota ao inicializar o limitador<a href="https://github.com/milvus-io/milvus/pull/33152">(#33152</a>)</li>
<li>Resolvido o problema em que o limite do etcd era excedido<a href="https://github.com/milvus-io/milvus/pull/33041">(#33041</a>)</li>
<li>Resolvida a ultrapassagem do limite da transação etcd devido a demasiados campos<a href="https://github.com/milvus-io/milvus/pull/33040">(#33040</a>)</li>
<li>Removida a reentrada de RLock em GetNumRowsOfPartition<a href="https://github.com/milvus-io/milvus/pull/33045">(#33045</a>)</li>
<li>Iniciado o LeaderCacheObserver antes do SyncAll<a href="https://github.com/milvus-io/milvus/pull/33035">(#33035</a>)</li>
<li>Ativado o balanceamento do canal standby libertado<a href="https://github.com/milvus-io/milvus/pull/32986">(#32986</a>)</li>
<li>Inicializado o registador de acesso antes da inicialização do servidor<a href="https://github.com/milvus-io/milvus/pull/32976">(#32976</a>)</li>
<li>Tornou o compactador capaz de limpar segmentos vazios<a href="https://github.com/milvus-io/milvus/pull/32821">(#32821</a>)</li>
<li>Preenchido o número de entrada do deltalog e o intervalo de tempo nas compactações l0<a href="https://github.com/milvus-io/milvus/pull/33004">(#33004</a>)</li>
<li>Corrigido o crash do proxy devido à corrida de dados da cache do líder do shard<a href="https://github.com/milvus-io/milvus/pull/32971">(#32971</a>)</li>
<li>Corrigida a unidade de tempo para a métrica do índice de carga<a href="https://github.com/milvus-io/milvus/pull/32935">(#32935</a>)</li>
<li>Corrigido o problema onde o segmento na paragem do nó de consulta não podia ser libertado com sucesso<a href="https://github.com/milvus-io/milvus/pull/32929">(#32929</a>)</li>
<li>Corrigida a estimativa de recursos do índice<a href="https://github.com/milvus-io/milvus/pull/32842">(#32842</a>)</li>
<li>Definido o ponto de controlo do canal para a posição delta<a href="https://github.com/milvus-io/milvus/pull/32878">(#32878</a>)</li>
<li>Fez o syncmgr bloquear a chave antes de retornar o futuro<a href="https://github.com/milvus-io/milvus/pull/32865">(#32865</a>)</li>
<li>Assegurado que o índice invertido tinha apenas um segmento<a href="https://github.com/milvus-io/milvus/pull/32858">(#32858</a>)</li>
<li>Corrigido o gatilho de compactação escolhendo dois segmentos idênticos<a href="https://github.com/milvus-io/milvus/pull/32800">(#32800</a>)</li>
<li>Corrigido o problema onde o nome da partição não podia ser especificado na importação do binlog<a href="https://github.com/milvus-io/milvus/pull/32730">(#32730</a>, <a href="https://github.com/milvus-io/milvus/pull/33027">#33027</a>)</li>
<li>Tornada a coluna dinâmica opcional na importação de parquet<a href="https://github.com/milvus-io/milvus/pull/32738">(#32738</a>)</li>
<li>Saltava a verificação do ID automático ao inserir dados<a href="https://github.com/milvus-io/milvus/pull/32775">(#32775</a>)</li>
<li>Validado o número de linhas para inserir dados de campo com o esquema<a href="https://github.com/milvus-io/milvus/pull/32770">(#32770</a>)</li>
<li>Adicionado Wrapper e Keepalive para IDs CTraceContext<a href="https://github.com/milvus-io/milvus/pull/32746">(#32746</a>)</li>
<li>Corrigido o problema em que o nome da base de dados não era encontrado no meta objeto datacoord<a href="https://github.com/milvus-io/milvus/pull/33412">(#33412</a>)</li>
<li>Sincronizado o segmento descartado para a partição descartada<a href="https://github.com/milvus-io/milvus/pull/33332">(#33332</a>)</li>
<li>Corrigida a falha na recolha de métricas do quotaCenter devido a parâmetros incorrectos<a href="https://github.com/milvus-io/milvus/pull/33399">(#33399</a>)</li>
</ul>
<h2 id="v241" class="common-anchor-header">v2.4.1<button data-href="#v241" class="anchor-icon" translate="no">
      <svg translate="no"
        aria-hidden="true"
        focusable="false"
        height="20"
        version="1.1"
        viewBox="0 0 16 16"
        width="16"
      >
        <path
          fill="#0092E4"
          fill-rule="evenodd"
          d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"
        ></path>
      </svg>
    </button></h2><p>Data de lançamento: 6 de maio de 2024</p>
<table>
<thead>
<tr><th>Versão do Milvus</th><th>Versão do Python SDK</th><th>Versão do Java SDK</th><th>Versão do SDK do Node.js</th></tr>
</thead>
<tbody>
<tr><td>2.4.1</td><td>2.4.1</td><td>2.4.0</td><td>2.4.2</td></tr>
</tbody>
</table>
<p>A versão 2.4.1 do Milvus traz inúmeras melhorias e correcções de erros que visam melhorar o desempenho, a observabilidade e a estabilidade do software. Estas melhorias incluem uma API declarativa de grupo de recursos, uma funcionalidade melhorada de inserção em massa que suporta tipos de dados vectoriais Float16/BFloat16, um mecanismo refinado de recolha de lixo (GC) que reduz as operações de lista para armazenamento de objectos e outras alterações relacionadas com optimizações de desempenho. Além disso, as correções de bugs abordam problemas como erros de compilação, correspondências difusas com falha em caracteres de nova linha, tipos de dados de parâmetro incorretos para interfaces RESTful e BulkInsert gerando erros em arquivos numpy quando os campos dinâmicos estão ativados.</p>
<h3 id="Breaking-changes" class="common-anchor-header">Alterações de rutura</h3><ul>
<li>Suporte descontinuado para excluir com uma expressão de filtro vazia.<a href="https://github.com/milvus-io/milvus/pull/32472">(#32472</a>)</li>
</ul>
<h3 id="Features" class="common-anchor-header">Caraterísticas</h3><ul>
<li>Adicionado suporte para tipos de dados de vetor Float16/BFloat16 na inserção em massa<a href="https://github.com/milvus-io/milvus/pull/32157">(#32157</a>)</li>
<li>Vetor float esparso melhorado para suportar pesquisa de iteradores de força bruta e pesquisa de intervalos<a href="https://github.com/milvus-io/milvus/pull/32635">(#32635</a>)</li>
</ul>
<h3 id="Improvements" class="common-anchor-header">Melhorias</h3><ul>
<li>Adicionada a API declarativa de grupo de recursos<a href="https://github.com/milvus-io/milvus/pull/31930">(#31930</a>, <a href="https://github.com/milvus-io/milvus/pull/32297">#32297</a>, <a href="https://github.com/milvus-io/milvus/pull/32536">#32536</a>, <a href="https://github.com/milvus-io/milvus/pull/32666">#32666</a>)</li>
<li>Reescreveu o observador da coleção no QueryCoord para o tornar orientado para a tarefa<a href="https://github.com/milvus-io/milvus/pull/32441">(#32441</a>)</li>
<li>Refacturada a estrutura de dados usada no SyncManager do DataNode para reduzir a utilização de memória e evitar erros<a href="https://github.com/milvus-io/milvus/pull/32673">(#32673</a>)</li>
<li>Revisto a implementação da recolha de lixo para minimizar as operações de lista associadas ao armazenamento de objectos<a href="https://github.com/milvus-io/milvus/pull/31740">(#31740</a>)</li>
<li>Reduzida a utilização do cpu quando o número de colecções é elevado<a href="https://github.com/milvus-io/milvus/pull/32245">(#32245</a>)</li>
<li>Melhorou a gestão do milvus.yaml, gerando automaticamente itens de configuração relevantes no ficheiro milvus.yaml através de código<a href="https://github.com/milvus-io/milvus/pull/31832">(#31832</a>, <a href="https://github.com/milvus-io/milvus/pull/32357">#32357</a>)</li>
<li>Melhorado o desempenho da Query, recuperando os dados depois de efetuar a redução local<a href="https://github.com/milvus-io/milvus/pull/32346">(#32346</a>)</li>
<li>Adicionada a opção WithBlock para a criação do cliente etcd<a href="https://github.com/milvus-io/milvus/pull/32641">(#32641</a>)</li>
<li>Usado client_request_id especificado pelo cliente como o TraceID se o cliente forneceu<a href="https://github.com/milvus-io/milvus/pull/32264">(#32264</a>)</li>
<li>Adicionada etiqueta db às métricas para as operações de eliminação e inserção em massa<a href="https://github.com/milvus-io/milvus/pull/32611">(#32611</a>)</li>
<li>Adicionada lógica para saltar a verificação através da configuração para as colunas AutoID e PartitionKey<a href="https://github.com/milvus-io/milvus/pull/32592">(#32592</a>)</li>
<li>Erros refinados relacionados com a autenticação<a href="https://github.com/milvus-io/milvus/pull/32253">(#32253</a>)</li>
<li>Registos de erros refinados para AllocSegmentID em DataCoord<a href="https://github.com/milvus-io/milvus/pull/32351">(#32351</a>, <a href="https://github.com/milvus-io/milvus/pull/32335">#32335</a>)</li>
<li>Remoção de métricas duplicadas<a href="https://github.com/milvus-io/milvus/pull/32380">(#32380</a>, <a href="https://github.com/milvus-io/milvus/pull/32308">#32308</a>) e limpeza de métricas não utilizadas<a href="https://github.com/milvus-io/milvus/pull/32404">(#32404</a>, <a href="https://github.com/milvus-io/milvus/pull/32515">#32515</a>)</li>
<li>Adicionada a opção de configuração para controlar se a ativação da funcionalidade partitionKey deve ser imposta<a href="https://github.com/milvus-io/milvus/pull/32433">(#32433</a>)</li>
<li>Adicionada opção de configuração para controlar a quantidade máxima de dados que podem ser inseridos num único pedido<a href="https://github.com/milvus-io/milvus/pull/32433">(#32433</a>)</li>
<li>Paralelização da operação applyDelete ao nível do segmento para acelerar o processamento de mensagens Delete pelo Delegador<a href="https://github.com/milvus-io/milvus/pull/32291">(#32291</a>)</li>
<li>Usou o índice<a href="https://github.com/milvus-io/milvus/pull/32232">(#32232</a>, <a href="https://github.com/milvus-io/milvus/pull/32505">#32505</a>, <a href="https://github.com/milvus-io/milvus/pull/32533">#32533</a>, <a href="https://github.com/milvus-io/milvus/pull/32595">#32595</a>) e adicionou a cache<a href="https://github.com/milvus-io/milvus/pull/32580">(#32580</a>) para acelerar as operações de filtragem frequentes no QueryCoord.</li>
<li>Reescreveu a estrutura de dados<a href="https://github.com/milvus-io/milvus/pull/32273">(#32273</a>) e refacturou o código<a href="https://github.com/milvus-io/milvus/pull/32389">(#32389</a>) para acelerar operações comuns no DataCoord.</li>
<li>Removido o openblas do conan<a href="https://github.com/milvus-io/milvus/pull/32002">(#32002</a>)</li>
</ul>
<h3 id="Bug-fixes" class="common-anchor-header">Correcções de erros</h3><ul>
<li>Corrigida a compilação milvus no rockylinux8<a href="https://github.com/milvus-io/milvus/pull/32619">(#32619</a>)</li>
<li>Corrigidos erros de compilação para SVE em ARM<a href="https://github.com/milvus-io/milvus/pull/32463">(#32463</a>, <a href="https://github.com/milvus-io/milvus/pull/32270">#32270</a>)</li>
<li>Corrigido o problema de crash em imagens GPU baseadas em ARM<a href="https://github.com/milvus-io/milvus/pull/31980">(#31980</a>)</li>
<li>Corrigido a consulta regex não pode lidar com texto com nova linha<a href="https://github.com/milvus-io/milvus/pull/32569">(#32569</a>)</li>
<li>Corrigido a pesquisa obter resultado vazio causado por GetShardLeaders retornar lista de nós vazios<a href="https://github.com/milvus-io/milvus/pull/32685">(#32685</a>)</li>
<li>Corrigido o erro levantado pelo BulkInsert ao encontrar campos dinâmicos em ficheiros numpy<a href="https://github.com/milvus-io/milvus/pull/32596">(#32596</a>)</li>
<li>Corrigidos os erros relacionados com a interface RESTFulV2, incluindo uma correção importante que permite que os parâmetros numéricos nos pedidos aceitem a entrada numérica em vez do tipo string<a href="https://github.com/milvus-io/milvus/pull/32485">(#32485</a>, <a href="https://github.com/milvus-io/milvus/pull/32355">#32355</a>)</li>
<li>Corrigida a fuga de memória no proxy ao remover o evento de configuração de observação no limitador de taxa<a href="https://github.com/milvus-io/milvus/pull/32313">(#32313</a>)</li>
<li>Corrigido o problema em que o limitador de taxa informava incorretamente que a partição não podia ser encontrada quando partitionName não era especificado<a href="https://github.com/milvus-io/milvus/pull/32647">(#32647</a>)</li>
<li>Adicionada a deteção entre os casos da coleção estar no estado de recuperação e não estar carregada no tipo de erro.<a href="https://github.com/milvus-io/milvus/pull/32447">(#32447</a>)</li>
<li>Correção da métrica negativa de entidades numéricas consultáveis<a href="https://github.com/milvus-io/milvus/pull/32361">(#32361</a>)</li>
</ul>
<h2 id="v240" class="common-anchor-header">v2.4.0<button data-href="#v240" class="anchor-icon" translate="no">
      <svg translate="no"
        aria-hidden="true"
        focusable="false"
        height="20"
        version="1.1"
        viewBox="0 0 16 16"
        width="16"
      >
        <path
          fill="#0092E4"
          fill-rule="evenodd"
          d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"
        ></path>
      </svg>
    </button></h2><p>Data de lançamento: 17 de abril de 2024</p>
<table>
<thead>
<tr><th>Versão do Milvus</th><th>Versão do Python SDK</th><th>Versão do SDK do Node.js</th></tr>
</thead>
<tbody>
<tr><td>2.4.0</td><td>2.4.0</td><td>2.4.0</td></tr>
</tbody>
</table>
<p>Temos o prazer de anunciar o lançamento oficial do Milvus 2.4.0. Com base na base sólida da versão 2.4.0-rc.1, concentrámo-nos em resolver os erros críticos relatados pelos nossos utilizadores, preservando a funcionalidade existente. Além disso, o Milvus 2.4.0 introduz uma série de optimizações destinadas a melhorar o desempenho do sistema, melhorando a observabilidade através da incorporação de várias métricas, e simplificando a base de código para uma maior simplicidade.</p>
<h3 id="Improvements" class="common-anchor-header">Melhorias</h3><ul>
<li>Suporte para conexões MinIO TLS<a href="https://github.com/milvus-io/milvus/pull/31396">(#31396</a>, <a href="https://github.com/milvus-io/milvus/pull/31618">#31618</a>)</li>
<li>Suporte AutoIndex para campos escalares<a href="https://github.com/milvus-io/milvus/pull/31593">(#31593</a>)</li>
<li>Refactoring de pesquisa híbrida para caminhos de execução consistentes com pesquisa regular<a href="https://github.com/milvus-io/milvus/pull/31742">(#31742</a>, <a href="https://github.com/milvus-io/milvus/pull/32178">#32178</a>)</li>
<li>Filtragem acelerada através de bitset e bitset_view refactoring<a href="https://github.com/milvus-io/milvus/pull/31592">(#31592</a>, <a href="https://github.com/milvus-io/milvus/pull/31754">#31754</a>, <a href="https://github.com/milvus-io/milvus/pull/32139">#32139</a>)</li>
<li>As tarefas de importação suportam agora a espera pela conclusão do índice de dados<a href="https://github.com/milvus-io/milvus/pull/31733">(#31733</a>)</li>
<li>Compatibilidade de importação melhorada<a href="https://github.com/milvus-io/milvus/pull/32121">(#32121</a>), agendamento de tarefas<a href="https://github.com/milvus-io/milvus/pull/31475">(#31475</a>), e limites no tamanho e número de ficheiros importados<a href="https://github.com/milvus-io/milvus/pull/31542">(#31542</a>)</li>
<li>Esforços de simplificação do código, incluindo a normalização da interface para verificação de tipos<a href="https://github.com/milvus-io/milvus/pull/31945">(#31945</a>, <a href="https://github.com/milvus-io/milvus/pull/31857">#31857</a>), remoção de código e métricas obsoletas<a href="https://github.com/milvus-io/milvus/pull/32079">(#32079</a>, <a href="https://github.com/milvus-io/milvus/pull/32134">#32134</a>, <a href="https://github.com/milvus-io/milvus/pull/31535">#31535</a>, <a href="https://github.com/milvus-io/milvus/pull/32211">#32211</a>, <a href="https://github.com/milvus-io/milvus/pull/31935">#31935</a>), e normalização de nomes constantes<a href="https://github.com/milvus-io/milvus/pull/31515">(#31515</a>)</li>
<li>Nova métrica para a latência do atraso do ponto de verificação do canal de destino atual do QueryCoord<a href="https://github.com/milvus-io/milvus/pull/31420">(#31420</a>)</li>
<li>Nova etiqueta db para métricas comuns<a href="https://github.com/milvus-io/milvus/pull/32024">(#32024</a>)</li>
<li>Novas métricas relativas à contagem de entidades eliminadas, indexadas e carregadas, com a inclusão de etiquetas tais como collectionName e dbName<a href="https://github.com/milvus-io/milvus/pull/31861">(#31861</a>)</li>
<li>Melhorias no tratamento de erros para tipos de vectores incompatíveis<a href="https://github.com/milvus-io/milvus/pull/31766">(#31766</a>)</li>
<li>Suporte para lançar erros em vez de falhar quando o índice não pode ser construído<a href="https://github.com/milvus-io/milvus/pull/31845">(#31845</a>)</li>
<li>Suporte para invalidar a meta cache da base de dados quando se deixa cair bases de dados<a href="https://github.com/milvus-io/milvus/pull/32092">(#32092</a>)</li>
<li>Refactoring de interface para distribuição de canais<a href="https://github.com/milvus-io/milvus/pull/31814">(#31814</a>) e gestão da vista de líder<a href="https://github.com/milvus-io/milvus/pull/32127">(#32127</a>)</li>
<li>Refactorizar a interface do gestor de distribuição de canais<a href="https://github.com/milvus-io/milvus/pull/31814">(#31814</a>) e Refactorizar a interface do gestor de vista do líder<a href="https://github.com/milvus-io/milvus/pull/32127">(#32127</a>)</li>
<li>Processamento em lote<a href="https://github.com/milvus-io/milvus/pull/31632">(#31632</a>), adicionando informação de mapeamento<a href="https://github.com/milvus-io/milvus/pull/32234">(#32234</a>, <a href="https://github.com/milvus-io/milvus/pull/32249">#32249</a>), e evitando a utilização de lock<a href="https://github.com/milvus-io/milvus/pull/31787">(#31787</a>) para acelerar operações frequentemente invocadas</li>
</ul>
<h3 id="Breaking-Changes" class="common-anchor-header">Alterações de rutura</h3><ul>
<li>Pesquisa de agrupamento descontinuada em vectores binários<a href="https://github.com/milvus-io/milvus/pull/31735">(#31735</a>)</li>
<li>Descontinuação da pesquisa de agrupamento com pesquisa híbrida<a href="https://github.com/milvus-io/milvus/pull/31812">(#31812</a>)</li>
<li>Descontinuação do índice HNSW em vectores binários<a href="https://github.com/milvus-io/milvus/pull/31883">(#31883</a>)</li>
</ul>
<h3 id="Bug-Fixes" class="common-anchor-header">Correcções de erros</h3><ul>
<li>Verificações melhoradas do tipo de dados e valores para consultas e inserções para evitar falhas<a href="https://github.com/milvus-io/milvus/pull/31478">(#31478</a>, <a href="https://github.com/milvus-io/milvus/pull/31653">#31653</a>, <a href="https://github.com/milvus-io/milvus/pull/31698">#31698</a>, <a href="https://github.com/milvus-io/milvus/pull/31842">#31842</a>, <a href="https://github.com/milvus-io/milvus/pull/32042">#32042</a>, <a href="https://github.com/milvus-io/milvus/pull/32251">#32251</a>, <a href="https://github.com/milvus-io/milvus/pull/32204">#32204</a>)</li>
<li>Correcções de erros da API RESTful<a href="https://github.com/milvus-io/milvus/pull/32160">(#32160</a>)</li>
<li>Previsão melhorada da utilização de recursos de índice invertido<a href="https://github.com/milvus-io/milvus/pull/31641">(#31641</a>)</li>
<li>Resolução de problemas de ligação com o etcd quando a autorização está activada<a href="https://github.com/milvus-io/milvus/pull/31668">(#31668</a>)</li>
<li>Atualização de segurança para o servidor nats<a href="https://github.com/milvus-io/milvus/pull/32023">(#32023</a>)</li>
<li>Ficheiros de índices invertidos armazenados num caminho de armazenamento local do QueryNode em vez de /tmp<a href="https://github.com/milvus-io/milvus/pull/32210">(#32210</a>)</li>
<li>Resolvida a fuga de memória do datacoord para o collectionInfo<a href="https://github.com/milvus-io/milvus/pull/32243">(#32243</a>)</li>
<li>Correcções para bugs relacionados com fp16/bf16 que potencialmente causam panes no sistema<a href="https://github.com/milvus-io/milvus/pull/31677">(#31677</a>, <a href="https://github.com/milvus-io/milvus/pull/31841">#31841</a>, <a href="https://github.com/milvus-io/milvus/pull/32196">#32196</a>)</li>
<li>Resolvidos problemas com a pesquisa de agrupamento que retornava resultados insuficientes<a href="https://github.com/milvus-io/milvus/pull/32151">(#32151</a>)</li>
<li>Ajustamento da pesquisa com iteradores para lidar com os desvios no passo Reduzir mais eficazmente e assegurar resultados adequados com "reduceStopForBest" ativado<a href="https://github.com/milvus-io/milvus/pull/32088">(#32088</a>)</li>
</ul>
<h2 id="v240-rc1" class="common-anchor-header">v2.4.0-rc.1<button data-href="#v240-rc1" class="anchor-icon" translate="no">
      <svg translate="no"
        aria-hidden="true"
        focusable="false"
        height="20"
        version="1.1"
        viewBox="0 0 16 16"
        width="16"
      >
        <path
          fill="#0092E4"
          fill-rule="evenodd"
          d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"
        ></path>
      </svg>
    </button></h2><p>Data de lançamento: 20 de março de 2024</p>
<table>
<thead>
<tr><th>Versão do Milvus</th><th>Versão do Python SDK</th></tr>
</thead>
<tbody>
<tr><td>2.4.0-rc.1</td><td>2.4.0</td></tr>
</tbody>
</table>
<p>Esta versão introduz várias funcionalidades baseadas em cenários:</p>
<ul>
<li><p><strong>Novo índice GPU - CAGRA</strong>: Graças à contribuição da NVIDIA, este novo índice GPU oferece um aumento de desempenho de 10x, especialmente para pesquisas em lote. Para obter detalhes, consulte <a href="/docs/pt/gpu_index.md">Índice de GPU</a>.</p></li>
<li><p><strong>Pesquisa</strong><strong>multi-vetorial</strong> e <strong>híbrida</strong>: Este recurso permite armazenar embeddings vetoriais de vários modelos e realizar pesquisas híbridas. Para obter detalhes, consulte <a href="/docs/pt/multi-vector-search.md">Pesquisa híbrida</a>.</p></li>
<li><p><strong>Vectores esparsos</strong>: Ideais para interpretação e análise de palavras-chave, os vectores esparsos são agora suportados para processamento na sua coleção. Para obter detalhes, consulte <a href="/docs/pt/sparse_vector.md">Vectores esparsos</a>.</p></li>
<li><p><strong>Pesquisa de agrupamento</strong>: A agregação categórica melhora a recuperação a nível de documento para aplicações de Geração Aumentada por Recuperação (RAG). Para obter detalhes, consulte <a href="https://milvus.io/docs/single-vector-search.md#Grouping-search">Pesquisa de agrupamento</a>.</p></li>
<li><p><strong>Índice invertido</strong> e <strong>Fuzzy Matching</strong>: Estas capacidades melhoram a recuperação de palavras-chave para campos escalares. Para obter detalhes, consulte <a href="/docs/pt/index-scalar-fields.md">Indexar campos escalares</a> e <a href="/docs/pt/single-vector-search.md#filtered-search">pesquisa filtrada</a>.</p></li>
</ul>
<h3 id="New-Features" class="common-anchor-header">Novos recursos</h3><h4 id="GPU-Index---CAGRA" class="common-anchor-header">Índice GPU - CAGRA</h4><p>Gostaríamos de expressar a nossa sincera gratidão à equipa da NVIDIA pela sua inestimável contribuição para o CAGRA, um índice de grafos baseado em GPU de última geração (SoTA) que pode ser utilizado online.</p>
<p>Ao contrário dos índices GPU anteriores, o CAGRA demonstra uma superioridade esmagadora mesmo em consultas de pequenos lotes, uma área em que os índices CPU tradicionalmente se destacam. Além disso, o desempenho do CAGRA em consultas de grandes lotes e na velocidade de construção de índices, domínios em que os índices de GPU já se destacam, é verdadeiramente incomparável.</p>
<p>O código de exemplo pode ser encontrado em <a href="https://github.com/milvus-io/pymilvus/blob/2.4/examples/example_gpu_cagra.py">example_gpu_cagra.py</a>.</p>
<h4 id="Sparse-Vector-Beta" class="common-anchor-header">Vetor esparso (Beta)</h4><p>Nesta versão, estamos a introduzir um novo tipo de campo vetorial chamado vetor esparso. Os vectores esparsos são diferentes dos seus homólogos densos, uma vez que tendem a ter um número de dimensões superior em várias magnitudes, sendo que apenas algumas são diferentes de zero. Esta caraterística oferece uma melhor interpretabilidade devido à sua natureza baseada em termos e pode ser mais eficaz em determinados domínios. Os modelos esparsos aprendidos, como o SPLADEv2/BGE-M3, provaram ser muito úteis para tarefas comuns de classificação na primeira fase. O principal caso de utilização desta nova funcionalidade do Milvus é permitir uma pesquisa semântica aproximada eficiente do vizinho mais próximo em vectores esparsos gerados por modelos neurais como o SPLADEv2/BGE-M3 e modelos estatísticos como o algoritmo BM25. O Milvus suporta agora armazenamento, indexação e pesquisa eficazes e de alto desempenho (MIPS, Maximum Inner Product Search) de vectores esparsos.</p>
<p>O código de exemplo pode ser encontrado em <a href="https://github.com/milvus-io/pymilvus/blob/2.4/examples/hello_sparse.py">hello_sparse.py</a>.</p>
<h4 id="Multi-Embedding---Hybrid-Search" class="common-anchor-header">Pesquisa híbrida e incorporação múltipla</h4><p>O suporte multi-vetorial é a pedra angular para aplicações que requerem processamento de dados multi-modelo ou uma mistura de vectores densos e esparsos. Com o suporte multi-vetorial, agora é possível:</p>
<ul>
<li>Armazenar embeddings vectoriais gerados para amostras de texto, imagem ou áudio não estruturados a partir de vários modelos.</li>
<li>Realizar pesquisas ANN que incluam vários vectores de cada entidade.</li>
<li>Personalizar estratégias de pesquisa atribuindo pesos a diferentes modelos de incorporação.</li>
<li>Experimentar vários modelos de incorporação para encontrar a combinação ideal de modelos.</li>
</ul>
<p>O suporte a vários vetores permite armazenar, indexar e aplicar estratégias de reranking a vários campos de vetores de diferentes tipos, como FLOAT_VECTOR e SPARSE_FLOAT_VECTOR, em uma coleção. Atualmente, estão disponíveis duas estratégias de reclassificação: <strong>Reciprocal Rank Fusion (RRF)</strong> e <strong>Average Weighted Scoring</strong>. Ambas as estratégias combinam os resultados da pesquisa de diferentes campos vectoriais num conjunto de resultados unificado. A primeira estratégia dá prioridade às entidades que aparecem consistentemente nos resultados de pesquisa de diferentes campos vectoriais, enquanto a outra estratégia atribui pesos aos resultados de pesquisa de cada campo vetorial para determinar a sua importância no conjunto de resultados final.</p>
<p>O código de exemplo pode ser encontrado em <a href="https://github.com/milvus-io/pymilvus/blob/2.4/examples/hybrid_search.py">hybrid_search.py</a>.</p>
<h4 id="Inverted-Index-and-Fuzzy-Match" class="common-anchor-header">Índice invertido e Fuzzy Match</h4><p>Em versões anteriores do Milvus, os índices de pesquisa binária baseados em memória e os índices Marisa Trie eram usados para indexação de campos escalares. No entanto, esses métodos consumiam muita memória. A versão mais recente do Milvus agora emprega o índice invertido baseado em Tantivy, que pode ser aplicado a todos os tipos de dados numéricos e de strings. Este novo índice melhora drasticamente o desempenho da consulta escalar, reduzindo em dez vezes a consulta de palavras-chave em cadeias de caracteres. Além disso, o índice invertido consome menos memória, graças a optimizações adicionais na compressão de dados e no mecanismo de armazenamento mapeado por memória (MMap) da estrutura de indexação interna.</p>
<p>Esta versão também suporta correspondências difusas na filtragem escalar usando prefixos, infixos e sufixos.</p>
<p>O código de exemplo pode ser encontrado em <a href="https://github.com/milvus-io/pymilvus/blob/2.4/examples/inverted_index_example.py">inverted_index_example.py</a> e <a href="https://github.com/milvus-io/pymilvus/blob/2.4/examples/fuzzy_match.py">fuzzy_match.py</a>.</p>
<h4 id="Grouping-Search" class="common-anchor-header">Agrupamento de pesquisa</h4><p>Agora é possível agregar os resultados da pesquisa pelos valores de um campo escalar específico. Isso ajuda os aplicativos RAG a implementar a recuperação no nível do documento. Considere uma coleção de documentos, cada documento dividido em várias passagens. Cada passagem é representada por um vetor de incorporação e pertence a um documento. Para encontrar os documentos mais relevantes em vez de passagens dispersas, pode incluir o argumento group_by_field na operação search() para agrupar os resultados pelo ID do documento.</p>
<p>O código de exemplo pode ser encontrado em <a href="https://github.com/milvus-io/pymilvus/blob/2.4/examples/example_group_by.py">example_group_by.py</a>.</p>
<h4 id="Float16-and-BFloat--Vector-DataType" class="common-anchor-header">Float16 e BFloat- Vetor DataType</h4><p>A aprendizagem automática e as redes neurais utilizam frequentemente tipos de dados de meia-precisão, como Float16 e BFloat. Embora estes tipos de dados possam melhorar a eficiência da consulta e reduzir a utilização de memória, têm como contrapartida uma precisão reduzida. Com esta versão, o Milvus suporta agora estes tipos de dados para campos vectoriais.</p>
<p>O código de exemplo pode ser encontrado em <a href="https://github.com/milvus-io/pymilvus/blob/2.4/examples/float16_example.py">float16_example.py</a> e <a href="https://github.com/milvus-io/pymilvus/blob/2.4/examples/bfloat16_example.py">bfloat16_example.py</a>.</p>
<h3 id="Upgraded-Architecture" class="common-anchor-header">Arquitetura atualizada</h3><h4 id="L0-Segment" class="common-anchor-header">Segmento L0</h4><p>Esta versão inclui um novo segmento chamado Segmento L0, projetado para registrar dados excluídos. Este segmento compacta periodicamente os registos apagados armazenados e divide-os em segmentos selados, reduzindo o número de descargas de dados necessárias para pequenas eliminações e deixando uma pequena pegada de armazenamento. Com este mecanismo, o Milvus separa completamente as compactações de dados das descargas de dados, melhorando o desempenho das operações de eliminação e inserção.</p>
<h4 id="Refactored-BulkInsert" class="common-anchor-header">BulkInsert refatorado</h4><p>Esta versão também introduz uma lógica melhorada de inserção em massa. Isto permite-lhe importar vários ficheiros num único pedido de inserção em massa. Com a versão refacturada, tanto o desempenho como a estabilidade da inserção em massa registaram melhorias significativas. A experiência do utilizador também foi melhorada, como a limitação de taxa ajustada e mensagens de erro mais fáceis de utilizar. Além disso, é possível aceder facilmente aos pontos finais de inserção em massa através da API RESTful do Milvus.</p>
<h4 id="Memory-mapped-Storage" class="common-anchor-header">Armazenamento com memória mapeada</h4><p>O Milvus utiliza o armazenamento mapeado na memória (MMap) para otimizar a utilização da memória. Em vez de carregar o conteúdo do ficheiro diretamente para a memória, este mecanismo mapeia o conteúdo do ficheiro para a memória. Esta abordagem tem como contrapartida a degradação do desempenho.  Ao ativar o MMap para uma coleção indexada HNSW num anfitrião com 2 CPUs e 8 GB de RAM, pode carregar 4x mais dados com menos de 10% de degradação do desempenho.</p>
<p>Além disso, esta versão também permite um controlo dinâmico e fino do MMap sem necessidade de reiniciar o Milvus.</p>
<p>Para obter detalhes, consulte <a href="/docs/pt/mmap.md">MMap Storage</a>.</p>
<h3 id="Others" class="common-anchor-header">Outros</h3><h4 id="Milvus-CDC" class="common-anchor-header">Milvus-CDC</h4><p>O Milvus-CDC é uma ferramenta complementar fácil de usar para capturar e sincronizar dados incrementais entre instâncias do Milvus, permitindo um backup incremental fácil e recuperação de desastres. Nesta versão, o Milvus-CDC melhorou a estabilidade e a sua funcionalidade de Captura de Dados de Alteração (CDC) está agora disponível para todos.</p>
<p>Para saber mais sobre o Milvus-CDC, consulte o <a href="https://github.com/zilliztech/milvus-cdc">repositório GitHub</a> e a <a href="/docs/pt/milvus-cdc-overview.md">Visão geral do Milvus-CDC</a>.</p>
<h4 id="Refined-MilvusClient-Interfaces" class="common-anchor-header">Interfaces MilvusClient refinadas</h4><p>MilvusClient é uma alternativa fácil de usar para o módulo ORM. Ele adota uma abordagem puramente funcional para simplificar as interações com o servidor. Em vez de manter um pool de conexões, cada MilvusClient estabelece uma conexão gRPC com o servidor. O módulo MilvusClient implementou a maioria das funcionalidades do módulo ORM. Para saber mais sobre o módulo MilvusClient, visite <a href="https://github.com/milvus-io/pymilvus">pymilvus</a> e os <a href="/api-reference/pymilvus/v2.4.x/About.md">documentos de referência</a>.</p>
