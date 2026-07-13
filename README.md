
# 🩻 Tech Challenge – Fase 1 (Extra) | Classificação de Radiografias Torácicas com Deep Learning

> Projeto EXTRA desenvolvido para o Tech Challenge da Pós-Graduação em Inteligência Artificial da FIAP, aplicando Redes Neurais Convolucionais (CNN) e Visão Computacional para classificação de radiografias torácicas em pacientes com ou sem pneumonia.

---

## 📖 Sobre o Projeto

Este projeto complementa o desafio principal da Fase 1 do Tech Challenge da FIAP, demonstrando a aplicação de Deep Learning em imagens médicas.

O objetivo é construir uma Rede Neural Convolucional (CNN) capaz de classificar radiografias torácicas em duas categorias:

- NORMAL
- PNEUMONIA

Durante o desenvolvimento foram aplicadas técnicas de exploração dos dados, pré-processamento, treinamento de modelos, avaliação e interpretação crítica dos resultados.

---

## 🎯 Objetivos

- Explorar um conjunto de radiografias torácicas;
- Avaliar a qualidade das imagens;
- Identificar duplicidades e inconsistências;
- Construir um pipeline utilizando TensorFlow;
- Aplicar técnicas de Data Augmentation;
- Treinar uma CNN para classificação binária;
- Avaliar o modelo utilizando métricas adequadas ao contexto clínico;
- Discutir limitações e possibilidades de evolução.

---

## 🩻 Dataset

Foi utilizado o **Chest X-Ray Images (Pneumonia)**, disponibilizado publicamente no Kaggle.

Dataset:

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

Classes:

- NORMAL
- PNEUMONIA

---

## 🔬 Etapas Desenvolvidas

O notebook contempla:

- Exploração do dataset;
- Análise da distribuição das classes;
- Verificação das dimensões das imagens;
- Identificação de imagens corrompidas;
- Identificação de duplicidades;
- Limpeza dos dados;
- Divisão em treino, validação e teste;
- Pipeline TensorFlow;
- Data Augmentation;
- Balanceamento utilizando Class Weight;
- Construção de CNN Baseline;
- Treinamento;
- Avaliação no conjunto de validação;
- Avaliação final no conjunto de teste;
- Matriz de Confusão;
- Curva ROC;
- Curva Precision-Recall;
- Discussão crítica;
- Limitações;
- Trabalhos futuros.

---

## 🛠 Tecnologias

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Google Colab

---

## 📁 Estrutura

```
fiap-pos-ia-tech-challenge-fase-1-extra-visao-computacional/

├── 02_Extra_Visao_Computacional.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Executar

1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/fiap-pos-ia-tech-challenge-fase-1-extra-visao-computacional.git
```

2. Instale as dependências

```bash
pip install -r requirements.txt
```

3. Abra o notebook

```
02_Extra_Visao_Computacional.ipynb
```

ou execute diretamente no Google Colab.

---

## 📒 Notebook no Google Colab

https://colab.research.google.com/drive/1whUVoabNR4grBizmEWDSz8lFHKT-cnPs?usp=sharing

---

## ⚠️ Limitações

Este projeto possui algumas limitações:

- dataset público;
- tamanho limitado da base;
- possível viés da população utilizada;
- ausência de validação em bases externas;
- o modelo não deve ser utilizado para diagnóstico clínico sem validação adicional.

---

## 🚀 Trabalhos Futuros

Como evolução do projeto podem ser implementadas:

- Transfer Learning (DenseNet121, EfficientNetB0);
- Fine-Tuning;
- Grad-CAM para interpretabilidade;
- SHAP para explicabilidade;
- Validação multicêntrica;
- Deploy da solução.

---

## 👩‍💻 Autora

**Natalia da Costa Silva**

Projeto EXTRA desenvolvido como complemento ao Tech Challenge – Fase 1 da Pós-Graduação em Inteligência Artificial da FIAP.
