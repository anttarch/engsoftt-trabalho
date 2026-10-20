# Verificação do email do usuário

## Estado

Aceito

## Contexto

É necessário garantir que o usuário exista, que foi ele mesmo quem realizou o cadastro e que o email será válido para funções como recuperar email e receber confirmação de gravação do conteúdo. Garantindo as características de segurança 

## Decisão

Para que esse contexto seja atingido será realizada uma verificação do email do usuário no momento em que ele está fazendo o cadastro. Essa verificação consistirá no envio de um código por email, que será digitado no site. Dentre as possibilidades, o email foi escolhido como o meio por ser considerado mais seguro do que SMS ou Whatsapp, já que é necessário um login.

## Consequências

Apesar de adicionar mais uma etapa ao usuário e tornar o processo de cadastro um pouco mais demorado, essa decisão é essencial para garantir a segurança do dono do email e impede que outras pessoas usem endereços de emails indevidamente.

