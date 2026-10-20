# Confiabilidade

## Estado

Aceita

## Contexto

O Veridit parte do princípio de gravação e captura das telas de determinadas aplicações web, como redes sociais, tendo isso em vista, é importante que esse serviço esteja sempre disponível. Considerando que muitas redes sociais apresentam limite de tempo em suas postagens, não é viável que o Veridit apresente falhas que atrapalhem a captura das informações desejadas e comprometa o usuário.

## Decisão

Nessa situação, a confiabilidade torna-se crítica para garantir a experiência do usuário e a devida utilização do sistema, por isso o enfoque nessa característica e sua importância para a decisão de que a arquitetura baseada em serviços seria a melhor a ser utilizada. Como as demandas do sistema estão dividas em serviços isso garante que uma falha em um componente não afetará todo o sistema.

## Consequências

Apesar de garantir a experiência do usuário, fortalecer a confiabilidade pode causar alguns gastos com servidor pela necessidade de manter essa aplicação sempre ativa e haverá também a necessidade de manutenção constante para a detecção e correção de falhas, evitando travamentos e similares.
