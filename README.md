# BTC Prediction


## Conteúdo
- [Descrição do Projeto](##Descrição-do-Projeto)
- [Funcionalidades](##Funcionalidades)
- [Tecnologias Utilizadas](##Tecnologias-Utilizadas)
- [Como Usar](#Como-usar)
- [Pré-requisitos](##Pré-requisitos)
- [Passos](##Passos)
- [Resultados](##Resultados)

## Descrição do Projeto

Este projeto utiliza redes neurais recorrentes do tipo LSTM (Long Short-Term Memory) para prever o preço de fechamento do Bitcoin (BTC-USD) com base em dados históricos obtidos do Yahoo Finance. Ele também implementa visualizações de médias móveis para análise temporal dos preços.

## Funcionalidades

Coleta automática de dados históricos do Bitcoin.
Visualização dos preços de fechamento e suas médias móveis (100 e 365 dias).
Construção e treinamento de um modelo LSTM para previsão de preços.
Predição de preços futuros para 10 dias.
Salvamento do modelo treinado para reutilização.

## Tecnologias Utilizadas

Linguagem: Python
Bibliotecas:
- yfinance (coleta de dados financeiros)
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- TensorFlow/Keras

# Como usar

## Pré-requisitos
Certifique-se de ter Python 3.8 ou superior instalado e as bibliotecas listadas acima. Para instalá-las, execute:

```bash
pip install yfinance numpy pandas matplotlib scikit-learn tensorflow
````

## Passos

1. Clones este repositório:
```bash
git clone (link)
```

2. Navegue até o diretório do projeto:
```bash
cd (projeto)
```

3. Execute o script:
```bash
python (arquivo)
```

## Resultados
- Gráficos interativos exibem os preços de fechamento e previsões futuras
- O modelo treinado será salvo no arquivo model.keras
