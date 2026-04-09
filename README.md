# 🐍📊 7 Days of Code: Python & Pandas

## Sobre o desafio

O **#7DaysOfCode** é uma iniciativa da Alura que propõe um desafio prático por dia, durante 7 dias consecutivos. O objetivo é desenvolver habilidades reais de programação resolvendo problemas concretos, sem teoria em excesso, apenas prática. Nesta edição, o foco é **Python com Pandas**, uma das combinações mais utilizadas no dia a dia de quem trabalha com análise e ciência de dados.

---

## Sobre este projeto

Este projeto foi desenvolvido por **Fernanda Farias**, Analista e Cientista de Dados.
🔗 [Clique aqui para se conectar comigo no LinkedIn](https://www.linkedin.com/in/fernanda-fariasz/)

---

## Dias do desafio

### 📁 Dia 1: Importando e preparando os dados
[Acessar notebook](https://github.com/Fernanda-Farias/7DaysOfCode-Pandas/blob/main/Dia_01_Importa%C3%A7%C3%A3o_de_Dados_7DaysOfCode.ipynb)

Etapa de coleta e organização dos dados de empréstimos e acervo das bibliotecas da UFRN.

| Etapa | Descrição |
|-------|-----------|
| Importação | CSVs carregados via API do GitHub + arquivo `.parquet` pelo link bruto |
| Unificação | Múltiplos arquivos consolidados em um único DataFrame |
| Limpeza | Remoção de duplicatas e linhas completamente nulas |
| Merge | Tabelas unidas pela coluna de código de barras |

---

### 📁 Dia 2: Limpeza e manipulação dos dados
[Acessar notebook](https://github.com/Fernanda-Farias/7DaysOfCode-Pandas/blob/main/Dia_02_Limpeza_e_Manipula%C3%A7%C3%A3o_de_Dados_7DaysOfCode.ipynb)

Etapa de transformação dos dados para que façam sentido no contexto da análise, incluindo o mapeamento dos materiais pela CDU (Classificação Decimal Universal).

| Etapa | Descrição |
|-------|-----------|
| Exclusão | Coluna `registro_sistema` removida por ser irrelevante para a análise |
| Conversão | Coluna `matricula_ou_siape` convertida de número para string |
| Enriquecimento | Nova coluna `classe_cdu` criada com base nos códigos de localização |

>  189.257 registros foram perdidos no merge do Dia 1 por não terem correspondência no acervo. O DataFrame passou de 2.261.779 para 2.072.522 linhas.

---

### 📁 Dia 3: Explorando os dados
[Acessar notebook](https://github.com/Fernanda-Farias/7DaysOfCode-Pandas/blob/main/Dia_03_An%C3%A1lise_Explorat%C3%B3ria_de_Dados_e_DateTime_7DaysOfCode.ipynb)

Início da análise exploratória, investigando como os empréstimos se comportam ao longo do tempo para apoiar decisões da diretoria da biblioteca.

| Etapa | Descrição |
|-------|-----------|
| Por ano | Evolução do total de exemplares emprestados entre 2010 e 2020 |
| Por mês | Identificação dos períodos de maior e menor demanda ao longo do ano |
| Por hora | Mapeamento dos horários de pico para planejamento de atividades internas |

>  Os dados de 2020 apresentam queda abrupta devido ao fechamento das bibliotecas durante a pandemia de COVID-19.

---

### 📁 Dia 4: Em breve
### 📁 Dia 5: Em breve
### 📁 Dia 6: Em breve
### 📁 Dia 7: Em breve
