# Análise do Dataset Netflix

## Visão Geral do Dataset
Este conjunto de dados contém informações sobre o catálogo de conteúdo da Netflix, incluindo filmes e séries de TV. Os dados fornecem informações detalhadas sobre títulos, gêneros, anos de lançamento, classificações e recomendações de conteúdo.

## Descrição dos Dados
O dataset inclui 6.404 registros com 8 colunas de informações sobre o conteúdo da Netflix.

### Descrição das Colunas

1. **N_id**: Identificador único para cada título
2. **Title**: Nome do filme ou série
3. **Main Genre**: Classificação do gênero principal
4. **Sub Genres**: Lista de gêneros adicionais e classificações regionais
5. **Release Year**: Ano de lançamento do conteúdo (variando de 1962 a 2013)
6. **Maturity Rating**: Classificação etária do conteúdo (ex: U/A 13+, A, U/A 16+)
7. **Original Audio**: Idiomas de áudio disponíveis, com indicação do idioma original
8. **Recommendations**: Lista de IDs de conteúdos relacionados recomendados

## Formato dos Dados
- Tipo de Arquivo: CSV (Valores Separados por Vírgula)
- Codificação: UTF-8
- Delimitador: Vírgula (,)

## Exemplo de Registro
```csv
N_id,Title,Main Genre,Sub Genres,Release Year,Maturity Rating,Original Audio,Recommendations
215309,Ace Ventura: Pet Detective,Comedy,"Comedy, Mystery, US",1994,A,"Hindi, English [Original]","70184054, 60001650, 70112729, 70027007, 1152469, 81222715, 21303955, 70021643, 60004471, 70044593, 17236928, 215318"