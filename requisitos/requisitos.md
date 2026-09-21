# Objetivo do Sistema

Desenvolver um sistema para registrar e consultar inspeções de materiais recebidos pela empresa, armazenando informações como nota fiscal, fornecedor, material, tipo, diâmetro, quantidade e resultado da inspeção.

------
# Requisitos Funcionais

## RF001 — Cadastrar inspeção

O sistema deve permitir o cadastro de uma nova inspeção.

### Campos do cadastro

- Nota Fiscal
- Fornecedor
- Material
- Tipo de Material
- Diâmetro
- Quantidade
- Resultado da Inspeção

---

## RF002 — Consultar inspeções

O sistema deve permitir consultar as inspeções cadastradas.

O sistema deve permitir:

- Visualizar todas as inspeções cadastradas;
- Pesquisar inspeções por Nota Fiscal;
- Pesquisar inspeções por fornecedor;
- Pesquisar inspeções por material;
- Filtrar inspeções por resultado (Aprovado/Reprovado);
- Filtrar inspeções por quantidade do material;
- Filtrar inspeções por diâmetro do material;
- Filtrar inspeções pelo tipo do material.

---

## RF003 — Editar inspeção

O sistema deve permitir alterar os dados de uma inspeção cadastrada.

O sistema deve permitir:

- Editar quantidade do material;
- Editar tipo do material;
- Editar diâmetro do material;
- Editar fornecedor;
- Editar Nota Fiscal.

---

## RF004 — Excluir inspeção

O sistema deve permitir excluir uma inspeção cadastrada.

---

## RF005 — Gerar relatório

O sistema deve permitir gerar um relatório das inspeções cadastradas.

---

# Requisitos Não Funcionais

## RNF001 - Desempenho

- O sistema deve apresentar o resultado das consultas em até 2 segundos.
- O sistema deve manter seu desempenho adequado mesmo sob alta quantidade de acessos simultâneos.
- O sistema deve utilizar os recursos de memória de forma eficiente durante sua execução.

---

## RNF002 - Segurança

- O sistema deve permitir acesso somente a usuários autorizados.
- O sistema deve utilizar autenticação em dois fatores.

---

## RNF003 - Usabilidade

- O sistema deve apresentar os campos de cadastro de forma clara e organizada.
- O sistema deve possuir uma interface simples e fácil de utilizar.
