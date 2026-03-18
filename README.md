Projeto: Saúde 4.0: Robótica Assistiva

1. Identificação do Grupo
Instituição: Faculdade Enhenheiro Salvador Arena (FESA)
Curso: Engenharia de Controle e Automação 
Grupo: Grupo 8
Integrantes: Júlia Rodrigues Lima - RA: 062220026
Gustavo Florencio Simeão - RA: 061230041
Leonardo Rodolfo Bortoluci - RA: 062220014
---
2. Área Problema Selecionada
Selecione a trilha tecnológica do projeto (marque com um [x]):
[x] Saúde 4.0: Robótica Assistiva (Controladores Inteligentes/Fuzzy)
[ ] Smart Grid: Eficiência Energética e Descarbonização
[ ] Agtech: Automação de Precisão e Visão Computacional
[ ] Logística Autônoma: Coordenação de AGVs e Otimização de Rotas
---
3. Diagnóstico e Definição do Agente
Nesta seção, descrevemos o cenário de atuação e a modelagem do agente inteligente.
---
Contexto: A saúde 4.0 é a aplicação das tecnologias da Indústria 4.0 no setor da saúde, integrando Inteligência Artificial, Internet das Coisas, Big Data e computação em nuvem para tornar o cuidado mais conectado, eficiente e personalizado. Nesse modelo, dados dos pacientes são coletados e analisados em tempo real, permitindo monitoramento contínuo, diagnósticos mais precisos e tratamentos individualizados, inclusive em doenças como a Doença de Parkinson. Além disso, a saúde 4.0 amplia o uso da telemedicina, melhora a integração entre sistemas de saúde e otimiza a gestão hospitalar, tornando o atendimento mais proativo e centrado no paciente, embora traga desafios relacionados à segurança e privacidade dos dados.
Problema: A Doença de Parkinson é uma doença neurológica progressiva que afeta principalmente o controle dos movimentos. Ela ocorre devido à degeneração de neurônios produtores de dopamina no cérebro. 
Devido à natureza não linear, dinâmica e incerta dos sistemas biomecânicos humanos, abordagens baseadas em controle clássico apresentam limitações significativas.
Impacto: redução significativa do tremor e na melhoria da qualidade de vida do paciente, permitindo maior autonomia em atividades do dia a dia como escrever, se alimentar e segurar objetos.
Modelagem PEAS (Agente Inteligente)
Componente	Descrição
Performance (P)	Critérios de sucesso (ex: precisão de acerto, kWh economizados).
Ambiente (E)	Onde o agente opera (ex: armazém simulado, rede elétrica).
Atuadores (A)	Como o agente age (ex: acionamento de motores, válvulas).
**Sensores (S) **	Como o agente percebe o ambiente (ex: câmeras, sensores de carga).
---
4. Arquitetura de Dados e IA
Definição das fontes de dados e da inteligência por trás da solução.
Origem dos Dados: [Link para dataset no Kaggle/UCI ou descrição da fonte].
Lógica de IA: [Técnica utilizada: ex: Redes Neurais, Lógica Fuzzy, Busca A*].
Justificativa: Por que essa técnica é ideal para este problema específico?
---
5. Plano de Tratamento de Dados (ETL)
O fluxo de processamento dos dados segue estas etapas:
Extração: Coleta de dados via arquivos [CSV/JSON] ou simulação.
Transformação: Limpeza de nulos, normalização e engenharia de atributos.
Carga: Disponibilização dos dados para o treinamento do modelo de IA.
---
6. Estrutura do Repositório
Organização simplificada para o Milestone 1:
`/data`: Arquivos de dados originais (raw) e tratados (processed).
`/notebooks`: Experimentos iniciais e análise exploratória.
`/scripts`: Códigos Python (.py) contendo a lógica do agente e do ETL.
`requirements.txt`: Lista de bibliotecas para rodar o projeto.
`README.md`: Documentação atual do projeto.
---
7. Instruções para Execução
Para reproduzir o ambiente e testar o diagnóstico:
Clone este repositório.
Instale as dependências:
```bash
   pip install -r requirements.txt
