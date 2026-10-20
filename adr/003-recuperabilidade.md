# CARACTERÍSTICA: Recuperabilidade

## Estado

Aceita 

## Contexto

Um problema crítico que o Veredict poderia apresentar seria as provas em processo de autenticação ou já autenticadas fossem perdidas ou comprometidas tendo em vista que o usuário já pagou por elas. 

## Decisão

Para que esse cenário seja evitado ao máximo, foi tomada a decisão de possuir dois bancos de dados na aplicação, para dados não estruturados utilizando o file storage ou object storage, os dados são replicados em múltiplas zonas de disponibilidade, protegendo-os contra falhas de hardware.

## Consequências

Essa decisão vai implicar em mais operações para ligar as informações de cada banco de dados, um com as provas, gravações e imagens e o outro relacional com as informações do cliente, pagamento e relatório. Ou seja, exigirá uma complexidade a mais na hora da implementação, todavia, esse recurso é importante para garantir que qualquer problema que exista no banco estruturado não impacte a existência e a veracidade das provas.
