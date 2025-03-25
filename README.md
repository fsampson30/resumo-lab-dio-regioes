# Resumo sobre Regiões e Grupos de Recursos

O Azure opera em vários datacenters no mundo inteiro. Esses datacenters estão agrupados em regiões geográficas, possibilitando uma escolha de onde criar seus recursos globalmente.

Dentro de cada região, há vários datacenters para fornecer redundância e disponibilidade. É possível criar recursos em várias regiões para que seus recursos estejam sempre disponíveis. Caso uma região saia do ar, existe o mesmo serviço em outro local do mundo.

Foi visto também a questão de Pares de Regiões, que consistem numa replicação automática de cada Região.

## Níveis de gerenciamento e hierarquia

O Azure fornece quatro níveis de gerenciamento: grupos de gerenciamento, assinaturas, grupos de recursos e recursos:

 - Grupos de gerenciamento ajudam você a gerenciar acesso, política e conformidade para diversas assinaturas. Todas as assinaturas em um grupo de gerenciamento herdam automaticamente as condições aplicadas ao grupo de gerenciamento.

 - Assinaturas associam logicamente contas de usuários aos recursos que eles criam. Cada assinatura tem limites ou cotas na quantidade de recursos que pode criar e usar. As organizações podem usar assinaturas para gerenciar custos e os recursos criados por usuários, equipes e projetos.

 - Grupos de recursos são contêineres lógicos em que você pode implantar e gerenciar recursos do Azure, como máquinas virtuais, aplicativos Web, bancos de dados e contas de armazenamento.

 - Recursos são instâncias de serviços que você pode criar em um grupo de recursos, como máquinas virtuais, armazenamento e bancos de dados SQL.
