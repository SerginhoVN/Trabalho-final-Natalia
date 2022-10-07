# Feminicídios no estado de São Paulo
Este repositório contém o projeto final da disciplina "Análise exploratória de dados", no Master em jornalismo dados, automação e data storytelling do Insper. Este documento faz uma análise de Boletins de Ocorrências relacionados à feminicídios com base no cruzamento de dados da Secretaria de Segurança Pública de São Paulo e o SIM (Sistema de Informação de Mortalidade) do Ministério da Saúde (Dataset)

O grupo é formado por Julianna Granjeia ([@jugranjeia](https://github.com/jugranjeia)): Jugranjeia@gmail.com; Leticia Godoy Nakoa [(@leticiagnakao)](https://github.com/leticiagnakao): leticia.godoy@hypr.mobi; Natali Carvalho ([@natalicarvalho](https://github.com/natalicarvalho)): xxxxxxx e Sérgio Vieira (@SerginhoVN): serginho.vieira.rio@gmail.com; 

**Um breve relato sobre nossa tese**

A morte de mulheres no Brasil tem índices alarmantes e, a cada dia, ganham as manchetes de jornais e telejornais com mais frequência. Para ter uma ideia correta desses assassinatos é preciso conhecer o cenário e as circuntâncias que estes crimes ocorrem para se fazer um bom diagnóstico do feminicídio. São muitos os viéses existentes e, inicialmente, para fazer este levantamento, cruzamos as informações de idade, profissão e cor da pele de mulheres que registraram boletim de ocorrência no estado de São Paulo durante o ano de 2021 com o número de mortes de mulheres por agressão registradas pelo SIM no mesmo período. 

A primeira tese que queremos levantar e/ou confirmar com os dados que poderemos tirar dessa coleta é se mulheres negras são as que mais registram BOs. Também testamos se há alguma correlação entre o tipo de profissão e escolaridade com agressão/feminicídio.

**Base de Dados Utilizadas**

**SSPSP - CSV**  - Clique aqui para ler e baixar o arquivo.

Planilha completa pode ser encontrada [neste link](https://basedosdados.org/dataset/feminicidio-sp?external_link=Feminicidio+ocorridos+no+Estado+de+SP)

**SIM - CSV** - Clique aqui para ler e baixar o arquivo.

Planilha completa pode ser encontrada [neste link](https://opendatasus.saude.gov.br/dataset/sim-2020-2021/resource/904b9632-171f-4b06-8f09-26a6bf590b1b)

**Roteiro criado para aplicar a essa base de dados:**

a) O número de BOs registrados por mulheres no estado de São Paulo durante o ano de 2021 é maior entre qual raça?

b) O número de BOs registrados por mulheres no estado de São Paulo durante o ano de 2021 é maior entre qual profissão?

c) É possível estabelecer alguma ligação entre profissões ou grau de escolaridade com o número de BOs? (donas de casa registram mais ou menos boletins de ocorrência por agressão do que estudantes/universitárias, por ex?)

d) É possível correlacionar o número de mortes de mulheres registradas no SIM com alguma variação disponível na base de dados da SSP?

e) Em qual mês há mais BOs? (Para verificar se alguma data/evento/efeméride influi nessas ocorrências.)

f) Em qual local o crime é praticado com mais frequência? (casa, trabalho etc)

**O que aprendemos com os dados?**

a) A partir da delimitação por cor e raça, conseguimos concluir que a maioria dos boletins de ocorrência abertos entre 2015 e 2021 foram feitos por mulheres brancas de 36 anos de idade.

b) Os boletins de ocorrência estão ligados à educação, e portanto, à profissão (uma das variáveis disponíveis na base da SSP-SP para análise). Pois, observando no gráfico 3, as mulheres brancas, possuem opções como “estudante”, “comerciante” e “vendedora”, em destaque. Para as pardas e pretas, é possível observar um alto número de auxiliares de limpeza e balconistas ou secretárias. Chegamos, então, ao número de mulheres brancas que informaram no BO com a profissão “estudante”: 108.501. Enquanto o número de pardas e negras representam 60.480.

c) Na base de óbitos de mulheres por agressão no Brasil (SIM). É possível ver que no Sudeste, os casos de óbitos por mulheres pardas e negras foram, em média, 35% maiores do que para as brancas.
 
d) Foi possível observar que, no período de 2015 a 2021, o último trimestre dos anos possuía o maior peso em relação aos outros meses. Isso possibilitou o grupo a levantar a hipótese de que o número de boletins de ocorrência é em decorrência as festas de finais de ano, momento em que as famílias ficam mais em casa.

e) A maior parte dos Boletins de ocorrências registrados ocorrem no mês de dezembro, seguido de outubro e novembro, meses do quarto trimestre. As festas de Natal e Ano Novo, além da grande quantidade de confraternizações e feriados, podem contribuir com esse aumento, já que há grande ingestão de bebidas alcoolicas neste período. 

f) Maciçamente, a residência é o onde ocorrem com mais frequência os crimes contra a mulher. Vale destacar que as favelas foram colocadas em outra categoria. Nossa análise é de que criaram esta categoria para que o poder público pudesse desenvolver políticas públicas voltadas especificamente para estas situações. 

**Análise e Conclusão**

A primeira análise realizada pelo grupo foi a partir da variável “Cor/Raça”. Observamos que a maioria dos boletins de ocorrência abertos em 2021 foram provenientes de mulheres brancas de 36 anos de idade. Esta informação guiou grande parte da pesquisa, de forma que também nos indagamos, não somente sobre boletins de ocorrência (BO), mas o número de óbitos registrados oficialmente dessas mulheres.

Pesquisa realizada por uma magistrada do Tribunal de Justiça de São Paulo em 2016 com os dados de atendimento da vara de violência doméstica da zona oeste da capital apontou que 59% das vítimas que vão à Justiça são brancas (36% pardas e 5% negras), e 55% têm escolaridade mais alta.

O grupo, então, levantou a hipótese de que o número de B.Os estaria diretamente ligado à educação e ao acesso de informação, e portanto, à profissão (uma das variáveis disponíveis na base da SSP-SP para análise).

Dessa forma, mesmo que o gráfico 3 de profissão categorizado por raça partilhe as mesmas categorias para todas as estudadas, é possível observar a variedade entre elas. Para mulheres brancas há opções como “estudante”, “comerciante” e “vendedora”, em destaque. Para as pardas e pretas, é possível observar um alto número de auxiliares de limpeza e balconistas ou secretárias. 

Chegamos, então, ao número de mulheres brancas que informaram no BO com a profissão “estudante”: 108.501. Enquanto o número de pardas e negras representam 60.480.
Para que fosse possível entender mais sobre o caso de boletins de ocorrência baseado em demografia, o grupo obteve acesso à base de óbitos de mulheres por agressão no Brasil (SIM). Nele é possível ver que no Sudeste, os casos de óbitos por mulheres pardas e negras foram, em média, 35% maiores do que para as brancas. 
Portanto, o grupo consegue concluir que o acesso à informação têm salvado mulheres ao longo dos anos.

**DASHBOARD** - [Clique aqui](https://github.com/SerginhoVN/Trabalho-final-Natalia/blob/main/Dashboard_A201331189_28_143_208) para ver a análise dos Feminicídios 

**Projeto Final: Entrevistando dados**

O objetivo do projeto final é demonstrar conhecimentos aplicados de entrevista a bases de dados utilizando planilha eletrônica e/ou SQL. Para isso, você deverá seguir os passos abaixo:

Escolha ao menos uma base de dados pública para trabalhar. Justifique em um parágrafo sua escolha, incluindo também informações básicas sobre a base (fonte, metodologia de coleta, data de atualização e limitações mais evidentes). Crie um roteiro de entrevista para aplicar a essa base de dados.

Documente as funções e cálculos aplicados para obter as respostas no github.
Indique um caminho inicial de pauta que poderia ser explorado a partir dos insights obtidos.

Indique abaixo o(s) link(s) para a documentação do projeto no github.

https://github.com/SerginhoVN/Trabalho-final-Natalia/blob/main/README.md 
