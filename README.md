# Calculo-de-Moda-no-Power-BI
O Power BI não trás , como ferramenta "Built in", nativa, a função para realizar o calculo do dado estatístico de Moda de uma amostra. Essa foi a nossa solução.

Explicação do código:
	
	1. SUMMARIZE: Agrupa os valores únicos da coluna que você deseja analisar.
	
	2. ADDCOLUMNS: Adiciona uma coluna calculada que conta a frequência de cada valor.
	
	3. MAXX: Identifica o valor com a maior frequência.
	
	4. FILTER: Garante que apenas os valores com a frequência máxima sejam considerados.


Notas importantes:
	• Substitua Tabela pelo nome da sua tabela e Coluna pela coluna que você deseja analisar.
	• Se houver mais de um valor com a mesma frequência máxima, o DAX retornará apenas um deles (o maior ou menor, dependendo do contexto).

	
<img width="1379" height="184" alt="image" src="https://github.com/user-attachments/assets/4755a704-d2b4-45ac-912c-f225e6ef1d3c" />

