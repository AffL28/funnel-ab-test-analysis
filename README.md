📊 Análise de Funil de Vendas e Teste A/A/B
📌 Visão Geral do Projeto

Neste projeto é realizada uma análise do comportamento dos utilizadores em uma aplicação mobile de uma startup de produtos alimentícios.

O objetivo principal é compreender como os utilizadores progridem através do funil de vendas da aplicação e avaliar os resultados de um experimento A/A/B realizado para testar uma alteração no design da interface.

Os designers da aplicação propuseram alterar a fonte utilizada em toda a aplicação, enquanto os gestores estavam preocupados que a nova fonte pudesse afetar negativamente a experiência do utilizador. Para tomar uma decisão baseada em dados, foi realizado um teste A/A/B.

Os utilizadores foram divididos em três grupos:

Grupo 246 — Grupo de controlo (fonte antiga)

Grupo 247 — Grupo de controlo (fonte antiga)

Grupo 248 — Grupo de teste (nova fonte)

A análise permite avaliar se a alteração do design teve impacto no comportamento dos utilizadores e nas taxas de conversão.

🎯 Objetivos do Projeto

Os principais objetivos desta análise são:

Estudar o funil de eventos da aplicação

Identificar em que etapa os utilizadores abandonam o processo

Calcular a taxa de conversão entre as diferentes etapas

Validar a consistência dos grupos de controlo no teste A/A

Avaliar se a mudança de fonte impactou o comportamento dos utilizadores

📂 Descrição dos Dados

Cada linha do conjunto de dados representa uma ação realizada por um utilizador na aplicação.

Coluna	Descrição
EventName	Nome do evento
DeviceIDHash	Identificador único do utilizador
EventTimestamp	Data e hora do evento
ExpId	Identificador do grupo experimental (246, 247, 248)
🔎 Etapas da Análise
1️⃣ Preparação dos Dados

Renomeação das colunas para melhor interpretação

Verificação de valores ausentes

Ajuste dos tipos de dados

Conversão da coluna de tempo para formato datetime

Criação de colunas adicionais de data e data/hora

2️⃣ Análise Exploratória de Dados

Contagem do número total de eventos

Identificação do número total de utilizadores

Cálculo da média de eventos por utilizador

Análise do período temporal dos dados

Remoção de dados iniciais incompletos para garantir maior fiabilidade da análise

3️⃣ Análise do Funil de Eventos

Identificação dos eventos registados e sua frequência

Cálculo do número de utilizadores que realizaram cada evento

Construção do funil de conversão

Identificação das etapas com maior abandono de utilizadores

Cálculo da proporção de utilizadores que completam todo o processo até à compra

4️⃣ Análise do Experimento A/A/B

Comparação entre os dois grupos de controlo (246 e 247) para validar o experimento

Teste de significância estatística entre os grupos

Análise do impacto da nova fonte no comportamento dos utilizadores

Comparação entre:

Grupos de controlo

Grupo de teste

Grupos de controlo combinados vs grupo de teste

Foram utilizados testes estatísticos de hipótese para verificar se as diferenças observadas entre os grupos são estatisticamente significativas.

🛠 Ferramentas Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

SciPy (Testes Estatísticos)

Jupyter Notebook

📈 Competências Demonstradas

Análise Exploratória de Dados (EDA)

Análise de Funil de Conversão

Testes A/B

Testes Estatísticos de Hipóteses

Visualização de Dados

Análise de comportamento de utilizadores
