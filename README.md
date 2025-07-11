# Detecção de Pneumonia utilizando PCA e Regressão Logística

## 📌 Visão Geral
Este projeto de classificação utiliza técnicas de aprendizado de máquina para identificar pneumonia em imagens de raio-X do tórax. Combinando Análise de Componentes Principais (PCA) para redução de dimensionalidade e Regressão Logística para classificação, o modelo alcança 87% de acurácia na detecção de casos.


## 🔍 Sobre o Projeto

O objetivo deste trabalho é desenvolver um sistema eficiente capaz de classificar imagens médicas em duas categorias: "normal" ou "pneumonia". Para isso, aplicamos:

- **Pré-processamento** das imagens (conversão para escala de cinza, redimensionamento e achatamento).
- **Normalização** dos dados para garantir que cada variável tenha média zero e desvio padrão um.
- **Redução de dimensionalidade com PCA**, mantendo 85% da variância original, o que corresponde a 71 componentes principais.
- **Classificação com Regressão Logística**, treinada para distinguir entre casos normais e pneumônicos.
- **Visualização clara**: Gráficos de variância e matriz de confusão


## 📊 Resultados Principais
| Métrica       | Normal | Pneumonia |
|---------------|--------|-----------|
| Precisão      | 70%    | 95%       |
| Recall        | 85%    | 87%       |
| F1-score      | 77%    | 91%       |



## 🛠️ Tecnologias e Bibliotecas

O projeto foi implementado em Python e utilizou as seguintes bibliotecas:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `opencv-python` (cv2)
- `seaborn`



## 📝 Conclusões e Melhorias Futuras
O modelo demonstrou eficácia na detecção de pneumonia, porém com algumas oportunidades de melhoria:
- Balanceamento do dataset para melhorar precisão em casos normais
- Teste com redes neurais convolucionais (CNNs)
- Análise mais aprofundada dos falsos positivos/negativos



## 📚 Dataset

O conjunto de dados utilizado foi obtido no Kaggle e contém 5.863 imagens de raio-X divididas em treino, teste e validação, com subpastas para as classes "normal" e "pneumonia".  
Link para o dataset:  
[Chest X-Ray Images (Pneumonia) - Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/data)

---

Desenvolvido por **Arthur de Melo Barbosa** como projeto final para a disciplina de Computação Científica e Análise de Dados na UFRJ.
