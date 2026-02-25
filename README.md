# projeto-analise-ibge

meu projeto analise de dados ibge

📊 Projeto de Análise de Dados – Resultados 2024

📌 Objetivo

Este projeto tem como objetivo realizar o tratamento, padronização e análise exploratória dos dados públicos de resultados de 2024, garantindo qualidade, consistência e organização das informações para geração de insights estratégicos.

O foco principal é aplicar boas práticas de:

Limpeza de dados

Padronização

Tratamento de valores nulos

Identificação de inconsistências

Análise de registros duplicados

Estruturação para visualização posterior

🧠 Problema de Negócio

Bases públicas frequentemente apresentam:

Valores inconsistentes

Campos nulos

Registros duplicados

Padronização textual incorreta

Dados parcialmente preenchidos

Antes de qualquer análise estratégica, é essencial garantir a integridade e confiabilidade dos dados.

Este projeto atua exatamente nessa etapa crítica.

🛠️ Tecnologias Utilizadas

Python

Pandas

NumPy

Google Colab

GitHub

Próxima etapa:

Streamlit (para criação de dashboards interativos)

📂 Estrutura do Projeto
projeto-analise-ibge/
│

├── README.md

├── IBGE_projeto.ipynb

└── RESULTADOS_2024_copia.csv

🔄 Etapas Realizadas

1️⃣ Importação e Leitura dos Dados

Leitura do CSV com encoding adequado

Validação inicial da estrutura

2️⃣ Padronização de Texto

Remoção de espaços com .str.strip()

Conversão para Title Case

Conversão para Upper Case em colunas estratégicas

3️⃣ Tratamento de Valores Nulos

Definição de constante padrão:

VALOR_NULO_PADRAO = "Indefinido"

Substituição controlada de campos vazios

4️⃣ Mapeamento de Códigos

Exemplo:

MAPA_DEPENDENCIA = {
    1: "Federal",
    2: "Estadual",
    3: "Municipal",
    4: "Privada"
}

Aplicação para tornar os dados mais interpretáveis.

5️⃣ Análise de Registros Duplicados

Identificação de duplicados completos

Separação entre:

Duplicados reais

Registros com dados parciais (ex: ausentes)

Análise crítica antes de qualquer remoção.

📊 Insights Iniciais

Existem registros com presença “Ausente” contendo apenas município e estado.

Esses registros são relevantes para análises de abstenção.

Nem todo dado parcialmente preenchido deve ser removido.

Decisões sempre orientadas por contexto analítico.

🚀 Próxima Fase

A próxima etapa do projeto será:

Construção de dashboards interativos com Streamlit

Visualizações de:

Taxa de presença por estado

Distribuição por município

Indicadores de ausência

Comparações regionais

Objetivo: transformar dados tratados em suporte visual para tomada de decisão.

🧩 Como Executar o Projeto

Abra o notebook no Google Colab

Execute as células na ordem

O dataset é carregado diretamente via link público do GitHub

📈 Evolução do Projeto

Este projeto faz parte da minha jornada de desenvolvimento como Analista de Dados, com foco em:

Organização de código

Estrutura profissional

Tomada de decisão baseada em dados

Pensamento analítico estruturado

👨‍💻 Autor

Eder Alan
Estudante de Análise de Dados | Foco em BI e Inteligência de Mercado
Construindo projetos práticos com foco em aplicação real
