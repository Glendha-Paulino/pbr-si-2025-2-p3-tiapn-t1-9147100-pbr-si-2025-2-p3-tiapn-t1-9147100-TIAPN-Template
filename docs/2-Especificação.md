# Especificações do Projeto

Este documento detalha as especificações do projeto "Mão na Massa", uma plataforma digital que conecta clientes a prestadores de serviços técnicos e manuais. A partir da documentação de contexto fornecida, este relatório abrange a definição do problema, a ideia da solução, e as especificações técnicas e de negócio. Para isso, foram utilizadas as seguintes técnicas e ferramentas:

Definição de Personas: Para representar os usuários-alvo da plataforma.

Histórias de Usuários: Para descrever as funcionalidades do sistema a partir da perspectiva do usuário.

Requisitos Funcionais e Não Funcionais: Para detalhar o escopo técnico do projeto.

Restrições do Projeto: Para elencar as limitações e os fatores limitantes para a execução do projeto.

## Personas

Para o projeto "Mão na Massa", foram definidas dois personas principais que representam os usuários-alvo da plataforma: o Contratante, o Prestador de Serviço e o Administrador.

1. O Contratante
Nome: João Victor
Idade: 28 anos
Ocupação: Professor de Educação Física
Motivação: João Victor tem uma rotina intensa entre a academia e as aulas particulares. Ele gosta de manter a casa organizada, mas não entende de reparos técnicos. Valoriza agilidade e segurança, já que não tem tempo para lidar com várias negociações.

Cenário: João planeja receber amigos em casa para um churrasco no fim de semana e percebe que a área externa precisa de ajustes: uma tomada está queimada, o portão eletrônico apresenta falhas e a iluminação do quintal não funciona. Ele procura rapidamente por um profissional que consiga resolver todos esses pontos de uma vez, evitando que precise chamar diferentes prestadores.

2. O Prestador de Serviço (Profissional)
Nome: Marcos Silva
Idade: 38 anos
Ocupação: Técnico em Manutenção Residencial
Motivação: Marcos é conhecido como “faz-tudo”: trabalha com reparos elétricos, pequenos consertos hidráulicos e manutenção geral em residências. Costuma atender em bairros próximos, mas quer aumentar sua clientela e conquistar clientes que valorizem sua versatilidade.

Cenário: Marcos busca oportunidades de atender clientes que precisam de múltiplos reparos em um único atendimento. Ele vê nas plataformas digitais uma forma de mostrar seu diferencial: resolver vários problemas domésticos de forma rápida e segura, economizando tempo para o cliente.


## Histórias de Usuários

Com base nas personas, as seguintes histórias de usuários são relevantes para o projeto "Mão na Massa":

|EU COMO | QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Contratante  | solicitar um serviço detalhadamente (descrição, fotos e urgência)     | que os profissionais saibam exatamente o que eu preciso. |
|Contratante| me comunicar com o prestador de serviço antes de fechar o negócio      | Ptirar dúvidas e negociar os detalhes do trabalho. |
|Contratante| realizar o pagamento de forma segura dentro do aplicativo         | garantir que o valor só será repassado após a conclusão do serviço. |
|Contratante| avaliar o prestador de serviço após a conclusão do trabalho        | contribuir para a reputação dele na plataforma e ajudar outros usuários.|


|EU COMO | QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Prestador de Serviço  | ser notificado sobre novas solicitações de serviço em minha área de atuação         |que eu possa responder rapidamente e conseguir mais trabalhos.              |
|Prestador de Serviço       |ter um chat integrado e poder fazer chamadas de vídeo                 | negociar o orçamento e visualizar o trabalho antes de aceitá-lo. |
|Prestador de Serviço | receber o pagamento de forma segura e garantida      | que eu não tenha que me preocupar com inadimplência.  |
|Prestador de Serviço  | avaliar o cliente após a conclusão do serviço       | que eu possa contribuir para a reputação dele na plataforma e ter um histórico de boas interações.     |



|EU COMO | QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Administrador       | acessar dados do banco de dados    | realizar a manutenção da aplicação.             |
|Administrador       |gerar relatórios               | monitorar o desempenho da plataforma e tomar decisões.|
|Administrador       | alterar as permissões de usuários               | garantir que apenas os perfis designados tenham acesso a funcionalidades específicas.|




## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RNF-001| O sistema deve permitir que o Contratante solicite um serviço com detalhes. | ALTA | 
|RNF-002| O sistema deve permitir a comunicação via chat entre Contratante e Prestador.| ALTA | 
|RNF-003| O sistema deve permitir que o Prestador receba notificações de novas solicitações.| ALTA | 
|RNF-004| O sistema deve gerenciar um sistema de pagamento seguro (retenção do valor).|  MÉDIA | 
|RNF-005| O sistema deve permitir a avaliação mútua entre Contratante e Prestador.|ALTA | 
|RNF-006| O sistema deve permitir a realização de chamadas de vídeo integradas. |  MÉDIA | 
|RNF-007| O sistema deve permitir que o Prestador gerencie sua agenda.| MÉDIA | 
|RNF-008| O sistema deve permitir que o Administrador acesse dados do banco de dados. |   ALTA  | 
|RNF-009| O sistema deve permitir que o Administrador gere relatórios. | ALTA  | 
|RNF-010| O sistema deve permitir alterar o cadastro de contratante e contratado  |  ALTA  |
|RNF-011| O sistema deve permitir buscas com base em tipo de serviço pelo contratante.   |  ALTA  |
|RNF-012|  O sistema deve permitir ao prestador de serviço incluir o tipo de serviço que ele presta. |  ALTA  | 
|RNF-013|  O sistema deve permitir ao contratante fazer buscas com base em sua região |  ALTA  |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve ser responsivo para rodar em dispositivos móveis (web,iOS e Android). | ALTA | 
|RF-002| A plataforma deve ter um tempo de resposta máximo de 3 segundos para carregamento.  | MÉDIA |
|RF-003| A plataforma deve garantir a segurança das transações financeiras e dos dados pessoais. | ALTA | 
|RF-004| O sistema deve estar disponível 99,5% do tempo. | MÉDIA |
|RF-005| A interface do Administrador deve ser intuitiva para facilitar a manutenção. | MÉDIA |
|RF-006| Deve processar requisições do usuário em no máximo 3s | MÉDIA |

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend, utilizando apenas ferramentas no-code. |


