<body>
	<h1>Projeto de Predição de Churn em Clientes do Beta Bank</h1>
  <h2>Descrição do Projeto</h2>
	<p>Os clientes do Beta Bank estão saindo: pouco a pouco, escapulindo todo mês. Os banqueiros descobriram que é mais barato salvar os clientes existentes do que atrair novos. Precisamos prever se um cliente deixará o banco em breve. Você tem os dados sobre o comportamento passado dos clientes e rescisões de contratos com o banco. Construa um modelo com o valor máximo possível de F1. Para passar na revisão, você precisa de um valor F1 de pelo menos 0,59 para o conjunto de dados de teste. Além disso, meça a métrica AUC-ROC e compare-a com o valor F1.</p>
  <h2>Fonte de Dados</h2>
<p>Os dados do projeto estão disponíveis no arquivo Churn.csv. As variáveis contidas nos dados são:</p>
<ul>
	<li>RowNumber: índice das strings de dados</li>
	<li>CustomerId: identificador exclusivo do cliente</li>
	<li>Surname: sobrenome</li>
	<li>CreditScore: pontuação de crédito</li>
	<li>Geography: país de residência</li>
	<li>Gender: gênero</li>
	<li>Age: idade</li>
	<li>Tenure: tempo de serviço para o cliente</li>
	<li>Balance: saldo da conta</li>
	<li>NumOfProducts: número de produtos bancários usados pelo cliente</li>
	<li>HasCrCard: cliente possui cartão de crédito (1 - sim; 0 - não)</li>
	<li>IsActiveMember: cliente ativo (1 - sim; 0 - não)</li>
	<li>EstimatedSalary: salário estimado</li>
	<li>Exited: o cliente saiu (1 - sim; 0 - não)</li>
</ul>

<h2>Preparação dos Dados</h2>
<p>Antes de construir o modelo, os dados precisam ser preparados. O processo de preparação de dados envolve a limpeza dos dados e a transformação de variáveis categóricas em variáveis numéricas. O equilíbrio das classes também é examinado para garantir que o modelo não seja viésado em relação a uma classe.</p>

<h2>Treinamento do Modelo</h2>
<p>O modelo é treinado sem levar em conta o desequilíbrio das classes. Descobertas breves são descritas após a execução do modelo.</p>
<p>Para melhorar a qualidade do modelo, duas abordagens para corrigir o desequilíbrio de classe são utilizadas. Um conjunto de treinamento e validação é usado para encontrar o melhor modelo e o melhor conjunto de parâmetros. Descobertas breves são descritas após a execução do modelo.</p>

<h2>Teste Final</h2>
<p>O teste final é realizado para avaliar a eficácia do modelo na previsão de clientes que estão em risco de deixar o banco. A métrica F1 e AUC-ROC são medidas e comparadas para avaliar a eficácia do modelo.</p>
 
<h2>Conclusão</h2>
<p>Este projeto de previsão de churn do Beta Bank envolveu a preparação dos dados, treinamento do modelo e teste final. O objetivo era construir um modelo que maximize o valor F1, com um mínimo de 0,59 para o conjunto de dados de teste. O equilíbrio das classes foi examinado e duas abordagens para corrigir o desequilíbrio de classe foram utilizadas para melhorar a qualidade do modelo. O modelo final foi avaliado usando a métrica F1 e AUC-ROC.</p>
