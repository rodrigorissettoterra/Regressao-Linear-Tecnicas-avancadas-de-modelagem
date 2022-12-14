<strong>REGRESSÃO LINEAR: TÉCNICAS AVANÇADAS EM MODELAGEM</strong>
<ul>
 	<li>1.1 Conhecendo o Dataset
<ul>
 	<li>Importando a biblioteca pandas</li>
 	<li>O Dataset e o Projeto</li>
 	<li>Leitura dos dados</li>
 	<li>Visualizar os dados</li>
 	<li>Verificando o tamanho do dataset</li>
</ul>
</li>
 	<li>1.2 Análises Preliminares
<ul>
 	<li>Estatísticas descritivas</li>
 	<li>Matriz de correlação</li>
</ul>
</li>
 	<li>2.1 Comportamento da Variável Dependente (Y)
<ul>
 	<li>Importando biblioteca seaborn</li>
 	<li>Configurações de formatação dos gráficos</li>
 	<li>Box plot da variável dependente (y)</li>
</ul>
</li>
 	<li>2.2 Distribuição de Frequências
<ul>
 	<li>Distribuição de frequências da variável dependente (y)</li>
</ul>
</li>
 	<li>2.3 Dispersão Entre as Variáveis
<ul>
 	<li>Gráficos de dispersão entre as variáveis do dataset</li>
 	<li>seaborn.pairplot</li>
</ul>
</li>
 	<li>3.1 Transformando os Dados
<ul>
 	<li>Distribuição Normal</li>
 	<li>Importando biblioteca numpy</li>
 	<li>Aplicando a transformação logarítmica aos dados do dataset</li>
 	<li>Distribuição de frequências da variável dependente transformada (y)</li>
</ul>
</li>
 	<li>3.2 Verificando Relação Linear
<ul>
 	<li>Gráficos de dispersão entre as variáveis transformadas do dataset</li>
</ul>
</li>
 	<li>4.1 Criando os Datasets de Treino e Teste
<ul>
 	<li>Importando o train_test_split da biblioteca scikit-learn</li>
 	<li>Criando uma Series (pandas) para armazenar o Preço dos Imóveis (y)</li>
 	<li>Criando um DataFrame (pandas) para armazenar as variáveis explicativas (X)</li>
 	<li>Criando os datasets de treino e de teste</li>
 	<li>Regresão Linear</li>
 	<li>Importando a biblioteca statsmodels</li>
 	<li>Estimando o modelo com statsmodels</li>
</ul>
</li>
 	<li>4.2 Avaliando o Modelo Estimado
<ul>
 	<li>Avaliando as estatísticas de teste do modelo</li>
</ul>
</li>
 	<li>4.3 Modificando o Modelo e Avaliando Novamente o Ajuste
<ul>
 	<li>Criando um novo conjunto de variáveis explicativas (X)</li>
 	<li>Criando os datasets de treino e de teste</li>
 	<li>Estimando o modelo com o statsmodels</li>
 	<li>Avaliando as estatísticas de teste do novo modelo</li>
</ul>
</li>
 	<li>5.1 Estimando o Modelo com os Dados de Treino
<ul>
 	<li>Importando LinearRegression e metrics da biblioteca scikit-learn</li>
 	<li>Instanciando a classe LinearRegression()</li>
 	<li>Utilizando o método fit() do objeto "modelo" para estimar nosso modelo linear utilizando os dados de</li>
 	<li>TREINO (y_train e X_train)</li>
 	<li>Obtendo o coeficiente de determinação (R²) do modelo estimado com os dados de TREINO</li>
 	<li>Gerando previsões para os dados de TESTE (X_test) utilizando o método predict() do objeto "modelo"</li>
 	<li>Obtendo o coeficiente de determinação (R²) para as previsões do nosso modelo</li>
</ul>
</li>
 	<li>5.2 Obtendo Previsões Pontuais
<ul>
 	<li>Dados de entrada</li>
 	<li>Gerando previsão pontual</li>
 	<li>Invertendo a transformação para obter a estimativa em R$</li>
 	<li>Criando um simulador simples</li>
</ul>
</li>
 	<li>5.3 Interpretação dos Coeficientes Estimados
<ul>
 	<li>Obtendo o intercepto do modelo</li>
 	<li>Obtendo os coeficientes de regressão</li>
 	<li>Confirmando a ordem das variáveis explicativas no DataFrame</li>
 	<li>Criando uma lista com os nomes das variáveis do modelo</li>
 	<li>Criando um DataFrame para armazenar os coeficientes do modelo</li>
 	<li>Interpretação dos Coeficientes Estimados</li>
</ul>
</li>
 	<li>5.4 Análises Gráficas dos Resultados do Modelo
<ul>
 	<li>Gerando as previsões do modelo para os dados de TREINO</li>
 	<li>Gráfico de dispersão entre valor estimado e valor real</li>
 	<li>Obtendo os resíduos</li>
 	<li>Plotando a distribuição de frequências dos resíduos</li>
</ul>
</li>
</ul>
