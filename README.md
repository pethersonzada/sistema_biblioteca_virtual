# Sistema de Gerenciamento de Biblioteca

Este repositório apresenta a modelagem completa de um sistema de biblioteca, desenvolvida com foco em organização, clareza e normalização dos dados.

O projeto inclui modelo conceitual e modelo lógico, elaborados com base em regras de negócio reais aplicáveis a sistemas de empréstimos e reservas de livros.

## Estrutura do Projeto

O Repositório contêm os arquivos:

  \Sistema de Biblioteca Virtual - DRAWIO
  
    \Sistema de Biblioteca Virtual - DRAWIO\Modelo Conceitual.drawio
    \Sistema de Biblioteca Virtual - DRAWIO\Modelo Conceitual.pdf
    \Sistema de Biblioteca Virtual - DRAWIO\Modelo Conceitual.png
    
  \Sistema de Biblioteca Virtual - BRMODELO
  
    \Sistema de Biblioteca Virtual - BRMODELO\Link para o BRMODELO.txt
    \Sistema de Biblioteca Virtual - BRMODELO\Sistema de Biblioteca Lógico.png
    \Sistema de Biblioteca Virtual - BRMODELO\Sistema de Biblioteca Conceitual.png

## Regras de Negócio

- Cada prateleira possui apenas um gênero.

- Cada publicação pertence a um único gênero.

- Uma publicação pode ter vários exemplares.

- Cada colaborador está vinculado a uma unidade.

- Um colaborador pode realizar vários empréstimos.

- Um empréstimo está sempre relacionado a um único exemplar.

- Cada empréstimo gera uma cobrança (1:1).

- Uma cobrança pertence a uma unidade.

- Uma reserva é feita por um colaborador para uma publicação.

- As publicações podem ser pesquisadas por autores e palavras-chave (relacionamentos N).

##  Cardinalidades

Relacionamento x Cardinalidade

GÊNERO — PRATELEIRA	1:1

GÊNERO — PUBLICAÇÃO	1

PUBLICAÇÃO — EXEMPLAR	1

UNIDADE — COLABORADOR	1

COLABORADOR — EMPRÉSTIMO	1

EXEMPLAR — EMPRÉSTIMO	1

EMPRÉSTIMO — COBRANÇA	1:1

COBRANÇA — UNIDADE	N:1

COLABORADOR — RESERVA	1

PUBLICAÇÃO — RESERVA	1

PUBLICAÇÃO — AUTOR	N

PUBLICAÇÃO — PALAVRA_CHAVE	N

## Ferramentas Utilizadas

Draw.io → Criação do modelo conceitual inicial

brModelo → Modelagem conceitual e lógica detalhada

GitHub → Versionamento e documentação

## Diagrama

### Modelo Conceitual - DRAWIO
<img width="1651" height="1251" alt="Modelo Conceitual png" src="https://github.com/user-attachments/assets/714226f3-61e2-4076-a308-9d25d3a8ae89" />

### Modelo Conceitual - BRMODELO 
<img width="1344" height="740" alt="Sistema de Biblioteca Conceitual" src="https://github.com/user-attachments/assets/e7e176dc-5f7b-42f9-bdad-86f6038fe589" />

### Modelo Lógico - BRMODELO
<img width="957" height="726" alt="Sistema de Biblioteca Lógico" src="https://github.com/user-attachments/assets/44a5592b-c4bb-47ac-af74-7feffe538e50" />

## Comentário!

Projeto desenvolvido por Petherson, para fins acadêmicos e de estudo em análise e modelagem de sistemas e também modelagem de banco de dados.

### Licença

Este projeto é de uso educacional.
Sinta-se à vontade para usar, modificar e compartilhar com os devidos créditos. 
