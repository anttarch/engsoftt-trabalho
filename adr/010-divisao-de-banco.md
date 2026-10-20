
# Divisão dos bancos de dados

## Estado

Aceita 

## Contexto

Pensando em um sistema que envolve provas jurídicas é necessário que elas estejam armazenadas de forma segura, garantindo assim a recuperabilidade. O sistema precisa apresentar suporte a consultas complexas e relacionamentos bem definidos entre entidades (usuários, pedidos e pagamentos). A equipe precisa de uma solução madura, com boa performance e suporte nativo a dados estruturados e semiestruturados

## Decisão

Para que isso fosse alcançado a decisão tomada foi dividir os bancos de dados entre estrutural e não-estruturado. O estruturado para armazenar os dados de identificação, pagamento e relatórios, já o não estruturado para armazenamento dos vídeos e fotos. Também pensado no uso de object storage, para gerenciar os dados com unidades independentes, se torna ideal para dados não estruturados, com acesso via API.
  

## Consequências

A divisão do banco de dados vai evitar com que um travamento em uma parte do banco do sistema que não tenha relação com as provas falhe e isso comprometa as gravações. Com essa decisão as relações entre os bancos será feita de maneira complicada, sendo necessárias mais conexões para ligar uma prova a um advogado ou a um cliente. Todavia, a garantia da recuperabilidade e segurança dos dados possui uma importância maior.
