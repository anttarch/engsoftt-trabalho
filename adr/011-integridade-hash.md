# Confirmação da integridade das provas por hash

## Estado

Aceito

## Contexto

Considerando a sensibilidade dos dados armazenados, é importante que o usuário tenha certeza de que os registros feitos não foram alterados pelo sistema ou por agentes externos

## Decisão

Para todo dado capturado (vídeo e foto), ao final da captura será calculado um hash, com base em um algoritmo moderno, e esse valor será armazenado pelo sistema e disponibilizado para o usuário.

## Consequências

Fazer o cálculo do hash pode ser custoso dependendo do dado capturado, o que pode influenciar negativamente na experiência do usuário considerando o tempo computacional. Além disso, é mais um dado a ser armazenado, o que deve ser considerado. Por outro lado, a existência do hash permite uma maior confiabilidade do usuário na plataforma, considerando que ele pode verificar por conta própria a imutabilidade da captura.
