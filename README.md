# Brandt Meio Ambiente
## Padronização de Banco de Dados
### [Manual de Padronização]

**Francisco de Paula Ribeiro**  
**Data do Documento: 11/12/2021**

---

## Sumário

1. Formatação Básica  
2. Nome do Arquivo  
3. Planilha Única  
4. Identificador  
5. Variáveis por Colunas  
6. Variáveis por Linhas  
7. Codificação  
8. Coordenadas  
9. Data e Hora  
10. Dados Acumulados  

---

## Introdução

Este documento foi elaborado para orientar a padronização dos bancos de dados da Brandt Meio Ambiente, visando prevenir inconsistências nas bases de dados e promovendo uma organização eficaz para facilitar o armazenamento e a consulta dos dados em planilhas Excel. Este manual constitui uma base inicial e poderá ser revisado futuramente para ajustes e expansões conforme novas necessidades.

---

## Padrões de Formatação e Procedimentos

### 1. Formatação Básica

As planilhas devem adotar:
- **Fonte**: Arial
- **Tamanho**: 12 pt
- **Altura da Linha**: 15
- **Alinhamento**: Centralizado

### 2. Nome do Arquivo

Os arquivos de Excel devem seguir o padrão de nomenclatura:
- Exemplo: `5RC CODIGO DO PROGRAMA/PROJETO NOME DA PLANILHA (AAAAMMDD)-1.xlsx`

### 3. Planilha Única

Quando for necessário utilizar várias planilhas, mantenha uma variável chave para vincular as informações entre elas.

### 4. Identificador

Adicione uma coluna "Identificador" na primeira posição da planilha, preenchendo-a com uma sequência única e fixa para cada registro, que facilite a identificação e vinculação com dados físicos.

### 5. Variáveis por Colunas

Cada variável deve ocupar uma coluna, identificada pela pergunta correspondente do questionário. Para múltiplas escolhas, distribua cada resposta em uma coluna específica.

### 6. Variáveis por Linhas

Cada registro deve ocupar uma linha, com a variável ID identificando o questionário específico e facilitando consultas futuras.

### 7. Codificação

Codifique variáveis para evitar erros de digitação. Exemplo:
- Solteiro: 1, Casado: 2, Sim: 1, Não: 0

Guarde a codificação em uma aba separada com o mapeamento de códigos para variáveis e respostas.

### 8. Coordenadas

- **Fuso**: 22 Sul, **Datum**: SAD69, **Projeção**: UTM
- **X**: Seis dígitos, **Y**: Sete dígitos, sem decimais.

### 9. Data e Hora

- **Data**: DD/MM/AAAA
- **Hora**: hh:mm:ss

### 10. Dados Acumulados

O banco de dados deve conter todos os dados acumulados desde o início do projeto, mantendo consistência exata com o Relatório Consolidado.

---

Este README serve como referência básica para a padronização dos bancos de dados, promovendo clareza e uniformidade para os colaboradores da Brandt Meio Ambiente.
