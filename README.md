## Análise Exploratória de Dados

Este projeto contém uma análise exploratória de dados sobre o churn de clientes, focada na identificação de padrões e fatores que contribuem para a rotatividade de clientes em uma base de dados específica.

Este notebook busca fornecer uma visão clara e detalhada sobre os fatores que contribuem para o cancelamento de clientes, permitindo uma análise eficaz e oferecendo insights para possíveis ações de retenção.

### Objetivos

- Compreender o comportamento dos clientes que deixam o serviço (churn) e os que permanecem.
- Identificar padrões nas variáveis que influenciam a taxa de cancelamento.
- Criar gráficos e métricas para entender as correlações entre variáveis.
- Realizar ajustes nos dados para melhorar a qualidade da análise.

### Estrutura do Notebook

1. Carregamento dos Dados:
   - Importação da base de dados contendo informações sobre os clientes e suas características.
   - Verificação de dados ausentes, inconsistências e valores duplicados.

2. Análise Exploratória (EDA):
   - Descrição estatística das variáveis.
   - Visualizações com gráficos como histograma, boxplot e gráficos de dispersão para explorar a distribuição das variáveis.
   - Análise de correlação entre as variáveis e o churn.

3. Ajustes nos Dados:
   - Remoção de outliers para evitar distorções na análise.
   - Conversão de variáveis categóricas em numéricas para facilitar a modelagem.
   - Criação de variáveis ajustadas para melhorar a predição do churn.

4. Análise Gráfica e Estatística:
   - Visualizações sobre a relação entre variáveis financeiras (por exemplo, MonthlyCharges e TotalCharges) e o churn.
   - Análise de clientes com diferentes tipos de contrato (mensal, anual etc.).
   - Identificação de clientes de alto risco.

### Principais Bibliotecas Utilizadas

- **pandas:** Manipulação e análise de dados.
- **matplotlib e seaborn:** Visualização de dados com gráficos.
- **numpy:** Suporte a operações numéricas.
- **sklearn:** Ferramentas para ajuste de dados e análise estatística.

### Como usar

1. Clone o repositório:

   ```sh
   git clone https://github.com/Guilherme006/EDA.git
   ```

2. Certifique-se de ter as bibliotecas instaladas.
3. Execute o notebook em seu ambiente local ou no Google Colab.
