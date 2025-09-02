# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO no caso um resumo do que foi aprendido durante o Bootcamp do AZ-900.
ESTUDOS AZ-900.

A computação em nuvem é o fornecimento de serviços de computação pela internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala
Permite a criação de forma rápida de recursos e serviços, você paga apenas o que usa, e abrange diversas ferramentas (Armazenamento, aplicações, computação, rede, etc...)

# MODELOS DE NUVEM
### Nuvem-Privada, 
ambiente 100% On premise um ambiente totalmente voltado para empresa, não divide com ninguém 
As organizações criam um ambiente em nuvem em seu datacenter.
As Organizações são responsáveis por operar os serviços que fornecem.
Não fornecem acesso aos usuários fora da organização
	
### Nuvem Publica,
oposto da privada, uma única instituição como a Microsoft por exemplo, cria diversos datacenters ao redor do mundo e quem quiser e puder pagar, utiliza os serviços através do Azure por exemplo
Pertencente a serviços de nuvem ou provedor de hosting.
Fornece recursos e serviços a várias organizações e usuários.
Acessada via conexão de rede segura (geralmente pela internet).
	
### Nuvem hibrida,
“O melhor entre os dois mundos”  Geralmente empresas que já estão há muito tempo no mercado, que já possuem um data center para hostiar a nuvem privada, integram a nuvem pública e as comunicam para gerir recursos.
Combina nuvens públicas e provadas para permitir que os aplicativos sejam executados no local mais adequado.



	


# COMPARAÇÂO DE MODELOS DE NUVEM
### Nuvem-Privada,
Nenhuma despesa de capital para escalar verticalmente.
Os aplicativos podem ser provisionados e desprovisionados rapidamente.
As organizações pagam apenas pelo que utilizam.


### Nuvem Publica,
As organizações têm controle total sobre os recursos e a segurança
As organizações são responsáveis pela manutenção e pelas atualizações de Hardware e Software.


### Nuvem hibrida,
As organizações determinam onde executar seus aplicativos.
As organizações controlam a segurança, a conformidade e os requisitos legais.
Fornece a maior flexibilidade.

### COMPARAÇÂO CapEx e OpEx
Despesas de capital (CapEx)
•	O Gasto inicial de dinheiro em infraestrutura física.
•	As Despesas do CapEx têm um valor que se reduz com o tempo.
### Despesas Operacionais (OpEx)
•	Gastar com produtos e serviços conforme necessário, pagamento conforme o uso.
•	Seja cobrado imediatamente.

### Modelo Baseado em consumo
Os provedores de serviços em nuvem operam em um modelo baseado no consumo, o que significa que os usuários finais pagam somente pelos recursos que usam.
•	Melhor previsão de custos.
•	São fornecidos preços para recursos e serviços individuais.
•	A cobrança é feita com base no seu uso real.

#BENEFÍCIOS DA NUVEM AZURE
### ALTA DISPONIBILIDADE 
•	Recursos disponíveis sempre que necessário 
•	Ligado a questão de SLA (Ao contratar um recurso, caso ele não seja fornecido corretamente, a Microsoft “Abraça” esse problema.
•	Caso o serviço não seja entregue dentro do prazo contratado, a Microsoft possui um tipo de ressarcimento em créditos para melhor experiencia do usuário.
•	Mesmo possuído todo o suporte da Microsoft e uma alta disponibilidade, os serviços em nuvem está sujeito a ficar indisponível. Um serviço em nuvem pode ficar degradado principalmente por rede congestionada, sobrecarga de recursos, falha s em updates/manutenções, ataques de segurança ou dependência de terceiros.
•	A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.

### ESCALABILIDADE
•	A escalabilidade refere-se à capacidade de ajustar recursos para entender à demanda. (exemplo: em uma empresa diversos colaboradores realizam a instalação de filmes para assistir durante seus intervalos, o servidor vai continuar dando conta pelo processamento, sistema operacional e diversos outros recursos, porém o disco de armazenamento acaba ficando cheio, para escalonar basta adicionar um disco. Ou seja, é possível adicionar somente um dos recursos conforme sua necessidade.
•	A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
•	O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços.
•	Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa.
•	Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.
•	Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.


### ELASTICIDADE
•	Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (Automaticamente ou manualmente). (como exemplo a black Friday, antigamente diversos sites ficavam fora, pois, a demanda durante esse período era muito maior que o normal, ou também diversas empresas se preparavam gastando muito dinheiro em servidores adicionais, mas quando chegava a época nem eram tão requisitadas assim.
•	Por exemplo, você pode adicionar máquinas virtuais ou contêiner por meio da expansão. (Você pode configurar por exemplo, caso meu servidor atinja 80% da capacidade de armazenamento, eu quero que um novo servidor seja adicionado, caso a média dos dois servidores estejam em 80% adicionar mais um.
•	Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (podendo também impor um limite de quantos eu desejo, e pode ser configurado para remover servidores, caso a média de ambos estejam em 35% desejo remover um servidor, dessa forma sempre estará com recursos disponíveis de acordo com a necessidade)
### CONFIABILIDADE
•	Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente.
•	Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo.
•	Existe a resiliência de ter um sistema que se recupera de falhas e continua funcionando.
•	Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.
### PREVISIBILIDADE
•	A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework




### SEGURANÇA
•	A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes, mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.
•	Se você quiser o controle máximo da segurança, a infraestrutura como serviços fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção
•	Quando falamos de segurança estamos associando o modelo que o nosso provider vai oferecer, quem faz o que etc.
•	Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você
•	Responsabilidade do Provider é oferecer recursos e serviços para atender a minha demanda, e a minha responsabilidade é aplicá-los.
### GOVERNANÇA
•	A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora da conformidade com seus padrões corporativos e fornece estratégias de mitigação. (Mitigação = Resolução de problemas)
•	Serve também para atribuir padrões de gestão dentro da nuvem (Como exemplo, existe algumas regiões do mundo no qual eu não quero que crie recursos pois não faz sentido para mim, então eu realizo o bloqueio desta ação independente da pessoa ou do nível de acesso. para manter a organização da minha empresa).
•	Esses padrões ou regras podem ser definidos pela própria empresa ou também para quem ela responde, por exemplo a indústria farmacêutica ou financeira exige alguns padrões e protocolos de segurança, outro exemplo é na hora de prestar um serviço a uma prefeitura ou governo, que também tem suas normas e exigências.
•	 Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.
•	Muito ligada a segurança, pois os padrões e protocolos de governança geralmente vem do que a área de segurança define.



### GERENCIABILIDADE
•	Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem e ambos trazem excelentes benefícios 
•	Escalar automaticamente a implantação de recursos com base na necessidade.
Ao criar recursos é possível utilizar o próprio portal ou até mesmo comandos, vai de acordo com a preferência do cliente, porém temos alguns exemplos que vale mais a pena a criação de ambientes ou serviços por meio de comandos, quando o ambiente é muito complexo e necessita de muitas especificações vale muito mais a pena através de comandos, seja pelo tempo economizado e para evitar erros humanos.
•	Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Por exemplo:
•	Por meio de um portal da web.
•	Usando uma interface de linha de comando.
•	Usando APIs.
•	Usando PowerShell.


# RESUMO DO MÓDULO 1
## Computação em Nuvem
A computação em nuvem é o fornecimento de serviços de computação pela internet. Um dos principais benefícios desse modelo é a flexibilidade — tanto de recursos, quanto de serviços e no aspecto financeiro.
Isso significa que você pode aumentar ou diminuir a capacidade de hardware de acordo com a necessidade, de forma manual ou automática, configurando previamente essas funções. Além disso, é possível contratar serviços por um período determinado, pagando apenas pelo que for realmente utilizado.
## Modelos de Nuvem
Existem três modelos principais de nuvem:
1.	Nuvem Privada:
o	A organização cria e gerencia seu próprio datacenter.
o	O ambiente é exclusivo, com maior controle e segurança.
2.	Nuvem Pública:
o	O oposto da nuvem privada.
o	Grandes provedores criam datacenters espalhados pelo mundo e oferecem serviços para qualquer cliente que queira (e possa) pagar.
o	É possível criar ambientes, armazenar e processar dados, além de usar diversos serviços pela internet.
3.	Nuvem Híbrida:
o	Combina o melhor dos dois mundos (privada e pública).
o	As duas nuvens se comunicam entre si e os aplicativos/serviços são executados no local mais adequado conforme a necessidade.
## Modelos de Custos
•	CapEx (Despesas de Capital)
o	Gasto inicial com infraestrutura física.
o	Esses ativos se desvalorizam com o tempo.
•	OpEx (Despesas Operacionais)
o	Pagamento conforme o uso de produtos e serviços.
o	Cobrança imediata, baseada no consumo.
Nos provedores de nuvem, o modelo é baseado no consumo. Ou seja, você paga apenas pelo que realmente utilizou, o que melhora a previsão de custos e torna a cobrança mais justa.
## Benefícios da Nuvem Azure
•	Alta disponibilidade
•	Escalabilidade
•	Elasticidade
•	Confiabilidade
•	Previsibilidade
•	Segurança
•	Governança
•	Gerenciabilidade
## Tipos de Serviços em Nuvem
1.	IaaS (Infraestrutura como Serviço)
o	Aluguel de servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais.
o	Modelo de pagamento conforme o uso.
2.	PaaS (Plataforma como Serviço)
o	Ambiente para criação, teste e implantação de aplicativos.
o	O foco é no desenvolvimento, sem se preocupar com a infraestrutura subjacente.
3.	SaaS (Software como Serviço)
o	Uso de aplicativos em nuvem diretamente pela internet.
o	Exemplos: Microsoft 365, e-mail e calendários.
## Responsabilidade do Usuário e do Provedor
Cada modelo de serviço (IaaS, PaaS e SaaS) exige níveis diferentes de responsabilidade tanto do usuário quanto do provedor. Quanto mais completo o serviço, menos o usuário precisa gerenciar diretamente.
