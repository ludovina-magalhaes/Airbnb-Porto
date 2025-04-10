# Airbnb Porto: Análise Exploratória e Insights

[![Licença](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Este repositório contém um projeto de análise exploratória de dados (EDA) sobre anúncios do Airbnb na cidade do Porto. O objetivo principal é fornecer insights valiosos sobre o mercado de alojamento local na região, identificando padrões, tendências e oportunidades.

## Descrição do Projeto

O projeto é desenvolvido em Python, utilizando a biblioteca Pandas para manipulação e análise de dados, e outras bibliotecas como Matplotlib e Seaborn para visualização. A análise é realizada a partir de um *dataset* do Airbnb, explorando diversas variáveis como preços, tipos de propriedade, localização, avaliações e número de hóspedes.

Este projeto procura responder a questões como:

*   Qual a distribuição dos preços dos alojamentos no Porto?
*   Quais os bairros com maior concentração de anúncios?
*   Existe alguma correlação entre o preço e o número de avaliações?
*   Quais os tipos de propriedade mais comuns e os seus preços médios?
*   Qual a influência da localização no preço do alojamento?

## Conteúdo do Repositório

*   **`Airbnb-Porto.ipynb`**: *Notebook* Jupyter com o código da análise exploratória de dados. Este ficheiro contém os passos de limpeza, tratamento e visualização dos dados, bem como as conclusões e insights obtidos.
*   **`README.md`**: Este ficheiro, que fornece uma descrição geral do projeto e instruções para a sua utilização.

## Tecnologias Utilizadas

*   **Python**: Linguagem de programação utilizada para a análise de dados.
*   **Pandas**: Biblioteca para manipulação e análise de dados tabulares.
*   **Matplotlib**: Biblioteca para criação de visualizações estáticas, interativas e animadas em Python.
*   **Seaborn**: Biblioteca para criação de visualizações estatísticas informativas e atraentes, baseada em Matplotlib.
*   **Jupyter Notebook**: Ambiente interativo para desenvolvimento e documentação do projeto.

## Como Utilizar

1.  **Clonar o Repositório:**

    ```bash
    git clone https://github.com/ludovina-magalhaes/Airbnb-Porto.git
    cd Airbnb-Porto
    ```

2.  **Criar e Ativar um Ambiente Virtual (Recomendado):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # Para Linux/macOS
    venv\Scripts\activate  # Para Windows
    ```

3.  **Instalar as Dependências:**

    ```bash
    pip install -r requirements.txt
    ```

    Se não tiver um `requirements.txt`, instale individualmente:

    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```

4.  **Executar o *Notebook*:**

    Abra o ficheiro `Airbnb-Porto.ipynb` no Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

    Ou utilize o Jupyter Lab:

    ```bash
    jupyter lab
    ```

    Execute as células do *notebook* sequencialmente para reproduzir a análise.


## Licença

Este projeto está licenciado sob a licença MIT - consulte o ficheiro [LICENSE](LICENSE) para mais detalhes.


