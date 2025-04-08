# Airbnb-Porto
# Data Analytic Airbnb Porto: Análise de Preços e Fatores Influenciadores

Este projeto visa analisar os preços de anúncios do Airbnb na cidade do Porto, Portugal, e identificar os principais fatores que influenciam esses preços. O objetivo é fornecer insights valiosos para anfitriões, hóspedes e outros interessados no mercado de arrendamento de curta duração.

## Descrição

Através da análise exploratória de dados (EDA) e modelagem preditiva, este projeto procura responder a perguntas como:

*   Qual o impacto da localização (bairro) no preço do Airbnb?
*   Qual a influência do tipo de quarto (apartamento inteiro, quarto privado, etc.) no preço?
*   Quais outras características (ex: número de reviews, disponibilidade) afetam o preço?
*   É possível prever o preço de um anúncio com base nas suas características?

##  Tecnologias Utilizadas

*   **Linguagem de Programação:** Python
*   **Bibliotecas:**
    *   Pandas: Manipulação e análise de dados.
    *   NumPy: Computação numérica.
    *   Matplotlib: Criação de gráficos e visualizações.
    *   Seaborn: Criação de gráficos estatísticos.
    *   Scikit-learn: Modelagem preditiva e machine learning.



## Como Executar o Projeto

1.  **Clonar o repositório:**

    ```bash
    git clone [link para o repositório]
    cd Data-Analytic-Airbnb-Porto
    ```

2.  **Criar um ambiente virtual (opcional, mas recomendado):**

    ```bash
    python3 -m venv .venv
    source .venv/bin/activate  # No Linux/macOS
    .venv\Scripts\activate  # No Windows
    ```

3.  **Instalar as dependências:**

    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

4.  **Abrir e executar o notebook Jupyter:**

    ```bash
    jupyter notebook Airbnb-Porto.ipynb
    ```

## Resultados e Insights

*   **Distribuição de Preços:** A maioria dos Airbnbs no Porto tem preços entre X e Y euros por noite, com alguns outliers de preços mais elevados.
*   **Tipos de Quarto:** Os apartamentos inteiros (`Entire home/apt`) tendem a ser mais caros do que os quartos privados (`Private room`) e os quartos partilhados (`Shared room`).
*   **Localização:** Bairros como [Lista dos bairros mais caros] têm os preços médios mais elevados.
*   **Modelagem Preditiva:** Um modelo de regressão linear conseguiu prever o preço com uma precisão de X% (R² = X).

**Nota:** Estes são apenas exemplos. Os resultados e insights específicos dependerão dos dados e dos modelos utilizados.

## Melhorias Futuras

*   **Exploração de Dados Adicionais:** Incluir dados externos (ex: clima, eventos) para enriquecer a análise.
*   **Modelagem Mais Avançada:** Experimentar modelos de machine learning mais complexos, como Random Forest ou Gradient Boosting.
*   **Feature Engineering:** Criar novas features (ex: distância a pontos de interesse) que possam melhorar a precisão do modelo.
*   **Visualização Interativa:** Criar visualizações interativas para facilitar a exploração dos dados.
*   **Deploy do Modelo:** Implementar o modelo como uma API para prever os preços dos Airbnbs em tempo real.

## Contribuições

Contribuições são bem-vindas! Se quiseres contribuir para este projeto, podes:

*   Criar um fork do repositório.
*   Implementar as tuas alterações.
*   Enviar um pull request.

##  Licença

Este projeto está licenciado sob a licença [Nome da Licença] - vê o ficheiro `LICENSE` para mais detalhes.

