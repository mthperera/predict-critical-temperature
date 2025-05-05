# 🔬 Superconductors Regression Project

Este projeto explora técnicas de **regressão preditiva** aplicadas à previsão da **temperatura crítica (`critical_temp`)** de supercondutores, utilizando algoritmos de aprendizado de máquina.

---

## 📂 Sobre o Projeto

O objetivo principal é desenvolver modelos capazes de prever a temperatura crítica de materiais supercondutores com base em suas propriedades físico-químicas.  
Para isso, são aplicados e comparados diversos algoritmos de regressão, avaliando seu desempenho por meio de métricas como RMSE e R².

---

## 📊 Dataset

Utiliza-se o [Superconductivity Data Set](https://archive.ics.uci.edu/dataset/464/superconductivty+data), disponibilizado pelo **UCI Machine Learning Repository**.  
O conjunto de dados contém informações sobre 21.263 supercondutores, com 81 características extraídas de suas fórmulas químicas e a temperatura crítica correspondente.

**⚠️ Importante:** Os dados não estão incluídos neste repositório.  
Para utilizá-los, baixe diretamente do repositório oficial:

🔗 [Download direto](https://archive.ics.uci.edu/ml/machine-learning-databases/00464/)

**📄 Uso permitido somente para fins educacionais e de pesquisa.**

**Por favor, cite o artigo original ao utilizar este dataset:**

> Hamidieh, Kam (2018).  
> *A data-driven statistical model for predicting the critical temperature of a superconductor*.  
> Computational Materials Science, 154, 346–354.  
> DOI: [10.1016/j.commatsci.2018.07.019](https://doi.org/10.1016/j.commatsci.2018.07.019)

---

## 🧪 Teoria

Para compreender os conceitos físicos por trás do projeto, consulte o arquivo [teoria_supercondutividade.md](teoria_supercondutividade.md), que aborda os fundamentos da supercondutividade e sua relação com as propriedades dos materiais.

---

## 🛠️ Tecnologias Utilizadas

- Python 3.12+
- Bibliotecas de análise de dados: pandas, numpy
- Visualização de dados: matplotlib, seaborn
- Modelagem e aprendizado de máquina:
   * scikit-learn (regressão, métricas, seleção de features)
   * PyTorch (implementação de redes neurais personalizadas)
- Persistência de dados intermediários: pickle

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/mthperera/predict-critical-temperature.git
   cd predict-critical-temperature
   ```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Baixe o dataset conforme instruções acima e coloque os arquivos `train.csv` e `unique_m.csv` na pasta `data/`.

5. Execute os notebooks ou scripts conforme necessário para treinar e avaliar os modelos.

---

## 📈 Resultados Esperados

Espera-se, idealmente, que os modelos desenvolvidos sejam capazes de prever com boa acurácia a temperatura crítica de novos materiais, contribuindo com insights para a descoberta de novos supercondutores.

---

## 📄 Licença

Este repositório de código está licenciado sob os termos da [MIT License](LICENSE).
