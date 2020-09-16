<h5><a href="blank_">[en]</a> | <a href="blank_">[pt-br]</a>
</h5>
<h5>
<div>
  <table>
    <tr>
      <th>PROJETO</th>
      <th>OBJETIVO</th>
      <th>TIPO DE DADOS</th>
      <th>TIPO MACHINE LEARNING</th>
    </tr>
    <tr>
      <td>Recomendador de vídeos do youtube</td>
      <td>Entender Ciência de dados na prática</td>
      <td>Time Series</td>
      <td>Supervisionado</td>
    </tr>
    <tr>
        <td colspan="4">LinkedIn : https://www.linkedin.com/in/claudineien/</td>
    </tr>
  </table>
</div>
</h5>

<h2>CICLO DE VIDA DE UMA SOLUÇÃO EM CIÊNCIA DE DADOS</h2>
<h3>DEFINIR O PROBLEMA E A SOLUÇÃO</h3>
<h4>01 QUAL É O PROBLEMA ?</h4>
<p>Antes mesmo de iniciar um projeto de ciência de dados, você deve definir o problema que deverá ser resolvido. O problema deverá estar diretamente relacionado ao objetivo do requisito do negócio.</p>
<p>Definir o problema é uma responsabilidade do cientista de dados com o time de negócios, responsabilidade bilateral.</p>
<p>Em nosso projeto <strong>O problema</strong> é : ' Muito tempo gasto buscando novos vídeos no youtube '.</p>
<hr>
<h4>02 QUAL A MELHOR SOLUÇÃO ?</h4>
<p>O Cientista de dados é o especialista em sua área, e é seu trabalho guiar/ajudar a organização a encontrar o que quer e/ou que precisa.</p>
<p>O Cientista de dados deve ser capaz de traduzir as questões de negócio ao seu "botão mágico para conquistar o sucesso" em algo que possa ser resolvido matematicamente com o dataset da organização.</p>
<p>Definir a melhor solução é uma responsabilidade bilateral : Cientista de dados com o time de negócios. O processo e iterativo, que significa seguir desenhando e apresentando a solução aos parceiros de negócios até chegar ao problema e a solução ideal diretamente relacionada a este problema.</p>
<p>Em nosso projeto <strong>A solução ideal</strong> é ' Listar apenas vídeos que eu vou gostar '.</p>

<h4>03 COMO CRIAR A/UMA SOLUÇÃO DATA SCIENCE USANDO MACHINE LEARNING ?</h4>
<p>O Cientista de dados como uma ferramenta a mais para eliminar problemas, analisa o processo da organização e o relaciona ao problema definido versus a melhor solução definida, então desenvolve o algoritmo machine learning sob determinadas amostras. O algoritmo deve ter um resultado igual ou melhor ao resultado esperado.</p>
<p>Em nosso projeto <strong>Criaremos um Recomendador de vídeos</strong> que irá executar um ou mais processos a seguir :
    <ul>
        <li>Exibir apenas os vídeos que eu vou gostar</li>
		<li>Criar Solução com Hanking dos vídeos que primeiramente eu vou gostar seguido dos que eu menos vou gostar</li>
        <li>Consultar os últimos nnn vídeos por data de upload/publicação, considerando o título, visualizações totais desde seu upload, visualizações por dia desde seu upload.</li>
        <li>Estabelecer uma abordagem de ponto corte : Retornar apenas 3 que eu vou gostar</li>
        <li>Abordagem de ranking : ordenar dos vídeos eu mais vou gostar aos que eu menos vou gostar</li>
        <li>Consultará pelas seguintes palavras chave : machine-learning, kaggle, datascience</li>
    </ul>
</p>

<h4>04 COMO A SOLUÇÃO SERÁ USADA PRODUTIVAMENTE ?</h4>
<p>O Cientista de dados analisa o resultado retornado, como este resultado será apresentado e define como devem ser tratados os novos dados.</p>
<p>O resultado pode ser apresentado em um Web app, ERP system, Dashboard, Excel, etc...</p>
<p>Em primeiro momento é responsabilidade do Cientista de dados definir como a solução será usada produtivamente. Após ter o modelo definitivo o Cientista de dados com o time de negócios estabelecem como a solução será usada definitivamente em produção.</p>
<p>Em nosso projeto <strong>criaremos um Web App</strong> com link dos vídeos e as previsões ordenadas e com os seguintes dados : Título, Label, Anotações, Descrição</p>

<h4>05 COMO SABER SE A SOLUÇÃO DEU CERTO ?</h4>
<p>O Cientista de dados define as métricas de acordo com a área de negócio e dados obtidos, compara os resultados entre solução machine learning e os resultados atualmente conquistados sem machine learning.</p>
<p>Deve haver uma métrica primária e uma ou mais métricas secundárias.</p>
<p>Em nosso projeto :
    <ul>
        <li>A métrica primária será : Top NNN vídeos inclusos na lista watch later</li>
		<li>As métricas secundárias podem ser :</li>
        <ul>
            <li>Quantidades NNN de vídeos assistidos até o final</li>
            <li>Tempo X investido selecionando os vídeos recomendados por Machine Learning</li>
            <li>Os top NNN recomendados por Machine Learning são mais assistidos do que os top NNN da busca google ? : [YES] ou [NO]</li>
        </ul>
    </ul>
</p>
<p><strong>Dica para sair do zero com Machine Learning :</strong><br>
Desenvolva machine learning sobre um problema resolvido diversas vezes com objetivo de fazer um modelo preditivo no mínimo 10% melhor que o atual modelo.</p>

<p>
<h4>EM CIÊNCIA DE DADOS DEVEMOS CONSIDERAR QUE :</h4>
    <ol>
        <li>Passos 01 e 02 : serve para entender todo o processo do negócio, para definir o problema e a melhor solução.</li>
        <li>Passos 03 e 04 : serve para desenvolver o modelo machine learning sob os processos e métricas do negócio.</li>
        <li>Passo 05 : serve para testar o modelo machine learning desenvolvido sob os processos e métricas do negócio e disponibilizá-lo em produção.</li>
    </ol>
</p>

<h3>COLETAR E TRABALHAR OS E/OU NOS DADOS</h3>
<p>Nesta etapa o Cientista de dados aplicará todas as técnicas para tornar os dados em perfeita conformidade ao modelo de predição que será desenvolvido</p>

<h4>COLETAR OS DADOS</h4>
<p>Os dados podem ser coletados das seguintes fontes :</p>
<p>
    <ul>
        <li>banco de dados relacional e estruturado</li>
        <li>banco de dados NoSQL</li>
        <li>buscando na internet (scraping)</li>
        <li>de imagens</li>
        <li>de emails</li>
        <li>com as pessoas envolvidas no processo</li>
        <li>planilhas excel</li>
        <li>redes sociais</li>
        <li>sensores</li>
        <li>documentos word/pdf e similares</li>
    </ul>
</p>

<h4>ANALISAR E EXPLORAR OS DADOS</h4>
<p>
    <ul>
        <li>detectar se há os dados que precisa para desenvolver a solução</li>
        <li>analisar o tipo de cada dado : string, objeto, float, inteiro</li>
        <li>analisar o conteúdo de cada dado</li>
        <li>analisar a correlação entre os dados</li>
        <li>Detectar padrões entre os dados</li>
        <li>Detectar tendências entre os dados</li>
    </ul>
</p>

<h4>LIMPAR OS DADOS</h4>
<p>
    <ul>
        <li>remover dados redundantes</li>
        <li>trabalhar nos dados faltantes</li>
        <li>trabalhar nos dados duplicados</li>
        <li>trabalhar nos dados desnecessários</li>
    </ul>
</p>

<h4>CONVERTER OS DADOS</h4>
<p>
    <ul>
        <li>de objetos para data</li>
        <li>de objetos para string</li>
        <li>de data para string</li>
        <li>categóricos para numéricos</li>
    </ul>
</p>

<h4>ANALISAR E EXPLORAR OS DADOS</h4>
<p>
    <ul>
        <li>Detectar padrões entre os dados</li>
        <li>Detectar tendências entre os dados</li>
        <li>Detectar correlação entre os dados</li>
    </ul>
</p>

<h4>MODELAR OS DADOS</h4>
<p>Nesta fase o Cientista de dados separa seu conjunto de dados nas seguinte proporções :</p>
<p>
    <ul>
        <li>Uma proporção para treinar o modelo, conhecido como conjunto de dados de treino</li>
        <li>Uma proporção para testar a eficiência do modelo, conhecido com conjunto de dados de teste</li>
    </ul>
Nesta fase o modelo de dados esta sendo contruÍdo pelo conjunto de dados de treino e sendo evoluÍdo pelo conjunto de dados de teste.
</p>

<h3>OTIMIZAR E IMPLANTAR</h3>
<p>Esta fase serve para melhorar a eficiência do modelo machine learning, e realizar mais predições precisas.</p>
<p>O objetivo final é implantar o modelo de machine learning em ambiente de validação ou em ambiente de produção para aceitação dos usuários</p>
<p>Os usuários deverão testar o desempenho do modelo machine learning e verificar se há quaisquer inconsistências, que serão corrigidos pelo Cientista de dados.</p>
<br><br><br>
<hr>
<p>Fontes de estudo
    <ul>
        <li><a href="https://curso.mariofilho.com/">   
        Curso Solução Completa de Data Science - Instrutor Mario Filho-Kagle Gran Master</a></li>
        <li><a href="https://www.edureka.co/blog/data-science-projects/#A%20Basic%20Approach%20To%20Solving%20A%20Problem%20Using%20Data%20Science">Edureka</a></li>
    </ul>
</p>