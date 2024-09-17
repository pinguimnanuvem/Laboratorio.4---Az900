Introdução

Este relatório descreve o processo e a experiência de construção de arquiteturas na nuvem usando o Microsoft Azure. O objetivo foi entender como projetar e implementar uma arquitetura de nuvem escalável e eficiente, utilizando os serviços oferecidos pelo Azure. O relatório inclui uma descrição dos passos seguidos e a utilização de impressões fictícias para ilustrar o processo.

1. Acesso ao Portal do Azure

O primeiro passo foi acessar o Portal do Azure , onde todos os recursos e serviços do Azure são gerenciados. A interface principal do portal apresenta uma visão geral dos recursos, um painel de navegação e uma barra de pesquisa para localização de serviços específicos.

Imprimir Fictício: Tela Inicial do Portal Azure

2. Projeto da Arquitetura

A arquitetura projetada incluiu os seguintes componentes:

Máquinas Virtuais (VMs) : Servidores para processamento e aplicação.
Banco de Dados SQL : Armazenamento de dados estruturados.
Rede Virtual (VNet) : Configuração de rede para comunicação entre os recursos.
Load Balancer : Distribuição de tráfego entre várias VMs.
Application Gateway : Gerenciamento de tráfego HTTP/HTTPS com recursos de firewall e balanceamento de carga.
Conta de armazenamento : Armazenamento de dados e arquivos.
Azure Monitor : Monitoramento e análise de desempenho dos recursos.
Imprimir Fictício: Diagrama de Arquitetura

3. Criação dos Recursos

3.1. Criando a Rede Virtual (VNet)

Navegue até "Redes Virtuais" e selecione "Criar".
Configurei o nome da VNet, o endereço IP, as sub-redes e os grupos de segurança de rede (NSGs).
Imprimir Ficção: Configuração da Rede Virtual

3.2. Configuração das Máquinas Virtuais

Acesse a seção "Máquinas Virtuais" e selecione "Criar".
Defina o nome da VM, sistema operacional, tipo de tamanho e configure as opções de rede para associar a VM à VNet criada.
Imprimir Fictício: Configuração da Máquina Virtual

3.3. Implementando o Banco de Dados SQL

Navegue até "Banco de Dados SQL" e selecione "Criar".
Configurei o nome do banco, servidor SQL, camada de desempenho e regras de firewall.
Imprimir Ficção: Configuração do Banco de Dados SQL

3.4. Adicionando um Load Balancer

Acesse "Load Balancer" e selecione "Criar".
Configurei os grupos de backend, como regras de balanceamento de carga e como regras de NAT.
Imprimir Ficção: Configuração do Load Balancer

3.5. Configuração do Application Gateway

Navegue até "Application Gateway" e selecione "Criar".
Defina o nome, tipo de SKU, regras de listener e pools de back-end.
Imprimir Ficção: Configuração do Application Gateway

3.6. Criando uma Conta de Armazenamento

Acesse "Contas de Armazenamento" e selecione "Criar".
Configurei o nome da conta, tipo de redundância e opções de acesso.
Imprimir Ficção: Configuração da Conta de Armazenamento

4. Monitoramento e Gerenciamento

Utilize o Azure Monitor para configurar alertas e visualizar métricas de desempenho para todos os recursos criados. Configurei alertas para notificações sobre desempenho e integridade dos recursos.

Imprimir Ficção: Configuração do Azure Monitor

5. Conclusão

A construção de arquiteturas no Azure revelou-se uma tarefa bem estruturada e flexível. A plataforma Azure oferece uma vasta gama de serviços que podem ser integrados para criar soluções escaláveis ​​e eficientes. A utilização de prints fictícios ajudou a ilustrar o processo de configuração e gerenciamento de diversos componentes.

6. Próximos Passos

Para ampliar o conhecimento e a experiência, os próximos passos incluem:

Explore o Azure DevOps para automação de implantações e gerenciamento de código.
Implementar o Azure Kubernetes Service (AKS) para gerenciar contêineres.
Investigar o Azure Policy para governança e conformidade dos recursos em nuvem.
