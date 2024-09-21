# data_science
Learning data science with AI_Labs
Curso de formação em ciencia de dados - 400h - Ia_Labs em parceira com o SENAI - Futuro.Digital

Matriz curricular composta por: 

Introdução à Ciência de Dados - Uso de vetores, matrizes e dicionários:

  
Criar vetores ou matrizes
Criar matrizes esparsas
Redimensionar array “Numpy”
Converter dicionários em matrizes
Inverter matriz ou “nArray”
Calcular diagonal da matriz
Calcular determinante de uma matriz
Transformar matriz em vetor
Calcular: média , desvio padrão e variância
Encontrar classificação de uma matriz (rank)
Máximos e mínimos de uma matriz
Adicionar valor numérico a um elemento de matriz
Calcular produto de dois (02) vetores
Adicionar, subtrair, multiplicar e dividir – valor numérico para cada elemento da matriz
Adicionar e subtrair entre duas (02)  matrizes
Ler características de um dicionario
 

Pré-Processamento de Dados - Representação e a qualidade dos dados:

  
Carregar e trabalhar dados via sklearn (dataset Boston)
Criar dados simulados para regressão
Criar dados simulados para classificação
Criar dados simulados para armazenamento em cluster
Preparar um fluxo de trabalho de aprendizado de máquina
Converter recursos (características) categóricos em recursos numéricos
Imputar rótulos de classes ausentes
Imputar rótulos de classes ausentes usando método "vizinho próximo"
Excluir instâncias com valores ausentes
Como fazer operações numéricas
Como encontrar outliers
Codificar recursos categóricos ordinais
Lidar com classes de desequilíbrio com redução da resolução
Como lidar com classes de desbalanceadas
Como lidar com outliers
Imputar valores ausentes com médias
Codificação com vários rótulos
Codificação com recursos nominais categóricos
Processar recursos categóricos
Redimensionar recursos
Padronizar recursos
Padronizar dados "IRIS"
Dividir dados DateTime ("features") para criar vários recursos
Calcular a diferença entre datas
Codificar os dias da semana
Tratar valores ausentes em uma série temporal
Como introduzir o tempo "LAG" (lagged time-series), tempo de latência são muito usadas em analises econômicas
Como lidar com "Janelas de Tempo"
Selecionar DateTime dentro de um intervalo
Selecionar DateTime [formato (PM) ou (AM)] dentro de um intervalo
Como trabalhar itens em uma lista


Análise de Dados:

  
Análise de Componentes Principais (PCA)
Análise da Variância (ANOVA)
Curva Característica de Operação do Receptor (Curva ROC)
Trabalhar os Hiperparâmetros
Descrever a relação entre uma variável Y e uma X
Uso da biblioteca “Seaborn”


Classificação, Clusterização e Regressão:

 
Criar e otimizar modelo para regressão e classificação
Utilizar “Nearest Neighbours” para regressão e classificação
Fazer agrupamento aglomerativo (Agglomerative Clustering)
Fazer clusterização com o “Kmeans”
Fazer clusterização baseado em afinidade
Utilizar “DBSCAN Clustering”
Utilizar a abordagem do deslocamento médio (MinShift)
Utilizar a arvore de classificação e regressão
Utilizar algoritmo de aprendizado de máquina “AdaBoost”
Utilizar algoritmo de aprendizado de máquina “RandomForest”
Utilizar algoritmo de aprendizado de máquina “GradientBoosting”
Utilizar classificador e regressor multicamadas –  “MLP - Multi Layer Perceptron”
Utilizar classificador e regressor de reforço gradual “XgBoost”
Utilizar classificador e regressor “CatBoost”
Utilizar classificador e regressor “LightGBM”
Utilizar classificador e regressor “SVM”
Classificar com modelos lineares – “Multiclass Classification”
Classificar com modelos lineares – “Naive Bayes”
Classificar com modelos lineares – “Nearest Neighbors”
Classificar com modelos lineares – “LDA e QDA”
Classificar com modelos lineares – “Tree Model”
Classificar com modelos lineares – “Ensemble Bagging Model”
Classificar com modelos lineares – “Ensemble Boosting Model”
Utilizar métrica de classificação e regressão
Comparar algoritmos de classificação
Implementar “Ensemble Model”
Salvar modelos treinados
Avaliar modelos com curvas de aprendizagem
Paralelizar execução e validação cruzada no “XGBoost”
Otimizar número de árvores no “XGBoost”


Visualização de Dados:

  
Autocorrelação (ACF) e Autocorrelação Parcial (PACF)
Pizza com destacamento
Plotagem de textos
Divergências de escala
Densidade
Series temporais múltiplas com escalas
Boxplot
Correlograma – “Correllogram”
Curvas de densidade – “Cross Correlation”
Decomposição de serie temporal
Dispersão com linha de regressão linear de melhor ajuste
Área
Barras
Bolha – “Bubble”
Cascata- “Waterfall”
Lotes em par – “Pairwise”
Histograma empilhado
Variáveis continuas (Histograma)
Histogramas marginais – “Marginal Boxplot”
Quadro de marcadores – “Lollipop”
Piramide populacional
Diagramas de dispersão – “Scatter”
Anotações de picos e vales em series temporais
Cilindros – “Cylinder”
Feixes sólidos – “Joy”
Dado sazonal


Projetos práticos (casos de uso) do nível iniciante ao avançado com bases de dados públicas - Kaggle:

 
Análise de Buscas Google
Análise de Mobilidade Urbana
Análise de densidade Populacional
Análise de Chefes de Estado
Análise da Taxa de Natalidade
Análise de Resumo de Texto
Análise de Anotacoes em Texto
Análise de Digitos Manuscritos
Análise de Reconhecimento Facial/li>
   
Análise de Histograma Gradientes (HOG)
Análise da Detecção de Email Spam
Análise de Predição de Doença
Análise de Desempenho Estudantil
Análise de Desempenho Esportivo


Projeto Final:

	
1. Carregar as Bibliotecas de trabalho (todas que se fizerem necessárias);
2. Carregar  os conjuntos de dados com sua biblioteca de preferência p/ o algoritmo de Aprendizagem de Máquina a ser aplicado:
		
a) carregar a partir de um arquivo CSV ou 
b) carregar a partir de uma Base de Dados;

	   
3. Sumarizar os dados carregados para compreender o conjunto das informações - “dataset” (uso de Estatística Descritiva);
4. Visualizar os dados para compreender o conjunto das informações – “dataset” (criar gráficos variados, conforme o negócio)
5. Preprocessar os dados, aplicar limpeza e transformação - “Data Cleaning & Data transformation” (o “dataset” deve ser dividido em conjuntos de dados de “treino & teste”)
6. Utilizar um algoritmo de aprendizado ao conjunto de dados de treino:
		
a) configurar um algoritmo de aprendizado e suas definições de parâmetros;
b) aplicar validação cruzada com o conjunto de dados de treino;
c) empregar algoritmo para “treino & ajuste” com “dataset” de treino;
d) efetuar avaliação do algoritmo (ou Modelo) treinado e seus resultados;
e) persistir o modelo treinado para previsão futura.

	   
7. Finalizar o modelo treinado e fazer a previsão.
