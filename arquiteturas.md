# Cliente Servidor

## Vantagens

- Divisão de papeis
- Maior controle
- Dados mais centralizados
- maior segurança

## Desvantagens

- Sobrecarga de servidor
- se derrubar agua no servidor fudeu


# Em camadas

- Derivada da cliente servidor
- divide o software em hierarquia
- as camadas conversam entre si, mas só as que estão pertinho

## Vantagens

- Escalabilidade por estar menos acoplado
- integridade dos dados por estarem mais isolados

## Desvantagens

- é mais complexo na implementação
- dificil compreensão e divisão das camadas
- separação fisica de servidores entre camadas

# Peer to Peer (P2P)

- Cada nó coopera com o outro
- Cada maquina pode ser servidor ou cliente
- recebe e faz requisições
- geralmente é pra usar dados imutáveis

## Vantagem

- Disponibilidade maior
- Desempenho limitado a internet

# Service Oriented Architecture (SOA)

- Utiliza componentes de software como serviços independentes para compor uma aplicação
- Cada serviço propoe um SERVIÇO (OBVIO), assim sendo de certa forma unico
- Comunicação entre serviços
- Cada componente pode ser feito em linguagens diferentes

## Vantagens

- Mais rápido de implementar
- Reutilização é bem maior
- Manutenção é muito mais facil
- testar é mais rapido

## Desvantagens

- Escalabilidade é mais complexa e dificil, pela questão que a coordenação dos serviços fica complexa
- Aumento de interdependencia

# Microserviços

- Evolução do SOA
- Serviçõs se comunicão via APIs
- Implementadas normalmente em containeres
- Acesso local a todos dados que precisam

## Vantagens

- Maior escalabilidade que a SOA
- Desacoplamento maior ainda
- Serviços são Isolados entre si, rodam sem dependencias
- Sem um ESB da vida que se cair, cai tudo

## Desvantagens

- Gerenciamento de diferentes partes autonomas
- Governança dos dados mais complexa
- Segurança tem uma "vulnerabilidade maior"