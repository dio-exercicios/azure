# Serviços de Computação da Azure
Responsáveis por fornecer os recursos de computação.
## Máquinas Virtuais (VM)
Emulam softwares de computadores físicos. Inclui processador virtual, memória, armazenamento e rede.
- Conjunto de Dimensionamento:  <br>
Permite a automatização de recursos de uma VM, como balanceamento de carga e controle de escala.
- Conjunto de Disponibilidade:  <br>
Consiste em duas partes
- Domínio de falha: conjunto de VM's que cada outro domínio do conjunto funciona como uma cópia dele.
- Domínio de atualização: fileira de VM's que compartilham um mesmo ciclo de criação / atualização.
## Área de Trabalho Virtual
Responsável pela execução em nuvem de uma área de trabalho e aplicativos. Reduz risco de dados serem deixados para trás. Possibilita o multi-acesso de usuários a uma área de trabalho.
## Contêineres
Ambiente virtual leve, com rápida criação e exclusão do mesmo. Não necessita de sistema operacional. Bom para microsserviços.
## Instâncias de Contêiner
Oferta PaaS que executa um contêiner ou uma pool de contêineres.
## Aplicativos de Contêiner
Oferta PaaS que é similar a uma instância, mas possibilita também o uso de recursos como balancemamento de carga e controle de escala.
## Serviços de Kubernetes (AKS)
Serviço usado para organização / orquestração de contêineres. Bom para casos onde há arquitetura distribuída e em casos onde há um grande volume de contêineres.
## Azure Function
Oferta PaaS que executa funções a partir de uma condição. Executado no momento que é chamado.
## Serviços de Aplicativos
Oferta PaaS que permite a criação, implementação e gerenciamento de aplicativos Web e API's.
## Serviços de Rede (VNet)
Permite a comunicação dos recursos via Internet e redes locais.
Pontos de Extremidade
- Públicos: acessíveis a partir de qualquer rede.
- Privados: acessível apenas a partir de uma rede específica.
## Gateway de VPN
Usado para comunicação de uma rede virtual com uma rede local.
## ExpressRoute
Usa encabeamento para a comunicação entre recursos.
## Domain Name Server (DNS)
A segurança é garantida a partir da configuração correta do gerenciador de recursos.