# Iniciação

> A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
> Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
> É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
> Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
> Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
> O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Critérios de Sucessos](#critérios-de-sucesso)
- [Partes Interessadas](#partes-interessadas)
  - [Identificação das Partes Interessadas](#identificação-das-partes-interessadas)
  - [Avaliação das Partes Interessadas](#avaliação-das-partes-interessadas)
- [Termo de Abertura do Projeto](#termo-de-abertura-do-projeto)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
  - [Escopo Preliminar e Premissas](#escopo-preliminar-e-premissas)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos Não Funcionais](#requisitos-não-funcionais)
    - [Restrições](#restrições)
    - [Contra-Escopo](#contra-escopo)
    - [Condições para início do Projeto](#condições-para-início-do-projeto)
  - [Marcos Agendados e Entregas](#marcos-agendados-e-entregas)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)

# Introdução

```diff
+ Tarefa 01:
+ Tema do projeto e lista de Stakeholders
```

## Problema

A perda de tempo no trânsito é cada vez mais frequente, e os semáforos são um dos principais causadores. Eles podem levar mais de 2 minutos para reabrir, enquanto o tempo médio de abertura é de apenas 30 segundos, resultando em filas que agravam o congestionamento.

## Objetivos

O objetivo é desenvolver um protótipo funcional de um semáforo inteligente
utilizando um ESP32, câmeras e algoritmos de detecção, capaz de:
Monitorar e contabilizar o fluxo de veículos em tempo real.
Identificar e priorizar a passagem de veículos de emergência. 
Ajustar dinamicamente os tempos de sinalização com base nas condições do tráfego.

## Justificativa

Hoje em dia, o aumento do fluxo de veículos nas áreas urbanas causa congestionamentos frequentes e perda de tempo. Os semáforos tradicionais, com tempos fixos, não conseguem se adaptar em tempo real para melhorar o trânsito. Isso acaba tornando o tráfego ineficiente e afeta diretamente a vida das pessoas. Com isso, o nosso projeto busca tornar o trânsito mais ágil e reduzir o tempo de espera nos semáforos, facilitando o dia a dia de todos. 

## Critérios de Sucesso

Redução do tempo de espera: dados demonstram uma melhoria no fluxo de veículos bem como o tempo de espera.
Integração com sensores: os dispositivos respondem com precisão e como esperado.
Segurança: pedestres e ciclistas sentido-se mais seguros.
Entrega dentro do prazo: produto finalizado e entregue no tempo esperado.
Partes interessadas: satisfação das partes interessadas com o resultado final.

# Partes Interessadas

## Identificação das Partes Interessadas

| Nome            | Posição / Cargo | Papel Projeto                              | E-mail                           | Telefone       |
|-----------------|-----------------|--------------------------------------------|----------------------------------|----------------|
| Vinicius Castro | Sócio           | Técnico de informática                     | vinicius_castro@TecnoVias.com.br | (31)92929-8716 |
| Vitor Augusto   | Sócio           | Analista de dados e analista de requisitos | vitor_augusto@TecnoVias.com.br   | (31)93679-6781 |
| Rammid Andrew   | Sócio           | Desenvolvedor                              | rammid_andrew@TecnoVias.com.br   | (31)92769-8386 |


## Avaliação das Partes Interessadas

| Nome            | Expectativa no Projeto | Influência    | Importância / Poder | Apoio       | Observações   |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|--------|----------|---------------------------------|
| Órgãos municipais de trânsito      | O semáforo inteligente otimize o fluxo de veículos, priorizando o transporte de emergência além de reduzir o congestionamentos e aumentando a segurança nas ruas.       | Média | Alta   | Positivo | São clientes                    | 
| Empresas de transporte público     | O semáforo inteligente otimize o fluxo de veículos, priorizando o transporte de emergência além de reduzir o congestionamentos e aumentando a segurança nas ruas.       | Média | Alta   | Positivo | São clientes                    |
| prestadoras de serviços municipais | Os concorrentes esperam que o projeto de semáforo inteligente não de certo, para que percam espaço para uma nova tecnologia.                                            | Média | Alta   | Negativo | São concorrentes                |
| Empresas de tecnologia             | Esperam que o projeto de semáforo inteligente seja bem-sucedido, pois isso pode gerar novas oportunidades de negócios, aumentar a demanda por seus produtos e serviços. | Alta  | Alta   | Positivo | São fornecedores de tecnologias |
| Pedestres, ciclistas e motoristas  | Os clientes esperam que o projeto de semáforo inteligente melhore a eficiência do tráfego, reduza congestionamentos e aumente a segurança das ruas.                     | Alta  | Neutro | Positivo | São os cllientes                |      

```diff
+ Tarefa 01
+ Fim da seção a ser atualizada.
```


-----
```diff
+ Tarefa 02
+ Termo de Abertura do Projeto
```

# Termo de Abertura do Projeto

> [Termo de Abertura do Projeto](artefatos/termo-abertura-projeto.docx)

## Estimativa de Custo

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        |           |      2100      |       50       |       105000      |
| Hardware                |    leitor RFID de longa distância.(R$600 Unidade) esp32cam (50 Unidade) tags RFID para veículos (10 Unidade) |            |              |      670       |
| Serviços de Rede        |    Protocolo de comunicação com o esp (MQTT)       |            |      1 dólar(por milhão de mensagens)      |            |
| Hospedagem e Nuvem      |     Banco de dados (SQL)      |            |       0,5       |      400(Mensais)       |
| Software de terceiros   |           |            |              |             |
| Serviços e treinamento  |     Cursos para usar as tecnologias     |     40       |      5        |       200      |
| **Total Geral**         |           |       2140     |       61       |      106270       |


## Estimativa de Prazo

* Prazo previsto (em horas): 2100 horas
* Data de início: 01 / 09 / 2024
* Data de término: 15 / 12 / 2024

## Escopo Preliminar e Premissas

> Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas. 
> 
> ***A quantidade mínima de requisitos a serem preenchidos nas seções abaixo não incluem os exemplos previamente fornecidos.***

## Declaração de Escopo

> Você pode utilizar como referência o seguinte documento:
- [Declaração de Escopo](artefatos/declaracao-escopo.docx)

> Enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


### Requisitos Funcionais

......  ATUALIZE OS REQUISITOS FUNCIONAIS DO SISTEMA (MÍNIMO 10) ......

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos Não Funcionais

......  ATUALIZE OS REQUISITOS NÃO FUNCIONAIS DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA     | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s             | BAIXA     | 


### Restrições

......  ATUALIZE AS RESTRIÇÕES DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RE-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RE-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Contra-Escopo

......  ATUALIZE O CONTRA-ESCOPO DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as atividades que não serão executadas no projeto

|ID    | Descrição do Contra-Escopo          | 
|------|-------------------------------------|
|CE-001| Treinamento de modelo de LLM        |
|CE-002| Pesquisa de viabilidade do mercado. |

### Condições para início do Projeto

......  ATUALIZE AS CONDIÇÕES PARA INÍCIO DOS PROJETOS (MÍNIMO 3) ......

A tabela a seguir, apresente as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto    | 
|------|--------------------------------------------------|
|CI-001| Assinatura de contrato de prestação de serviços. |
|CI-002| Apresentação de garantias definidas no contrato. |

## Marcos Agendados e Entregas

......  ATUALIZE OS MARCOS AGENDADOS DO PROJETO E AS DATAS PARA ENTREGAS DAS TAREFAS ......

A tabela a seguir, identifique os marcos do projeto e os entregáveis previstos (requisitos).

|ID   | Marco do Projeto                                                  | 
|-----|-------------------------------------------------------------------|
|M-1  | Liberação do sistema para cadastro de informações e configuração. |
|M-2  | Permissão para uso do sistema, por usuários focais.               |
|M-3  |                                                                   |
|M-4  |                                                                   |
|M-5  |                                                                   |
|M-6  |                                                                   |

```diff
+ Tarefa 02
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 03:
+ Metodologia do Projeto
```

# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, a divisão de papéis e tarefas e as ferramentas empregadas.
>
> Coloque detalhes sobre o processo utilizado e a implementação do Framework Scrum seguido pelo grupo. 
> O grupo deverá gerenciar as tarefas utilizando o GitHub Project para acompanhar o andamento do projeto, a execução das tarefas e o status de desenvolvimento da solução.
> 
> **Links Úteis**:
> - [Github Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project)
> - [O que é o GitHub Projects? | Guia de Iniciantes](https://www.youtube.com/watch?v=vxYTpsFKdiQ&ab_channel=JulioArruda)
> - [Introduction to GitHub Project Boards](https://www.youtube.com/watch?v=idZyqNIrt84&list=PLiO7XHcmTslc5hGrbnnmHIb0SeJLTpOEu&ab_channel=MickeyGousset)
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
> Indique as responsabilidades de cada membro do grupo no projeto.

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

> Liste as ferramentas empregadas no desenvolvimento do projeto, justificando a escolha delas, sempre que possível.
> Todas as ferramentas utilizadas devem ser listadas.
> Qualquer tipo de ferramenta que for utilizada para construção de um artefato deve ser identificada, uma vez que podem ser necessárias alterações.
> A necessidade de uso de licenças e possíveis custos relacionados devem ser indicados.

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/XXXXXXX | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/XXXXXXX |               |
| Protótipo Interativo  | MavelApp ou Figma  | https://figma.com/XXXXXXX  |               |
| Documentos Textuais   | LibreOffice Writer | N/A                        |               |
| Planilhas e Gráficos  | Google Planilhas   | https://docs.google.com/   |               |
| EAP / WBS             | | | |
| Cronograma do Projeto | | | |
| Matriz RACI           | | | |

```diff
+ Tarefa 03:
+ Fim da seção a ser atualizada.
```

----
