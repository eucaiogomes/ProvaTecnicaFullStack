# ProvaTecnicaFullStack


## Descrição
Este projeto é uma aplicação Java para uma vaga de estágio que lê dados de candidatos de um arquivo de texto, processa as informações e gera estatísticas sobre os candidatos com base em suas vagas de emprego. Os dados são armazenados em uma lista e um arquivo CSV é gerado com a lista ordenada por idade.

## Funcionalidades
- Leitura de dados de candidatos a partir de um arquivo `Academy_Candidates.txt`.
- Cálculo e exibição de estatísticas:
  - Proporção de candidatos por vaga (Web, Mobile, QA).
  - Idade média dos candidatos por vaga.
  - Idades máxima e mínima dos candidatos por vaga.
  - Número de estados distintos.
- Geração de um arquivo CSV (`Sorted_Academy_Candidates.csv`) com a lista de candidatos ordenada por idade.

## Estrutura do Projeto
## Como Usar

1. **Requisitos**:
   - Java 8 ou superior.
   - Git (opcional, se você deseja clonar o repositório).

2. **Clone o repositório** (se você usar Git):
   ```bash
   git clone https://github.com/seu-usuario/ProvaTecnicaFullStack.git
   cd ProvaTecnicaFullStack

   Nome;Idade;Vaga;Estado
João;30 anos;Web;SP
Maria;25 anos;Mobile;RJ
Pedro;28 anos;QA;MG


javac src/ProvaTecnicaFullStack.java
java -cp src ProvaTecnicaFullStack
