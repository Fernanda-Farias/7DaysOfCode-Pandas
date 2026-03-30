# 🐍📊 7 Days of Code: Python & Pandas

## Sobre o desafio
O **#7DaysOfCode** é uma iniciativa da Alura que propõe um desafio prático por dia, durante 7 dias consecutivos.  
O objetivo é desenvolver habilidades reais de programação resolvendo problemas concretos, sem teoria em excesso, apenas prática.

Nesta edição, o foco é **Python com Pandas**, uma das combinações mais utilizadas no dia a dia de quem trabalha com análise e ciência de dados.

---

## Sobre este projeto
Este notebook foi desenvolvido por **Fernanda Farias**, Analista e Cientista de Dados.  

🔗 [Clique aqui para se conectar comigo no LinkedIn](https://www.linkedin.com/in/fernanda-fariasz/)

---

## Dia 1: Importando e preparando os dados

[Acessar notebook do Dia 1](https://github.com/Fernanda-Farias/7DaysOfCode-Pandas/blob/main/Dia_01_Importação_de_Dados_7DaysOfCode.ipynb)

O primeiro dia do desafio trabalha uma etapa fundamental em qualquer projeto de dados: entender, importar e preparar os dados antes de qualquer análise.

Os dados utilizados são referentes aos empréstimos e ao acervo das bibliotecas da UFRN (Universidade Federal do Rio Grande do Norte), e o desafio propõe trabalhar apenas com os últimos 10 anos disponíveis.

---

## O que foi feito nessa etapa

### 1. Importação dos dados
Os dados de empréstimos estavam distribuídos em múltiplos arquivos CSV em um repositório público no GitHub.  
Para evitar downloads manuais, os arquivos foram importados diretamente via API do GitHub.  

Já os dados do acervo estavam disponíveis em um único arquivo `.parquet`, importado diretamente pelo link bruto do repositório.

---

### 2. Unificação dos DataFrames
Como os empréstimos estavam fragmentados em vários arquivos (um por período), o primeiro passo foi consolidar todos em um único DataFrame, facilitando a manipulação e análise dos dados de forma centralizada.

---

### 3. Limpeza dos dados
Dados do mundo real raramente chegam perfeitos.  
Por isso, foram identificadas e tratadas:
- linhas duplicadas  
- linhas completamente nulas  

Garantindo a integridade dos dados antes de qualquer análise.

---

### 4. Merge entre as tabelas
Para enriquecer os dados de empréstimos com informações do acervo (como a biblioteca de origem do material e o tema ao qual ele pertence), as duas tabelas foram mescladas através da coluna de **código de barras**, que é a chave de relacionamento entre elas.


