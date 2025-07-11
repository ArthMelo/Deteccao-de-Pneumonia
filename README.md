# Detecção de Pneumonia utilizando PCA e Regressão Logística

## 📌 Visão Geral
Este projeto de classificação utiliza técnicas de aprendizado de máquina para identificar pneumonia em imagens de raio-X do tórax. Combinando Análise de Componentes Principais (PCA) para redução de dimensionalidade e Regressão Logística para classificação, o modelo alcança 87% de acurácia na detecção de casos.

## 🔍 Principais Características
- **Pré-processamento avançado**: Redimensionamento, normalização e flattening de imagens
- **PCA otimizado**: Manutenção de 85% da variância com apenas 71 componentes
- **Avaliação robusta**: Métricas detalhadas (precisão, recall, F1-score) e validação cruzada
- **Visualização clara**: Gráficos de variância e matriz de confusão

## 📊 Resultados Principais
| Métrica       | Normal | Pneumonia |
|---------------|--------|-----------|
| Precisão      | 70%    | 95%       |
| Recall        | 85%    | 87%       |
| F1-score      | 77%    | 91%       |

## 🛠️ Tecnologias Utilizadas
- Python 3.9+
- Bibliotecas:
  - Scikit-learn (PCA, Regressão Logística)
  - OpenCV (processamento de imagens)
  - Matplotlib/Seaborn (visualização)


## 📝 Conclusões e Melhorias Futuras
O modelo demonstrou eficácia na detecção de pneumonia, porém com algumas oportunidades de melhoria:
- Balanceamento do dataset para melhorar precisão em casos normais
- Teste com redes neurais convolucionais (CNNs)
- Análise mais aprofundada dos falsos positivos/negativos

## 📚 Referências
- Kermany et al. (2018) - Identifying Medical Diagnoses by Image-Based Deep Learning
- Dataset Chest X-Ray Images (Pneumonia) - Kaggle

---

Desenvolvido por **Arthur de Melo Barbosa** como projeto final para a disciplina de Computação Científica e Análise de Dados na UFRJ.
