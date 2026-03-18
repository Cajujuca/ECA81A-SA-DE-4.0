# Projeto: \Saúde 4.0: Robótica Assistiva

### 1\. Identificação do Grupo

* **Instituição:** Centro Universitário da Fundação Santo André (FSA) / UNICID
* **Curso:** \[Inserir Nome do Curso]
* **Grupo:** \[Inserir Nome ou Número do Grupo]
* **Integrantes:** \* \[Nome Completo] - RA: \[000000]

  * \[Nome Completo] - RA: \[000000]
  * \[Nome Completo] - RA: \[000000]

\---

### 2\. Área Problema Selecionada

Selecione a trilha tecnológica do projeto (marque com um \[x]):

* \[ ] **Saúde 4.0:** Robótica Assistiva (Controladores Inteligentes/Fuzzy)
* \[ ] **Smart Grid:** Eficiência Energética e Descarbonização
* \[ ] **Agtech:** Automação de Precisão e Visão Computacional
* \[ ] **Logística Autônoma:** Coordenação de AGVs e Otimização de Rotas

\---

### 3\. Diagnóstico e Definição do Agente

Nesta seção, descrevemos o cenário de atuação e a modelagem do agente inteligente.

* **Contexto:** \[Descrever o setor, ex: Indústria 4.0 ou Gestão de Energia].
* **Problema:** \[Explicar o gargalo ou falha que a IA ajudará a resolver].
* **Impacto:** \[Mencionar o ganho esperado, ex: redução de custos ou aumento de segurança].

#### Modelagem PEAS (Agente Inteligente)

|Componente|Descrição|
|-|-|
|**Performance (P)**|Critérios de sucesso (ex: precisão de acerto, kWh economizados).|
|**Ambiente (E)**|Onde o agente opera (ex: armazém simulado, rede elétrica).|
|**Atuadores (A)**|Como o agente age (ex: acionamento de motores, válvulas).|
|\*\*Sensores (S) \*\*|Como o agente percebe o ambiente (ex: câmeras, sensores de carga).|

\---

### 4\. Arquitetura de Dados e IA

Definição das fontes de dados e da inteligência por trás da solução.

* **Origem dos Dados:** \[Link para dataset no Kaggle/UCI ou descrição da fonte].
* **Lógica de IA:** \[Técnica utilizada: ex: Redes Neurais, Lógica Fuzzy, Busca A\*].
* **Justificativa:** Por que essa técnica é ideal para este problema específico?

\---

### 5\. Plano de Tratamento de Dados (ETL)

O fluxo de processamento dos dados segue estas etapas:

1. **Extração:** Coleta de dados via arquivos \[CSV/JSON] ou simulação.
2. **Transformação:** Limpeza de nulos, normalização e engenharia de atributos.
3. **Carga:** Disponibilização dos dados para o treinamento do modelo de IA.

\---

### 6\. Estrutura do Repositório

Organização simplificada para o Milestone 1:

* `/data`: Arquivos de dados originais (raw) e tratados (processed).
* `/notebooks`: Experimentos iniciais e análise exploratória.
* `/scripts`: Códigos Python (.py) contendo a lógica do agente e do ETL.
* `requirements.txt`: Lista de bibliotecas para rodar o projeto.
* `README.md`: Documentação atual do projeto.

\---

### 7\. Instruções para Execução

Para reproduzir o ambiente e testar o diagnóstico:

1. Clone este repositório.
2. Instale as dependências:

```bash
   pip install -r requirements.txt


Projeto: 

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

Contexto: A saúde 4.0 é a aplicação das tecnologias da Indústria 4.0 no setor da saúde, integrando Inteligência Artificial, Internet das Coisas, Big Data e computação em nuvem para tornar o cuidado mais conectado, eficiente e personalizado. Nesse modelo, dados dos pacientes são coletados e analisados em tempo real, permitindo monitoramento contínuo, diagnósticos mais precisos e tratamentos individualizados, inclusive em doenças como a Doença de Parkinson. Além disso, a saúde 4.0 amplia o uso da telemedicina, melhora a integração entre sistemas de saúde e otimiza a gestão hospitalar, tornando o atendimento mais proativo e centrado no paciente, embora traga desafios relacionados à segurança e privacidade dos dados.

Problema: A Doença de Parkinson é uma doença neurológica progressiva que afeta principalmente o controle dos movimentos. Ela ocorre devido à degeneração de neurônios produtores de dopamina no cérebro. 
Devido à natureza não linear, dinâmica e incerta dos sistemas biomecânicos humanos, abordagens baseadas em controle clássico apresentam limitações significativas.

Impacto: redução significativa do tremor e na melhoria da qualidade de vida do paciente, permitindo maior autonomia em atividades do dia a dia como escrever, se alimentar e segurar objetos.

Modelagem PEAS (Agente Inteligente)

Componente	Descrição
Performance (P)	Critérios de sucesso (ex: precisão de acerto, kWh economizados).
Para que uma solução inteligente voltada a pacientes com Doença de Parkinson seja considerada bem-sucedida, o agente deve perseguir metas objetivas relacionadas à redução de sintomas, melhoria funcional e segurança clínica. A principal meta é reduzir significativamente a amplitude e a frequência do tremor sem prejudicar o movimento voluntário. Isso significa que o sistema deve ser capaz de identificar corretamente o tremor e aplicar compensação ativa apenas quando necessário. Um critério de sucesso mensurável seria, por exemplo, uma redução percentual consistente da amplitude do tremor medida por sensores inerciais, mantendo a fluidez do movimento intencional.

Ambiente (E)	Onde o agente opera (ex: armazém simulado, rede elétrica).
O agente opera diretamente no corpo do paciente, por meio de um dispositivo vestível (como uma órtese ou exoesqueleto leve), geralmente aplicado em membros superiores como mão, punho ou braço. Esse ambiente é considerado um ambiente físico-biológico, pois envolve interação com o sistema neuromuscular humano, especialmente em condições como a Doença de Parkinson. Além disso, o agente também atua em um ambiente digital complementar, onde os dados coletados são processados, armazenados e analisados, podendo incluir sistemas embarcados e, em alguns casos, integração com plataformas de monitoramento clínico.


Atuadores (A)	Como o agente age (ex: acionamento de motores, válvulas).
O agente inteligente interage com o ambiente principalmente por meio de atuadores eletromecânicos, como motores ou servomotores acoplados a uma órtese ou exoesqueleto, que aplicam torque para compensar o tremor ou auxiliar o movimento.
As decisões são executadas por um controlador embarcado (microcontrolador ou processador), que roda os algoritmos de IA e envia comandos aos motores. Esses comandos passam por um driver de potência, responsável por regular corrente e tensão com segurança.
O sistema também utiliza feedback em malha fechada, com encoders e sensores de torque ou corrente, para garantir estabilidade e evitar sobrecompensação.

Sensores (S)	Como o agente percebe o ambiente (ex: câmeras, sensores de carga).
Atividade muscular (intenção de movimento)
Sensores Eletromiografia (EMG) de superfície - Permite diferenciar movimento voluntário de tremor.

Aceleração e frequência do tremor
Unidade de Medição Inercial (IMU - acelerômetro + giroscópio) - Permite identificar padrão típico do tremor e medir sua intensidade.

Posição e velocidade angular do membro
Giroscópio da IMU ou encoder no atuador - Necessário para aplicar compensação proporcional e estável.

Torque/força aplicada pelo atuador
Sensor de torque ou corrente do motor - Garante controle seguro e evita sobrecompensação.

---
4. Arquitetura de Dados e IA
Definição das fontes de dados e da inteligência por trás da solução.
Origem dos Dados: [Link para dataset no Kaggle/UCI ou descrição da fonte].
Lógica de IA: Controladores Inteligentes/Fuzzy.
Justificativa: Por que essa técnica é ideal para este problema específico?
Essa técnica — combinando Redes Neurais e controle inteligente — é ideal para esse problema porque a Doença de Parkinson envolve sinais motores altamente não lineares, variáveis e cheios de ruído, o que dificulta o uso de métodos tradicionais com parâmetros fixos. As Redes Neurais conseguem aprender padrões complexos dos sinais (como diferenciar tremor de movimento voluntário), enquanto técnicas como Lógica Fuzzy ou controle adaptativo permitem gerar respostas suaves e graduais, mais próximas do comportamento humano. Além disso, essas abordagens se adaptam ao paciente ao longo do tempo, acompanhando a progressão da doença, o que torna o sistema mais robusto, personalizado e eficaz em situações reais.
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
