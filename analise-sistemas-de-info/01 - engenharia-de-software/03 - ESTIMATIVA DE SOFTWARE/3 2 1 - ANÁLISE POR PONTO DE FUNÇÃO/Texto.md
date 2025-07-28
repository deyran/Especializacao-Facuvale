# Análise por ponto de função

A análise por Ponto de Função (APF) ou Function Point Analysis (FPA) configura-se como técnia voltada à medição da funcionalidades, dimensionando a complexidade de um Software por meio de processos aplicados ao tamanho do projeto, contudo, tendo por parâmetro o ponto de visão do usuário (PRESSMAN; MAXIM, 2016; VAZQUEZ et al., 2018).

Como os métodos de medição identificam e quantificam as qualidades existentes em um produto, em se tratando de Ponto de Função, tem-se um processo que mede os requisitos funcionais atribuíveis ao usuário em um software (histórias de usuário), ou seja, os requisitos de negócio, sem estabelecer atenção ao aspecto tecnológico, de plataforma e/ou linguagem, focando exclusivamente na ação direta da ferramenta desenvolvida (VAZQUEZ et al., 2018).

Como já especificado, considera-se como requisitos funcionais aqueles que expressam as ações do software ao ser aplicado na atividade do usuário, de modo que, caracterizam elementos aplicados ao processo de negócios da organização, podendo se fazer relacionados à transferência e armazenagem de dados (WAZLAWICK, 2013).

Deste modo, aos Pontos de Função, sendo os requisitos que passarão por medição, efetiva-se a atribuição de valores numéricos, os quais processados posteriormente, permitem identificar o esforço dispendido durante o desenvolvimento do software, pois em se tratando deste aspecto, amplia-se o entendimento considerando esforço, prazo, custo e demais parâmetros, o que pode em projetos de software respadar as conclusões acerca do seu tamanho e complexidade (WAZLAWICK, 2013; VAZQUEZ et al., 2018).

Nesta base, destaca-se os seguintes elementos dispostos abaixo na figura 7 como objetivo atribuíveis à Análise por Ponto de Função:

	1. Medir a funcionalidade solicitada pelo usuário
	2. Medir a funcionalidade efetivamente recebida pelo usuário
	3. Medir o desempenho do software independente da tecnologia de desenvolvimento
	4. Medir a manutenção do software independente da tecnologia de desenvolvimento

    Figura 7

Efetivando-se a Análise por Ponto de Função em atributos do sistema, aos quais compreende-se que seja os requisitos, o resultado alcançado pelo processo também pode se voltar as intenções que não estejam elencados na Figura 7, cabendo ainda para outros intentos como os apontados por meio da Figura 8.
	
	1. Melhorias em produção
		
		Após a efetivação de uma manutenção contabiliza-se as funcionalidades adicionais, alteradas e excluídas.

	2. Contagem em aplicação

		Aplicadas na contabilização de pontos de aplicação existentes.

	Figura 8

Para tal, o processo que envolve a Análise por Ponto de Função necessita seguir os parâmetros dispostos pela Figura 9:

	1. Simplicidade
		
		Pela necessidade do envolvido humano e manual no processo de análise de métrica, a simplicidade é essencial, de modo que o esforço seja minimizado, não onerando o projeto

	2. Consistência
		
		Pela possibilidade de haver mais de uma pessoa envolvida na análise, há de se identificar sistemáticas que garantam resultados semelhantes entre os avaliadores, denotando a qualidade da medição por meio de uma melhor e igualitária compreensão dos requisitos.

	3. Capacitação

		O medidor necessita possuir conhecimentos suficientes que o dotem para a ação que pretende efetivar sob o risco de que o processo se faça permeado de erros em face da ausência de uma formação consistente para tal

	Figura 9: Parâmetros ideais para a Análise por Ponto de Função

A contagem por ponto de função, visando sua posterior análise, efetiva-se de modo simplificado por meio da sistemática dispostas na Figura 10

- **CPF01 - Determinar**
	
	- Tipo de contagem e método CPF0101

- **CPF02 - Identificar**
	
	- CPF0101 -> Escopo e fronteira da aplicação CPF0201

- **CPF03 - Contar**

	- CPF0201 -> Função de dados CPF0301
	- CPF0201 -> Funções de trasações CPF0302

- **CPF04 - Ajustar**

	- CPF0301, CPF0302 -> Pontos a ajustar e ajustados 
	- CPF0101 -> Fator de ajuste
 
Figura 10: Sistemática de contagem de Pontos de Função

Neste contexto, em se tratando dos elementos destacados na sistemática simplificada presente no meio da Figura 11, tem-se de modo mais abragente um detalhamento de ações apresentados através do quadro 13.

- **Ação: Determinar**

	1. *Processo: Tipo de Contagem*
   
		- Projeto
		- Melhoria
		- Aplicação

	2. *Processo: Método*
	
		- Estimado
		- Detalhado 

- **Ação: Identificar**

	- *Processo: Escopo e fronteira da aplicação*

		- Limite entre sistema e usuário
		- Limite entre sistema e outra aplicação
		- Visão do usuário
		- Função de negócio
		- Independência de tecnologia
		- Manutenção

- **Ação: Contar**

	- *Processo: Funções de dados*
  
		- Arquivos Lógicos Internos (ALI)
		- Arquivos de Interface Externa (AIE)

	- *Processo: Funções de transações*

		- Entrada Externa (EE)
		- Consulta Externa (CE)
		- Saída Externa (SE)

- **Ação: Ajustar**

	- *Processo: Fator de Ajuste*
  
		- Atualização Online
		- Complexidade de Processamento
		- Comunicação de dados
		- Configuração Altamente utilizada

	- *Processo: Pontos a ajustar*

		- Eficiência de usuário final
		- Entrada de dados online
		- Facilidade de instalação
		- Facilidade de mudanças
		- Facilidade de operação
  
	- *Processo: Pontos ajustados*

		- Múltipas localidades
		- Performance
		- Processamento distribuído
		- Reutilização
		- Taxa de transações

	Quadro 13

Considerando a Figura 10 e o Quadro 13, e compreendendo que a dimensão dos requisitos funcionais do usuário recebe a denominação de tamanho funcional e que uma aplicação seja um composto de dados e procedimentos que sofreram automatização fornecendo suporte ao processo de negócio de acordo com a ação do usuário (VAZQUEZ et al. 2018) os Tipos de Contagem possíveis de efetivação na análise por ponto de função, seguem explicitados por meio da Figura 11.

> *Contagem de um projeto de desenvolvimento*

Permite, por meio da identificação do tamanho funcional do sistema, medir se as funcionalidades ofertadas ao usuário no projeto inicial permitem-se ser migradas em caso de ajustes futuro na ferramenta, pois é comum que, à medida que um sistema vai sendo utilizado os requisitos se tornam mais fáceis de compreensão permitindo que funcionalidades adicionais sejam identificadas durante o projeto, impactando no seu tamanho original.

> *Contagem de um projeto de melhoria*

Permite medir as funções adicionais, modificadas, excluídas e/ou convertidas do sistema pelo projeto

> *Contagem de uma aplicação*

Permite medir a funcionalidade fornecida aos usuários por meio de uma aplicação instalada, de modo a se identificar uma medida atualizada da funcionalidade que o usuário está fazendo utilização, tendo por parâmetro os dados coletados ao final do projeto em comparação com cada processo de melhoria.

Figura 11: Tipos de contagem em análise por ponto de função

Em se tratando do aspecto referente à Fronteira da Aplicação, tem-se a identificação dos limites entre o software e o mundo em que ele se faz inserido, seguindo os critérios de ponto de vista do usuário, a separação de funções, atribuídas aos negócios, e, em caso de projetos de melhoria, os aspectos já definidos devem ser reanalisados com intuito de verificar se existe a necessidade de adaptação (VAZQUEZ et al., 2018). Neste sentido, tem-se como aspectos facilitadores para a identificação das fronteiras de uma aplicação estes que se fazem citados na Figura 12.

  1. Identificar pela documentação de fluxo do sistema os elementos internos/externos
  2. Verificar como se efetiva manutenção dos dados
  3. Identificar as áreas funcionais por meio das entidades e processos do sistema
  4. Verificar se, por meio de outras métricas, os resultados alcançados em medição são os mesmos
  5. Reconhecer como ocorre o processo de gestão da aplicação
  6. Identificar a existência no sistema de ordens de serviço
  7. Compara o organograma da empresa com a estrutura de área e de sistemas.

  Figura 12: Aspectos que facilitam a identificação das Fronteiras de uma aplicação

Referindo-se ao escopo, tem-se a identificação de quais as funcionalidades a serem contadas por meio da sistemática escolhida, podendo incorporar todas as existentes, apenas aquelas que são utilizadas pelo usuário, ou ainda algumas em específico (VAZQUEZ er al., 2018).

Tem-se, deste modo, a identificação de quantos sistemas serão quantificados, definindo claramente onde começam e terminam (WAZLAWICK, 2013).

Por conseguinte, define-se o Tipo de Método, podendo, conforme Pressman e Maxim (2016) ser:

a) Estimado: Calcula os Pontos de Função de acordo com regras internacionalmente definidas no intuito de estimar as Funções de Dados (preferencialmente de complexidade baixa) e as funções de Transações (preferencialmente de complexidade média).

b) Detalhado: Efetiva a quantificação dos Pontos de Função com regras internacionalmente definidas no intuito de estimar as Funções de Dados e de Transação de acordo com as especificidades de caso.

Em relação à contagem/medição das funções de dados e de transação, identificar a natureza dos dados configura-se como o primeiro passo do processo, pois é justamente a partir dele que se reconhece as reais necessidades do usuário em relação ao negócio, assim como as funcionalidades previstas pelos usuários (VAZQUEZ et al., 2018; PRESSMAN; MAXIM, 2016; WAZLAWICK, 2013), sendo tais ações melhor especificadas por meio do Quadro 14.