# DIO_AZ-104

Diretório para documentação de aprendizado do bootcamp da AZ-104 oferecido pela dio.me

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
	
Módulo 2
Administração de Governança e Conformidade
	2.1 Configurando Assinaturas do Azure
		* Introdução
			Identificar Regiões
				Verificar em images/02-01_Identificar Regiões.png (imagem pode estar desatualizada)
				Uma regiãorepresenta uma coleção de datacenters;
				Fornece flexibilidade e escala;
				Preservar a residência de dados;
				Selecioar regiões próximas de seus usuários;
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
		*
		
	2.3 Configurando o Controle de Acesso Baseado em Função
		*

Módulo 3
Administração dos Recursos
	3.1 Configurando Recursos do Azure com Ferramentas
	3.2 Configurando Recursos com Modelos ARM

Módulo 4
Administração de Rede Virtual
	4.1 Configurando Redes Virtuais
	4.2 Configurando Grupos de Segurança de Rede
	4.3 Configurando o DNS do Azure

Módulo 5
Administração de Conectividade entre Sites
	5.1 Configurando o Emparelhamento de VNet
	5.2 Configurando Pontos de Extremimdade e Roteamente de Rede
	
Módulo 6
Administração do Tráfego de Rede
	6.1 Configurando o Azure Load Balancer
	6.2 Configurando o Gateway de Aplicativo
	6.3 Configurando o Observador de Rede
	
Módulo 7
Administração do Azure
	7.1 Configurando Contas de Armazenamento
	7.2 Configurando Armazenamento de Blobs
	7.3 Configurando a Segurança de Armazenamento
	7.4 Configurando Arquivos do Azure

Módulo 8
Administração de Máquinas Virtuais do Azure
	8.1 Configurando Máquinas Virtuais no Azure
	8.2 Configurando a Disponibilidade da Máquina Virtual no Azure
	8.3 Gerenciando Máquinas Virtuais no Azure

Módulo  9
Administração de Opções de Computação PaaS
	9.1 Configurando Planos do Serviço de Aplicativo do Azure
	9.2 Configurando os Serviços de Aplicativos do Azure
	9.3 Configurando Instâncias de Cointêiner do Azure
	
Módulo 10
Administração de Projeto de Dados
	10.1 Configurando Backups de Arquivos e Pastas no Azure
	10.2 Configurando Backups da Máquina Virtual no Azure
	10.3 Desafios de Código: Aperfeiçoe Sua Lógica e Pensamento Computacional
	10.4 Associando Conceitos de Identidade, Rede e Armazenamento

Módulo 11
Administração de Monitoramente
	11.1 Configurando o Azure Monitor
	11.2 Configurando Alertas do Azure
	11.3 Configurando a Análise de Logs
	11.4 Implementando Monitoramento no Azure
	11.5 Simulando Preparatório para o Exame AZ-104
	11.6 Avalie este Bootcamp 2025
