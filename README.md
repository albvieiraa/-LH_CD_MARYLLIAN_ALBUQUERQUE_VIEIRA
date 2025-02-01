# Previsão de Preço de Aluguel por Temporada

Este projeto utiliza técnicas de análise exploratória de dados (EDA) e modelagem preditiva para prever o preço de aluguel por temporada baseado em um conjunto de dados de aluguéis.
---
## Estrutura do Repositório
* README.md: Este arquivo explicativo.
* notebook/: Contém o Jupyter Notebook com as análises realizadas (EDA e modelagem).
* modelo/: Arquivo .pkl contendo o modelo treinado.
* requirements.txt: Arquivo contendo todas as dependências e versões necessárias para executar o projeto.
* dataset.csv: Arquivo csv com o dataset.

## Como Rodar o Projeto
### Requisitos
Antes de rodar o projeto, é necessário instalar os pacotes necessários. Utilize o arquivo `requirements.txt` para instalar as dependências:
1. Clone o repositório
```bash
  git clone https://github.com/albvieiraa/LH_CD_MARYLLIAN_ALBUQUERQUE_VIEIRA.git
  cd LH_CD_MARYLLIAN_ALBUQUERQUE_VIEIRA
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```
3. Carregue o arquivo CSV contendo os dados. Certifique-se de fazer o upload do arquivo para o Google Colab ou altere o caminho para o arquivo localmente.

4. Execute os notebooks presentes na pasta `notebooks/` para realizar a análise exploratória e predição.

5. O modelo treinado estará disponível na pasta `modelos/` como um arquivo `.pkl`.

## Executando no Google Colab
- Acesse o Google Colab (https://colab.research.google.com/).
- Faça o upload do arquivo CSV (`teste_indicium_precificacao.csv`) com os dados de aluguéis.
- Carregue os notebooks de `notebooks/` e execute as células conforme necessário.
