# Arquitetura baseada em serviços 

## Estado

Aceito

## Contexto

O Veridit atualmente é um sistema pequeno e desenvolvido por alunos então algumas coisas precisam ser levadas em consideração como por exemplo não ser uma implementação extremamente complexa e uma aplicação muito grande sem essa necessidade atualmente.  Outra motivação essencial do sistema é que realize gravações de tela e que essa ação mais pesada não comprometa o sistema como um todo. 

## Decisão

Pensando nas arquiteturas estudadas, foi escolhida a Arquitetura Baseada em Serviços (Service-Based). Tendo em vista que será possível separar cada necessidade como bloco de serviços maiores, dividindo as funções mas também não será extremamente dividido como em Microsserviços pois, como é um sistema inicial, não há necessidade de uma aplicação tão robusta. A divisão dos serviços também garante que se um falhar os outros seguem funcionando sem interrupções, ou seja, confiabilidade. Além disso, a possibilidade de divisão do banco de dados garante a recuperabilidade. A segurança pode ser garantida dedicando um serviço para a identificação do usuário. 
  
## Consequências

Em relação a um sistema monolítico, a arquitetura em eventos terá uma implementação mais complexa e as transmissões não serão automáticas. Entretanto,  a divisão em serviços será essencial para o funcionamento adequado da aplicação.
