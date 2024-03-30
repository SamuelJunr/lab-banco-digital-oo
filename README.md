# Preparatorio para certificação AZ-900

## 26/03/24 - beneficios da nuvem Azure 
 Os beneficios de nuvem são:
 Elasticidade: A capacidade de escalar recursos de TI para cima ou para baixo automaticamente, de acordo com as necessidades do negócio.

 Confiabilidade:  A garantia de que os serviços e aplicações estarão disponíveis quando necessários, com redundância e backup adequados.

 Alta disponibilidade: A habilidade de manter os serviços operacionais e acessíveis mesmo diante de falhas ou manutenções.
 
 Estes são aspectos chave que fazem a plataforma Azure uma escolha robusta para hospedar e gerenciar serviços na nuvem.

Para criar uma máquina virtual no Azure e garantir a maior disponibilidade global, você pode seguir estes passos:

1. Entrar no Azure: Acesse o Portal do Azure.
2. Criar máquina virtual: No portal, busque por “máquinas virtuais” e selecione o serviço correspondente. Clique em “Criar” e escolha “Máquina virtual do Azure”.
3. Configurar a VM: Preencha os detalhes da instância, como nome e imagem da máquina virtual. Escolha uma região que suporte zonas de disponibilidade.
4. Definir disponibilidade: Na seção de opções de disponibilidade, selecione “Zonas de disponibilidade” para distribuir suas VMs em zonas fisicamente separadas dentro da região escolhida.
5. Conjuntos de disponibilidade: Para aplicações altamente disponíveis, crie duas ou mais VMs dentro de um conjunto de disponibilidade1.
6. Balanceador de carga: Combine o Azure Load Balancer com zonas de disponibilidade e conjuntos de dimensionamento para obter a maior resiliência da aplicação1.
7. Revisar e criar: Verifique as configurações e, após a validação, clique em “Criar” para implantar sua VM.
Lembre-se de que a escolha de zonas de disponibilidade e conjuntos de disponibilidade são cruciais para garantir a alta disponibilidade global da sua máquina virtual.

## 30/03/24 - Tipos de Nuvens

IaaS (Infrastructure as a Service):
Definição: O IaaS é um modelo de computação em nuvem que oferece aos usuários uma infraestrutura gerenciada, incluindo servidores, armazenamento e rede.
Responsabilidades:
O provedor de nuvem fornece a infraestrutura básica (servidores, switches, roteadores etc.).
Os clientes têm controle total sobre o sistema operacional, middleware e aplicativos.
Responsáveis por configurar e gerenciar seus próprios recursos de TI.
Exemplo: Criar uma máquina virtual (VM) no Azure.
Flexibilidade: É o modelo mais flexível, permitindo personalização completa12.
PaaS (Platform as a Service):
Definição: O PaaS oferece uma plataforma completa para desenvolvimento e implantação de aplicativos.
Responsabilidades:
O provedor gerencia a infraestrutura subjacente (servidores, rede etc.).
Os clientes se concentram no desenvolvimento de aplicativos.
Não precisam se preocupar com a manutenção do sistema operacional ou do hardware.
Exemplo: Usar o Azure App Service para hospedar um aplicativo da web.
Equilíbrio: Oferece um equilíbrio entre controle e facilidade de uso13.
SaaS (Software as a Service):
Definição: O SaaS oferece aplicativos prontos para uso pela internet.
Responsabilidades:
O provedor gerencia tudo: infraestrutura, aplicativos e dados.
Os clientes simplesmente usam o software sem se preocupar com a manutenção.
Exemplo: Usar o Microsoft 365 (anteriormente Office 365) para e-mail e colaboração.
Conveniência: É o modelo mais conveniente, mas com menos controle14.
Em resumo:

IaaS: Controle total sobre a infraestrutura.
PaaS: Foco no desenvolvimento de aplicativos.
SaaS: Aplicativos prontos para uso.

A responsabilidade compartilhada é um conceito fundamental na computação em nuvem, especialmente quando se trata de serviços como o Microsoft Azure. Vamos entender como funciona:

Provedor de Nuvem (Azure):
O provedor de nuvem (como a Microsoft) é responsável por:
Infraestrutura física: Isso inclui data centers, servidores, switches, roteadores e armazenamento.
Segurança física: Proteger os data centers contra ameaças físicas, como incêndios, inundações e acesso não autorizado.
Redundância: Garantir que os serviços sejam altamente disponíveis, mesmo em caso de falhas.
Atualizações de hardware e software: Manter a infraestrutura atualizada e segura.
Conectividade de rede: Fornecer conectividade confiável para os serviços.
Conformidade regulatória: Cumprir regulamentações e padrões de segurança.
Essas responsabilidades são invisíveis para os clientes.
Cliente (Você):
Como cliente, você tem responsabilidades específicas:
Configuração e gerenciamento de recursos: Configurar e gerenciar máquinas virtuais, bancos de dados, redes etc.
Segurança de aplicativos: Proteger seus aplicativos e dados.
Acesso e identidade: Gerenciar quem tem acesso aos recursos.
Backup e recuperação: Planejar e executar backups e recuperação de dados.
Conformidade de aplicativos: Garantir que seus aplicativos atendam aos requisitos regulatórios.
Monitoramento e alertas: Monitorar o desempenho e receber alertas.
Essas responsabilidades são visíveis e configuráveis por você.



 
