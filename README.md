DIO_AZ-104

Diretório para documentação de aprendizado do bootcamp da AZ-104 oferecido pela dio.me



##############################################################################
Módulo 1
Administração de Identidade
	1.1 Introdução
		* Foi apresentado pelo Felipe Aguiar o curso e a importância de aprofundar-se em cloud e do administrador do Azure
			- Responsabilidades do Administrador
				Gerenciar os acessos
				Monitorar
				Movimentar backups
				Garantir custos controlados
				
			- Habilidades
				Identificar gargalos
				Otimização
				Preocupação dos acessos e preocupação com segurança
		* Apresentado o curso de modo geral do bootcamp, apresentando os módulos sem aprofundamento, instigando a continuidade do curso
		
		
	1.2 Configurando o Microsoft Entra Identidade
		* Apresentação da Valéria Baptista
			Mentora altamente qualificada
		
		* Apresentação mais detalhada do curso
			Reforça a intensidade do curso, conteúdo complexo e denso, prova de peso, certificação que exige certa experiência

		* Habilidades Medidas
			Repassados habilidades que são exigidas no exame e o percentual equivalente
		
		* Objetivo e Pré-requisitos
			Administrador do Azure e a necessidade de ter conhecimento do ambiente
		
		* Apresentação do conteúdo programático
			11 módulos
			Curso com base no curso oficial da Microsoft
		
		* Configurar o Microsoft Entra ID
			Descrever os benefícios e recursos do Microsoft Entra ID
				Verificar em images/01-02_Benefícios e Recursos do Entra ID.png
			Descrever confeitos do Microsoft Entra ID
				Verificar em images/01-03_Conceitos do Entra ID.png
			Comparar o Microsoft Entra ID com o Active Directory Domain Services
				O Entra ID é principalemnte uma solução de identidade
				Usa protocolos HTTP e HTTPS
				Incluí serviços de federação e muitos serviços de terceiros (como facebook)
				São criados em estrutura plana e não existem unidades organizacionais ou objetos de grupos (GPOs)
				
				Selecionar planos de preços do Microsoft Entra ID
				Gratuita, P1, P2 e Governança
				Verificar em images/01-04_Planos e Preços.png
				
			Configurar Identidades de Dispositivo
				Dispositivos Registrados
				Dispositivos Associados
				Dispositivos híbridos
			Implementar a Redefinição de Senha por Autoatendimento
				SSPR
				Verificar em images/01-05_Implementando o SSPR.png
	1.3 Configurando Contas de Usuário e de Grupo
		Apresentação do Laboratório com o conteúdo apresentado até o momento
##############################################################################



##############################################################################
Módulo 2
Administração de Governança e Conformidade
	2.1 Configurando Assinaturas do Azure
		* Introdução
			Identificar Regiões
				Verificar em images/02-01_Identificar Regiões.png (imagem pode estar desatualizada)
				Uma regiãorepresenta uma coleção de datacenters;
				Fornece flexibilidade e escala;
				Preservar a residência de dados;
				Selecionar regiões próximas de seus usuários;
				Esteja ciente da disponibilidade de implatnação da região;
				Há serviços globais que são independetes da região;
				As regiões são emparelhadas para alta disponibilidade.
			
			- Implementar assinaturas
				Verificar em images/02-02_Implementar Assinaturas.png
				Somente identidades no Azure AD ou em um diretório confiável pelo Azure AD podem criar assinaturas;
				A unidade lógica de serviços do Azure que está vinculada a uma conta do Azure.
			
			- Criar Grupos de Recursos
				Verificar em images/02-03_Criar Grupos de Recursos.png
				Os recursos somente podem existem em um grupo de recursos;
				Os grupos podem ter recurso de muitos tipos diferentes;
				Os grupos não podem ser renomeados ou aninhados;
				Podemos mover recursos entre grupos;
			
			- Cotas e Limites de Serviço
			Verificar em images/02-04_Cotas e Limites de Serviço.png
			Os recursos têm um limite padrão - uma cota de assinatura;
			Útil para acompanhar o uso atual e planejar o uso futuro;
			Podemos abrir um caso de suporte gratuito para aumentar os limits para máximos publicados.
			
			- Hierarquia de Recursos no Azure
			Verificar em images/02-05_Hierarquia de Recursos no Azure.png
			Os grupos de gerenciamento do Azure fornecem um nível de escopo sobre assinaturas;
			Direcionamento de políticas e gastos de orçamentos entre assinaturas e herança nas hierarquias;
			Implementar relatórios de conformidade e custos por organização (empresas/equipes).
			
			- Marcação de Recursos
			Verificar em images/02-06_Marcação de Recursos.png
			
			- Gerenciar Custos
			Verificar em images/02-07a_Gerenciar Custos.png
			Verificar em images/02-07b_Gerenciar Custos.png
			
			- Laboratório
			
	2.2 Configurando o Azure Policy
		* Implementar Políticas do Azure
			Usar serviço para criar, atribuir e gerenciar políticas;
			Executar avaliações e varreduras em busca de recursos;
			Vantagens:
				Imposição e conformidade;
				Aplicar políticas em escala;
				Remediação.
			
			Implementar Políticas do Azure
			Verificar em images/02-08_Implementar Políticas do Azure.png
			
			Criar políticas do Azure
			Verificar em images/02-09_Criar Políticas do Azure.png
			
			Laboratório
					
		
	2.3 Configurando o Controle de Acesso Baseado em Função
		* Laboratório
##############################################################################


##############################################################################
Módulo 3
Administração dos Recursos
	3.1 Configurando Recursos do Azure com Ferramentas
	Verificar em images/03-01_Portal do Azure.png
	Verificar em images/03-02a_Azure Cloud Shell.png
	Verificar em images/03-02b_Azure Cloud Shell.png
	Verificar em images/03-02c_Azure Cloud Shell.png
	Verificar em images/03-02d_Azure Cloud Shell.png
	Verificar em images/03-02e_Azure Cloud Shell.png
	Verificar em images/03-02f_Azure Cloud Shell.png
	Verificar em images/03-02g_Azure Cloud Shell.png
	Verificar em images/03-02h_Azure Cloud Shell.png
	Verificar em images/03-02i_Azure Cloud Shell.png
	Verificar em images/03-02j_Azure Cloud Shell.png
	Laboratório
	
	3.2 Configurando Recursos com Modelos ARM
	Laboratório
##############################################################################


##############################################################################
Módulo 4
Administração de Rede Virtual
	4.1 Configurando Redes Virtuais
		Planejar Redes Virtuais;
			Verificar em images/04-01_Planejar Redes Virtuais.png
			Representação lógica da sua própria rede;
			Criar uma rede virtual dedicada somente de nuvem privada;
			Ampliar o data center com redes virtuais de modo seguro;
			Habilitar cenários de nuvem híbrida.
		
		Criar Sub-redes;
			Verificar em images/04-02_Criar Sub-redes.png
			Uma rede virtual pode ser segmentada em uma ou mais sub-redes;
			As sub-redes podem ajudar a aprimorar a segurança, aumentar o desempenho e facilitar o gerenciamento da rede;
			As sub-redes fornecem divisões lógicas dentro da rede;
			Cada sub-rede deve ter um intervalo de endereços exclusivos - não pode se sobrepor a outras sub-redes na vnet na assinatura.
			
		Planejar o Endereçamento IP.
			Verificar em images/04-03_Planejar Endereçamento IP.png
			Endereços IP públicos
			Verificar em images/04-04a_Criar Endereço IP público.png
				Disponníel em IPv4 ou IPv6 ou ambos
				SKU Básico vs Standard
				Dinamico vs EStatico
				Microsoft vs roteamento da Internet
				Verificar em images/04-04b_Criar Endereço IP público.png
			Endereços IP privados
			Verificar em images/04-05_Atribuir Endereço IP privado.png
				Dinâmico (padrão)
				Estático
			Laboratório
			
	4.2 Configurando Grupos de Segurança de Rede
		NSGs (Network Security Groups)
			Verificar em images/04-06_Implementar NSGs.png
			Limita o tráfego de rede a recursos em uma rede virtual
			Lista as regras de segurança que permitem ou negam o tráfego de entrada ou saída
				A regra de negação vem primeiro
			Associado a uma sub-rede ou a uma interface de rede
			Pode ser associado várias vezes
		Criar regras NSG
			Origem
			Destino
			Verificar em images/04-07_Criar regras NSG.png
			*Quanto menor o número maior a prioridade (inicia em 100)*
		Implementar ASGs (Application Security Group)
			Verificar em images/04-08_Implementar ASG.png
			Amplia a estrutura do aplicativo
			Os ASGs agrupam logicamente máquinas virtuais - servidores web, servidores de aplicativos
			Definir regras para fluxo de tráfego
			Envolva o ASG com um NSG para maior segurança
			Laboratório
			
	4.3 Configurando o DNS do Azure
		Laboratório com o conteúdo do módulo
		
##############################################################################



##############################################################################
Módulo 5
Administração de Conectividade entre Sites
	5.1 Configurando o Emparelhamento de VNet
		Verificar em images/05-01_Determinar Usos de Emparelhamento VNet.png
		Temos dois modelos de peering: Global e Regional;
		Conecta duas redes virtuais do Azure - posso emparelhar entre assinaturas e locatários;
		As redes emarelhadas usam o backbone do Azure para privacidade e isolamento;
		Fácil de configurar, transfêrencia de dados perfeita e ótimo desempenho.
		
		Trânsito de Gateway e as Necessidades de Conectividade
		Verificar em images/05-02_Trânsito de Gateway e as Necessidades de Conectividade.png
		O trânsito de gateway permite que as redes virtuais emparelhadas compartilhem o gateway e tenham acesso a recursos;
		Nenhum gateway VPN é necesário na rede virtual spolke emparelhada;
		O emparelhamento de VNet padrão fornece conectividade total;
		Os espaços de endereço  IP de redes conectadas não podem se sobrepor.
		
		Criar Emparelhamento VNet
		Verificar em images/05-03_Criar Emparelhamento VNet.png
		Permitir configurações de acesso de rede virtual;
		Definir configurações de tráfego encaminhado;
		O status deve mostrar "conectado";
		
		Usos do Encadeamento de Services
		Verificar em images/05-04_CUsos do Encadeamento de Services.png
		Implementar um hub VNet com um dispositivo virtual de rede ou um gateway VPN;
		O encadeamento de serviços permite que eu direcione o tráfego de uma rede virtual para uma solução de virtualização, ou um gateway de rede virtual ematelhada através de rotas definidas pelo usuário;
		Laboratório
		
	5.2 Configurando Pontos de Extremimdade e Roteamente de Rede
		Laboratório
##############################################################################



##############################################################################
Módulo 6
Administração do Tráfego de Rede
	6.1 Configurando o Azure Load Balancer
		Verificar em images/06-01_Balanceador de Carga.png
		Verificar em images/06-02_Balanceador de Carga Pública.png
		Verificar em images/06-03_Determinar SKus.png
			Familias
		Verificar em images/06-04_Balanceador de Carga Interno.png
		
		Regras para o balanceador de carga
		Verificar em images/06-05_Regras para o balanceador de carga.png
			Uma regra NAT é explicitamente anexada a uma BM (ou interface de rede) para concluir o caminho para o destino;
			Mapeia uma combinação de porta e IP de front-end e combinação de portas;
			As regras podem ser combinadas com regras NAT.
		
		Configurar sessão persistente
		Verificar em images/06-06_Configurar sessão persistente.png
			A persistência da sessão especifica como o tráfego do cliente é tratado;
			Nenhuma solicitação (padrão) pode ser tratada por qualquer máquina virtual;
			As solicitações de IP do cliente serão tratadas pela mesma máquina virtual;
			O IP e o protocolo do cliente especificam que solicitações sucessivas do mesmo endereço e protocolo serão tratadas pela mesma máquina virtual.
			Laboratório
					
	6.2 Configurando o Gateway de Aplicativo
		Verificar em images/06-07_Implantar o Gw de Aplicativo.png
		Verificar em images/06-08_Roteamento do Gw de Aplicativo.png
		Verificar em images/06-09_Componenentes do Gw de Aplicativo.png
			Frontend IP
			Liseners
			Routing rules
			Backend pools
			Web application firewall (opcional)
			Health probes
		Laboratório
		
	6.3 Configurando o Observador de Rede
		Laboratório
	
##############################################################################



##############################################################################
Módulo 7
Administração do Azure
	7.1 Configurando Contas de Armazenamento
		Verificar em images/07-01_Serviços de Armazenamento do Azure.png
			Contêineres do Azure: um repositório de objetos altamente escalonável para texto e dados binários
			Tabelas do Azure: ideias para armazenar dados estruturados não relacionais
		Verificar em images/07-02_Tipos de Contas de Armazenamento.png
		Verificar em images/07-03_Estratégias de Replicação LRS.png
		Verificar em images/07-04_Estratégias de Replicação ZRS.png
		Verificar em images/07-05_Estratégias de Replicação GRS.png
		Verificar em images/07-06_Estratégias de Replicação RA-GRS.png
		Verificar em images/07-07_Estratégias de Replicação GZRS.png
		Verificar em images/07-08_Estratégias de Replicação RA-GZRS.png
		Verificar em images/07-09_Armazenamento de Acesso.png
		Verificar em images/07-10_Pontos de Extremimdadeda de Armazenamento Seguro.png
			Os Firewalls e as Redes Virtuais restringem o acesso à Conta de Armazenamento de sub-redes específicas em Redes Virtuais ou IPs públicos;
			As sub-redes e as Redes Virtuais devem existir na mesma Região do Azure ou Par de Regiões que a Conta de Armazenamento.
		Laboratório
		
	7.2 Configurando Armazenamento de Blobs
		Verificar em images/07-11a_Armazenamento de Blobs.png
			Ele também é chamado de armazenamento de objetos;
			Armazena dados não estruturados na nuvem;
			Pode armazenar qualquer tipo de dados binários ou de texto.
			
			Usos comuns:
				Fornecer imagens ou documentos diretamente a um navegador;
				O armazenamento de arquivosa para acesso distribuído;
				Transmitir áudio e vídeo por streaming;
				O armazenamento de dados para backup e restauração, recuperação de desastre e arquivamento;
				O armazenamento de dados para análise por um serviço local ou hospedado no Azure.
		Verificar em images/07-12a_Criar Contêineres de Blobs.png
		Verificar em images/07-12b_Criar Contêineres de Blobs.png
			Todos os blobs devem estar em um contêiner;
			As contas têm contêineres ilimitados;
			Os contêineres podem ter blobs ilimitados;
			Restringir o acesso usando o nível de acesso público.
		Verificar em images/07-13_Camadas de Acesso de Blobs.png
			Camadas de acesso de blobs
				Camada de acesso frio: dados acessados ou modificados com pouca frequência, armazenados por pelo menos 90 dias;
				Camada de arquivos: uma camada offline otimizada para armazenar dados acessados raramente, mínimo de 180 dias;
		Verificar em images/07-14_Ciclo de Vida de Blobs.png
			Transição de blobs para um nível de armazenamento mais frio para otimizar o desempenho e o custo;
			Aplicar regras a caminhos filtrados na conta de Armazenamento;
			Excluir os blobs no final do ciclo de vida.
		Verificar em images/07-15_Replicação de Objetos do Blobs.png
			Assíncrono para qualquer outra Região;
			Minimiza a latência para solicitações de leitura;
			Aumento da eficiência ddas cargas de trabalho de computação;
			Otimização da distribuição de dados;
			Otimiza os custos.
		Laboratório
		
	7.3 Configurando a Segurança de Armazenamento
		Estratégias de Segurança de Armazenamento
			Criptografia do Serviço de Armazenamento
			Autenticação com Azure AD e RBAC
			Criptografia do lado do cliente, HTTPS e SMB 3.0 para dados em trânsito
			Criptografia de disco do Azure
			Acesso anônimo a contêineres e blobs
		Verificar em images/07-16a_Assinaturas de Acesso Compartilhado.png
		Verificar em images/07-16b_Assinaturas de Acesso Compartilhado.png
		Parâmetros de URI e SAS
			Uma SAS e um URI assubadi que aponta para um ou mais recursos de armazenamento
			Composto por um URI do recurso de armazenamento e o token de SAS
		Verificar em images/07-17_Parâmetros de URI e SAS.png
		Laboratório
		
	7.4 Configurando Arquivos do Azure
		Verificar em images/07-18_Comparar ARquivos com Blobs.png
		Verificar em images/07-19_Gerenciar Compartilhamento de Arquivos.png
			Atenção: Porta 445 deve estar aberta (costuma cair no exame)
		Verificar em images/07-20_Serviço de Importação e Exportação.png
		
		AzCopy
		
		Laboratório
	
##############################################################################



##############################################################################
Módulo 8
Administração de Máquinas Virtuais do Azure
	8.1 Configurando Máquinas Virtuais no Azure
	Responsabilidades dos Serviços de Nuvem
		Verificar em images/08-01_Responsabilidades dos Serviços de Nuvem.png
	
	Planejar máquinas virtuais
		Começar com a rede
		Nomear a máquina virtual
		Escolher um local
			Cada região tem recursos de hardware e serviço diferentes
			Localize as máquinas virtuais mais proximo possível de seus usuários e garanta a conformidade e as obrigações legais
			Considere os preçõs
		Verificar em images/08-02_Dimensionamento da Máquina Virtual.png
		Verificar em images/08-03_Armazenamento da Máquina Virtual.png
		Laboratório
	
	8.2 Configurando a Disponibilidade da Máquina Virtual no Azure
		Planejar Manutenção e o Tempo de Inatividade
		Configurar Conjuntos de Disponibilidade
			Combinar um Balanceador de Carga com os conjutos de disponibildiades
			Usar discos gerenciados com as máquinas virtuais
		Domínios de Falha e Autalização
		Verificar em images/08-04_Domínios de Falha e Autalização.png
		Examinar Zonas de Disponibilidade
		Verificar em images/08-05_Examinar Zonas de Disponibilidade.png
			Locais físicos exclusivos em uma região
			Proteção contra falhas no datacenter
			Incluir datacenters com alimentação, resfriamento e rede independentes
			Combina domínios de atualização e falha
			Fornece um SLA de 99,99%
		Escala Vertical e Horizontal
			Verificar em images/08-06a_Escala Vertical e Horizontal.png
			Verificar em images/08-06b_Escala Vertical e Horizontal.png
		Laboratório
	
	8.3 Gerenciando Máquinas Virtuais no Azure
		Laboratório
	
	
	
	
##############################################################################



##############################################################################
Módulo  9
Administração de Opções de Computação PaaS
	9.1 Configurando Planos do Serviço de Aplicativo do Azure
	Planos do Serviço de Aplicativo do Azure
		Determina o desempenho, o preço e os recursos
		Define um conjunto de recursos de computação para um aplicativo Web ser executado
		A região em que recursos de computação serão criados
		Números de instâncias de máquinas virtuais
		Tamanho das instâncias de máquina virtual
			Um ou mais aplicativos podem ser configurados para execução do mesmo plano do Serviço de Aplicativo
		Verificar em images/09-01_Planos do Serviço de Aplicativo.png
		Computação compartilhada
		Computação deditacada
		Isoladas
		
		Escalar vertial de horizontalmente
		Laboratório
	
	9.2 Configurando os Serviços de Aplicativos do Azure
		Verificar em images/09-02_Serviço de Aplicativos do Azure.png
			Produtividade do desenvolvedor usando .NET, .NET Core, Java, Python etc
			Fornece segurança e conformidade de nível empresarial
			
		Linux cou Windows
		A região mais próxima dos usuários
		Plano de servido de aplicativo
		
		Criar Slots de Implantação
		Verificar em images/09-03_Criar Slots de Implantação.png
			Plano -> slots
			Gratuito, Compartilhado, Básico -> 0
			Standard -> até 5
			Premium -> até 20
			Isolado -> até 20
			
		Beneficios e recursos do Entra ID
		Adicionar Slots de Implantação
		
		Proteger um Serviço de Aplicativo
			Autenticação
			Segurança
	
		Laboratório
	
	9.3 Configurando Instâncias de Contêiner do Azure
		Máquinas Virtuais e Contêineres
		Verificar em images/09-04_Máquinas Virtuais e Contêineres.png
			Isolamento
			Sistema Operacional
			Implantação
			Armazenamento persistente
			Tolerância a falhas
		Instâncias de Contêineres
		Verificar em images/09-05_Instâncias de Contêineres.png
			Serviço PaaS
			Inicialização mais rápida
			Conectividade de IP público e nome DNS
			Isolamento de recursos
			Tamanhos personalizados
			Armazenamento persistente
			Contêineres do Windows e do Linux
			Grupos Coagendados
			Implantação da Rede virtual
		Grupos de Contêineres
			Recurso de nível superiro em instâncias de Contêiner do Azure
			Uma coleção de contêineres que são agendados no mesmo host
			Os contêineres no grupo compartilham ciclo de vida, recursos, rede local e volumes de armazenamento
		Verificar em images/09-06_Plataforma Docker.png
			Permite que os desenvolvedores hospedem aplicativos em um contêiner
			Disponível no Linux e no Windows e pode ser hospedado no Azure
			Um contêiner é uma "unidade de software" padronizada que contem tudo o que é necessário para que um aplicativo seja executado.
		Gerenciar Contêineres
		Verificar em images/09-07_Gerenciar Contêineres.png
		Verificar em images/09-08_Azure Kubernetes Service.png
			Gerencia o monitoramnto e a manutenção da intensidade
			Executa escalonamento de cluster simples
			Permite que os nós sejam totalmente gerenciados pela Microsoft
			Você é responsável apenas por gerenciar os nós do agente
			Paga-se apenas pelos nós do agente
		Verificar em images/09-09_AKS Terminologia.png
		
		Laboratório
##############################################################################



##############################################################################
Módulo 10
Administração de Projeto de Dados
	10.1 Configurando Backups de Arquivos e Pastas no Azure
	10.2 Configurando Backups da Máquina Virtual no Azure
	10.3 Desafios de Código: Aperfeiçoe Sua Lógica e Pensamento Computacional
	10.4 Associando Conceitos de Identidade, Rede e Armazenamento
##############################################################################



##############################################################################
Módulo 11
Administração de Monitoramente
	11.1 Configurando o Azure Monitor
	11.2 Configurando Alertas do Azure
	11.3 Configurando a Análise de Logs
	11.4 Implementando Monitoramento no Azure
	11.5 Simulando Preparatório para o Exame AZ-104
	11.6 Avalie este Bootcamp 2025
##############################################################################
