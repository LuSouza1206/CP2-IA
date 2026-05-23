# CP2 — Análise do MNIST com Redes Neurais MLP

Atividade prática de Inteligência Artificial explorando o impacto de diferentes hiperparâmetros em MLPs aplicadas ao dataset MNIST.

## Integrantes 
- Kaio Vinicius Meireles Alves - RM553282
- Lucas Alves de Souza -  RM553956

## Conteúdo

| Arquivo | Descrição |
|---|---|
| `cp-ia.ipynb` | Notebook com código, experimentos e análise |

## Experimentos realizados

- **Implementação base** — MLP baseline com avaliação inicial
- **Variação de arquitetura** — 1 a 3 camadas ocultas × 64 a 512 neurônios
- **Hiperparâmetros de treinamento** — Learning rate (0.1 / 0.01 / 0.001) e batch size (32 / 64 / 128 / 256)
- **Regularização** — Dropout e L2 (weight decay), individualmente e combinados
- **Avaliação** — Matriz de confusão, análise de erros, acurácia treino vs teste
- **Análise crítica** — Discussão sobre overfitting, saturação de complexidade e configuração ótima

## Stack

- Python 3.10+
- PyTorch
- scikit-learn
- seaborn / matplotlib

## Como executar

Abra o notebook no Google Colab ou Jupyter e execute as células em ordem. O dataset MNIST é baixado automaticamente via `torchvision`.
