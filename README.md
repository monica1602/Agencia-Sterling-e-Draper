# Projeto Análise de Dados Agencia Sterling e Draper

## Descrição do Projeto
Esse projeto consiste em uma análise de anúncios de vídeo de tendências no Youtube oara determinar qual conteúdo merece atenção de marketing. A agência de marketing se chama Sterling e Draper. Cada vídeo tem uma categoria específica (entretenumento, música, notícias e política etc.), região e data de tendência. Um vídeo pode estar na seção de tendências por vários dias seguidos. Toda semana, os funcionários precisam responder as mesmas perguntas:
- Quais categorias de vídeo foram tendências na semana passada?
- Como foram distribuídos entre as várias regiões?
- Quais categorias foram espwcialmente populares nos Estados Unidos?
Depois de algumas semanas, foi percebido a necessidade de automatizar o processo e para isso foi preciso construir um dashboard.

## As tarefas são:
- Quais são os dados que realmente são coletados
- Projetar tabelas agregadas e a estrutura do pipeline
- Contruir o dashboard
- Discutir o conteúdo do dashboard, seu layout e os dados que precisam ser exibidos
- Utilizar o Tableau para a construção do dashboard

## Ferramentas e Bibliotecas utulizadas
- Tableau: construção de dashboard

## Resultados
- Objetivo dos negócios: analisar o histórico de vídeos de tendências no Youtube
- Com que frequência o dashboard será usado: pelo menos uma vez por dia
- Usuário do dashboard de destino: gerentes de planejamento de anúncios em vídeo
- Conteúdo de dados do dashboard:
  - Vídeos de tendências do passado, divididos por dia e categoria
  - Vídeos de tendências, divididos por países
  - Uma tabela de correspondência entre categorias e países
- Parâmetros segundo os quais os dados devem ser agrupados:
  - Data e hora da tendência
  - Categoria de vídeo
  - País
- Todos os gráficos são igualmente importantes
- Intervalo de atualização de dados: uma vez a cada 24 horas. à meia-noite UTC

## Dicionário de dados
- 'record_id': chave primária
- 'region': país/região geográfica
- 'trending_date': data e hora
- 'category_title': a categoria de vídeo
- 'videos_count': o número de vídeos na seção de tendências

## Imagens

### Categoria vs videos count
<img src="https://github.com/user-attachments/assets/163cdf15-e501-4df5-8b3f-4a41ef779454" alt="Projeto 12" width="200"/>

### Região vs videos count
<img src="https://github.com/user-attachments/assets/96f6d247-a19f-47d9-9952-1ecdd89df489" alt="Projeto 12" width="200"/>

### País vs categoria
<img src="https://github.com/user-attachments/assets/2e299bf1-55ac-49a1-b873-281fe3c96889" alt="Projeto 12" width="200"/>

### Região vs data
<img src="https://github.com/user-attachments/assets/ba906528-d1d8-4568-8418-27b1b70260a8" alt="Projeto 12" width="200"/>

### Categoria vs data
<img src="https://github.com/user-attachments/assets/9a401a01-172f-4716-8d42-623ff9258d02" alt="Projeto 12" width="200"/>

### Categoria vs países
<img src="https://github.com/user-attachments/assets/af3b5a12-2722-480c-8f99-a641e9f0f54f" alt="Projeto 12" width="200"/>

### Porcentagem por país
<img src="https://github.com/user-attachments/assets/78cca0d9-51ab-4abe-8068-0814c28b5e62" alt="Projeto 12" width="200"/>

### Porcentagem por país por ano
<img src="https://github.com/user-attachments/assets/78d86112-34ab-461d-9995-304d8cb0bb67" alt="Projeto 12" width="200"/>

### Região vs day
<img src="https://github.com/user-attachments/assets/fd16c9e2-15e3-4cac-bcba-2296f7fe9060" alt="Projeto 12" width="200"/>

### Categoria vs day
<img src="https://github.com/user-attachments/assets/652aa73e-f713-4c13-a4ce-b62f6e1b8876" alt="Projeto 12" width="200"/>

### Região vs day vs date
<img src="https://github.com/user-attachments/assets/5e09c645-1b36-4b41-bd9b-ee6368f819bf" alt="Projeto 12" width="200"/>

### Categoria vs região vs day
<img src="https://github.com/user-attachments/assets/b0ee004c-2e4d-48bc-b8b9-270f46c88895" alt="Projeto 12" width="200"/>

### País vs video count
<img src="https://github.com/user-attachments/assets/69e65e8d-c571-45b9-971c-e20eacc33f0c" alt="Projeto 12" width="200"/>

### País vs categoria
<img src="https://github.com/user-attachments/assets/cd5f93af-1af7-42e6-988e-19761b3b0401" alt="Projeto 12" width="200"/>

### Date vs video count
<img src="https://github.com/user-attachments/assets/f9d80d6e-021a-4cc9-b35a-6c9b46dbba21" alt="Projeto 12" width="200"/>

### Date vs categoria
<img src="https://github.com/user-attachments/assets/d7e5fa0b-be1f-4066-8be1-3e763d1b02cd" alt="Projeto 12" width="200"/>

### Date vs categoria vs país
<img src="https://github.com/user-attachments/assets/5da379c7-4332-4713-a954-f3d3dbd9f786" alt="Projeto 12" width="200"/>

## Aprendizados
- Tableau
- Construção de dashboard
- Construção e análise de gráficos

## Contexto real
- Empresa de marketing que desejam entender tendências do mercado, não necessariamente vídeos
- Novas empresas que desejam utulizar diferentes ferramentas para entender as mesmas situações


