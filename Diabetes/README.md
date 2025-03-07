# Dataset de Diabetes

Este repositório contém um conjunto de dados abrangente relacionado ao diagnóstico de diabetes e seus fatores de risco, com 9.538 registros médicos.

## Descrição

O dataset inclui diversos parâmetros de saúde, hábitos de estilo de vida e predisposições genéticas que contribuem para o risco de diabetes. Os dados são estruturados com distribuições realistas, tornando-os valiosos para pesquisa médica, análise estatística e aplicações de aprendizado de máquina.

## Estrutura do Dataset

O arquivo `diabetes.csv` contém as seguintes variáveis:

| Variável | Descrição | Unidade/Valores |
|----------|-----------|----------------|
| Idade | Idade do indivíduo | 18-90 anos |
| Gestações | Número de gestações | Número inteiro |
| IMC | Índice de Massa Corporal | kg/m² |
| Glicose | Concentração de glicose no sangue | mg/dL |
| Pressão arterial | Pressão arterial sistólica | mmHg |
| HbA1c | Nível de hemoglobina A1c | % |
| LDL | Lipoproteína de Baixa Densidade (colesterol "ruim") | mg/dL |
| HDL | Lipoproteína de Alta Densidade (colesterol "bom") | mg/dL |
| Triglicerídeos | Níveis de gordura no sangue | mg/dL |
| Circunferência da Cintura | Medida da cintura | cm |
| Circunferência do quadril | Medida do quadril | cm |
| RCQ | Relação Cintura-Quadril | Razão |
| Histórico familiar | Presença de histórico familiar de diabetes | 1 = Sim, 0 = Não |
| DietType | Hábitos alimentares | 0 = Desequilibrado, 1 = Equilibrado, 2 = Vegano/Vegetariano |
| Hipertensão | Presença de pressão arterial elevada | 1 = Sim, 0 = Não |
| MedicationUse | Uso de medicamentos | 1 = Sim, 0 = Não |
| Resultado | Diagnóstico de diabetes | 1 = Diabetes, 0 = Sem Diabetes |

## Aplicações

Este conjunto de dados pode ser utilizado para:
- Pesquisa médica e epidemiológica
- Desenvolvimento de modelos preditivos
- Análise de fatores de risco para diabetes
- Estudos sobre a relação entre estilo de vida e diabetes
- Avaliação da influência de fatores genéticos no desenvolvimento da doença

## Características do Dataset

- **Número de registros:** 9.538
- **Número de variáveis:** 17
- **Variável alvo:** Resultado (diagnóstico de diabetes)
- **Tipo de problema:** Classificação binária

## Observações

Os dados fornecidos apresentam distribuições realistas e podem ser utilizados para:
- Explorar relações entre escolhas de estilo de vida e risco de diabetes
- Analisar a influência de fatores genéticos
- Desenvolver modelos de previsão de risco
- Estudar a correlação entre diferentes indicadores de saúde