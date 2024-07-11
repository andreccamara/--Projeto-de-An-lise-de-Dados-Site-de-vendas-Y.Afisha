# Projeto de Análise Site de vendas

# Descrição do Projeto
Este projeto consiste em uma análise dos acessos ao site da Y.Afisha.  
A tarefa é ajudar a empresa a otimizar suas despesas com marketing.

# As tabelas são:
- Logs do servidor com dados sobre os acessos a Y.Afisha de janeiro de 2017 até dezembro de 2018
- Arquivo de despejo (ou dump file, em inglês) com todos os pedidos feitos durante o período
- Estatísticas de despesas com marketing

*as colunas criadas de logs são* 
- tempo'':tempo da seçao em segundos;
- u_p_dia, u_p_semana, u_p_mes: usuarios totais que usaram o site por dia, semana e mes;
- acesso1: data do primeiro acesso
- acesso1m: mes do primeiro acesso
*as de compras são:*
- acesso1, compra1: data do acesso e da compra	
- conversao: em qual dia foi realizada a compra, ontando do primeiro acesso
- compra1m, acesso1m: mes do primeiro acesso e da primeira compra

# Objetivos - analisar e responder:
- Como as pessoas usam o produto
        ◦ Quantas pessoas usam-no cada dia, semana e mês?
        ◦ Quantas sessões ocorrem por dia? (um usuário pode realizar várias sessões).
        ◦ Que comprimento tem cada sessão?
        ◦ Com que frequência os usuários voltam?
- Quando elas começam a comprar
- Quanto dinheiro cada cliente traz para a empresa
        ◦ Quantos pedidos os clientes fazem durante um determinado período de tempo?
        ◦ Qual é o volume médio de uma compra?
        ◦ Quanto dinheiro eles trazem para a empresa (LTV)?
- Quando as despesas serão cobertas
        ◦ Quanto dinheiro foi gasto? No total/por origem/ao longo do tempo
        ◦ Quanto custou a aquisição de clientes para cada origem?
        ◦ Os investimentos valeram a pena? (ROI)

# Ferramentas e Bibliotecas Utilizadas
- Python: Linguagem principal utilizada para a análise.
- Pandas: Biblioteca para manipulação e análise de dados.
- Matplotlib.pyplot, nunpy, seaborn: Biblioteca para criação de gráficos.

# Metodologia
- Importação e dados: Os dados foram importados das tabelas fornecidas para a analise.
- Tratamento dos dados: retirando valores irreais, linhas duplicadas, convertendo tipo.
- Análise Exploratória de Dados (EDA): Utilização de Pandas para exploração dos dados, criando colunas de valores agrupados, colunas de datas dia e mês. Divisão em coortes, analise de coortes.
- Criação de graficos ilustrativos
- Interpretação dos dados
- Recomendações a equipe de marketing

# Aprendizados
Este projeto permitiu-me desenvolver as seguintes habilidades:

- tratar os dados modificando tipos de colunas, valores irreais, linhas duplicadas
- modificar as tabelas de dados adicionando colunas do dia, mes e semana
- criar colunas de dados agrupados
- trabalhar com dados de datas realizando operações de deltatime, conversão para dias meses , 
- realização e analises de coortes
- construção de gráficos e mapas de calor para analisar as métricas
- Interpretação dos gráficos
- Calculos e interpretação dos parâmetro
- calcular ROI, LVT, CAC, ROMI
- apresentar recomendações aos especialistas de marketing 

# Como Executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal


## Contato:
Andre Corso Camara
[linkedin](https://www.linkedin.com/in/andre-corso-c%C3%A2mara/)
[email](devandrecorso@hotmail.com)