# Recuperação da conta por link via email

## Estado

Aceito

## Contexto

No contexto de contas de usuário, é necessário permitir a recuperação da conta caso o mesmo não lembre da senha, ou exista a necessidade.

## Decisão

Utilizar o email verificado do usuário para a recuperação da conta, baseado na geração de um token de recuperação incorporado em um link e enviado por email.

## Consequências

Permite que o usuário tenha maior facilidade com a recuperação de senha, sendo mais conveniente. Entretanto, isso abre um vetor de ataque maior considerando que, caso haja uma falha de segurança relacionada ao email do usuário, isso pode comprometer a conta desse usuário no sistema.
