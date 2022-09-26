# Checklist normalização de banco de dados

## 1º Forma Normal
Todos os atributos de uma tabela devem ser atômicos, ou seja, a tabela não deve conter grupos repetidos e nem atributos com mais de um valor. 

-[ ] Identificar a chave primária da tabela;
-[ ] Remover colunas repetidas;
-[ ] Remover dados repetidos;
-[ ] Assegurar que as colunas possuam apenas um valor;
-[ ] Assegurar que os valores em uma coluna sejam do mesmo tipo de dados;
-[ ] Nomear cada coluna deve com um nome único;
-[ ] A ordem dos dados registrados em uma tabela não deve afetar a integridade dos dados;
-[ ] Criar uma nova tabela com a chave primária para armazenar o dado repetido;
-[ ] Criar uma relação entre a tabela principal e a tabela secundária.

## 2º Forma Normal
Os registros não devem depender de nada além da chave primária de uma tabela (uma chave composta, se necessário). Ou seja, a tabela não deve possuir dependências parciais.

-[ ] Estar adequado à primeira forma normal;
-[ ] Identificar colunas que não são funcionalmente dependentes da chave primária da tabela;
-[ ] Remover essa(s) coluna da tabela principal;
-[ ] Criar uma (ou mais) nova(s) tabela(s) utilizando esses dados;

## 3º Forma Normal
Todos os atributos dessa tabela devem ser funcionalmente independentes uns dos outros, ao mesmo tempo que devem ser dependentes exclusivamente da chave primária da tabela. Ou seja, a tabela não deve conter atributos (colunas) que não sejam dependentes exclusivamente da chave primária.

-[ ] Estar adequado à primeira e segunda forma normal;
-[ ] Identificar as colunas que são funcionalmente dependentes de colunas não chave;
-[ ] Extraí-las para outra tabela;

Fontes de consulta:
https://learn.microsoft.com/pt-br/office/troubleshoot/access/database-normalization-description#normalizing-an-example-table
http://www.dsc.ufcg.edu.br/~pet/jornal/maio2011/materias/recapitulando.html
