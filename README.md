## 📌 Dataset (Fonte)

Os dados originais utilizados neste projeto estão disponíveis publicamente no **IEEE DataPort**:  
🔗 [A Large-Scale Dataset of 4G, NB-IoT, and 5G Non-Standalone Network Measurements](https://ieee-dataport.org/documents/large-scale-dataset-4g-nb-iot-and-5g-non-standalone-network-measurements)

---

## 📁 Arquivos principais

- **Pré-processamento dos dados (DataFrame final)**  
  🔗 [processed_df.parquet](https://github.com/arthurvale/TCC-2026/blob/main/processed_df.parquet)  
  Arquivo resultante do tratamento e padronização da campanha **“5G – Passive Measurements”**, após análise exploratória.

- **Análise Exploratória (EDA)**  
  🔗 [Análise_Exploratória.ipynb](https://github.com/arthurvale/TCC-2026/blob/main/An%C3%A1lise_Explorat%C3%B3ria.ipynb)  
  Notebook que documenta o processo de limpeza, transformação e exploração dos dados.

- **Modelagem e Machine Learning**  
  🔗 [predicao_velocidade_v2.ipynb](https://github.com/arthurvale/TCC-2026/blob/main/predicao_velocidade_v2.ipynb)  
  Notebook responsável pelo treinamento e avaliação dos modelos de Machine Learning utilizando o dataset pré-processado.

---

## 🚀 Fluxo de execução recomendado

1. Acesse o dataset original via [IEEE DataPort](https://ieee-dataport.org/documents/large-scale-dataset-4g-nb-iot-and-5g-non-standalone-network-measurements).  
2. Consulte o notebook de análise exploratória: [Análise_Exploratória.ipynb](https://github.com/arthurvale/TCC-2026/blob/main/An%C3%A1lise_Explorat%C3%B3ria.ipynb).  
3. Utilize o arquivo final pré-processado: [processed_df.parquet](https://github.com/arthurvale/TCC-2026/blob/main/processed_df.parquet).  
4. Execute os modelos no notebook: [predicao_velocidade_v2.ipynb](https://github.com/arthurvale/TCC-2026/blob/main/predicao_velocidade_v2.ipynb).

---

## ⚠️ Ambiente de desenvolvimento

Este projeto foi desenvolvido e executado originalmente no **Google Colab**.  
Caso seja necessário rodá-lo localmente, pode ser preciso ajustar os caminhos de leitura dos arquivos (substituindo referências ao Google Drive por caminhos do seu computador).

As bibliotecas utilizadas no ambiente do Colab estão listadas no arquivo: **[requirements_local.txt]([requirements_colab.txt](https://github.com/arthurvale/TCC-2026/blob/main/requirements_local.txt))**.
