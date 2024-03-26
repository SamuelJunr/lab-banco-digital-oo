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


 
