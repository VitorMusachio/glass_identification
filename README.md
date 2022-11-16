# Glass Identification

Para este experimento, será utilizado o dataset Glass Identification originado do Serviço de Ciência Forense dos Estados Unidos. O dataset possui 214 instâncias contendo exemplos de análise química de 7 tipos diferentes de vidro. O problema consiste em prever o tipo de vidro baseado em análise química. O estudo de classificação de tipos de vidro foi motivado pela investigação criminalística. Para mais detalhes sobre o dataset, consulte [este link](https://archive.ics.uci.edu/ml/datasets/glass+identification).

## Informações sobre os atributos

| Atributo | Descrição |
| -------- | --------- |
| Id number | 1 to 214 |
| RI |  Índice de refração |
| Na |  Sódio (unidade de medida: porcentagem em peso do óxido correspondente) |
| Mg |  Magnésio (unidade de medida: porcentagem em peso do óxido correspondente) |
| Al |  Alumínio (unidade de medida: porcentagem em peso do óxido correspondente) |
| Si |  Silício (unidade de medida: porcentagem em peso do óxido correspondente) |
| K |  Potássio (unidade de medida: porcentagem em peso do óxido correspondente) |
| Ca |  Cálcio (unidade de medida: porcentagem em peso do óxido correspondente) |
| Ba |  Bário (unidade de medida: porcentagem em peso do óxido correspondente) |
| Fe |  Ferro (unidade de medida: porcentagem em peso do óxido correspondente) |
| Type of glass | classe: 1-building_windows_float_processed; 2-building_windows_non_float_processed; 3-vehicle_windows_float_processed; 4-vehicle_windows_non_float_processed (nenhum neste dataset); 5-containers; 6-tableware; 7-headlamps |

Fontes de dados: para este experimento será utilizado o dataset Glass Identification originado do Serviço de Ciência Forense dos Estados Unidos. O dataset está disponível no UCI Machine Learning Repository. Para mais detalhes, consulte: https://archive.ics.uci.edu/ml/datasets/glass+identification.

Coleta dos dados: dados coletados diretamente do UCI Machine Learning Repository.

Dinâmica de criação/atualização do modelo: o modelo não será atualizado com novos dados.

Dinâmica de execução do modelo: o modelo será executado uma única vez.

Avaliação offline do modelo: utilização de base de testes para validar o modelo em dados não vistos durante o treinamento (hold-out).

Monitoramento online do modelo: não aplicável.

Qualidade dos dados: espera-se que os dados estejam balanceados entre as diferentes classes de vidro. Hold-out: 80% treino e 20% teste. Validação cruzada estratificada: 10-fold.

Fairness: não aplicável.

Explicabilidade: deseja-se um balanceamento entre acurácia e explicabilidade.

Confiabilidade: acurácia > 70%.

Desempenho: tempo de inferência < 5 minutos.
