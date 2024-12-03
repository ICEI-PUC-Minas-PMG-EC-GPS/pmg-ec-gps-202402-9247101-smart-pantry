# *Iniciação*

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
|-------------------|---------------------------------------|---------------------------|---------------------------------|----------------|
| Igor Rattes       |  Dev Pleno                            | Desenvolvedor             | rattes.igor@empresa.com         | (31)98563-2535 |
| Chrystian Fonseca |  Dev Sênior                           | Desenvolvedor             | fonseca.Chrys@empresa.com       | (31)98158-1589 |
| Samara Chaves     |  Dev Pleno                            | Desenvolvedora            | chaves.samara@empresa.com       | (31)98121-1658 |
| João Silva        |  Gerente de TI                        | Gerente de Projeto	      | joao.silva@empresa.com          | (11)99999-0000 |
| Maria Fernandes   |  Analista de Sistemas                 | Analista de Requisitos    | maria.fernandes@empresa.com     | (21)98888-1111 |
| Renata Lima	      |  Especialista em sistemas embarcados  | Desenvolvedor de Firmware | renata.lima@empresa.com         | (51)99555-4444 |
| Felipe Ramos      |  Analista de Testes                   | Testador de Sistema       | felipe.ramos@empresa.com        | (61)99444-5555 |
| Júlia Andrade     |  Product Owner                        | Representante do Cliente  | julia.andrade@empresa.com       | (71)99333-6666 |
| Roberto Teixeira  |  Gerente de Operações (Cliente)       | Usuário Final             | roberto.teixeira@cliente.com    | (81)98222-7777 |
| Vanessa Oliveira  |  Chefe de Cozinha (Cliente)           | Usuária Final             | vanessa.oliveira@cliente.com    | (91)99111-8888 |
| Leonardo Santos   | Consultor de Sustentabilidade         | Consultor Externo         | leonardo.santos@consultoria.com | (31)98000-9999 |
| Rafael Costa      | Especialista em Atendimento ao Cliente| Consultor Externo         | rafael.costa@consultoria.com    | (31)98234-5678 |
| Fernanda Almeida  | Especialista em Qualidade             | Consultor Externo         | fernanda.alm@consultoria.com    | (31)98765-4321 |

## Avaliação das Partes Interessadas

| Nome              | Expectativa no Projeto                                                                    | Influência | Importância / Poder | Apoio    | Observações                              |
|-------------------|-------------------------------------------------------------------------------------------|------------|---------------------|----------|------------------------------------------|
| Igor Rattes       | Contribuir para o desenvolvimento eficiente e funcional do sistema                        | Média      | Alta                | Positivo | Focado no desenvolvimento back-end       |
| Chrystian Fonseca | Garantir que o sistema esteja bem arquitetado e escalável                                 | Alta       | Alta                | Positivo | Liderança técnica                        |
| Samara Chaves     | Implementar uma interface intuitiva e amigável para o usuário final                       | Média      | Alta                | Positivo | Focado no desenvolvimento front-end      |
| João Silva        | Sucesso geral do projeto, garantindo prazos e qualidade                                   | Alta       | Alta                | Positivo | Responsável pela gestão do projeto       |
| Maria Fernandes   | Coletar e definir requisitos claros para o sistema                                        | Alta       | Alta                | Positivo | Conduz a análise de requisitos           |
| Renata Lima	      | Desenvolver e integrar o firmware dos sistemas embarcados com eficiência                  | Média      | Alta                | Positivo | Especialista em sistemas embarcados      |
| Felipe Ramos      | Garantir que o sistema esteja livre de bugs antes de ser entregue                         | Média      | Alta                | Positivo | Focado em testes de qualidade            |
| Júlia Andrade     | Alinhar o produto final às necessidades do cliente                                        | Alta       | Alta                | Positivo | Voz do cliente dentro do projeto         |
| Roberto Teixeira  | Ter um sistema fácil de usar que melhore a gestão de estoque no dia a dia                 | Alta       | Média               | Positivo | Usuário final com expectativas práticas  |
| Vanessa Oliveira  | Facilitar a operação diária com um sistema que previna desperdícios                       | Média      | Média               | Positivo | Feedback direto sobre usabilidade        |
| Leonardo Santos   | Garantir que o sistema contribua para a sustentabilidade do negócio                       | Média      | Média               | Positivo | Focado em práticas sustentáveis          |
| Fernanda Almeida  | Assegurar que os processos de qualidade sejam cumpridos conforme os padrões estabelecidos | Média      | Alta                | Positivo | Atenção aos detalhes e melhoria contínua |
| Rafael Costa      | Garantir a satisfação dos clientes e resolver dúvidas com eficiência e cordialidade       | Média      | Alta                | Positivo | Excelente comunicação e foco no cliente  |
  

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

## Estimativa de Custo

A estimativa de custos do projeto abrange os principais componentes necessários, incluindo recursos humanos, hardware, software e serviços associados. A análise foi realizada com base em valores de mercado atuais e referências de projetos similares, visando fornecer uma projeção financeira realista. Os custos estão organizados de forma a permitir uma visualização clara das despesas envolvidas em cada etapa do desenvolvimento e implementação do sistema. A seguir está a tabela detalhada dos custos estimados para a implementação do projeto, repartida em seções "Recursos Huamanos", "Hardware", "Serviços de Rede", Hospedagem e Nuvem", "Software de Terceiros" "Serviços e Treinamento" e finalizando com o "Total Geral".


| Item de Custo               | Descrição                                                                   | Qtd.       | Unidade       | Valor unitário | Valor total   |
|-----------------------------|-----------------------------------------------------------------------------|------------|---------------|----------------|---------------|
| **Recursos Humanos**        |                                                                             |            |               |                |               |
| Desenvolvimento Back-end    | Implementação do sistema de monitoramento, APIs e integração com hardware.  | 1060 horas  | R$            | 120,00         | R$ 127.200,00  |
| Desenvolvimento Front-end   | Criação da interface mobile e funcionalidades de visualização.              | 790 horas  | R$            | 110,00         | R$ 86.900,00  |
| Analista de Requisitos      | Levantamento de requisitos e documentação técnica.                          | 410 horas  | R$            | 100,00         | R$ 41.000,00  |
| Testador de Sistemas        | Testes de qualidade e depuração do sistema.                                 | 530 horas  | R$            | 90,00          | R$ 47.700,00  |
| Gerente de Projeto          | Coordenação do projeto e comunicação entre as partes interessadas.          | 480 horas  | R$            | 150,00         | R$ 72.000,00  |
| **Hardware**                |                                                                             |            |               |                |               |
| Sensores de Peso            | Dispositivos para monitoramento em tempo real dos estoques.                 | 50 unid.   | R$            | 200,00         | R$ 10.000,00  |
| Leitores RFID               | Dispositivos para leitura de etiquetas RFID.                                | 30 unid.   | R$            | 150,00         | R$ 4.500,00   |
| Etiquetas RFID              | Etiquetas para identificação dos produtos.                                  | 500 unid.  | R$            | 5,00           | R$ 2.500,00   |
| Microcontroladores          | Placas para controle e processamento dos dados dos sensores.                | 20 unid.   | R$            | 300,00         | R$ 6.000,00   |
| Cabos e Conectores          | Fios, cabos e conectores para instalação dos dispositivos.                  | 100 metros | R$            | 10,00          | R$ 1.000,00   |
| Estanho para Solda          | Material utilizado para soldagem dos componentes eletrônicos.               | 5 kg       | R$            | 150,00         | R$ 750,00     |
| Pano Anti-Estático          | Pano utilizado para proteção dos componentes eletrônicos durante a montagem.| 10 unid.   | R$            | 25,00          | R$ 250,00     |
| **Serviços de Rede**        |                                                                             |            |               |                |               |
| Infraestrutura de Rede      | Configuração e manutenção da rede para conectividade dos dispositivos.      | -          | -             | -              | R$ 6.000,00   |
| **Hospedagem e Nuvem**      |                                                                             |            |               |                |               |
| Servidores em Nuvem         | Hospedagem do sistema e banco de dados.                                     | 12 meses   | R$            | 1.200,00       | R$ 14.400,00  |
| **Software de Terceiros**   |                                                                             |            |               |                |               |
| Licenças de Software        | Ferramentas de desenvolvimento, monitoramento e automação.                  | -          | -             | -              | R$ 8.000,00   |
| Licença Python              | Licença para uso de bibliotecas e frameworks específicos em Python.         | 1 ano      | R$            | 500,00         | R$ 500,00     |
| Licença .NET Core           | Licença para uso de ferramentas .NET Core para o back-end.                  | 1 ano      | R$            | 1.000,00       | R$ 1.000,00   |
| Licença Angular             | Licença para uso de ferramentas Angular no front-end.                       | 1 ano      | R$            | 800,00         | R$ 800,00     |
| **Serviços e Treinamento**  |                                                                             |            |               |                |               |
| Treinamento de Usuários     | Capacitação dos funcionários dos estabelecimentos.                          | 40 horas   | R$            | 200,00         | R$ 8.000,00   |
| Suporte Técnico             | Serviço de suporte e manutenção pós-implementação.                          | 12 meses   | R$            | 1.000,00       | R$ 12.000,00  |
| **Total Geral**             |                                                                             |            |               |                | R$ 450.500,00 |

## Estimativa de Prazo

A estimativa de duração do projeto do Smarty Pantry é vital para orientar a equipe de desenvolvimento e o cliente sobre o tempo necessário. Estimar o cronograma preciso das etapas do projeto, garantindo que os recursos sejam utilizados de forma eficaz e possibilitando a previsão e prevenção de desafios que possam surgir. Um cronograma realista é útil em termos de desenvolvimento, mas também no desenvolvimento das expectativas e dos objetivos políticos alcançáveis ​​no projeto.

* Prazo previsto (em horas): 3270 horas
* Data de início: 01 / 08 / 2024
* Data de término: 15 / 12 / 2024

## Escopo Preliminar e Premissas

## Declaração de Escopo

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito                                                                                               | Prioridade |
|------|----------------------------------------------------------------------------------------------------------------------|------------|
|RF-001| Monitorar o inventário em tempo real utilizando sensores de peso e tecnologia RFID.                                  |    ALTA    | 
|RF-002| Enviar alertas para itens próximos ao vencimento ou em quantidade crítica.                                           |    ALTA    |
|RF-003| Atualizar automaticamente o inventário com base nas entradas e saídas de produtos detectadas.                        |    ALTA    |
|RF-004| Gerar automaticamente listas de compras com base na quantidade atual de estoque e previsão de demanda.               |    ALTA    |
|RF-005| Permitir que o usuário cadastre tarefas de monitoramento e reposição de estoque.                                     |    ALTA    |
|RF-006| Emitir relatórios analíticos sobre o desempenho do estoque, incluindo desperdício e reposição.                       |    MÉDIA   |
|RF-007| Emitir um relatório de tarefas de gestão de estoque realizadas no mês.                                               |    MÉDIA   |
|RF-008| Implementar um sistema de feedback para que os funcionários possam relatar problemas ou melhorias no sistema.        |    MÉDIA   |
|RF-009| Fornecer uma funcionalidade para comparar o estoque atual com os históricos de períodos anteriores.                  |    MÉDIA   |
|RF-010| Implementar alertas para anomalias detectadas, como diferenças significativas entre inventário físico e registrado.  |    MÉDIA   |

### Requisitos Não Funcionais

A tabela a seguir apresenta os requisitos não funcionais do projeto.

|ID     | Descrição do Requisito                                                                                                   | Prioridade |
|-------|--------------------------------------------------------------------------------------------------------------------------|------------|
|RNF-001| A interface do usuário deve ser intuitiva e acessível, com suporte a dispositivos móveis e desktops.                     |    ALTA    | 
|RNF-002| O sistema deve ser capaz de processar dados de inventário em tempo real, com um tempo de resposta inferior a 2 segundos. |    ALTA    | 
|RF-003 | A plataforma deve oferecer suporte a múltiplos idiomas, incluindo pelo menos português e inglês.                         |    MÉDIA   |
|RF-004 | O sistema deve ser compatível com as principais assistentes virtuais do mercado, como Alexa e Google Assistant.          |    MÉDIA   |
|RF-005 | O sistema deve ser modular, facilitando futuras atualizações e integração com outros sistemas.                           |    MÉDIA   |



### Restrições


A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito                                                                 | Prioridade |
|------|----------------------------------------------------------------------------------------|------------|
|RE-001| Limitações quanto à quantidade de cada produto do inventário que podem ser armazenados |    ALTA    | 
|RE-002| Suporte a conectividade em redes estáveis de internet (Wi-fi ou dados móveis)          |    ALTA    |
|RE-003| Compatibilidade com versões móveis Anroid 7.0 Nougat, IOS 12.0 e superiores            |    ALTA    |
|RE-004| Compatibilidade com tecnologia NFC, para leitura das tags RFID em dispositivos móveis  |    MÉDIA   |
|RE-005| Resolução automática de Conflitos de Dados do inventário                               |    MÉDIA   |
|RE-006| Disponibilidade do sistema nos idiomas "Português" e "Inglês"                          |    MÉDIA   |


### Contra-Escopo

A tabela a seguir apresenta o contra-escopo do projeto. 

|ID    | Descrição do Contra-Escopo                                                                                           | 
|------|----------------------------------------------------------------------------------------------------------------------|
|CE-001| Desenvolvimento de hardware específico, como sensores e dispositivos RFID, que serão adquiridos de terceiros.        |
|CE-002| Suporte técnico e manutenção pós-implementação, que será terceirizado ou tratado em contrato separado.               |
|CE-003| Customizações específicas para cada estabelecimento além das funcionalidades básicas definidas no escopo.            |
|CE-004| Desenvolvimento de funcionalidades específicas para a integração com plataformas de redes sociais.                   |
|CE-005| Criação de conteúdo educativo ou treinamentos extensivos para o uso do sistema, além do manual básico do usuário.    |

### Condições para início do Projeto


A tabela a seguir, apresente as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto                                                    | 
|------|--------------------------------------------------------------------------------------------------|
|CI-001| Aprovação do orçamento e financiamento.                                                          |
|CI-002| Assinatura de contrato de prestação de serviços com fornecedores.                                |
|CI-003| Contratação da equpe de desenvolvimento e de especialistas em hardware e software.               |
|CI-004| Liberação de acesso à(s) despensa(s)/estoque(s) da contratante, aos funcionários da contratada.  |
|CI-005| Acesso ao planejamento de estocagem de produtos (Lista de compras).                              |
|CI-006| Aquisição dos equipamentos e tecnologias, conforme análise in loco.                              |

## Marcos Agendados e Entregas


A tabela a seguir, identifique os marcos do projeto e os entregáveis previstos (requisitos).

|ID   | Marco do Projeto                                                   | 
|-----|--------------------------------------------------------------------|
|M-1  | Conclusão da Análise de Requisitos.                                |
|M-2  | Finalização do Design do Sistema e interface do usuário.           |
|M-3  | Testes de Integração Inicial entre Hardware e programação Back-end.|
|M-4  | Conclusão do Desenvolvimento do Back-end e Firmware.               |
|M-5  | Conclusão do Desenvolvimento do Front-end.                         |
|M-6  | Conclusão dos Testes Finais e Validação do Sistema.                |
|M-7  | Implantação e Entrega Final do Projeto.                            |

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

A metodologia do projeto será baseada no Scrum, um framework ágil amplamente utilizado para o desenvolvimento de software, focado em entregar resultados incrementais, adaptando-se às mudanças de requisitos e promovendo uma colaboração eficaz entre a equipe. Ele será dividido em 4 etapas, que são ciclos de trabalho curtos e iterativos, geralmente de duas a quatro semanas. Cada sprint resultará em uma versão incremental e funcional do sistema, permitindo uma avaliação contínua e a adaptação às necessidades do cliente e às mudanças nos requisitos.

Etapa 1 - Planejamento inicial:
Antes do início de cada etapa do projeto, será realizada uma reunião de planejamento onde a equipe irá definir quais tarefas serão abordadas no próximo ciclo. O objetivo é estabelecer metas claras para a entrega incremental de funcionalidades.

Etapa 2 - Reuniões diárias:
Diariamente, a equipe terá uma breve reunião, na qual os membros compartilharão o que fizeram no dia anterior, o que planejam fazer no dia atual e quaisquer bloqueis e impecilhos que possam estar enfrentando.

Etapa 3 - Avaliação:
Ao final de cada etapa do projeto, será feita uma pequena reunião com o(s) cliente(s) para demonstrar as funcionalidades desenvolvidas e receber feedback, para garantir que o projeto está evoluindo de acordo com as expectativas.

Etapa 4 - Resultados, Correções e Melhorias:
Após a avaliação, será realizada uma avaliação interna, onde a equipe apontará o que funcionou bem, o que pode ser melhorado, o que deve ser consertado e como otimizar o fluxo de trabalho nas próximas fases do projeto.

## Divisão de Papéis

* Igor Rattes – Desenvolvedor Back-end
Responsável pela construção da lógica do sistema, bancos de dados e integração com outros componentes. Seu foco está no desenvolvimento eficiente e funcional do sistema, assegurando que as informações sejam processadas e armazenadas de maneira adequada.

* Chrystian Fonseca – Desenvolvedor Full-stack / Líder Técnico
Atua na liderança técnica do projeto, garantindo que o sistema seja bem arquitetado, escalável e apto a suportar futuras expansões. Além disso, orienta as decisões técnicas e valida a qualidade da estrutura do software, além de dar apoio no desenvolvimento tanto back-end quanto front-end.

* Samara Chaves – Desenvolvedora Front-end
Focada na criação de uma interface de usuário intuitiva e amigável. É responsável pelo desenvolvimento das telas e interações visuais, visando garantir uma experiência positiva e fluida para o usuário final.

* João Silva – Gerente de Projeto
Responsável pela gestão global do projeto, incluindo o cumprimento de prazos, a coordenação das equipes e a garantia de que os objetivos de qualidade sejam alcançados. Além disso, é também responsável por assegurar o alinhamento entre as diferentes áreas e supervisionar o andamento das atividades.

* Maria Fernandes – Analista de Requisitos
Sua principal responsabilidade é coletar e definir os requisitos do sistema, interagindo com os stakeholders para assegurar que as expectativas sejam atendidas. É responsável também por traduzir as necessidades dos usuários e clientes em especificações claras para o desenvolvimento.

* Renata Lima – Desenvolvedora de Firmware
Especialista em sistemas embarcados, é responsável pelo desenvolvimento e integração do firmware dos dispositivos que compõem o projeto. Trabalha para garantir que os sensores e controladores físicos funcionem de forma sincronizada com o software.

* Felipe Ramos – Especialista em Qualidade
Sua função é garantir que o sistema esteja livre de erros antes da entrega, realizando testes rigorosos de qualidade. Concentra-se em identificar e corrigir bugs, assegurando que o produto final seja confiável e estável.

* Júlia Andrade – Especialista em Atendimento ao Cliente / Produto
Atua como a "voz do cliente" no projeto, garantindo que o sistema final atenda às necessidades e expectativas do cliente. É responsável por alinhar o desenvolvimento às demandas do usuário final, participando de revisões e feedbacks constantes.

* Leonardo Santos – Consultor de Sustentabilidade
Responsável por garantir que o projeto contribua para a sustentabilidade do negócio, com foco em práticas que previnam desperdícios e promovam uma gestão consciente de recursos. Responsável por avaliar se o sistema atende às metas de sustentabilidade estabelecidas.

## Ferramentas

| Ambiente              | Plataforma         | Link de Acesso                                                        | Justificativa |
|-----------------------|--------------------|-----------------------------------------------------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/orgs/ICEI-PUC-Minas-PMG-EC-GPS/projects/21/views/1 | Centralização e organização do projeto no próprio repositório. |
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
