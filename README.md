# Projeto Análise de Dados - Agencia Sterling e Draper

## Descrição do Projeto
Esse projeto envolve a análise de anúncios de vídeo em tendências no YouTube com o objetivo de determinar quais tipos de conteúdo merecem mais atenção para campanhas de marketing. A agência de marketing Sterling e Draper foi contratada para realizar essa análise semanal. A cada semana, a equipe da agência deve responder a perguntas sobre os vídeos em tendência, como:
- Quais categorias de vídeos foram tendência na semana passada?
- Como esses vídeos estavam distribuídos entre as diferentes regiões?
- Quais categorias de vídeos se destacaram especialmente nos Estados Unidos?

Após algum tempo, a equipe identificou a necessidade de automatizar esse processo para facilitar as respostas frequentes e aumentar a eficiência. Para isso, foi necessário construir um dashboard que permitisse acompanhar facilmente as métricas de vídeos em tendência, categorizados de acordo com a região, data e tipo de conteúdo.

O objetivo é simplificar o processo de obtenção de insights e melhorar a tomada de decisões de marketing, oferecendo uma visualização dinâmica e interativa das tendências de vídeos no YouTube.

## As tarefas são:
- Quais são os dados que realmente são coletados:
  - Categoria do vídeo: Cada vídeo tem uma categoria específica, como entretenimento, música, notícias, política, entre outros.
  - Região: A localização geográfica dos vídeos que estão em tendência, com foco particular nas tendências dos Estados Unidos.
  - Data de tendência: A data em que o vídeo foi classificado como tendência, podendo se estender por vários dias consecutivos.
  - Engajamento: Número de visualizações, curtidas, comentários e compartilhamentos, para entender a popularidade de cada vídeo.
- Projetar tabelas agregadas e a estrutura do pipeline:
  - Tabelas agregadas: É necessário criar tabelas que agreguem os dados por semana, categoria de vídeo, região e engajamento. Isso permitirá analisar as tendências de forma mais clara e facilitará a automação do processo.
  - Estrutura do pipeline: O pipeline será responsável por extrair, transformar e carregar (ETL) os dados de maneira eficiente. Ele deve incluir:
    - Extração: Coleta dos dados do YouTube sobre vídeos e suas métricas.
    - Transformação: Limpeza dos dados, agregação por categorias e regiões, e cálculo de métricas importantes, como média de visualizações e engajamento.
    - Carregamento: Envio dos dados processados para uma ferramenta de visualização, como o Tableau, para análise e apresentação.
- Construir o dashboard:
  - O dashboard será projetado para fornecer uma visão clara e interativa dos dados de vídeos em tendência no YouTube. Ele deve ser acessível a todos os membros da equipe da Sterling e Draper e deve ser fácil de interpretar e usar para tomada de decisões de marketing.
- Discutir o conteúdo do dashboard, seu layout e os dados que precisam ser exibidos:
  - Conteúdo:
    - Gráfico de Tendências por Categoria: Mostrar quais categorias de vídeos foram tendência por semana, com uma visualização de barras ou linha do tempo.
    - Distribuição Regional: Exibir a distribuição dos vídeos em tendência por região, com gráficos de pizza ou mapa geográfico.
    - Tendências nos Estados Unidos: Focar especificamente nos vídeos em tendência nos EUA, com ênfase em categorias populares.
    - Engajamento: Métricas sobre visualizações, curtidas, comentários e compartilhamentos, podendo ser exibidas como gráficos de barras ou de linha.
  - Layout: O layout deve ser limpo e organizado, com filtros para seleção de datas e regiões, e permitir a navegação rápida entre diferentes visualizações.
- Utilizar o Tableau para a construção do dashboard:
  - O Tableau será usado para criar visualizações interativas e dinâmicas dos dados coletados. Com ele, será possível construir gráficos de fácil compreensão e ajustar rapidamente os dados exibidos conforme necessário.
  - O Tableau permite importar dados de diferentes fontes (como bancos de dados ou planilhas), agregar informações de maneira eficiente e apresentar os resultados de forma visualmente atrativa.

## Ferramentas e Bibliotecas utulizadas
- Tableau: construção de dashboard

## Resultados
- Objetivo do Dashboard: Analisar o histórico de vídeos de tendências no YouTube, fornecendo uma visão detalhada sobre categorias, distribuição geográfica e tendências ao longo do tempo.
- Frequência de Uso: O dashboard será utilizado pelo menos uma vez por dia, permitindo atualizações diárias com dados de vídeos de tendências.
- Usuário Destino: Gerentes de planejamento de anúncios em vídeo serão os principais usuários do dashboard, utilizando-o para tomar decisões sobre campanhas de marketing e estratégias de conteúdo.
- Conteúdo de Dados do Dashboard:
  - Histórico de Vídeos de Tendência: Exibição de vídeos de tendência por dia e categoria.
  - Distribuição Geográfica: Análise de vídeos de tendências divididos por países.
  - Tabela de Correspondência: Relação entre categorias de vídeos e países.
- Parâmetros de Agrupamento de Dados:
  - Data e Hora: Tendências organizadas por data e hora.
  - Categoria de Vídeo: Agrupamento por tipo de vídeo.
  - País: Segmentação geográfica para entender as tendências em diferentes países.
- Importância dos Gráficos: Todos os gráficos têm igual relevância para fornecer uma visão clara e completa dos dados.
- Atualização de Dados: O dashboard será atualizado uma vez por dia, com dados sendo atualizados à meia-noite UTC, garantindo que as tendências mais recentes estejam sempre disponíveis.

## Dicionário de dados
- 'record_id': chave primária
- 'region': país/região geográfica
- 'trending_date': data e hora
- 'category_title': a categoria de vídeo
- 'videos_count': o número de vídeos na seção de tendências

## Imagens

### Gráfico - Categoria vs videos count
<img src="https://github.com/user-attachments/assets/163cdf15-e501-4df5-8b3f-4a41ef779454" alt="Projeto 12" width="800"/>

### Gráfico - Região vs videos count
<img src="https://github.com/user-attachments/assets/96f6d247-a19f-47d9-9952-1ecdd89df489" alt="Projeto 12" width="800"/>

### Gráfico - País vs categoria
<img src="https://github.com/user-attachments/assets/2e299bf1-55ac-49a1-b873-281fe3c96889" alt="Projeto 12" width="800"/>

### Gráfico - Região vs data
<img src="https://github.com/user-attachments/assets/ba906528-d1d8-4568-8418-27b1b70260a8" alt="Projeto 12" width="800"/>

### Gráfico - Categoria vs data
<img src="https://github.com/user-attachments/assets/9a401a01-172f-4716-8d42-623ff9258d02" alt="Projeto 12" width="800"/>

### Tabela - Categoria vs países
<img src="https://github.com/user-attachments/assets/af3b5a12-2722-480c-8f99-a641e9f0f54f" alt="Projeto 12" width="800"/>

### Gráfico - Porcentagem por país
<img src="https://github.com/user-attachments/assets/78cca0d9-51ab-4abe-8068-0814c28b5e62" alt="Projeto 12" width="800"/>

### Gráfico - Porcentagem por país por ano
<img src="https://github.com/user-attachments/assets/78d86112-34ab-461d-9995-304d8cb0bb67" alt="Projeto 12" width="800"/>

### Gráfico - Região vs day
<img src="https://github.com/user-attachments/assets/fd16c9e2-15e3-4cac-bcba-2296f7fe9060" alt="Projeto 12" width="800"/>

### Gráfico - Categoria vs day
<img src="https://github.com/user-attachments/assets/652aa73e-f713-4c13-a4ce-b62f6e1b8876" alt="Projeto 12" width="800"/>

### Gráfico - Região vs day vs date
<img src="https://github.com/user-attachments/assets/5e09c645-1b36-4b41-bd9b-ee6368f819bf" alt="Projeto 12" width="800"/>

### Gráfico - Categoria vs região vs day
<img src="https://github.com/user-attachments/assets/b0ee004c-2e4d-48bc-b8b9-270f46c88895" alt="Projeto 12" width="800"/>

### Gráfico - País vs video count
<img src="https://github.com/user-attachments/assets/69e65e8d-c571-45b9-971c-e20eacc33f0c" alt="Projeto 12" width="800"/>

### Tabela - País vs categoria
<img src="https://github.com/user-attachments/assets/cd5f93af-1af7-42e6-988e-19761b3b0401" alt="Projeto 12" width="800"/>

### Gráfico - Date vs video count
<img src="https://github.com/user-attachments/assets/f9d80d6e-021a-4cc9-b35a-6c9b46dbba21" alt="Projeto 12" width="800"/>

### Tabela - Date vs categoria
<img src="https://github.com/user-attachments/assets/d7e5fa0b-be1f-4066-8be1-3e763d1b02cd" alt="Projeto 12" width="800"/>

### Tabela - Date vs categoria vs país
<img src="https://github.com/user-attachments/assets/5da379c7-4332-4713-a954-f3d3dbd9f786" alt="Projeto 12" width="800"/>

## Aprendizados
- Tableau: Ferramenta utilizada para construção de dashboards interativos e visualizações de dados, permitindo a análise eficiente e intuitiva de grandes volumes de dados.
- Construção de Dashboard: Processo de criar um painel de controle interativo que consolida e organiza os dados de forma visual e acessível, facilitando a tomada de decisões.
- Desenvolvimento e Interpretação de Gráficos: Elaboração de representações visuais para exibir dados de forma clara e acessível, além da análise dessas visualizações para identificar padrões e tendências.

## Contexto real
- Empresas de marketing que buscam compreender as tendências de mercado, não se limitando apenas a vídeos, mas expandindo sua análise para diversos tipos de conteúdo e comportamentos do consumidor.
- Novas empresas que desejam adotar e explorar diferentes ferramentas analíticas para obter insights mais profundos sobre o mercado, comportamento dos usuários e estratégias de marketing, visando otimizar suas operações e campanhas.


