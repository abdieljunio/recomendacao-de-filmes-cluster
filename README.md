# 🎬 Sistema de Recomendação de Filmes com K-Means Clustering

Este projeto implementa um sistema de recomendação de filmes utilizando técnicas de **Aprendizado de Máquina Não Supervisionado**. O objetivo é agrupar usuários com gostos similares (clusters) e recomendar filmes com base nas preferências coletivas desses grupos.

O projeto foi desenvolvido em **Python** utilizando **Jupyter Notebook** e segue o ciclo de vida clássico de Data Mining abordado no curso de Inteligência Artificial.

---

## 🧠 Conceitos e Tecnologias Aplicadas

* **Linguagem:** Python 3.x
* **Bibliotecas:** * `pandas` (Manipulação de dados)
  * `scikit-learn` (Algoritmos de ML e Pré-processamento)
  * `matplotlib` & `seaborn` (Visualização de dados)
* **Técnica de IA:** Aprendizado Não Supervisionado (Unsupervised Learning).
* **Algoritmo Principal:** K-Means Clustering.
* **Técnicas de Apoio:** * Padronização (StandardScaler)
  * Redução de Dimensionalidade (PCA) para visualização.

---

## 📂 Sobre o Dataset

O projeto utiliza o famoso dataset **MovieLens 100k**, mantido pelo GroupLens Research.

* **Total de Avaliações:** 100.000
* **Total de Usuários:** 943
* **Total de Filmes:** 1.682
* **Arquivos utilizados:**
    * `u.data`: Contém as notas (1-5) dadas pelos usuários.
    * `u.item`: Contém os títulos dos filmes e seus respectivos gêneros.

> **⚠️ Importante:** Certifique-se de que a pasta `ml-100k` contendo esses arquivos esteja descompactada no mesmo diretório do notebook.

---

## 🚀 Como Executar o Projeto

### 1. Pré-requisitos
Certifique-se de ter o Python e o Jupyter instalados (via Anaconda é recomendado). Instale as dependências:

```bash
pip install pandas scikit-learn matplotlib seaborn
```
### 2. Configuração

Organize suas pastas da seguinte maneira:
```
/SeuProjeto/
    |
    +--- Sistema_Recomendacao.ipynb  (O arquivo do notebook)
    |
    +--- ml-100k/                    (A pasta do dataset)
          |
          +--- u.data
          +--- u.item
          +--- ...
```

### 3. Execução

    * Abra o AnacondaNavigator e depois abra o JupyterNotebook.

    * Navegue até a pasta do projeto.
    
    * Abra o arquivo do projeto e execute todas as células sequencialmente (Cell -> Run All).
