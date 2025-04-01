
# Projeto de Análise de Risco de Crédito

Este projeto tem como objetivo construir um modelo de Machine Learning para analisar o risco de crédito, ou seja, prever a probabilidade de um cliente de uma instituição financeira pagar ou não o seu empréstimo com base em variáveis históricas.

## Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Para manipulação de dados
- **NumPy** - Para operações matemáticas
- **Scikit-learn** - Para construção e avaliação do modelo
- **Matplotlib/Seaborn** - Para visualizações gráficas
- **Jupyter Notebooks** - Para análise interativa e desenvolvimento

## Estrutura do Projeto

```
.
├── data/
│   └── credit_data.csv         # Arquivo com dados de crédito
├── notebooks/
│   └── risco_credito.ipynb     # Jupyter notebook com o código de análise e modelo
├── src/
│   ├── data_preprocessing.py   # Funções para pré-processamento dos dados
│   ├── feature_engineering.py  # Funções para engenharia de características
│   └── model.py               # Código para construção e avaliação do modelo
└── README.md                   # Este arquivo
```

## Como Rodar o Projeto

1. **Clonar o repositório:**

   ```bash
   git clone [https://github.com/seu-usuario/projeto-analise-risco-credito.git
   cd projeto-analise-risco-credito](https://github.com/ElieserAmr/Analise-risco-credito.git)
   ```

2. **Instalar as dependências:**

   Recomendado usar um ambiente virtual (como `venv` ou `conda`):

   ```bash
   pip install -r requirements.txt
   ```

   Se você não tiver o arquivo `requirements.txt`, você pode instalar as bibliotecas manualmente:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. **Executar o Jupyter Notebook:**

   Para explorar o modelo de risco de crédito, inicie o Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/risco_credito.ipynb
   ```

4. **Pré-processamento e Modelagem:**

   Dentro do Jupyter Notebook, você encontrará um fluxo de trabalho que cobre:

   - Carregamento e limpeza de dados
   - Análise exploratória
   - Pré-processamento de variáveis
   - Treinamento de modelos (como regressão logística, árvores de decisão ou outros)
   - Avaliação do modelo usando métricas como acurácia, precisão, recall e F1-score

## Como Contribuir

1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b feature/novafeature`)
3. Faça commit das suas alterações (`git commit -am 'Add new feature'`)
4. Envie para o repositório remoto (`git push origin feature/novafeature`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Dados

Os dados utilizados neste projeto podem ser encontrados neste [link do Kaggle](https://www.kaggle.com/datasets/laotse/credit-risk-dataset).

---


