# Feminicídios no estado de São Paulo
Este repositório contém o projeto final da disciplina “Fundamentos e Ética do Jornalismo de Dados”, do Master em Jornalismo de Dados, Automação e Data Storytelling do Insper. 

O grupo é formado por Julianna Granjeia (@jugranjeia): juliannags@al.insper.edu.br; Leticia Godoy Nakoa (@leticiagnakao): leticia.godoy@hypr.mobi; Natali Carvalho (@natalicarvalho): natali.lima.carvalho@gmail.com e Sérgio Vieira (@SerginhoVN): serginho.vieira.rio@gmail.com.
A base de dados utilizada na análise é da SSP-SP (Secretaria de Segurança Pública do Estado de São Paulo). Filtramos pelo crime de feminicídios registrados entre 2015 e 2021.

SSP-SP: Clique aqui para ler e [baixar]([url](https://github.com/SerginhoVN/Trabalho-final-Natalia/blob/d2fdc3f50429eb3cdd7f013e2aa2171f05381a6e/Feminicidio_2015_2022%20(2).xlsx)) o arquivo.

Planilha completa pode ser encontrada [neste]([url](http://www.ssp.sp.gov.br/transparenciassp/Consulta.aspx)) link.

Utilizarmos o Google Sheets para a análise e tratamento dos dados e o Google Data Studio para visualizarmos e filtrarmos as informações por raça, profissão, local do crime etc.

Dashboard no Data Studio disponível [neste]([url](https://datastudio.google.com/u/0/reporting/6dad0246-220f-4ac7-a84b-6115a7eff2cf/page/uXd2C)) link.

**Contexto**

Uma [pesquisa]([url](https://www1.folha.uol.com.br/cotidiano/2016/08/1798729-em-sao-paulo-mulher-escolarizada-denuncia-mais-violencia-domestica.shtml)) realizada por uma magistrada do Tribunal de Justiça de São Paulo feita em 2016 com os dados de atendimento da vara de violência doméstica, da zona oeste da capital, apontou que 59% das vítimas que vão à Justiça são brancas (36% pardas e 5% negras), e 55% têm escolaridade mais alta.

Dados do [Anuário Brasileiro de Segurança Pública]([url](https://forumseguranca.org.br/wp-content/uploads/2022/06/anuario-2022.pdf?v=5)) de 2021 indicam que 37,5% das vítimas de feminicídio em todo o país são brancas e 62% são negras. Nas demais mortes violentas intencionais, contudo, 70,7% são negras e apenas 28,6% são brancas. 

“Em última instância, o que os dados nos indicam é uma possível subnotificação das negras enquanto vítimas de feminicídio. Demais estudos ainda devem ser realizados para aprofundar o fenômeno, entretanto, levanta-se a hipótese de que as autoridades policiais enquadram menos os homicídios de mulheres negras enquanto feminicídio. Ou seja, mais mulheres negras, mesmo sendo mortas pela condição de ser mulher, são incluídas na categoria de homicídio doloso e não feminicídio, o que parece acontecer menos com as mulheres brancas. Esta hipótese ganha força quando analisamos a mortalidade geral de mulheres por agressão ao longo da última década e verificamos que, se os assassinatos de mulheres brancas caíram, os de mulheres negras se acentuaram, aumentando a disparidade racial da violência letal”, afirma o relatório, corroborando nossa hipótese de subnotificação.

Com esses insights e os dados tratados da SSP-SP (Secretaria de Segurança Pública do Estado de São Paulo), foi possível concluir que as mulheres brancas estudantes são as que constam na maior parte dos boletins de ocorrências, totalizando 260 feminicídios (61,46%). O número de pardas e negras com esse tipo de assassinato registrado soma 159 (37,58%). 

O grupo, então, levantou a hipótese de que mulheres brancas com mais acesso à educação estão inseridas em famílias e comunidades que também possuem mais acesso à informação. Conseguindo, assim, que seus óbitos sejam registrados oficialmente. Enquanto que, como justificativa do número menor de registros de feminicídios de mulheres pretas e pardas, a hipótese é de que haja subnotificação, já que muitas mulheres negras se encontram em situação de vulnerabilidade social, fator analisado também pela profissão das vítimas.

Para investigar essa condição a fundo, pretendemos analisar se em outros estados do Brasil o caso de São Paulo - feminicídios de mulheres brancas estudantes ou com profissão ligada a uma maior escolaridade são mais registrados oficialmente - se repete. E se é possível concluir que o feminicídio de mulheres pardas e negras é subnotificado.

Para isso, também entrevistaremos pesquisadores do Fórum de Segurança Pública, responsável pelo anuário, para entender melhor essa situação.

**Perguntas que queremos responder: um roteiro de entrevista para aplicar a essa base de dados**

1) Qual a raça da maioria das mulheres que foram mortas em feminicídios registrados no estado de São Paulo durante o ano de 2021?
2) Qual a profissão da maioria das mulheres que foram mortas em feminicídios registrados no estado de São Paulo durante o ano de 2021?
3) É possível estabelecer alguma ligação entre profissões ou grau de escolaridade com as mulheres mortas por feminicídios? (donas de casa possuem mais registros desse tipo de morte do que estudantes/universitárias, por exemplo?)
4) Em qual mês há mais registro de BOs de feminicídios? (Para verificar se alguma data/evento/efeméride influi nessas ocorrências.)
5) Em qual local o crime é praticado com mais frequência? (casa, trabalho etc)

**O que aprendemos com os dados? Insights obtidos com a pré-análise do dashboard**

a) A partir da delimitação por raça, conseguimos concluir que a maioria dos boletins de ocorrência de feminicídios abertos entre 2015 e 2021 foram de vítimas brancas de 36 anos de idade.

b) O gráfico 3 do [dashboard]([url](https://datastudio.google.com/u/0/reporting/6dad0246-220f-4ac7-a84b-6115a7eff2cf/page/uXd2C)) mostra alguns dados interessantes sobre a profissão das mulheres assassinadas por homens. Entre as brancas, a maior da parte das vítimas de feminicídios aparecem como “prenda doméstica” (donas de casa), estudantes e aposentadas. Já entre as pretas e pardas, as vítimas eram donas de casa, estudantes e desempregadas. Profissões que aparecem entre brancas mortas e não constam entre pretas e pardas: vendedoras e comerciantes.

c) O percentual aproximado de mulheres brancas que eram estudantes, conforme os boletins de ocorrências, é de 14,23%. Enquanto que o número de pardas e negras, juntas, representam 12%.

d) Foi possível observar que, no período de 2015 a 2021, o último trimestre de todos os anos possuía o maior número de feminicídios em comparação com outros meses. Com isso, o grupo levantou a hipótese de que o alto número de boletins de ocorrência de feminicídio em dezembro pode ser em decorrência das festas de final de ano, momento em que as famílias ficam mais em casa e há grande consumo de bebidas alcoólicas neste período.

e) A casa (“residência” no dashboard) onde moram as mulheres é também o local onde ocorre a maior parte dos feminicídios. Vale destacar, também, que as favelas foram colocadas em outra categoria. Nossa análise é de que criaram esta categoria para que o poder público pudesse desenvolver políticas públicas voltadas especificamente para estas situações ou que menosprezam a favela e diferenciam de “residência”.

**Projeto Final: Entrevistando dados**

O objetivo do projeto final é demonstrar conhecimentos aplicados de entrevista a bases de dados utilizando planilha eletrônica e/ou SQL. Para isso, você deverá seguir os passos abaixo:

Escolha ao menos uma base de dados pública para trabalhar. Justifique em um parágrafo sua escolha, incluindo também informações básicas sobre a base (fonte, metodologia de coleta, data de atualização e limitações mais evidentes). Crie um roteiro de entrevista para aplicar a essa base de dados.

Documente as funções e cálculos aplicados para obter as respostas no github. Indique um caminho inicial de pauta que poderia ser explorado a partir dos insights obtidos.

Indique o(s) link(s) para a documentação do projeto no github.
