# Dataset de Saúde

## Visão Geral
Este conjunto de dados sintético de saúde foi criado para servir como um recurso valioso para entusiastas de ciência de dados, praticantes de machine learning e analistas de dados. Foi projetado para simular dados reais de saúde, permitindo que os usuários pratiquem, desenvolvam e demonstrem suas habilidades de manipulação e análise de dados no contexto do setor de saúde.

## Inspiração
A inspiração por trás deste conjunto de dados está enraizada na necessidade de dados práticos e diversos da área de saúde para fins educacionais e de pesquisa. Os dados de saúde são frequentemente sensíveis e sujeitos a regulamentações de privacidade, tornando o acesso difícil para aprendizado e experimentação. Para preencher essa lacuna, a biblioteca Python Faker foi utilizada para gerar um conjunto de dados que reflete a estrutura e atributos comumente encontrados em registros de saúde. Ao fornecer esses dados sintéticos, o objetivo é promover inovação, aprendizado e compartilhamento de conhecimento no domínio da análise de dados em saúde.

## Informações do Dataset
Cada coluna fornece informações específicas sobre o paciente, sua admissão e os serviços de saúde prestados. Aqui está uma explicação detalhada de cada coluna no conjunto de dados:

- **Nome**: Nome do paciente associado ao registro de saúde
- **Idade**: Idade do paciente no momento da admissão, expressa em anos
- **Gênero**: Gênero do paciente, "Masculino" ou "Feminino"
- **Tipo sanguíneo**: Tipo sanguíneo do paciente (ex: "A+", "O-", etc.)
- **Condição médica**: Condição médica primária ou diagnóstico (ex: Diabetes, Hipertensão, Asma)
- **Data de admissão**: Data em que o paciente foi admitido na unidade de saúde
- **Médico**: Nome do médico responsável pelo cuidado do paciente durante a admissão
- **Hospital**: Unidade de saúde ou hospital onde o paciente foi admitido
- **Provedor de seguro**: Provedor de seguro do paciente (Aetna, Blue Cross, Cigna, UnitedHealthcare, Medicare)
- **Valor de Faturamento**: Valor cobrado pelos serviços de saúde durante a admissão (número decimal)
- **Número do quarto**: Número do quarto onde o paciente foi acomodado
- **Tipo de admissão**: Tipo de admissão (Emergência, Eletiva ou Urgente)
- **Data de alta**: Data em que o paciente recebeu alta
- **Medicação**: Medicação prescrita ou administrada durante a admissão (ex: Aspirina, Ibuprofeno, Penicilina)
- **Resultados do teste**: Resultados dos exames médicos (Normal, Anormal ou Inconclusivo)

## Cenários de Uso
Este conjunto de dados pode ser utilizado para uma ampla gama de propósitos, incluindo:

1. **Modelagem Preditiva em Saúde**
   - Desenvolvimento e teste de modelos preditivos de saúde
   - Construção de modelos de classificação para previsão de resultados de testes

2. **Prática de Análise de Dados**
   - Técnicas de limpeza e transformação de dados
   - Análise exploratória de dados
   - Reconhecimento de padrões em dados de saúde

3. **Visualização de Dados**
   - Criação de visualizações informativas de tendências em saúde
   - Construção de painéis interativos

4. **Propósitos Educacionais**
   - Ensino de conceitos de ciência de dados no contexto da saúde
   - Prática de algoritmos de machine learning
   - Problemas de classificação multiclasse (usando resultados de testes com 3 categorias)

## Tarefa de Classificação
Uma aplicação específica deste conjunto de dados é tratá-lo como um problema de classificação multiclasse, onde o objetivo é prever os resultados dos testes (Normal, Anormal, Inconclusivo) com base em outros atributos do paciente e informações médicas.

## Observação
Este é um conjunto de dados sintético gerado usando a biblioteca Faker do Python. Embora simule estruturas de dados reais de saúde, não contém informações reais de pacientes e destina-se exclusivamente a fins educacionais e de prática.