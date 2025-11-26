# Dashboard de Performance de Vendas 📊📉

Este repositório contém um projeto que utiliza dados da Olist, uma plataforma que conecta lojistas aos principais marketplaces do Brasil. O objetivo é importar, tratar e analisar quatro diferentes bases de dados utilizando o Power Query no Power BI, fornecendo insights valiosos sobre vendas e comportamento do cliente.

<div>
<img src="Olist/Power-Query.png" width="700px" />


## Estruturas de Dados Importadas 🗃️

As seguintes bases de dados foram importadas:

1. **Pedidos (xlsx)**: Informações sobre todos os pedidos realizados.
2. **Itens Pedidos (csv)**: Itens específicos de cada pedido.
3. **Pagamentos (xml)**: Detalhes dos pagamentos realizados.
4. **Produtos (json)**: Informações detalhadas sobre os produtos vendidos.

## Importação dos Dados 📥🛢

### Pedidos (xlsx)
- Vá para a guia **Página Inicial** no Power BI.
- Clique em **Obter Dados** e selecione **De Pasta de Trabalho**.
- Navegue até o arquivo de pedidos e selecione-o.
- Escolha a planilha que contém os dados e clique em **Carregar**.

### Itens Pedidos (csv)
- Clique em **Obter Dados** e selecione **Arquivo &gt; Texto/CSV**.
- Navegue até o arquivo de itens pedidos e carregue os dados.

### Pagamentos (xml)
- Clique em **Obter Dados** e selecione **Arquivo &gt; XML**.
- Carregue o arquivo de pagamentos e verifique a estrutura dos dados.

### Produtos (json)
- Clique em **Obter Dados** e selecione **Arquivo &gt; JSON**.
- Carregue o arquivo de produtos e verifique a estrutura.

## Tratamento de Dados no Power Query 𝄜 

Durante o tratamento de dados, explorei várias funcionalidades do Power Query, incluindo:

- **Coluna de Exemplo**: Utilizei para limpar a coluna "Tipo de Pagamentos", removendo duplicatas e substituindo valores.
- **Remover Linhas**: Aprendi a remover linhas específicas utilizando a função "Remover linhas superiores".
- **Promover Cabeçalho**: Usei a opção "Usar primeira linha como cabeçalho".
- **Extração de Texto**: Extraí texto utilizando delimitadores específicos nas colunas.
- **Mesclagem de Consultas**: Mesclei consultas para correlacionar informações entre tabelas.
- **Substituição de Valores**: Utilize a ferramenta "Substituir Valores" para fazer modificações diretas na coluna "Payment Type".

### Manipulação Avançada ⚙️
- Explorei a **Coluna Personalizada** e a criação de parâmetros usando **Gerenciar Parâmetros** no Power Query.
- Aprendi a lidar com desafios de tipagem automática e como definir manualmente tipos de dados.
- Realizei a renomeação de colunas e a otimização das etapas aplicadas usando o **Editor Avançado**.
- Apliquei melhorias de performance eliminando etapas desnecessárias e unificando processos.

## Modelagem de Dados 💻

A modelagem de dados foi uma etapa essencial para transformar essas informações em insights úteis. Consegui integrar diversas fontes de dados e criar dashboards interativos que realçam o desempenho das vendas.

## Criação de Dashboard 👩🏻‍💻

O projeto inclui um dashboard com três gráficos:

1. **Gráfico de Tabela**: Tipo de pagamento por contagem de ID de pedido.
2. **Gráfico de Barras Empilhadas**: Soma de preço por nome de categoria.
3. **Gráfico de Colunas Clusterizado**: Soma de preço por tipo de pagamento.

Esses gráficos oferecem uma visualização clara e fácil de interpretar dos dados, facilitando a análise e a tomada de decisões estratégicas.

## Conclusão ✅

Este projeto é um excelente exemplo de como ferramentas como o Power BI e o Power Query podem ser utilizadas para transformar dados brutos em informações acionáveis. Espero que este repositório seja útil para quem busca entender mais sobre análise de dados e modelagem no Power BI! 

Sinta-se à vontade para explorar e adaptar as técnicas apresentadas aqui para seus próprios projetos!
