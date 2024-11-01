# Pasta `src/enc/`

Armazena modelos de transformação (encoders e scalers) usados para normalizar, escalonar e selecionar features. Esses arquivos `.sav` permitem reproduzir as mesmas transformações em novos dados, garantindo consistência entre treino e inferência.

## Arquivos:
- `minmax_with_outliers.sav`: MinMaxScaler ajustado ao conjunto de dados com outliers.
- `selection_model_with_outliers.sav`: Modelo de seleção de features ajustado ao conjunto com outliers.
- `normalized_with_outliers.sav`: StandardScaler ajustado ao conjunto de dados normalizado com outliers.
