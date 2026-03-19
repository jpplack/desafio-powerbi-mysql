📊 Dashboard de Gestão de Recursos - Azure Company


📝 Descrição do Projeto
Este projeto consistiu na migração, estruturação e visualização de dados de um sistema de RH e Gestão de Projetos. Os dados brutos foram processados em um banco de dados MySQL local e integrados ao Power BI para a criação de um Dashboard estratégico.

🛠️ Tecnologias Utilizadas
Banco de Dados: MySQL (via DBeaver)

Ferramenta de BI: Power BI Desktop

Linguagem: SQL


⚙️ Etapas de Processamento (ETL)
Como parte do desafio de BI e Engenharia de Dados, as seguintes etapas foram realizadas:

Criação e Ingestão: Estruturação do banco de dados azure_company e população das tabelas via scripts SQL.

Tratamento de Dados (Power Query):

Limpeza de endereços complexos (uso de delimitadores para separar rua, cidade e estado).

Tratamento de valores nulos (identificação do Gerente Geral/Diretor).

Identificação e correção de duplicatas após junções de tabelas.

Modelagem de Dados:

Self-Join: Realização de mesclagem na tabela de funcionários para identificar a hierarquia (Colaborador x Gerente).

Mesclagem de Consultas: Unificação de departamentos e localizações para facilitar a análise geográfica.

Criação de KPIs: Implementação de métricas de Total de Funcionários, Média Salarial e Headcount por Gerente.

📂 Como Replicar o Projeto

Execute o arquivo script_banco_dados.sql no seu ambiente MySQL.

Abra o arquivo .pbix no Power BI Desktop.

Atualize a fonte de dados para o seu localhost.
