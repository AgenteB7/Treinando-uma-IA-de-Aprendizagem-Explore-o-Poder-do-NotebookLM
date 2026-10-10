# Treinando-uma-IA-de-Aprendizagem-Explore-o-Poder-do-NotebookLM

Tema: Power BI

Objetivo: criar uma boa base para o aprendizado de Power BI

Diretrizes de comportamento: Ser compreensível e proporcionar uma boa base para iniciantes no uso do Power BI.

Fontes:

https://learn.microsoft.com/pt-br/power-bi/fundamentals/desktop-getting-started : Conteúdo introdutório produzido pela própria Microsoft

https://learn.microsoft.com/pt-br/training/paths/model-data-power-bi/ : Conteúdo de treinamento produzido pela própria Microsoft

https://escolapowerbi.com.br/dax/dax-para-iniciantes : Conteúdo de plataforma dedicada ao Powe BI

https://www.youtube.com/watch?v=KoTEjo2q8WM : Vídeo que apresenta uma balança entre conteúdo introdutório e conteúdo mais aprofundado

https://www.youtube.com/watch?v=ZIoOAsfKzVM : Introdução rápida e prática ao tema de plataforma de ensino conhecida

https://learn.microsoft.com/pt-br/training/powerplatform/power-bi : Conteúdo de treinamento produzido pela própria Microsoft

https://www.ev.org.br/cursos/introducao-a-analise-de-dados-microsoft-power-bi : Conteúdo aprofundado nos primeiros passo da plataforma

https://www.devmedia.com.br/microsoft-power-bi-primeiros-passos/38128 : Conteúdo de treinamento produzido por uma empresa consolidada no mercado como a Santander


Perguntas:

Quais os principais usos do Power BI?


O **Power BI** é utilizado principalmente para transformar dados brutos vindos de diversas fontes em relatórios e dashboards visuais, interativos e automatizados, facilitando a análise e a tomada de decisões nas empresas[1][2][3].

Com base nos materiais do seu caderno, os principais usos da ferramenta incluem:

### 1\. Aplicação em Diferentes Áreas de Negócio

O Power BI é versátil e pode ser empregado em praticamente qualquer setor organizacional[4]:

* **Vendas e Comercial**: Monitoramento do faturamento total, ticket médio, evolução das vendas ao longo do tempo e análise de desempenho por marca, produto, vendedor ou região[4].
* **Financeiro e DRE**: Acompanhamento de receitas, custos, despesas, margem de lucro, fluxo de caixa e comparações entre o orçamento previsto e o realizado[9].
* **Recursos Humanos (RH)**: Controle do total de contratações, funcionários ativos versus desligados, taxa de *turnover*, folha salarial, banco de horas extras e perfil demográfico[14].
* **Produção e Operações**: Controle da quantidade de itens produzidos, índice de peças aprovadas e rejeitadas, horas produtivas versus horas paradas e disponibilidade das máquinas[19].
* **Logística e Frotas**: Acompanhamento do volume de viagens, fretes, peso de mercadorias e custos operacionais dos veículos[24].
* **TI e Suporte**: Monitoramento do volume de chamados (abertos e encerrados), tipos de incidentes, tempo de resposta e cumprimento do acordo de nível de serviço (SLA)[25].

### 2\. Tratamento e Limpeza Automática de Dados (Power Query)

Por meio da ferramenta **Power Query**, o Power BI é utilizado para extrair, organizar e limpar dados brutos (remover linhas em branco, dividir colunas, unificar tabelas ou fazer edições de texto) sem alterar os arquivos originais[26]. Todas as etapas ficam salvas e o processo é automatizado: ao atualizar a base de dados, a limpeza ocorre automaticamente sem a necessidade de refazer tarefas manuais[30].

### 3\. Modelagem e Fórmulas Personalizadas (DAX)

Permite conectar e **relacionar tabelas diferentes** (como cruzar a tabela de vendas com o cadastro de produtos) sem precisar de cruzamentos manuais no Excel[27]. Através da linguagem **DAX**, é possível criar cálculos dinâmicos, métricas personalizadas (como contagem distinta de clientes) e análises temporais (como o acumulado do ano)[27].

### 4\. Visualização e Análise Interativa

Em reuniões de resultados, o Power BI substitui planilhas estáticas por **dashboards dinâmicos**[1]. Ao clicar em uma marca, barra ou período específico, todos os visuais da tela se filtram automaticamente em tempo real para detalhar aquela informação[1].

### 5\. Publicação e Compartilhamento na Nuvem

Os relatórios prontos podem ser **publicados no serviço do Power BI na web**, permitindo que gestores e equipes acessem os painéis atualizados diretamente do navegador ou do celula

Com base em: 

https://www.youtube.com/watch?v=KoTEjo2q8WM 

https://www.youtube.com/watch?v=ZIoOAsfKzVM 


Quais são as etapas no Power Query?

O **Power Query** é o ambiente interno do Power BI responsável pelo tratamento, limpeza e estruturação de dados (processo de ETL - Extração, Transformação e Carga) antes que as informações sejam usadas na criação de relatórios[1].

O fluxo de trabalho no Power Query engloba as seguintes etapas[1]:

### 1\. Acesso e Importação de Dados

Ao conectar o Power BI a uma fonte (como uma planilha do Excel ou banco de dados), deve-se selecionar a opção **Transformar Dados** em vez de apenas "Carregar"[5][6]. Isso abre a janela do Editor do Power Query para o tratamento inicial[2].

### 2\. Renomeação de Tabelas e Organização

É recomendável alterar nomes genéricos atribuídos às planilhas (como "Planilha1") para nomes intuitivos (como "Base Vendas"), facilitando a identificação no modelo[7][8].

### 3\. Limpeza de Dados Desnecessários

Nesta etapa, eliminam-se elementos que poluem a base[9]:

* **Remoção de colunas vazias**: exclusão de colunas nulas ou desnecessárias[9][10].
* **Remoção de linhas em branco**: aplicação do filtro automático para apagar linhas totalmente vazias registradas pelo sistema[2][11].

### 4\. Promoção de Cabeçalhos

Quando os títulos das colunas vêm dispostos nas primeiras linhas da planilha, utiliza-se a opção **Usar a Primeira Linha como Cabeçalho** para promover esses dados à posição correta de título[12].

### 5\. Transformação, Divisão e Extração de Texto

Ajustam-se os dados de texto para tornar a análise mais precisa[13]:

* **Divisão de colunas por delimitador**: separação de informações agrupadas em uma mesma célula (por exemplo, separar cidade, estado e país usando traços ou espaços como delimitadores)[14][15].
* **Coluna de Exemplos**: utilização de recursos visuais para reordenar ou ajustar textos (como transformar "Sobrenome, Nome" em "Nome Sobrenome") fornecendo apenas alguns exemplos para a ferramenta padronizar o restante[16][17].

### 6\. Definição dos Tipos de Dados

Cada coluna deve ter seu tipo de dado configurado explicitamente — definindo se o valor é Texto, Número Inteiro, Número Decimal ou Data[18]. Esse ajuste evita erros em cálculos ou gráficos futuros[19].

### 7\. Adição de Colunas Calculadas

É possível criar novas colunas diretamente no tratamento de dados, como realizar cálculos matemáticos entre colunas existentes (por exemplo, multiplicar a *Quantidade* pelo *Preço Unitário* para gerar a coluna de *Faturamento*)[10].

### 8\. Fechar e Aplicar

Após concluir os ajustes, clica-se no botão **Fechar e Aplicar** na guia *Página Inicial*[20]. O Power Query processa todas as modificações e carrega a tabela limpa para o ambiente de relatórios do Power BI[22][24].

---

### O Painel de "Etapas Aplicadas" (*Applied Steps*)

Todas as alterações feitas durante o processo ficam salvas em uma lista sequencial no painel lateral chamado **Etapas Aplicadas**[18]:

* **Histórico e Correção**: Funciona como um histórico detalhado onde é possível visualizar a tabela em qualquer momento anterior ou desfazer um erro clicando no "X" ao lado da etapa[18].
* **Automação**: Uma vez configuradas as etapas, o processo fica gravado[28]. Ao clicar no botão **Atualizar** para trazer novos dados da fonte original, o Power Query executa todas as etapas salvas automaticamente sobre os novos dados, eliminando o trabalho manual repetitivo[28][29].

Com base em:

https://www.youtube.com/watch?v=KoTEjo2q8WM

https://learn.microsoft.com/pt-br/training/powerplatform/power-bi 



Como criar um dashboard do zero?

Para criar um dashboard do zero no Power BI, você deve seguir um fluxo estruturado composto por **7 pilares essenciais** que levam os dados brutos até a publicação de um painel interativo[1]:

---

### 1\. Obtenção e Importação dos Dados

O processo começa conectando o Power BI à sua fonte de dados (planilhas do Excel, arquivos CSV, bancos de dados como SQL Server, ou web)[1].

* Na guia **Página Inicial**, clique em **Obter Dados** e selecione o tipo de arquivo ou sistema[4][5].
* Após selecionar a tabela ou planilha desejada, evite clicar direto em *Carregar*; escolha a opção **Transformar Dados** para abrir o ambiente de tratamento[6].

---

### 2\. Tratamento e Limpeza de Dados (Power Query)

No **Editor do Power Query**, você organiza os dados para garantir que estejam limpos e sem erros[7]:

* **Renomeie tabelas**: dê nomes intuitivos (como `Base Vendas`) em vez de nomes genéricos[6][11].
* **Limpe a base**: remova colunas desnecessárias e elimine linhas totalmente vazias[9].
* **Ajuste os cabeçalhos e tipos de dados**: promova a primeira linha para o título das colunas e garanta que cada coluna esteja definida corretamente como Texto, Data, Número Inteiro ou Decimal[14].
* **Edições e cálculos na base**: você pode separar colunas por delimitador (ex: separar cidade e país)[16], criar colunas unificando textos[17][18] ou criar novas colunas calculadas (como multiplicar *Quantidade* por *Preço Unitário* para obter a *Receita*)[19].
* **Fechar e Aplicar**: ao concluir, clique em **Fechar e Aplicar** na guia *Página Inicial* para carregar os dados limpos para o relatório[23].

---

### 3\. Modelagem de Dados e Relacionamentos

Ao trabalhar com mais de uma tabela (por exemplo, uma tabela de vendas e uma de cadastro de produtos)[26]:

* Acesse a **Exibição de Modelo** (terceiro ícone no menu esquerdo)[26].
* Crie relacionamentos entre as tabelas arrastando o campo em comum (como `Código do Produto`), estabelecendo a comunicação entre elas sem precisar de funções manuais de proc[27].

---

### 4\. Fórmulas e Medidas Personalizadas (Linguagem DAX)

Para calcular métricas dinâmicas sem pesar no arquivo[33][34]:

* Clique com o botão direito sobre a tabela e selecione **Nova Medida**[35].
* Crie os indicadores de negócio utilizando funções DAX[30], tais como:
  * **Somas básicas**: `SUM('Tabela'[Coluna])`[33].
  * **Contagens distintas**: `DISTINCTCOUNT('Tabela'[Coluna])`[38].
  * **Divisões seguras**: `DIVIDE([Medida1], [Medida2])`[39].
  * **Cálculos condicionais/filtros**: `CALCULATE([Medida], 'Tabela'[Coluna] = "Valor")`[34].

---

### 5\. Construção dos Visuais e Layout (Relatório)

Na **Exibição de Relatório** (primeiro ícone à esquerda)[26]:

* **Defina os indicadores principais**: liste primeiro os grandes números de forma geral (KPIs) antes de detalhar[42][43].
* **Escolha o visual correto para cada objetivo**[44][45]:
  * **Cartões**: para exibir números únicos e de alto impacto (ex: Faturamento Total, Total de Vendas)[46].
  * **Gráficos de Barras**: ideais para comparações e rankings (ex: Top Vendedores, Vendas por Marca)[49].
  * **Gráficos de Linha ou Área**: para analisar a evolução de métricas ao longo do tempo (ex: Faturamento por Mês)[52].
  * **Segmentação de Dados (Filtros)**: para criar botões interativos de seleção (ex: filtrar por Ano ou Região)[55][56].
  * **Matrizes / Tabelas**: para detalhamento tabular hierárquico[57].

---

### 6\. Design e Interatividade

Para dar um aspecto profissional ao dashboard[30]:

* **Formatação e Alinhamento**: ative o rótulo de dados nos gráficos e remova eixos ou legendas duplicadas para evitar poluição visual[60][61]. Garanta que todos os visuais estejam alinhados[62].
* **Padronização de Cores e Fundo**: defina uma paleta de cores consistente e, se desejar, importe um plano de fundo (background) criado em ferramentas como o PowerPoint para acomodar os blocos do dashboard[58].
* **Interatividade nativa**: ao clicar em uma barra ou categoria de qualquer gráfico, todos os outros visuais do painel se filtram automaticamente em tempo real[52].

---

### 7\. Salvamento e Publicação (Power BI Service)

* Salve o arquivo do projeto com a extensão `.pbix`[68].
* Na guia *Página Inicial*, clique no botão **Publicar**[69].
* Escolha seu *Workspace* no **Serviço do Power BI** (nuvem)[71][72]. A partir daí, é possível gerar links para navegação no navegador/celular, configurar atualizações automáticas e compartilhar o painel com outros usuários da empresa[69].

Com base em: 

https://www.youtube.com/watch?v=KoTEjo2q8WM

https://learn.microsoft.com/pt-br/training/powerplatform/power-bi 

https://www.youtube.com/watch?v=ZIoOAsfKzVM 

https://learn.microsoft.com/pt-br/training/powerplatform/power-bi 

https://www.ev.org.br/cursos/introducao-a-analise-de-dados-microsoft-power-bi 
