# Atividade 1 — EDA com Pandas: Emendas Parlamentares

Atividade prática da disciplina **Introdução à Ciência de Dados**, ministrada pelo professor **Pedro Mello**.

---

## Descrição

Análise exploratória de dados (EDA) aplicada a um dataset real de **emendas parlamentares brasileiras**, utilizando os comandos básicos da biblioteca **Pandas**. O objetivo é familiarizar o estudante com inspeção, leitura e interpretação inicial de um dataset.

---

## Dataset

**Arquivo:** `emendas.csv`  
**Registros:** ~88.596 linhas

### Dicionário de Variáveis

| Coluna | Descrição |
|---|---|
| `Código da Emenda` | Identificador único da emenda |
| `Ano da Emenda` | Ano de aprovação da emenda |
| `Tipo de Emenda` | Classificação (Individual, Bancada, etc.) |
| `Código do Autor da Emenda` | Código do parlamentar autor |
| `Nome do Autor da Emenda` | Nome do parlamentar autor |
| `Número da emenda` | Número sequencial da emenda |
| `Localidade de aplicação do recurso` | Cidade/UF de destino |
| `Código Município IBGE` | Código IBGE do município |
| `Município` | Nome do município |
| `Código UF IBGE` | Código IBGE do estado |
| `UF` | Sigla do estado |
| `Região` | Região do Brasil |
| `Código Função` / `Nome Função` | Área de atuação (Saúde, Educação, etc.) |
| `Código Subfunção` / `Nome Subfunção` | Subcategoria da função |
| `Código Programa` / `Nome Programa` | Programa orçamentário vinculado |
| `Código Ação` / `Nome Ação` | Ação específica do programa |
| `Código Plano Orçamentário` / `Nome Plano Orçamentário` | Plano orçamentário da ação |
| `Valor Empenhado` | Valor comprometido pelo orçamento |
| `Valor Liquidado` | Valor confirmado após entrega do serviço |
| `Valor Pago` | Valor efetivamente pago |
| `Valor Restos A Pagar Inscritos` | Valores não pagos inscritos para o ano seguinte |
| `Valor Restos A Pagar Cancelados` | Valores cancelados dos restos a pagar |
| `Valor Restos A Pagar Pagos` | Restos a pagar que foram quitados |

---

## Exercícios

A atividade cobre 9 exercícios de EDA:

1. Carregar o dataset e exibir as primeiras 10 linhas
2. Verificar o número de linhas e colunas (`shape`)
3. Listar e descrever as colunas (dicionário de variáveis)
4. Identificar valores nulos e quantificá-los
5. Verificar os tipos de variáveis e detectar tipagens incorretas
6. Descobrir o ano mais recente no dataset com ordenação decrescente
7. Executar `describe()` e interpretar as estatísticas
8. Exibir as últimas 5 linhas e analisar a completude dos dados
9. Verificar a existência de registros duplicados

---

## Tecnologias Utilizadas

- Python 
- [Pandas](https://pandas.pydata.org/)
- Jupyter Notebook / Google Colab

---

## Como Executar

1. Coloque o arquivo `emendas.csv` no mesmo diretório do notebook (ou ajuste o caminho no código).

2. Instale a dependência caso necessário:
   ```bash
   pip install pandas
   ```

3. Abra o notebook `pandas_intro_ex1.ipynb` no Jupyter ou Google Colab e execute as células em ordem.

---

## Disciplina

**Introdução à Ciência de Dados**  
Professor: Pedro Mello
