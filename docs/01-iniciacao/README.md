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

Diversas empresas do ramo de comércio alimentício, como restaurantes, lanchonetes e até mesmo bares; enfrentam problemas com a constante necessidade de repor seus estoques e dispensas. Tal dificuldade está no fato de praticamente 100% das vezes o controle dos estoques e despensas ser realizado de forma manual, com anotações físicas em cadernos e/ou cadernetas, ou através da utilização de planilhas que, mesmo possuindo algumas fórmulas para auxiliar na gestão, são incapazes de se atualizarem sozinhas; sendo necessária a mão de obra humana e realização constante de inventários e conferências para verificar a atual quantidade de itens, quais estão próximos do vencimento e até mesmo para montar uma lista de compras com produto por produto que deverá ser reposto. Como o processo acaba sendo totalmente dependente de conferência manual, o processo pode acabar tendo falhas humanas envolvendo esquecimento de contagem de algum produto, contagem errônea, "perda de tempo" dependendo da quantidade de produtos a serem contados, entre diversas outras.

## Objetivos

Objetivo Geral:

Desenvolver um sistema integrado e inteligente para a gestão automatizada de estoques alimentícios em estabelecimentos comerciais, visando melhorar a eficiência operacional, reduzir o desperdício de alimentos e otimizar o processo de reposição de produtos.

Objetivos Específicos:

1. Implementar um sistema de monitoramento em tempo real utilizando sensores de peso e tecnologia RFID para rastrear a quantidade e o estado dos itens armazenados.
2. Criar uma interface mobile intuitiva que permita a visualização do inventário, envio de alertas sobre itens próximos ao vencimento e a geração automática de listas de compras com base nas necessidades de reposição.
3. Desenvolver funcionalidades de automação, como a atualização automática do inventário e o envio de notificações personalizadas, para melhorar a organização e eficiência na gestão de estoques.
4. Integrar o sistema com assistentes virtuais para permitir o controle do inventário por comandos de voz, além de implementar uma gestão de acesso que permita diferentes níveis de controle aos funcionários do estabelecimento.

## Justificativa

A gestão eficiente de estoques em estabelecimentos alimentícios é essencial para evitar desperdícios e otimizar recursos. O "Smart Pantry" atende a essa necessidade ao combinar tecnologia RFID e sensores de peso para monitorar em tempo real a quantidade e o estado dos alimentos estocados. O sistema alerta sobre produtos próximos à data de validade, gera listas automáticas de reposição, e permite uma gestão de inventário mais precisa e sustentável. Com funcionalidades que automatizam processos e reduzem erros humanos, o Smart Pantry melhora a eficiência operacional e a sustentabilidade dos negócios alimentícios.

Os benefícios esperados pela construção do projeto "Smart Pantry" são significativos e variados. E aqui estão alguns deles: 

1. Redução de Desperdício de Alimentos: Ao monitorar os produtos em tempo real e alertar sobre itens próximos da data de validade, o Smart Pantry ajuda a minimizar o desperdício, resultando em economia de custos e práticas mais sustentáveis.

2. Melhoria na Gestão de Estoques: O sistema proporciona uma visão clara e organizada dos itens estocados, facilitando o planejamento de compras e reposições, além de evitar a perda de produtos por má administração de inventário.

3. Sustentabilidade: Com a redução de desperdícios e o uso mais eficiente dos recursos, o Smart Pantry contribui para práticas empresariais mais sustentáveis, o que está sendo cada vez mais valorizado no mercado.

4. Melhoria na Satisfação do Cliente: Com um controle mais eficaz do estoque, os estabelecimentos podem garantir que os produtos necessários estejam sempre disponíveis, o que pode resultar em melhor atendimento e maior satisfação do cliente.

## Critérios de Sucesso

Os critérios de sucesso que definimos para que o projeto seja considerado concluído corretamente são:

1. Entrega dentro do Prazo e Orçamento: O projeto deve ser concluído dentro do cronograma estabelecido e sem ultrapassar o orçamento previsto. O cumprimento desses parâmetros será um indicador essencial da eficiência na gestão do projeto.

2. Satisfação do Cliente: A satisfação dos usuários finais, que são os gestores de estabelecimentos alimentícios, será avaliada através de pesquisas e feedbacks. Então, o sucesso do projeto dependerá da capacidade do sistema de atender a essas necessidades e expectativas dos clientes em termos de funcionalidade, usabilidade e confiabilidade.

3. Qualidade do Produto Final: O sistema Smart Pantry deve funcionar de acordo com as especificações técnicas e operacionais estabelecidas. Isso inclui a precisão dos sensores de peso e da tecnologia RFID, a eficácia das notificações automáticas, e a integridade do inventário atualizado em tempo real.

4. Atendimento aos Requisitos das Partes Interessadas: O projeto deve atender a todos os requisitos e expectativas das partes interessadas, incluindo proprietários, gerentes de estabelecimentos, e equipe de TI. O alinhamento das entregas com as necessidades dessas partes interessadas será muito importante.

5. Gestão Eficaz de Riscos: É importante identificar e gerenciar riscos durante o desenvolvimento e implementação do Smart Pantry. Deveremos antecipar e responder de forma eficaz a possíveis desafios e imprevistos.

6. Impacto na Redução de Desperdícios: O sucesso do projeto será medido pela redução efetiva no desperdício de alimentos nos estabelecimentos que utilizarem o sistema. Através da diminuição de produtos vencidos e a otimização das reposições, poderemos ver o impacto real do sistema.

# Partes Interessadas

## Identificação das Partes Interessadas

| Nome              | Posição / Cargo                      | Papel Projeto             | E-mail                          | Telefone       |
|-------------------|--------------------------------------|---------------------------|---------------------------------|----------------|
| Igor Rattes       |  Dev Pleno                           | Desenvolvedor             | rattes.igor@empresa.com         | (31)98563-2535 |
| Chrystian Fonseca |  Dev Sênior                          | Desenvolvedor             | fonseca.Chrys@empresa.com       | (31)98158-1589 |
| Samara Chaves     |  Dev Pleno                           | Desenvolvedora            | chaves.samara@empresa.com       | (31)98121-1658 |
| João Silva        |  Gerente de TI                       | Gerente de Projeto	       | joao.silva@empresa.com          | (11)99999-0000 |
| Maria Fernandes   |  Analista de Sistemas                | Analista de Requisitos    | maria.fernandes@empresa.com     | (21)98888-1111 |
| Renata Lima	      |  Especialista em sistemas embarcados | Desenvolvedor de Firmware | renata.lima@empresa.com         | (51)99555-4444 |
| Felipe Ramos      |  Analista de Testes                  | Testador de Sistema       | felipe.ramos@empresa.com        | (61)99444-5555 |
| Júlia Andrade     |  Product Owner                       | Representante do Cliente  | julia.andrade@empresa.com       | (71)99333-6666 |
| Roberto Teixeira  |  Gerente de Operações (Cliente)      | Usuário Final             | roberto.teixeira@cliente.com    | (81)98222-7777 |
| Vanessa Oliveira  |  Chefe de Cozinha (Cliente)          | Usuária Final             | vanessa.oliveira@cliente.com    | (91)99111-8888 |
| Leonardo Santos   | Consultor de Sustentabilidade        | Consultor Externo         | leonardo.santos@consultoria.com | (31)98000-9999 |

## Avaliação das Partes Interessadas

| Nome              | Expectativa no Projeto                                                     | Influência | Importância / Poder | Apoio    | Observações                             |
|-------------------|----------------------------------------------------------------------------|------------|---------------------|----------|-----------------------------------------|
| Igor Rattes       | Contribuir para o desenvolvimento eficiente e funcional do sistema         | Média      | Alta                | Positivo | Focado no desenvolvimento back-end      |
| Chrystian Fonseca | Garantir que o sistema esteja bem arquitetado e escalável                  | Alta       | Alta                | Positivo | Liderança técnica                       |
| Samara Chaves     | Implementar uma interface intuitiva e amigável para o usuário final        | Média      | Alta                | Positivo | Focado no desenvolvimento front-end     |
| João Silva        | Sucesso geral do projeto, garantindo prazos e qualidade                    | Alta       | Alta                | Positivo | Responsável pela gestão do projeto      |
| Maria Fernandes   | Coletar e definir requisitos claros para o sistema                         | Alta       | Alta                | Positivo | Conduz a análise de requisitos          |
| Renata Lima	      | Desenvolver e integrar o firmware dos sistemas embarcados com eficiência   | Média      | Alta                | Positivo | Especialista em sistemas embarcados     |
| Felipe Ramos      | Garantir que o sistema esteja livre de bugs antes de ser entregue          | Média      | Alta                | Positivo | Focado em testes de qualidade           |
| Júlia Andrade     | Alinhar o produto final às necessidades do cliente                         | Alta       | Alta                | Positivo | Voz do cliente dentro do projeto        |
| Roberto Teixeira  | Ter um sistema fácil de usar que melhore a gestão de estoque no dia a dia  | Alta       | Média               | Positivo | Usuário final com expectativas práticas |
| Vanessa Oliveira  | Facilitar a operação diária com um sistema que previna desperdícios        | Média      | Média               | Positivo | Feedback direto sobre usabilidade       |
| Leonardo Santos   | Garantir que o sistema contribua para a sustentabilidade do negócio        | Média      | Média               | Positivo | Focado em práticas sustentáveis         |

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

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

> Você pode utilizar como referência o seguinte documento:
> [Termo de Abertura do Projeto](artefatos/termo-abertura-projeto.docx)

## Estimativa de Custo

......  COLOQUE AQUI O SEU TEXTO ......

> A avaliação da viabilidade econômica busca determinar a sustentabilidade financeira e o retorno sobre o investimento do empreendimento. 
> Este processo envolve a análise dos custos associados ao projeto, incluindo investimentos iniciais, despesas operacionais e potenciais custos de manutenção. 
> Simultaneamente, são examinados os benefícios esperados, como receitas, economias de custos e ganhos tangíveis e intangíveis. 
> A elaboração de projeções financeiras realistas e a aplicação de métricas como o Valor Presente Líquido (VPL) e a Taxa Interna de Retorno (TIR) contribuem para uma avaliação abrangente da viabilidade econômica do projeto. 
> Este processo permite que os gestores de projeto e as partes interessadas tomem decisões informadas sobre a continuidade, ajustes ou mesmo a interrupção do projeto, garantindo uma alocação eficiente de recursos e maximizando os benefícios econômicos esperados.

......  ATUALIZE OS ITENS DE CUSTO DO SISTEMA. ADICIONE NOVOS OU SUBDIVIDA ITENS, CASO NECESSÁRIO ......

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        |           |            |              |             |
| Hardware                |           |            |              |             |
| Serviços de Rede        |           |            |              |             |
| Hospedagem e Nuvem      |           |            |              |             |
| Software de terceiros   |           |            |              |             |
| Serviços e treinamento  |           |            |              |             |
| **Total Geral**         |           |            |              |             |

| Item de Custo            | Descrição                                                                 | Qtd. horas | Valor / hora | Valor total  |
|--------------------------|---------------------------------------------------------------------------|------------|--------------|--------------|
| **Recursos Humanos**      |                                                                           |            |              |              |
| Desenvolvimento Back-end  | Implementação do sistema de monitoramento, APIs e integração com hardware | 300        | R$ 120,00    | R$ 36.000,00 |
| Desenvolvimento Front-end | Criação da interface mobile e funcionalidades de visualização             | 250        | R$ 110,00    | R$ 27.500,00 |
| Analista de Requisitos    | Levantamento de requisitos e documentação técnica                         | 100        | R$ 100,00    | R$ 10.000,00 |
| Testador de Sistemas      | Testes de qualidade e depuração do sistema                                | 150        | R$ 90,00     | R$ 13.500,00 |
| Gerente de Projeto        | Coordenação do projeto e comunicação entre as partes interessadas         | 120        | R$ 150,00    | R$ 18.000,00 |
| **Hardware**              |                                                                           |            |              |              |
| Sensores de Peso          | Dispositivos para monitoramento em tempo real dos estoques                | 50 unidades| R$ 200,00    | R$ 10.000,00 |
| Leitores RFID             | Dispositivos para leitura de etiquetas RFID                               | 30 unidades| R$ 150,00    | R$ 4.500,00  |
| Etiquetas RFID            | Etiquetas para identificação dos produtos                                 | 500 unidades| R$ 5,00      | R$ 2.500,00  |
| **Serviços de Rede**      |                                                                           |            |              |              |
| Infraestrutura de Rede    | Configuração e manutenção da rede para conectividade dos dispositivos     | -          | -            | R$ 5.000,00  |
| **Hospedagem e Nuvem**    |                                                                           |            |              |              |
| Servidores em Nuvem       | Hospedagem do sistema e banco de dados                                    | 12 meses   | R$ 1.200,00  | R$ 14.400,00 |
| **Software de Terceiros** |                                                                           |            |              |              |
| Licenças de Software      | Ferramentas de desenvolvimento, monitoramento e automação                 | -          | -            | R$ 8.000,00  |
| **Serviços e Treinamento**|                                                                           |            |              |              |
| Treinamento de Usuários   | Capacitação dos funcionários dos estabelecimentos                         | 40 horas   | R$ 200,00    | R$ 8.000,00  |
| Suporte Técnico           | Serviço de suporte e manutenção pós-implementação                         | 12 meses   | R$ 1.000,00  | R$ 12.000,00 |
| **Total Geral**           |                                                                           |            |              | R$ 169.400,00|



## Estimativa de Prazo

......  COLOQUE AQUI O SEU TEXTO ......

> A estimativa de prazo orienta tanto o cliente quanto a equipe de desenvolvimento do projeto em termos do tempo necessário para a conclusão do projeto como um todo. 
> Esta estimativa possibilita a criação de um cronograma realista e viável, permitindo o planejamento adequado das fases do projeto, alocação de recursos de maneira eficiente e antecipação de eventuais desafios.
> Uma estimativa precisa orienta a execução do projeto, contribui para a gestão de expectativas e para o estabelecimento de metas alcançáveis.

> Indique:
> * Prazo previsto (em horas) 
> * Data de início
> * Data de término

* Prazo previsto (em horas): XX horas
* Data de início: __ / __ / _____
* Data de término: __ / __ / _____

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

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RF-001| Monitorar o inventário em tempo real utilizando sensores de peso e tecnologia RFID. | ALTA | 
|RF-002| Enviar alertas para itens próximos ao vencimento ou em quantidade crítica. | ALTA |
|RF-003| Atualizar automaticamente o inventário com base nas entradas e saídas de produtos detectadas. | ALTA |
|RF-004| Gerar automaticamente listas de compras com base na quantidade atual de estoque e previsão de demanda.  | ALTA |
|RF-005| Permitir que o usuário cadastre tarefas de monitoramento e reposição de estoque.   | ALTA |
|RF-006| Emitir relatórios analíticos sobre o desempenho do estoque, incluindo desperdício e reposição.   | MÉDIA |
|RF-007| Emitir um relatório de tarefas de gestão de estoque realizadas no mês.   | MÉDIA |
|RF-008| Implementar um sistema de feedback para que os funcionários possam relatar problemas ou melhorias no sistema. | MÉDIA |
|RF-009| Fornecer uma funcionalidade para comparar o estoque atual com os históricos de períodos anteriores.  | MÉDIA |
|RF-010| Implementar alertas para anomalias detectadas, como diferenças significativas entre inventário físico e registrado.   | MÉDIA |

### Requisitos Não Funcionais

A tabela a seguir apresenta os requisitos não funcionais do projeto.

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| A interface do usuário deve ser intuitiva e acessível, com suporte a dispositivos móveis e desktops. | ALTA     | 
|RNF-002| O sistema deve ser capaz de processar dados de inventário em tempo real, com um tempo de resposta inferior a 2 segundos.| ALTA     | 
|RF-003| A plataforma deve oferecer suporte a múltiplos idiomas, incluindo pelo menos português e inglês. | MÉDIA |
|RF-004| O sistema deve ser compatível com as principais assistentes virtuais do mercado, como Alexa e Google Assistant.  | MÉDIA |
|RF-005| O sistema deve ser modular, facilitando futuras atualizações e integração com outros sistemas.   | ALTA |
A tabela a seguir apresenta os requisitos não funcionais do projeto. 


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

|ID    | Descrição de Condições para Início do Projeto                                                    | 
|------|--------------------------------------------------------------------------------------------------|
|CI-001| Aprovação do orçamento e financiamento                                                           |
|CI-002| Assinatura de contrato de prestação de serviços com fornecedores                                 |
|CI-003| Contratação da equpe de desenvolvimento e de especialistas em hardware e software                |
|CI-004| Liberação de acesso à(s) despensa(s)/estoque(s) da contratante, aos funcionários da contratada   |
|CI-005| Acesso ao planejamento de estocagem de produtos (Lista de compras)                               |
|CI-006| Aquisição dos equipamentos e tecnologias, conforme análise in loco                               |

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
