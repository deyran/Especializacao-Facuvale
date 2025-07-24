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