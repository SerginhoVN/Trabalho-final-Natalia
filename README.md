# Feminicídios no estado de São Paulo
Este repositório contém o projeto final da disciplina "Fundamentos e ética do jornalismo de dados", no Master em Jornalismo de Dados, Automação e Data Storytelling do Insper. 

O grupo é formado por Julianna Granjeia ([@jugranjeia](https://github.com/jugranjeia)): juliannags@al.insper.edu.br; Leticia Godoy Nakoa [(@leticiagnakao)](https://github.com/leticiagnakao): leticia.godoy@hypr.mobi; Natali Carvalho ([@natalicarvalho](https://github.com/natalicarvalho)): natali.lima.carvalho@gmail.com e Sérgio Vieira [(@SerginhoVN)](https://github.com/SerginhoVN): serginho.vieira.rio@gmail.com; 

A base de dados utilizada na análise é da SSP-SP (Secretaria de Segurança Pública do Estado de São Paulo). Filtramos pelo crime de feminicídios registrados entre 2015 e 2021.

SSP-SP: Clique [aqui](https://github.com/SerginhoVN/Trabalho-final-Natalia/blob/main/Feminicidio_2015_2022%20(2).xlsx) para ler e baixar o arquivo.
Planilha completa pode ser encontrada neste [link](http://www.ssp.sp.gov.br/transparenciassp/Consulta.aspx).

Utilizarmos o Google Sheets para a análise e tratamento dos dados e o Google Data Studio para visualizarmos e filtrarmos as informações por raça, profissão, local do crime etc.

**Contexto**

Uma pesquisa realizada por uma magistrada do Tribunal de Justiça de São Paulo feita em 2016 com os dados de atendimento da vara de violência doméstica, da zona oeste da capital, apontou que 59% das vítimas que vão à Justiça são brancas (36% pardas e 5% negras), e 55% têm escolaridade mais alta.

Dados do Anuário Brasileiro de Segurança Pública de 2021 indicam que 37,5% das vítimas de feminicídio em todo o país são brancas e 62% são negras. Nas demais mortes violentas intencionais, contudo, 70,7% são negras e apenas 28,6% são brancas. 

“Em última instância, o que os dados nos indicam é uma possível subnotificação das negras enquanto vítimas de feminicídio. Demais estudos ainda devem ser realizados para aprofundar o fenômeno, entretanto, levanta-se a hipótese de que as autoridades policiais enquadram menos os homicídios de mulheres negras enquanto feminicídio. Ou seja, mais mulheres negras, mesmo sendo mortas pela condição de ser mulher, são incluídas na categoria de homicídio doloso e não feminicídio, o que parece acontecer menos com as mulheres brancas. Esta hipótese ganha força quando analisamos a mortalidade geral de mulheres por agressão ao longo da última década e verificamos que, se os assassinatos de mulheres brancas caíram, os de mulheres negras se acentuaram, aumentando a disparidade racial da violência letal”, afirma o relatório, corroborando nossa hipótese de subnotificação.
 
Com esses insights e os dados tratados da SSP-SP (Secretaria de Segurança Pública do Estado de São Paulo), foi possível concluir que as mulheres brancas estudantes são as que constam na maior parte dos boletins de ocorrências, totalizando 260 feminicídios (61,46%). O número de pardas e negras com esse tipo de assassinato registrado soma 159 (37,58%). 

O grupo, então, levantou a hipótese de que mulheres brancas com mais acesso à educação estão inseridas em famílias e comunidades que também possuem mais acesso à informação. Conseguindo, assim, que seus óbitos sejam registrados oficialmente. Enquanto que, como justificativa do número menor de registros de feminicídios de mulheres pretas e pardas, a hipótese é de que haja subnotificação, já que muitas mulheres negras se encontram em situação de vulnerabilidade social, fator analisado também pela profissão das vítimas.

Para investigar essa condição a fundo, pretendemos analisar se em outros estados do Brasil o caso de São Paulo - feminicídios de mulheres brancas estudantes ou com profissão ligada a uma maior escolaridade são mais registrados oficialmente - se repete. E se é possível concluir que o feminicídio de mulheres pardas e negras é subnotificado.

Para isso, também entrevistaremos pesquisadores do Fórum de Segurança Pública, responsável pelo anuário, para entender melhor essa situação.

**Roteiro criado para aplicar a essa base de dados:**

a) Qual a raça da maioria das mulheres que foram mortas em feminicídios registrados no estado de São Paulo durante o ano de 2021?

b)  Qual a profissão da maioria das mulheres que foram mortas em feminicídios registrados no estado de São Paulo durante o ano de 2021?

c) É possível estabelecer alguma ligação entre profissões ou grau de escolaridade com as mulheres mortas por feminicídios? (donas de casa possuem mais registros desse tipo de morte do que estudantes/universitárias, por exemplo?)

d) Em qual mês há mais registro de BOs de feminicídios? (Para verificar se alguma data/evento/efeméride influi nessas ocorrências.)

e) Em qual local o crime é praticado com mais frequência? (casa, trabalho etc)

**O que aprendemos com os dados?**

a) A partir da delimitação por cor e raça, conseguimos concluir que a maioria dos boletins de ocorrência abertos entre 2015 e 2021 foram feitos por mulheres brancas de 36 anos de idade.

b) Os boletins de ocorrência estão ligados à educação, e portanto, à profissão (uma das variáveis disponíveis na base da SSP-SP para análise). Pois, observando no gráfico 3, as mulheres brancas, possuem opções como “estudante”, “comerciante” e “vendedora”, em destaque. Para as pardas e pretas, é possível observar um alto número de auxiliares de limpeza e balconistas ou secretárias. Chegamos, então, ao número de mulheres brancas que informaram no BO com a profissão “estudante”: 108.501. Enquanto o número de pardas e negras representam 60.480.

c) Na base de óbitos de mulheres por agressão no Brasil (SIM). É possível ver que no Sudeste, os casos de óbitos por mulheres pardas e negras foram, em média, 35% maiores do que para as brancas.
 
d) Foi possível observar que, no período de 2015 a 2021, o último trimestre dos anos possuía o maior peso em relação aos outros meses. Isso possibilitou o grupo a levantar a hipótese de que o número de boletins de ocorrência é em decorrência as festas de finais de ano, momento em que as famílias ficam mais em casa.

e) A maior parte dos Boletins de ocorrências registrados ocorrem no mês de dezembro, seguido de outubro e novembro, meses do quarto trimestre. As festas de Natal e Ano Novo, além da grande quantidade de confraternizações e feriados, podem contribuir com esse aumento, já que há grande ingestão de bebidas alcoólicas neste período.

f) Maciçamente, a residência é o onde ocorrem com mais frequência os crimes contra a mulher. Vale destacar que as favelas foram colocadas em outra categoria. Nossa análise é de que criaram esta categoria para que o poder público pudesse desenvolver políticas públicas voltadas especificamente para estas situações. 

**Projeto Final: Entrevistando dados**

O objetivo do projeto final é demonstrar conhecimentos aplicados de entrevista a bases de dados utilizando planilha eletrônica e/ou SQL. Para isso, você deverá seguir os passos abaixo:

Escolha ao menos uma base de dados pública para trabalhar. Justifique em um parágrafo sua escolha, incluindo também informações básicas sobre a base (fonte, metodologia de coleta, data de atualização e limitações mais evidentes). Crie um roteiro de entrevista para aplicar a essa base de dados.

Documente as funções e cálculos aplicados para obter as respostas no github.
Indique um caminho inicial de pauta que poderia ser explorado a partir dos insights obtidos.

Indique abaixo o(s) link(s) para a documentação do projeto no github

https://github.com/SerginhoVN/Trabalho-final-Natalia

https://github.com/SerginhoVN/Trabalho-final-Natalia/blob/main/Feminicidio_2015_2022%20(2).xlsx
