# Solicitações ao canal 156 de Curitiba

O Canal 156 é o principal canal de comunicação entre a Prefeitura Municipal de Curitiba e seu cidadão. Os dados das solicitações a este canal são abertos a todos os cidadãos. Estes dados são atualizados mensalmente e são oriundos do Sistema Integrado ao Cidadão - SIAC. Você pode encontrar as informações disponíveis e os dicionários das tabelas [clicando aqui](https://www.curitiba.pr.gov.br/dadosabertos/busca/?termo=156). A partir dos dados coletados, a prefeitura de Curitiba faz uma triagem destes registros e classifica cada solicitação de acordo com o tipo: Solicitação, Reclamação, Elogio, Denúncia, Recadastro, Sugestão, Informação ou Consulta Pública. Além disso, durante a solicitação o cidadão elenca qual é o bairro do asssunto da solicitação e outras informações pertinentes a sua requisição. Cada solicitação é registrada com sua data e horário.

  
Desta forma, o projeto tem o objetivo de analisar as solicitações feitas ao canal 156 ao longo dos últimos 03 anos (2021~2023) e verificar o comportamento dos registros dentre os bairros da cidade.


Para fazer a extração dos dados foi utilizado código Python. [Você pode checar o código clicando aqui](https://github.com/FerrazThales/Curitiba156/blob/main/Importar_Dados_e_Carregar_no_meu_Drive_do_Google.ipynb). Neste código, detalho cada etapa para a obtenção e tratamento dos dados. Depois disso, devido ao grande volume de dados, foi necessário incluir todos os registros em uma tabela do BigQuery através da própria linguagem Python.

A fim de demonstrar os resultados de uma maneira visual, foi utilizado o Looker Studio. [Você pode conferir o relatório do Looker Studio, clicando aqui](https://lookerstudio.google.com/reporting/a248b98e-ce46-4132-86e8-e1a7d887c8cf). Neste relatório, é possível selecionar um período analisado (dentre 2020 a 2023), escolher o tipo de solicitação (conforme feita a triagem pela prefeitura) e o bairro que é assunto da solicitação. Desta forma, uma análise sobre as solicitações a cidade podem ser feitas, incluindo um detalhamento maior através de uma tabela dinâmica que traz os principais assuntos e subdivisões das solicitações!

*obs: Não sei se já teve contato com alguma ferramenta de BI, mas você também pode fazer filtros clicando em cima dos gráficos!!! Pode filtrar 2023, por exemplo, clicando em cima da coluna azul de 2023.*
