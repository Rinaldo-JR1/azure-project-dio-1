- # Computação

  A área de computação nos serviços da Microsoft Azure envolve a provisão de recursos virtuais e físicos necessários para executar aplicativos e serviços na nuvem. Esses serviços são altamente escaláveis, flexíveis e incluem uma ampla gama de opções, desde máquinas virtuais a containers, aplicativos e soluções de gerenciamento de identidades. Aqui estão os principais serviços de computação oferecidos pelo Azure:

  - #### Area de trabalho virtual do azure

    A Área de Trabalho Virtual do Azure (Azure Virtual Desktop, ou AVD) é uma solução de virtualização de desktops e aplicativos baseada em nuvem, que permite que empresas provisionem e gerenciem ambientes de trabalho remotos. Com ela, usuários podem acessar desktops completos ou aplicativos específicos de forma segura a partir de qualquer dispositivo, em qualquer lugar.

  - #### Máquinas Virtuais (VMs)
    O Azure oferece uma infraestrutura como serviço (IaaS) que permite criar e gerenciar máquinas virtuais na nuvem. As VMs podem ser configuradas com diversos sistemas operacionais, como Windows e Linux, e são usadas para executar aplicativos personalizados, hospedar bancos de dados, ou até mesmo replicar ambientes locais na nuvem.
    - ##### Azure Virtual Machines:
      Criação de VMs personalizáveis com capacidades de escalonamento.
      Escalonamento de VMs: Conjuntos de escalas que aumentam ou diminuem automaticamente o número de VMs de acordo com a demanda.
    <br/>

- # Rede
  A área de rede do Microsoft Azure\*\* é um conjunto abrangente de serviços que permitem a conexão, gestão e segurança de redes na nuvem. Esses serviços formam a espinha dorsal da infraestrutura de TI em nuvem, garantindo a conectividade entre diferentes recursos e aplicativos, sejam eles hospedados no Azure, em datacenters locais ou em outras nuvens. A Azure oferece soluções de redes que são escaláveis, seguras e flexíveis, permitindo a construção de redes privadas, a interconexão de diferentes ambientes e a otimização do tráfego de rede.
  - #### Rede Virtual (Azure Virtual Network - VNet)
    Azure Virtual Network (VNet) é o serviço básico de rede da Azure, permitindo que você crie redes privadas dentro da nuvem. Ele proporciona conectividade entre Máquinas Virtuais (VMs), Serviços de Aplicações e outros recursos da Azure.
    Funciona como uma rede tradicional on-premises, mas virtualizada na nuvem, oferecendo segmentação de sub-redes, endereçamento IP privado, políticas de segurança e roteamento personalizado.
    Através de VNet Peering, é possível conectar várias VNets de forma eficiente e segura, sem a necessidade de roteadores intermediários.

  - #### Bastions / Bastião
    O Azure Bastion é um serviço totalmente gerenciado pela Microsoft Azure que permite acessar de forma segura máquinas virtuais (VMs) usando protocolos de conexão remota, como RDP (Remote Desktop Protocol) e SSH (Secure Shell), diretamente pelo portal do Azure. A grande vantagem do Azure Bastion é que ele evita a necessidade de expor suas VMs à internet pública, proporcionando um acesso remoto seguro e eficiente.