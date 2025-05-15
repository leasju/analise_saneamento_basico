<h1>📊 Análise Estatística de Indicadores do IMRS – Dimensão Saneamento Básico</h1>

<p>
  Este repositório reúne os materiais desenvolvidos para o projeto da disciplina <strong>Estatística e Inferência</strong>, ministrada pelo professor <strong>Valdomiro Placido</strong>, da faculdade <strong>PUC Campinas</strong>.  
  O objetivo foi realizar uma análise exploratória de dados a partir do <strong>Índice Mineiro de Responsabilidade Social (IMRS)</strong>, com foco na <strong>dimensão de Saneamento Básico</strong>.
</p>

<h2>🗂️ Conteúdo do repositório</h2>
<ul>
  <li>📓 Notebook em Python com o processo de análise de dados (Google Colab)</li>
  <li>📄 Relatório em PDF com as análises estatísticas, gráficos e interpretações dos indicadores selecionados</li>
</ul>

<h2>🔍 Indicadores analisados</h2>
<p>A análise teve como base três indicadores relacionados à dimensão de Saneamento Básico:</p>
<ul>
  <li><strong>Percentual de Esgoto Coletado e Tratado</strong></li>
  <li><strong>Percentual da População Urbana em Domicílios com Abastecimento de Água</strong></li>
  <li><strong>Percentual da Disposição Final do Lixo Coletado</strong></li>
</ul>

<p>
  Esses indicadores foram extraídos da base de dados disponibilizada pela Fundação João Pinheiro:<br>
  📁 <a href="https://raw.githubusercontent.com/MiroPlacido/Datasets/refs/heads/main/imrs.csv">imrs.csv (Fonte de dados)</a>
</p>

<h2>🧪 Metodologia</h2>
<ul>
  <li>Análise descritiva individual de cada indicador (média, mediana, desvio padrão, distribuição, etc.)</li>
  <li>Visualizações gráficas (histogramas, boxplots, gráficos comparativos)</li>
  <li>Segmentação dos dados por <strong>mesorregiões</strong> e <strong>microrregiões</strong> do estado de Minas Gerais</li>
</ul>

<p>As análises foram realizadas utilizando a linguagem <strong>Python</strong>, no ambiente <strong>Google Colab</strong>, com as seguintes bibliotecas:</p>

<pre><code>import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
</code></pre>

<h2>🎯 Objetivo</h2>
<p>
  Investigar a situação do saneamento básico nos municípios de Minas Gerais a partir de três indicadores específicos, identificando <strong>padrões regionais</strong> e <strong>desigualdades territoriais</strong>.
</p>

## 👩‍💻 Integrantes do grupo

- [Isabel Baungartner](https://www.linkedin.com/in/isabel-baungartner-78a573296/)
- [Julia Leandro](www.linkedin.com/in/juliasleandro)  
- [Lavínia Oliveira](https://www.linkedin.com/in/lav%C3%ADnia-oliveira-santos/)
- [Maria Eduarda Fonseca](https://www.linkedin.com/in/maria-eduarda-fonseca-nascimento-7a93a82ba/)

<h2>🔗 Referências</h2>
<ul>
  <li><a href="https://imrs.fjp.mg.gov.br/Home/IMRS">Site oficial do IMRS</a></li>
  <li>Fundação João Pinheiro (FJP)</li>
</ul>
