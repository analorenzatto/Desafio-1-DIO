# Desafio-1-DIO
Resumo e anotações das aulas iniciais do DIO
COMO A COMPUTAÇÃO EM NUVEM FUNCIONA? – CLOUD
O que é nuvem?
Lembrar da maquina de lavar roupa – ou vc compra o produto ou utiliza uma lavanderia e paga pelo serviço (mais prático); essa lavanderia é chamada de as a servisse: vc paga pela quantidade que vc vai usar, vc tem a necessidade intriseca e a primeira maneira de resolver é comprar a maquina, mas o custo é alto – o ambiente compartilhado é mais barato, eles lucram pelo volume.
- As a service: aos invés de vc pagar pela máquina, vc aluga um ambiente com várias maquinas compartilhadas e paga pelo uso;
- A Cloud: processar todos os dados e informações (como um CPU); 
Data center: é um monte de máquinas processando informações o tempo todo (uma sala só pra isso)
Ambiente Cloud vs On premise vs Hybrid Model
Caso vc tenha um ambiente com várias máquinas e toda a infraestrutura necessária e vc que paga: on premise (ambiente no local)
As empresas acessam as máquinas através da internet, por meio dos cabos de rede/internet – é alugado de outra pessoa/empresa utilizar: cloud
Qual a vantagem da cloud? Não tem os custos de manutenção e infraestrutura
Hybrid Model: aluga maquinas na nuvem temporariamente; precisa e tem algumas maquinas presencial (on premise), mas somente em alguns meses precisa de mais maquinas para atender o pico, ou seja, nesses meses específicos ele aluga ambiente cloud
Empresas platform: empresas especializadas em aluguel de nuvem, vendem soluções para internet; elas possuem uma infraestrutura de maquinas grandes 
Quando a platform está longe – tem latência: as platforms criaram as regions e zones, conjuntos de maquinas em diferentes regiões para diminuir a latência, assim as empresas podem escolher uma region mais perto; as zones são subdivisão ou
  Link caderno de anotações do prof: https://felipe-aguiar.gitbook.io/cloud-fundamentals
AZ-900: INTRODUÇÃO AOS CONCEITOS BÁSICOS DO MICROSOFT AZURE
AZ900 é uma certificação de clouding – uma prova
Conceitos de nuvem
Tem bastante demanda em custos!! 
Criar conta: https://portal.azure.com/#view/Microsoft_Azure_Resources/QuickstartCenterMenuBlade/~/overviewTab?l=pt-br
Não esquecer de cancelar depois de 30 dias
Computação em nuvem: domínio do objetivo
•	Nuvem privada: ambiente 100% on premise; tenho nuvem mas para a própria empresa; é um datacenter privado da empresa
•	Nuvem pública: entrega serviços e recursos a vários usuários de vários locais; acessada via conexão de rede segura (internet)
•	Nuvem híbrida: tem os dois modelos; tem um datacenter próprio e usa tbm usa nuvem pública (e ambas conversam entre sim)
•	Multicloud: uso várias plataformas, várias nuvens (azure, aws, etc) além do modelo on premise
Comparação dos modelos em nuvem
•	Nuvem pública: não tem despesa de capital (CAPEX, OPEX) para escalar verticalmente (não to pagando na hora, somente depois e pelo o que eu usei); as organizações pagam apenas pelo que utilizam; os apps podem ser provisionados e desprovisionados rapidamente (posso excluir rapidamente, paga pelo tempo que ficou ali, se ficou pouco não pesa)
•	Nuvem privada: as org. tem controle total sobre recursos e segurança (determina quem entre e sai, quem tem acesso, o que pode fazer); as org. são responsáveis pela manutenção e atualizações de hardware e software
•	Nuvem hibrida: org. determinam onde executar seus apps (o que for mais benéfico); as org. controlam segurança, conformidade e os requisitos legais (a nuvem oferece e cabe a org. decidir o que vai aplicar, o que a org. exige); fornece maior flexibilidade
CapEx e OpEx:
Despesas de capital = CapEx: gasto inicial de dinheiro em infraestrutura física (cabeamento, climatização e tudo mais); despesas de Capex tem um valor que se reduz com o tempo (o custo de manutenção e de “sobrevivência” é mais baixo que o de instalação, por isso reduz)
Despesas Operacionais = OpEx: gasto com produtos e serviços conforme necessário, pgto conforme uso; cobrança imediata 
Modelo baseado em consumo: pgto somente pelos recursos que usam (qto mais tempo ativo, mas ele vai custar); melhor previsão de custos; preços para recursos e serviõs individuais; cobrança baseada no seu uso real
Resumo: https://hermes.dio.me/files/assets/0353df52-12c6-404c-bc41-e711128c2732.pptx
https://hermes.dio.me/files/assets/8b373a71-9a0d-4673-9e44-eed0d537c967.pptx
Benefícios da nuvem Azure
Alta disponibilidade: sempre funciona, tem em todo lugar; recursos disponíveis sempre que necessário; tem um SLA (contrato) e a Microsoft se responsabiliza se algo der errado (vai ter estorno caso ele não consiga te entregar o serviço); recebe créditos pela não entrega da Microsoft; existe nível de entrega (99%, 99,5%) e cada um delas está relacionado a um tempo, por contrato, que esse serviço pode ficar indisponível; se ficar indisponível além do tempo previsto, o cliente recebe estorno (voucher de crédito, não volta pra tua conta)
Escalabilidade: capacidade de ajustar recursos para atender a demanda – aumenta para atender a demanda; não paga além do necessário pelos serviços, paga apenas pelo que usa; se a demanda cair, vc pode reduzir recursos e custos; sobe a capacidade de recursos
Elasticidade: um salto repentino acentuado na demanda, os recursos implantados poderiam ser expandidos (automático ou manual) – tipo black Friday; subo o ambiente com uma programação condicional; adiciona maquinas por meio da expansão
Confiabilidade: infraestrutura confiável e resiliente; design descentralizado; associado a resiliência de um sistema que se recupera de falhas e volta rapidamente; escala global: mesmo que em um local caía, em outros continuam funcionando.
Previsibilidade: confiança; avançar com confiança seja no desempenho ou no custo; influenciadas pelo Microsoft Azure Well-Architected Framework
Segurança: oferece ferramentas de segurança que atendem a necessidade dos clientes, mas a implementação é responsabilidade do cliente
Governança: padrões para gerir os recursos; auditoria para verificar se nenhum recurso esteja fora da conformidade com os padrões corporativos e fornece estratégias de mitigação; patches de softwares e atualizações podem ser aplicados automaticamente  
Gerenciabilidade: gerenciar seus recursos da nuvem; escalar automaticamente a implantação de recursos com base em necessidade; implantar recursos com base em um modelo pré configurado, sem configuração manual
Material de apoio: https://hermes.dio.me/files/assets/8ac3de68-4ebd-4552-8349-41e93cb3c6e7.pptx
https://hermes.dio.me/files/assets/ca7236cb-ebfa-4a9a-b97c-35ae08cb27d7.pptx

Criando máquinas virtuais no Azure
Quando recebe um serviço, a primeira coisa a se perguntar é: quanto tempo de inatividade é aceitável?
Quanto mais noves, menos tempo indisponível o recurso vai ter – quanto menos noves, mais tempo indisponível vai ter 
