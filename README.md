# Tutorial de aprendizagem não supervisionada em R

Muitas vezes no aprendizado de máquina o objetivo é encontrar padrões nos dados sem tentar fazer previsões, isso é chamado de aprendizagem não supervisionada. É comum em campanhas de marketing direcionadas usar a aprendizagem não supervisionada para agrupar consumidores com base em dados demográficos e histórico de compras. Outro exemplo é querer descrever os fatores não medidos que mais influenciam as diferenças entre cidades. Este tutorial é uma introdução básica às técnicas de cluster e redução de dimensionalidade em R a partir de uma perspectiva de aprendizado de máquina.

* O código está no formato do RMarkdown.
* É necessário instalar o(s) seguinte(s) pacote(s) do R para rodar o código: readxl, FactoMineR, ade4, factoextra

Conteúdo do tutorial:

### 1) k-means
1.1) Visualizando clusters;
1.2) Aleatoriedade do algoritmo k-means;
1.3) Selecionando o número de clusters;
1.4) Trabalhando com dados reais;

### 2) Clustering hierárquico
2.1) Modelo simples de clustering hierárquico;
2.2) Podando a árvore;
2.3) Métodos de ligação;
2.4) Questões práticas: dimensionamento;
2.5) Comparando kmeans() e hclust();

### 3) Redução de dimensionalidade com PCA
3.1) PCA com FactoMineR;
3.2) Explorando a função PCA();
3.3) PCA com ade4;
3.4) Interpretando e visualizando modelos de PCA com factoextra;
3.4.1) Plotando a contribuição das variáveis;
3.4.2) Plotando as contribuições das variáveis selecionadas;
3.4.3) Plotando as contribuições das variáveis selecionadas pelo gráfico de barras;
3.4.4) Plotando cos2 para indivíduos;
3.4.5) Plotando cos2 para variáveis selecionadas;
3.4.6) Gráfico de barras do co2 para indivíduos;
3.4.7) Biplots;
3.5) Aplicando aos dados do cars;
3.5.1) Plotando cos2;
3.5.2) Plotando as contribuições;
3.5.3) Biplots e seus elipsóides;

Baseado nos cursos Unsupervised Learning with R e Dimensionality Reduction with R da DataCamp.
