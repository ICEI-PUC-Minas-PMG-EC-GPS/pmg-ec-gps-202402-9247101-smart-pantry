# Planejamento

> A fase de planejamento na gerência de projetos é um momento onde os detalhes do projeto são minuciosamente definidos para garantir uma execução bem-sucedida. 
> Durante essa etapa, os gerentes de projeto e suas equipes elaboram um plano abrangente que aborda aspectos como cronograma, orçamento, recursos necessários, riscos identificados e métodos de controle. 
> O objetivo é criar uma estrutura que guiará as atividades ao longo do projeto, garantindo que metas sejam alcançadas de maneira eficiente. 
> O plano de projeto não apenas define as tarefas específicas e suas interdependências, mas também estabelece critérios de sucesso e indicadores de desempenho. 
> A qualidade do planejamento influencia diretamente a capacidade da equipe em cumprir prazos, alocar recursos eficientemente e lidar com desafios que possam surgir durante a execução.

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

> O escopo do projeto define os limites, objetivos e entregáveis do projeto, estabelecendo clareza sobre o que será realizado e o que está excluído do escopo. 
> O escopo assegura a alocação adequada de recursos, evita desvios dos objetivos do projeto e garante que as expectativas dos stakeholders sejam atendidas. 
> A definição do escopo inclui documentação detalhada dos requisitos, restrições e premissas do projeto. 
> Ao longo do ciclo de vida do projeto, a gestão do escopo também inclui o controle de mudanças, garantindo que qualquer ajuste seja avaliado quanto ao seu impacto e aprovado de maneira adequada. 
> Utilize como referência a documentação existente na [Fase de Iniciação](/docs/01-iniciacao).

# Estrutura Analítica do Projeto

![Estrutura Analítica do Projeto](images/Estrutura_Analitica_do_Projeto.png)

> Softwares recomendados: 
> * [WBS Schedule Pro (Demo)](https://www.criticaltools.com/)
> * [Draw.io](https://app.diagrams.net/)
> * [ProjectLibre](https://www.projectlibre.com/)

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

> A Matriz de Responsabilidades é uma ferramenta para definir e indicar as responsabilidades de cada membro da equipe em relação às atividades do projeto. 
> Também conhecida como RACI (Responsável, Aprovador, Consultado e Informado), essa matriz atribui papéis específicos a cada envolvido, indicando quem é responsável pela execução de uma tarefa, quem deve aprovar, quem precisa ser consultado e quem deve ser mantido informado. 
> Ao criar uma visão visual e estruturada das responsabilidades, a matriz RACI minimiza ambiguidades e conflitos de papel.
> Essa ferramenta não apenas esclarece as expectativas em termos de contribuições individuais, mas também contribui para um ambiente de trabalho mais organizado e transparente, resultando em uma gestão de projeto mais eficaz e bem-sucedida.

![Matriz RACI](images/ORGANOGRAMA_RACI.png)
![Legenda](images/LEGENDA.png)
![Recursos Humanos](images/Recursos_Humanos.png)

> Informações Adicionais:
> * **R**esponsible -> Executor (pessoa(s) que executará(ão)/desenvolverá(ão) a atividade)
> * **A**ccountable -> Responsável (pessoa responsável por aprovar a atividade)
> * **C**onsulted   -> Consultado (especialista consultado sobre a atividade ou parte dela)
> * **I**nformed    -> Informado (pessoas interessadas no projeto que devem ser informadas sobre a execução).
> 
> Link de auxílio: https://www.forbes.com/advisor/business/raci-chart/

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

......  DESCREVA EM LINHAS GERAIS O CRONOGRAMA DO SEU PROJETO AQUI ......

> O cronograma do projeto fornece uma representação temporal detalhada de todas as atividades, marcos e eventos ao longo do ciclo de vida do projeto. 
> Elaborado durante o planejamento, o cronograma é uma ferramenta que oferece uma visão das interdependências entre as tarefas, alocando recursos e definindo prazos para as entregas.
> Utilizando técnicas como a análise de rede (PERT/CPM) e estimativas de duração, o cronograma ajuda na identificação de caminhos críticos, permitindo aos gestores de projeto otimizar recursos, antecipar potenciais atrasos e tomar decisões. 
> Além disso, o cronograma serve como um guia para monitorar o progresso, comunicar efetivamente com a equipe e as partes interessadas, e ajustar estratégias para garantir a conclusão bem-sucedida do projeto dentro dos prazos estabelecidos.

![image](https://github.com/user-attachments/assets/128739f7-470d-484c-a1a7-9ba991b8f493)
![image](https://github.com/user-attachments/assets/3d335d79-3ca9-4aeb-b4ac-d3f3192f7c85)

### Documento Editável

> Você deve atualiza o seguinte link (ou link correspondente), como o arquivo editável do Cronograma do Projeto:
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

......  DESCREVA EM LINHAS GERAIS O ORÇAMENTO DO SEU PROJETO AQUI ......

> O orçamento do projeto envolve a estimativa e alocação de recursos financeiros necessários para a execução bem-sucedida do projeto, abrangendo custos diretos e indiretos, despesas operacionais, investimentos em equipamentos, pessoal, entre outros. 
> O desenvolvimento do orçamento deve considerar variáveis como riscos, imprevistos e mudanças no escopo. 
> Uma vez estabelecido, o orçamento serve como guia para a utilização eficiente dos recursos financeiros ao longo do projeto. 
> A gestão do orçamento não apenas ajuda a controlar os custos, mas também fornece transparência e prestação de contas, permitindo que gestores tomem decisões informadas e evitem surpresas financeiras ao longo do ciclo de vida do projeto. 
> Assim, o orçamento contribui para o sucesso do projeto, garantindo a viabilidade econômica e a entrega dentro das expectativas financeiras estabelecidas.

### Documento Editável

> Você deve atualiza o seguinte link (ou link correspondente), como o arquivo editável do Orçamento do Projeto:
- [Cronograma e Orçamento do Projeto - Editável](artefatos/Smart_Pantry-Atualizado.mpp)

```diff
+ Tarefa 08:
+ Fim da seção a ser atualizada.
```

# Planos de Gerenciamento

> Os planos de gerenciamento do projetos consolidam as diretrizes e estratégias para a execução bem-sucedida de um empreendimento. 
> Ele abrange diversos aspectos, como escopo, cronograma, custos, riscos, qualidade, recursos humanos, comunicação e aquisições, proporcionando uma visão abrangente e integrada do projeto. 
> Este plano funciona como um guia mestre que orienta a equipe de projeto e as partes interessadas ao longo do ciclo de vida do projeto, estabelecendo expectativas, responsabilidades e processos. 
> Além disso, serve como um instrumento de comunicação, alinhando as expectativas entre os membros da equipe e as partes interessadas, mitigando riscos e fornecendo uma estrutura sólida para a tomada de decisões. 

```diff
+ Tarefa 09:
+ Checklist de Qualidade
```

## Plano de Qualidade

...... DESCREVA SUCINTAMENTE O PLANO DE QUALIDADE UTILIZADO NO PROJETO ......

> O Plano de Qualidade auxilia a garantir que as entregas do projeto atendam aos padrões de qualidade definidos. 
> Este plano abrange atividades como definição de padrões, procedimentos de garantia de qualidade, critérios de aceitação e processos de monitoramento e controle da qualidade ao longo do ciclo de vida do projeto. 
> Ao identificar metas de qualidade, responsabilidades da equipe, e métricas de avaliação, o Plano de Qualidade busca assegurar que o projeto atinja ou exceda as expectativas dos stakeholders em termos de desempenho e conformidade. 
> A adoção de políticas de qualidade auxilia a mitigar riscos, promove a confiança nas entregas do projeto e, por fim, aumenta a probabilidade de sucesso do empreendimento. 

> Referência - Conceitual
> * https://www.researchgate.net/publication/230636169_Software_Quality_Assurance

> Normas de Qualidade:
> * https://repositorium.uminho.pt/bitstream/1822/27266/1/Tese_MEI_PG19676_Juliana%20Oliveira.pdf
> * https://cin.ufpe.br/~processos/TAES3/Livro/00-LIVRO/07-Normas%20ISO%20e%20Qualidade%20de%20Software-v6_CORRIGIDO.pdf

> Métricas de software:
> * https://repositorio.unicamp.br/Busca/Download?codigoArquivo=489087
> * https://lume.ufrgs.br/bitstream/handle/10183/66095/000870909.pdf?sequence=1
> * https://www.computerweekly.com/br/tip/23-metricas-de-desenvolvimento-de-software-que-devem-ser-monitoradas

> Processos de Garantia da Qualidade de Software
> * https://ceur-ws.org/Vol-3200/paper22.pdf
> * https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=d6bd60206282a2d4449e414e81a703612ef78a0c
> * https://www.testbytes.net/blog/quality-assurance-process-methodology/
> * https://www.projectmanager.com/blog/quality-assurance-and-testing

> Você pode utilizar como referência o seguinte documento:
> [Checklist de Qualidade](artefatos/checklist_qualidade.docx)

### Artefatos a serem verificados

| Artefato   | Tipo Verif. | Data        | Responsável | Métrica     | Data Correção | Ação Não Conform. | Resp. Avaliação | Resp. Correção |
|------------|-------------|-------------|-------------|-------------|---------------|-------------------|-----------------|----------------|
|            |             |             |             |             |               |                   |                 |                |
|            |             |             |             |             |               |                   |                 |                |
|            |             |             |             |             |               |                   |                 |                |
|            |             |             |             |             |               |                   |                 |                |
|            |             |             |             |             |               |                   |                 |                |
|            |             |             |             |             |               |                   |                 |                |

### Padrões e Normas Utilizadas

| Nome       | Descrição   | 
|------------|-------------|
|            |             |
|            |             |
|            |             |
|            |             |
|            |             |

### Ambiente das Atividades de Qualidade

| Ambiente   | Descrição   | 
|------------|-------------|
|            |             |
|            |             |
|            |             |
|            |             |

### Equipe de Qualidade

| Nome       | Responsabilidade | 
|------------|------------------|
|            |                  |
|            |                  |
|            |                  |
|            |                  |
|            |                  |

### Metodologias de Qualidade Utilizadas

| Nome       | Descrição   | 
|------------|-------------|
|            |             |
|            |             |
|            |             |

```diff
+ Tarefa 09:
+ Fim da seção a ser atualizada.
```

```diff
+ Tarefa 10:
+ Especificação de Produto para Aquisição
```

## Plano de Aquisição

> O Plano de Aquisições define o processo relacionado à aquisição de bens e serviços necessários para a execução do projeto. 
> Este plano abrange a identificação de necessidades, a seleção de fornecedores, a elaboração de contratos, e a gestão do relacionamento com os fornecedores durante do ciclo de vida do projeto. 
> O Plano de Aquisições visa garantir a aquisição eficiente e eficaz dos recursos necessários, minimizando riscos e custos. 
> Além disso, ele proporciona transparência nas relações com fornecedores, promovendo a conformidade com os prazos estabelecidos e padrões de qualidade. 

### Documento Editável

> Você deve atualiza o seguinte link (ou link correspondente), como o arquivo editável de geração da WBS:
- [Especificação Produto Aquisição - Editável](artefatos/aquisicao_produtos.docx)


```diff
+ Tarefa 10:
+ Fim da seção a ser atualizada.
```

```diff
+ Tarefa 11:
+ Plano de Comunicação
```

## Plano de Comunicação

...... DESCREVA SUCINTAMENTE O PLANO DE COMUNICAÇÃO UTILIZADO NO PROJETO ......

> O Plano de Comunicação estabelece estratégias e diretrizes para facilitar a troca de informações entre os membros da equipe e as partes interessadas. 
> Este plano abrange aspectos como os meios de comunicação, a frequência das atualizações, os canais de distribuição de informações e os responsáveis pela comunicação. 
> Uma comunicação eficiente não apenas previne mal-entendidos e conflitos, mas também fortalece o engajamento da equipe e o apoio das partes interessadas. 
>
> Você pode utilizar como referência o seguinte documento:
- [Plano de Gerenciamento de Comunicação - Editável](artefatos/plano_comunicacao.docx)

### Plano de Comunicação do Projeto

| Entregável                         | Público Alvo | Met. Comunicação | Frequência  | Responsável | 
|------------------------------------|--------------|------------------|-------------|-------------|
| Ata de reunião                     |              |                  |             |             |
| Declaração de escopo               |              |                  |             |             |
| WBS                                |              |                  |             |             |
| Dicionário da WBS                  |              |                  |             |             |
| Cronograma                         |              |                  |             |             |
| Lista de Riscos                    |              |                  |             |             |
| Plano de qualidade                 |              |                  |             |             |
| Plano de projeto                   |              |                  |             |             |
| Relatório de Progresso             |              |                  |             |             |
| Relatório de Aderência ao Processo |              |                  |             |             |
| Checklists de Inspeção             |              |                  |             |             |
|                                    |              |                  |             |             |
|                                    |              |                  |             |             |
|                                    |              |                  |             |             |

> Legenda:
> - Público: a quem se destina a comunicação.
> - Método de Comunicação: e_mail, reunião presencial, reunião virtual, etc.
> - Freqüência: diária, semanal, quinzenal, mensal, etc.
> - Responsável: pessoa responsável pela comunicação.

### Plano de Gerência de Comunicação

> Indique:
> - Ferramentas utilizadas no projeto - adicionar link de acesso às ferramentas
> - Papéis: responsáveis pelas correspondentes no projeto
> - Princípios gerais: indica quais princípios serão adotados no plano de comunicação, como clareza, objetividade, impessoalidade, imparcialidade e cordialidade. Detalhar.
>
> Plano de Gerência de Configuração: definir, em linhas gerais, como (ferramenta) serão controladas e distribuídas as versões e se haverá algum controle de responsabilidades.

- Ferramentas utilizadas:
- - [Ferramenta 01](https://pucminas.br)
  - [Ferramenta 02](https://pucminas.br)
  - [Ferramenta 03](https://pucminas.br)
- Papéis:
- - ...
  - ...
  - ...
- Princípios gerais
- - ...
  - ...
  - ...
  - ...

```diff
+ Tarefa 11:
+ Fim da seção a ser atualizada.
```

```diff
+ Tarefa 12:
+ Riscos do Projeto
```

## Plano de Riscos

......  COLOQUE AQUI O SEU TEXTO ......


> O plano de riscos busca antecipar, avaliar e mitigar os desafios potenciais que podem surgir ao longo do projeto. 
> Este documento estratégico oferece uma visão global dos riscos, categorizando-os e delineando estratégias para lidar com cada uma das possíveis adversidades. 
> Inicialmente, é realizada a identificação detalhada dos riscos, abrangendo desde ameaças imprevistas até oportunidades que podem ser exploradas. 
> Uma vez catalogados, os riscos são avaliados quanto à sua probabilidade de ocorrência e impacto, permitindo a priorização e foco em áreas críticas.
>
> O plano de riscos não apenas destaca os perigos em potencial, mas também estabelece respostas e estratégias de contingência. 
> Isso inclui a definição de ações preventivas para mitigar riscos antes que se materializem, bem como estratégias de mitigação para minimizar seu impacto se ocorrerem. 
> Além disso, a identificação de pontos de monitoramento contínuo ao longo do projeto permite uma resposta ágil às mudanças nas condições do ambiente.
>
> Você pode utilizar como referência o seguinte documento:
- [Plano de Gerenciamento de Riscos - Editável](artefatos/plano_riscos.xls)

| Categoria do Risco  | Descrição do Risco | Impacto       | Risco         | Medidas de Prevenção (Contramedidas) | Medidas de Contingência (Mitigação) | 
|---------------------|--------------------|---------------|---------------|--------------------------------------|-------------------------------------|
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |

> Indique:
> Categoria do Risco: *ex.: Cliente, Cronograma, Orçamento, Aquisição de produtos, etc*
> Descrição do Risco: *ex.: Cliente não aparenta ter muito interesse no projeto*
> Impacto: *Baixo / Médio / Alto*
> Risco: *Baixo / Médio / Alto*
> Medidas de Prevenção: *Medidas que devem ser adotadas para evitar que o risco se concretize*
> Medidas de Contingência: *Medidas que devem ser adotadas caso o risco se concretize*
>
> *Obs.: Para determinar o risco considere a seguinte combinação entre Probabilidade e Impacto:

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






