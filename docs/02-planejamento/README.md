# *Planejamento*

# Estrutura do Documento

- [Fase de Planejamento](#planejamento)
- [Escopo do Projeto](#escopo-do-projeto)
- [Estrutura Analítica do Projeto](#estrutura-analítica-do-projeto)
- [Matriz de Responsabilidades](#matriz-de-responsabilidades)
- [Cronograma do Projeto](#cronograma-do-projeto)
- [Orçamento do Projeto](#orçamento-do-projeto)
- [Planos de Gerenciamento](#planos-de-gerenciamento)
  - [Plano de Qualidade](#plano-de-qualidade)
  - [Plano de Aquisição](#plano-de-aquisição)
  - [Plano de Comunicação](#plano-de-comunicação)
  - [Plano de Riscos](#plano-de-riscos)

-----
```diff
+ Tarefa 04:
+ Escopo e Estrutura Analítica do Projeto
```

# Escopo do Projeto

1. Visão Geral do Projeto:

O projeto tem como objetivo desenvolver um sistema automatizado de gestão de estoque para estabelecimentos alimentícios, utilizando sensores de peso e tecnologia RFID para monitoramento em tempo real. O sistema será capaz de gerar listas de compras automáticas, integrar-se a assistentes virtuais, permitir gestão de acesso e oferecer uma interface mobile. A metodologia de desenvolvimento é baseada no Scrum, com a entrega final prevista para 15/12/2024.

2. Objetivos do Projeto:

- Criar um sistema eficiente de controle de estoque automatizado para reduzir desperdícios e otimizar a reposição de insumos alimentares.
- Desenvolver uma interface mobile amigável para o usuário, permitindo o gerenciamento remoto de estoques.
- Integrar o sistema com tecnologias emergentes, como assistentes virtuais (Alexa, Google Assistant) para alertas e controle de inventário por voz.
- Facilitar o monitoramento em tempo real de estoques através de sensores de peso e etiquetas RFID.
- Implementar a gestão de acesso, garantindo que apenas usuários autorizados possam manipular o sistema.

3. Entregáveis do Projeto:

- Sistema de Monitoramento com Sensores de Peso e RFID: Implementação de hardware (sensores e etiquetas RFID) para a coleta de dados sobre os itens em estoque.
- Interface Mobile: Aplicativo mobile que permita a visualização de dados em tempo real, a criação de listas de compras automáticas e o gerenciamento de inventário.
- Integração com Assistentes Virtuais: Conexão do sistema com assistentes como Alexa e Google Assistant para controle e avisos automatizados.
- Gestão de Acesso: Implementação de níveis de permissão de acesso para diferentes perfis de usuários.
- Gerador Automático de Lista de Compras: Com base nos níveis de estoque, o sistema gerará automaticamente listas de compras.
- Relatórios e Painel de Controle: Dashboards e relatórios sobre o status dos estoques, alertas de itens críticos, e histórico de reposições.

4. Exclusões do Escopo

- Não inclui a criação de software ou hardware que permita o controle direto de câmeras de segurança.
- Integrações com sistemas de pagamento ou controle financeiro não estão previstas no escopo inicial.
- A implementação de análises preditivas mais avançadas para o monitoramento de tendência de consumo é considerada fora do escopo neste momento.

5. Requisitos do Projeto

- Hardware: Sensores de peso com precisão adequada para pequenos e grandes volumes, etiquetas RFID para rastreamento de produtos, microcontroladores para processar os dados (FreeRTOS).
- Software: Desenvolvimento de uma aplicação web e mobile, programação da lógica de controle dos microcontroladores, integração com assistentes virtuais.
- Segurança: Implementação de gestão de acesso e autenticação para usuários do sistema.
- Dados: Capacidade de gerar e armazenar logs de inventário, histórico de alterações e reposições.

6. Restrições

- O orçamento alocado para o projeto deve ser respeitado, sem extrapolações significativas.
- O tempo de entrega final está restrito ao prazo de 15/12/2024.
- As integrações externas (assistentes virtuais e dispositivos móveis) devem seguir as políticas de privacidade e segurança dos serviços associados (Google, Amazon).
- Limitações de hardware: a compatibilidade entre os sensores e os microcontroladores será um fator determinante para o escopo técnico.

7. Premissas

- Os sensores de peso e as etiquetas RFID estarão disponíveis conforme os requisitos de precisão e quantidade definidos no projeto.
- A equipe de desenvolvimento estará disponível durante todas as fases críticas, especialmente na integração de sistemas e testes de hardware.
- O ambiente de desenvolvimento será devidamente configurado para testes, com acesso a dispositivos reais para integração.

8. Gestão do Escopo e Controle de Mudanças

A gestão do escopo será baseada em uma abordagem iterativa, utilizando a metodologia Scrum para ajustar as prioridades e funcionalidades conforme o avanço do projeto. Qualquer solicitação de alteração no escopo deverá ser formalizada, passando pela análise dos seguintes fatores:

- Impacto no prazo final.
- Necessidade de recursos adicionais.
- Mudança nos requisitos de hardware ou software.

Após a avaliação, o pedido de mudança será submetido para aprovação e, se aceito, a mudança será documentada e implementada com os devidos ajustes no cronograma e orçamento.

9. Metodologia e Marcos do Projeto

O projeto seguirá a metodologia Scrum, com reuniões regulares para avaliação do progresso. Os marcos principais incluem:

- Fase de Planejamento e Prototipação (até 01/10/2024): Definição do sistema, aquisição de hardware e início do desenvolvimento do protótipo.
- Desenvolvimento da Arquitetura do Sistema (HAL, SYS, APP) (até 01/11/2024): Integração do hardware com a lógica de controle e testes iniciais.
- Integração com Aplicativo Mobile e Assistentes Virtuais (até 15/11/2024): Finalização das integrações e testes com assistentes virtuais.
- Testes e Validação Final (até 10/12/2024): Testes de funcionalidade, desempenho e segurança.
- Entrega Final (15/12/2024): Entrega do projeto completo para o cliente.

# Estrutura Analítica do Projeto

![Estrutura Analítica do Projeto](images/Estrutura_Analitica_do_Projeto.png)

### Documento Editável
- [Estrutura Analítica do Projeto - Editável.mind](artefatos/Smart_Pantry_Estrutura_Analitica_do_Projeto.mind)
- [Estrutura Analítica do Projeto - Editável.rtf](artefatos/Smart_Pantry_Estrutura_Analitica_do_Projeto_rtf.rtf)

```diff
+ Tarefa 04:
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 05:
+ Matriz de Responsabilidades (RACI)
```

# Matriz de Responsabilidades

![Matriz RACI](images/ORGANOGRAMA_RACI.png)
![Legenda](images/LEGENDA.png)
![Recursos Humanos](images/Recursos_Humanos.png)

### Documento Editável

- [Matriz de Responsabilidades (RACI) - Editável](artefatos/Organograma_RACI.xlsx)

```diff
+ Tarefa 05:
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 07:
+ Cronograma do Projeto
```

# Cronograma do Projeto

![image](https://github.com/user-attachments/assets/128739f7-470d-484c-a1a7-9ba991b8f493)
![image](https://github.com/user-attachments/assets/3d335d79-3ca9-4aeb-b4ac-d3f3192f7c85)

### Documento Editável

- [Cronograma e Orçamento do Projeto - Editável](artefatos/Smart_Pantry-Atualizado.mpp)

```diff
+ Tarefa 07:
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 08:
+ Orçamento do Projeto
```

# Orçamento do Projeto
### Documento Editável

- [Cronograma e Orçamento do Projeto - Editável](artefatos/Smart_Pantry-Atualizado.mpp)

```diff
+ Tarefa 08:
+ Fim da seção a ser atualizada.
```

# Planos de Gerenciamento



```diff
+ Tarefa 09:
+ Checklist de Qualidade
```

## Plano de Qualidade

### Artefatos a serem verificados

| Artefato                  | Tipo Verif.                | Data        | Responsável                  | Métrica              | Data Correção| Ação Não Conform.  | Resp. Avaliação            | Resp. Correção            |
|---------------------------|----------------------------|-------------|------------------------------|----------------------|--------------|--------------------|----------------------------|---------------------------|
| Documento de Requisitos	  | Revisão	                   | 05/11/2024	 | Analista de Qualidade        | Conformidade	       |	            | Atualização	       |  Gerente de Projeto        | Analista de Qualidade     |
| Código de Software 	      | Teste	                     | 12/11/2024	 | Engenheiro de Software       |	Cobertura de Teste   |              | Correção de Erros  |	Líder de Equipe	          | Engenheiro de Software    |
| Diagrama de Arquitetura   | Revisão	                   | 07/11/2024	 | Arquiteto de Sistemas        |	Aderência ao Projeto |              | Ajuste de Design   |	Arquiteto de Sistemas	    | Arquiteto de Sistemas     |
| Interface do Usuário (UI) | Inspeção	                 | 15/11/2024	 | Designer de UX/UI            |	Funcionalidade       |              | Correção de Layout |	Gerente de Projeto      	| Designer de UX/UI         |
| Manual do Usuário	        | Testes de Integração  		 | 25/11/2024	 | Especialista em Qualidade	  |	Compreensão          |              | Seções complexas   |	Representante do Cliente 	|  Especialista em Qualidade|
| Firmware        	        | Testes de Legibilidade		 | 28/11/2024	 | Desenvolvedor de Firmware	  |	Integração           |              | Incompatibilidade  |	Testador de Sistema     	|  Desenvolvedor de Firmware|

### Padrões e Normas Utilizadas

| Nome           | Descrição                                                                                          | 
|----------------|----------------------------------------------------------------------------------------------------|
| ISO 9001       | Padrão de Sistema de Gestão da Qualidade para assegurar qualidade no desenvolvimento.              |
| IEEE 829       | Padrão para documentação de testes de software para garantir qualidade nos testes.                 |
| ISO/IEC 12207  | Padrão para processos de ciclo de vida de software.                                                |
| ISO 25010      | Padrões de qualidade de software que abordam requisitos de funcionalidade, usabilidade e segurança.|
| Clean Code     | Padrões de desenvolvimento para melhorar a legibilidade e manutenção do código-fonte.              |

### Ambiente das Atividades de Qualidade

| Ambiente                    | Descrição                                                              | 
|-----------------------------|------------------------------------------------------------------------|
| Ambiente de Desenvolvimento | Ambiente configurado com ferramentas de desenvolvimento de software.   |
| Ambiente de Testes          | Plataforma dedicada para execução e validação de testes dos sistemas.  |
| Ambiente de Integração      | Ambiente onde são realizadas atividades de integração e testes finais. |
| Ambiente de Produção        | Sistema real em operação, utilizado após validações finais e aprovação.|

### Equipe de Qualidade

| Nome                      | Responsabilidade                                  | 
|---------------------------|---------------------------------------------------|
| Analista de Qualidade     | Revisão de documentos e inspeção de qualidade.    |
| Engenheiro de Software    | Teste e verificação de código.                    |
| Arquiteto de Sistemas     | Avaliação e validação de arquitetura do sistema.  |
| Designer de UX/UI         | Verificação de qualidade da interface do usuário. |
| Especialista em Qualidade | Avaliação de Documentação e Controle de Qualidade |
| Desenvolvedor de Firmware | Desenvolvimento e Verificação de Firmware         |
| Testador de Sistema       | Testador de Sistema e Qualidade                   |

### Metodologias de Qualidade Utilizadas

| Nome                | Descrição                                                                                       | 
|---------------------|-------------------------------------------------------------------------------------------------|
| Scrum               | Metodologia ágil para planejamento e acompanhamento do desenvolvimento de software.             |
| Teste de Unidade    | Técnica para garantir que cada unidade do software funcione conforme o esperado.                |
| Teste de Integração | Técnica para validar a integração e a comunicação entre diferentes módulos.                     |
| Teste de Usabilidade| Verificação da interface para garantir que seja intuitiva e fácil para os usuários finais.      |
| Revisão por Pares   | Revisão dos artefatos de desenvolvimento por outros membros da equipe para assegurar qualidade. |
| Análise de Feedback | Coleta e avaliação de feedback de usuários para identificar melhorias e não conformidades.      |

```diff
+ Tarefa 09:
+ Fim da seção a ser atualizada.
```

```diff
+ Tarefa 10:
+ Especificação de Produto para Aquisição
```

## Plano de Aquisição

### Documento Editável

- [Sensor de Peso - Cotação](artefatos/SensordePesoCotacao.pdf)


```diff
+ Tarefa 10:
+ Fim da seção a ser atualizada.
```

```diff
+ Tarefa 11:
+ Plano de Comunicação
```

## Plano de Comunicação

- [Plano de Gerenciamento de Comunicação - Editável](artefatos/plano_comunicacao.docx)

### Plano de Comunicação do Projeto

Plano de Comunicação:

| Entregável                         | Público Alvo                       | Met. Comunicação       | Frequência  | Responsável          | 
|------------------------------------|------------------------------------|------------------------|-------------|----------------------|
| Ata de reunião                     | Equipe do projeto, gestores        | E-mail, reunião virtual | Semanal     | Gerente do projeto   |
| Declaração de escopo               | Equipe de desenvolvimento, stakeholders principais | E-mail, portal do projeto | Uma vez, no início | Analista de negócios |
| WBS                                | Equipe técnica, gestor de projetos | Portal do projeto      | Uma vez, após definição | Gerente do projeto   |
| Dicionário da WBS                  | Equipe técnica, stakeholders       | Portal do projeto      | Uma vez, após a criação da WBS | Gerente do projeto |
| Cronograma                         | Equipe do projeto, gestores, patrocinadores | Reunião presencial/virtual, e-mail | Mensal | Coordenador do cronograma |
| Lista de Riscos                    | Equipe do projeto, gestor de riscos | Reunião quinzenal, portal do projeto | Quinzenal | Gestor de riscos |
| Plano de qualidade                 | Equipe de desenvolvimento, gestores | E-mail, reunião virtual | Uma vez, revisão trimestral | Coordenador de qualidade |
| Plano de projeto                   | Stakeholders principais, patrocinadores | E-mail, reunião de apresentação | Uma vez, no início | Gerente do projeto |
| Relatório de Progresso             | Equipe do projeto, stakeholders principais | E-mail, portal do projeto | Mensal | PMO (Project Management Office) |
| Relatório de Aderência ao Processo | Equipe de controle de qualidade    | Reunião quinzenal       | Quinzenal   | Coordenador de qualidade |
| Checklists de Inspeção             | Equipe de QA, gerente de projeto   | Portal do projeto       | Antes de cada revisão | Analista de QA |
|Manual de Usuário	                 | Usuários finais	                  | E-mail, Google Drive	  | Na conclusão do projeto	| Equipe de Documentação
|Relatório de Testes	               | Equipe de Qualidade	              | Reunião virtual, Google Drive	| Semanal	| Equipe de Testes
|Documentação de Procedimentos de Backup	| Equipe de TI	                | E-mail, Google Drive	  | Na conclusão do projeto	| Administrador de Sistemas

Legenda:
- Público: a quem se destina a comunicação.
- Método de Comunicação: e_mail, reunião presencial, reunião virtual, etc.
- Freqüência: diária, semanal, quinzenal, mensal, etc.
- Responsável: pessoa responsável pela comunicação.

### Plano de Gerência de Comunicação

### Ferramentas utilizadas:
- **Ferramenta 01:** [Microsoft Teams](https://teams.microsoft.com) - Para comunicação e reuniões virtuais
- **Ferramenta 02:** [Trello/Jira](https://trello.com/) - Para o acompanhamento de tarefas e gestão do projeto
- **Ferramenta 03:** [Google Drive](https://drive.google.com) - Para armazenamento e compartilhamento de documentos

### Papéis:
- **Gerente de Projeto:** Responsável pela comunicação geral e pela distribuição de relatórios e atas.
- **Coordenador de Qualidade:** Responsável pelos relatórios de aderência e checklists de inspeção.
- **Gestor de Riscos:** Gerencia e comunica a lista de riscos aos envolvidos.
    
### Princípios gerais
- **Transparência:** As comunicações devem ser abertas e acessíveis, garantindo que todas as partes interessadas tenham as informações necessárias para acompanhar o progresso do projeto.
- **Pontualidade:** As informações devem ser comunicadas de maneira oportuna, evitando atrasos que possam impactar o andamento do projeto.
- **Consistência:** O formato e o conteúdo das comunicações devem seguir um padrão definido para facilitar a compreensão e a comparação entre relatórios ou atualizações.
- **Interatividade:** O plano deve permitir e incentivar a participação e feedback dos membros da equipe e das partes interessadas, promovendo um diálogo aberto.
- **Confidencialidade:** As comunicações devem proteger informações sensíveis e respeitar a privacidade dos dados do projeto e dos envolvidos.
- **Adaptabilidade:** A comunicação deve ser flexível o suficiente para se ajustar a diferentes situações e necessidades que possam surgir durante o projeto.
- **Acessibilidade:** As informações devem estar disponíveis em diferentes formatos e meios para que todos possam acessá-las, levando em conta eventuais necessidades especiais dos membros da equipe.
- **Relevância:** Somente informações pertinentes devem ser comunicadas, evitando sobrecarregar os destinatários com dados desnecessários.
- **Foco em Soluções:** A comunicação deve priorizar abordagens voltadas para a resolução de problemas e a identificação de alternativas viáveis.
- **Documentação:** Todas as comunicações importantes devem ser registradas e arquivadas para referência futura e auditorias.

### Plano de Gerência de Configuração
**Controle de Versões e Ferramentas Utilizadas:**

1. Microsoft Teams
- Uso: Comunicação e reuniões virtuais para discutir mudanças, alinhamentos de versão e revisões de configuração.
- Controle: Notificação de atualizações e discussões em tempo real sobre alterações nos artefatos.
- Responsabilidade: Todos os membros da equipe devem participar das reuniões de atualização e manter a comunicação clara sobre as mudanças.

2. Trello/Jira
- Uso: Acompanhamento de tarefas, solicitações de mudança e monitoramento do progresso das atividades relacionadas à gestão de configuração.
- Controle: O Gerente de Configuração cria e atualiza cartões/tarefas para mudanças aprovadas, rastreando seu status desde a solicitação até a implementação e revisão.
- Responsabilidade: O Gerente de Configuração é responsável por monitorar e atualizar as tarefas de configuração, enquanto os desenvolvedores e outros membros da equipe atualizam o status conforme completam as atividades.

3. Google Drive
- Uso: Armazenamento e compartilhamento centralizado de documentos e artefatos, garantindo acesso à versão mais atualizada dos arquivos.
- Controle: As versões são gerenciadas por meio do recurso de histórico de versões do Google Drive, permitindo reverter e verificar alterações anteriores.
- Responsabilidade: O responsável por cada documento deve garantir que apenas a versão final revisada seja disponibilizada na pasta de acesso geral, enquanto as versões de trabalho permanecem em pastas restritas.

**Processo de Controle de Versão:**

- Solicitação de Mudança: Solicitações de mudança são registradas no Trello/Jira e incluem detalhes como justificativa, descrição da mudança e impacto esperado.
- Avaliação e Aprovação: O Gerente de Configuração e o Gerente de Projetos revisam a solicitação e avaliam o impacto. Mudanças aprovadas são registradas com um novo cartão/tarefa e priorizadas.
- Implementação da Mudança: A equipe realiza as mudanças conforme as instruções e registra as atualizações no Google Drive.
- Revisão e Testes: O documento ou artefato atualizado é revisado pelo responsável da qualidade, e feedback é coletado em reuniões via Microsoft Teams.
- Distribuição: A versão final é movida para a pasta de entrega no Google Drive e uma notificação é enviada pelo Microsoft Teams para toda a equipe.

**Controle de Responsabilidades:**
- Gerente de Configuração: Responsável por supervisionar o processo de controle de versão e garantir que todos os procedimentos sejam seguidos.
- Gerente de Projetos: Aprova mudanças significativas e gerencia os impactos gerais no cronograma e orçamento.
- Equipe de Desenvolvimento/Qualidade: Implementa as mudanças e verifica a conformidade com os critérios estabelecidos.
- Equipe de Documentação: Atualiza os documentos necessários no Google Drive e notifica a equipe sobre as mudanças.

```diff
+ Tarefa 11:
+ Fim da seção a ser atualizada.
```

```diff
+ Tarefa 12:
+ Riscos do Projeto
```

## Plano de Riscos

- [Plano de Gerenciamento de Riscos - Editável](artefatos/plano_riscos.xls)

| Categoria do Risco        | Descrição do Risco                                     | Probabilidade | Impacto | Risco  | Medidas de Prevenção                       | Medidas de Contingência                  |
|---------------------------|-------------------------------------------------------|---------------|---------|--------|-------------------------------------------|------------------------------------------|
| Cliente                   | Falta de engajamento no uso do produto                | Alto          | Médio   | Alto   | Realizar workshops e treinamento para o cliente.                               | Oferecer suporte pós-venda e contato contínuo para feedback.                      |
| Cronograma                | Atrasos na entrega dos módulos do projeto             | Médio         | Alto    | Alto   | Monitorar prazos com ferramentas como Trello e realizar reuniões semanais.     | Redistribuir tarefas ou contratar recursos temporários.                           |
| Orçamento                 | Estouro de custos devido a itens imprevistos          | Alto          | Médio   | Alto   | Realizar planejamento financeiro detalhado e manter uma reserva orçamentária.  | Repriorizar funcionalidades ou buscar recursos adicionais com investidores.       |
| Hardware                  | Defeitos em componentes durante o uso                 | Médio         | Alto    | Alto   | Testar todos os componentes antes da instalação final.                         | Substituir imediatamente os componentes defeituosos e acionar a garantia.          |
| Fornecedores              | Atraso ou indisponibilidade de componentes críticos   | Alto          | Alto    | Alto   | Firmar contratos com cláusulas de prazo e manter fornecedores alternativos.    | Negociar prazos de entrega ou buscar soluções emergenciais no mercado local.       |
| Compatibilidade           | Incompatibilidade com sistemas existentes dos usuários | Médio         | Médio   | Médio  | Mapear os sistemas mais comuns e realizar testes de compatibilidade.           | Desenvolver módulos adaptadores ou realizar atualizações para integração.          |
| Documentação              | Falta de documentação clara para implementação         | Baixo         | Médio   | Médio  | Criar documentação detalhada desde o início e revisá-la periodicamente.        | Disponibilizar sessões de esclarecimento com a equipe de desenvolvimento.          |
| Clima Organizacional      | Resistência interna ao uso da nova tecnologia          | Médio         | Médio   | Médio  | Envolver os stakeholders desde o início e demonstrar os benefícios do sistema. | Realizar encontros de engajamento e ouvir sugestões para adaptações.               |
| Infraestrutura            | Rede local não suporta a demanda do sistema IoT        | Médio         | Médio   | Médio  | Realizar um levantamento prévio da infraestrutura e propor melhorias.          | Contratar serviços externos para adequação da infraestrutura de rede.              |
| Regulamentação            | Produto não atende a normativas de segurança e qualidade | Baixo         | Alto    | Médio  | Validar o produto de acordo com as regulamentações locais antes do lançamento. | Realizar adequações emergenciais e submeter o produto à certificação novamente.     |
| Treinamento Técnico       | Equipe técnica não compreende a configuração do sistema | Médio         | Alto    | Alto   | Fornecer treinamentos detalhados e criar guias de uso.                         | Alocar consultores especializados para solucionar problemas técnicos emergentes.    |
| Manutenção Pós-Entrega    | Falta de um plano estruturado para manutenção          | Baixo         | Médio   | Médio  | Criar contrato de manutenção com especificação de SLA.                        | Contratar serviço técnico terceirizado para emergências.                           |
| Dados e Privacidade       | Vazamento de dados dos usuários                        | Médio         | Alto    | Alto   | Implementar criptografia robusta e revisar políticas de segurança.             | Notificar usuários, corrigir falhas imediatamente e reforçar barreiras de segurança. |
| Desempenho do Sistema     | Lentidão ou travamento do sistema durante o uso        | Médio         | Médio   | Médio  | Realizar testes de carga e otimização de código antes do lançamento.           | Disponibilizar atualizações de software para corrigir problemas de desempenho.      |
| Interface do Usuário      | Dificuldade dos usuários em operar o sistema           | Baixo         | Médio   | Médio  | Conduzir testes de usabilidade com grupos de foco.                             | Atualizar a interface com base no feedback dos usuários.                           |
| Comunicação com a Equipe  | Falhas na troca de informações entre equipes           | Médio         | Alto    | Alto   | Estabelecer cronograma de reuniões frequentes e uso de ferramentas como Teams. | Alocar um mediador para identificar e resolver problemas de comunicação.            |
| Energia                   | Queda de energia prejudicando o funcionamento do sistema | Baixo         | Alto    | Médio  | Instalar sistemas de backup de energia como no-breaks.                        | Implementar medidas de recuperação rápida para reinício do sistema.                |

| Probabilidade | Impacto       | Risco         |
|---------------|---------------|---------------|
| Baixo         | Baixo         | Baixo         |
| Médio         | Médio         | Médio         |
| Alto          | Alto          | Alto          |
| Baixo         | Médio         | Médio         |
| Médio         | Baixo         | Médio         |
| Baixo         | Alto          | Médio         |
| Alto          | Baixo         | Médio         |
| Médio         | Alto          | Alto          |
| Alto          | Médio         | Alto          |


```diff
+ Tarefa 12:
+ Fim da seção a ser atualizada.
```

-----






