### 1️⃣ **Preparar o ambiente no Azure Machine Learning**
- Criar um **workspace** no Azure Machine Learning.
- Configurar um **compute instance** para treinar o modelo.
- Criar um **armazenamento de dados** para os registros de temperatura e vendas.

### 2️⃣ **Importar e preparar os dados**
- Carregar os dados históricos de temperatura e vendas de sorvete.
- Realizar **limpeza e pré-processamento** dos dados (tratamento de valores ausentes, normalização, etc.).
- Dividir os dados em **treino e teste**.

### 3️⃣ **Treinar o modelo de Machine Learning**
- Escolher um algoritmo de regressão adequado (como **Regressão Linear** ou **Floresta de Decisão**).
- Treinar o modelo utilizando **Azure Machine Learning Designer** ou **SDK do Azure ML**.
- Avaliar o desempenho do modelo com métricas como **RMSE** e **R²**.

### 4️⃣ **Registrar e gerenciar o modelo com MLflow**
- Usar **MLflow Tracking** para registrar experimentos e métricas.
- Salvar o modelo treinado no **MLflow Model Registry**.
- Versionar modelos para facilitar comparações e melhorias.

### 5️⃣ **Implementar previsões em tempo real**
- Criar um **endpoint de inferência** no Azure Machine Learning.
- Implantar o modelo como um **serviço web** acessível via API.
- Testar previsões enviando dados de temperatura e verificando as respostas.

### 6️⃣ **Criar um pipeline estruturado**
- Automatizar o fluxo de treinamento e teste com **Azure Machine Learning Pipelines**.
- Garantir **reprodutibilidade** e escalabilidade do modelo.
- Monitorar o desempenho do modelo e atualizar conforme necessário.
