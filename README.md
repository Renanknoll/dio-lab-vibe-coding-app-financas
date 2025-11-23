# 💸 App de Finanças Pessoais com Vibe Coding com o uso do Lovable (Renan)

- **Prompt final** (PRD) do App refinado com agente Prompt Coach do Copilot:

```markdown
# Contexto
O objetivo é criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário, utilizando tecnologias de processamento de linguagem natural (NLP) e inteligência artificial (IA). A proposta é oferecer uma experiência simples e natural, eliminando a necessidade de formulários complexos ou planilhas, tornando o controle financeiro mais acessível e intuitivo.
 
# Problema
Muitas pessoas desistem de controlar seus gastos porque os aplicativos atuais exigem muita entrada manual, são pouco intuitivos e oferecem pouca personalização. Além disso, a falta de integração com outras ferramentas financeiras e a ausência de suporte em tempo real contribuem para a baixa adesão. A solução proposta é criar uma experiência baseada em interação conversacional, com automação e recomendações inteligentes, para reduzir a fricção e aumentar o engajamento.
 
# Público-Alvo
Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicações, incluindo jovens adultos, profissionais ocupados e indivíduos que não têm familiaridade com planilhas ou ferramentas complexas. O público-alvo também inclui aqueles que buscam uma solução financeira integrada e personalizada.
 
# Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural, permitindo que os usuários insiram despesas de forma rápida e intuitiva.
2. Registro de entradas de cartão de crédito, com integração automática com bancos e instituições financeiras.
3. Classificação automática das transações, utilizando algoritmos de aprendizado de máquina para categorizar despesas.
4. Definição e acompanhamento de metas financeiras, com notificações e lembretes personalizados.
5. Dicas de economia fornecidas pelo “Agente Financeiro”, com base nos hábitos de consumo do usuário.
6. Relatórios simples e personalizados (gráficos, resumo mensal), que oferecem uma visão clara e detalhada das finanças pessoais.
 
#Design Universal
Para garantir que o aplicativo seja acessível a todos os usuários, o design deve seguir os princípios de Design Universal, incluindo:
1. Acessibilidade: Interface compatível com leitores de tela e outras tecnologias assistivas.
2. Usabilidade: Navegação intuitiva e fácil de usar para pessoas com diferentes níveis de habilidade tecnológica.
3. Inclusão: Opções de personalização para atender às necessidades de usuários com deficiências visuais, auditivas, motoras ou cognitivas.
4. Consistência: Design visual e interativo consistente em todas as telas e funcionalidades.
 
# Entregável da IA
Gerar um plano de MVP contendo:
1. Principais telas do aplicativo, incluindo wireframes e descrições de funcionalidades.
2. Recursos necessários para implementação, como tecnologias, ferramentas e equipe de desenvolvimento.
3. Esboço de validação inicial com métricas e testes, detalhando os critérios de sucesso e os métodos de avaliação.
4. O documento deve usar tom educativo e linguagem acessível, totalmente em português, para garantir que todos os stakeholders compreendam claramente o projeto.
```

- Interações com o Lovable: 

> Crie um aplicativo baseado no PRD (Product Requirements Document) abaixo: {PRD}

> O chat para inclusão dos gastou ou entradas financeiras não está respondendo bem e não realiza os inputs. Preciso de uma aba que faça a interação com o usuário e sensibilize os dados no dashboard. Preciso também de uma aba com gráficos com os tipos de gastos mensais.
>> Resposta: Vou criar um sistema funcional de entrada de transações com formulário, gerenciamento de estado compartilhado e aba de gráficos de gastos mensais.
>> 
>> Sistema funcional criado com 3 abas: Dashboard (resumo em tempo real), Adicionar (formulário de transações) e Gráficos (visualização de gastos por categoria em pizza e barras).

- Prints do App em sua primeira versão:

<img width="1647" height="875" alt="image" src="https://github.com/user-attachments/assets/6e0236ce-5bb5-48fd-b757-a0e2f8c2552c" />

<img width="1645" height="875" alt="image" src="https://github.com/user-attachments/assets/8ea83bf2-6742-427f-af55-95ac082a4605" />

<img width="1647" height="877" alt="image" src="https://github.com/user-attachments/assets/f4785321-235b-43e0-9b42-56fbf5ed1b42" />

- Prints do App em sua versão final após interações:

<img width="1646" height="877" alt="image" src="https://github.com/user-attachments/assets/9592f0cb-7b33-43d9-99a2-d7f2c52572c5" />

<img width="1678" height="897" alt="image" src="https://github.com/user-attachments/assets/dccd588c-e46a-485a-ae57-876bf2da57f2" />

<img width="1683" height="892" alt="image" src="https://github.com/user-attachments/assets/ade78bcb-36ff-44d4-9c44-3345b678cf8c" />
  
- Resumo das funcionalidades do **App de Finanças Pessoais**:

O aplicativo de finanças pessoais "Assistente Financeiro" oferece uma experiência intuitiva e acessível para ajudar os usuários a gerenciar suas finanças de forma prática e eficiente. As principais funcionalidades incluem:

**Dashboard Principal**: Uma visão geral das finanças do usuário, incluindo saldo total, receitas, despesas e valor da fatura do cartão de crédito. O dashboard também apresenta um "Resumo Rápido" e uma seção de "Minhas Metas" com o progresso das metas financeiras, como Fundo de Emergência, Viagem para Europa e Entrada do Apartamento.

**Registro de Transações**: Uma tela dedicada para adicionar novas transações, permitindo que os usuários registrem receitas e despesas de forma rápida e intuitiva. O formulário inclui campos para selecionar o tipo de transação, categoria, descrição e valor em reais, com instruções claras para preenchimento.

**Classificação Automática**: Utilizando algoritmos de aprendizado de máquina, o aplicativo classifica automaticamente as transações em categorias específicas, facilitando o acompanhamento dos gastos.

**Definição e Acompanhamento de Metas**: Os usuários podem definir metas financeiras personalizadas e acompanhar seu progresso diretamente no aplicativo, com notificações e lembretes para manter o engajamento.

**Dicas de Economia**: O "Agente Financeiro" fornece dicas de economia personalizadas com base nos hábitos de consumo do usuário, ajudando a otimizar o orçamento e alcançar as metas financeiras.

**Relatórios e Gráficos**: O aplicativo oferece relatórios simples e personalizados, incluindo gráficos de pizza e barras que mostram a distribuição e os valores absolutos dos gastos por categoria. Esses relatórios fornecem uma visão clara e detalhada das finanças pessoais, ajudando os usuários a tomar decisões informadas.

**Design Universal**: O aplicativo segue os princípios de Design Universal para garantir acessibilidade e usabilidade para todos os usuários. Isso inclui compatibilidade com leitores de tela, navegação intuitiva, opções de personalização e um design visual consistente.

Essas funcionalidades visam proporcionar uma experiência de usuário fluida e eficiente, tornando o controle financeiro mais acessível e intuitivo para todos.

- Uma breve **reflexão sobre o processo**:
  
  - O que funcionou bem?
    > A facilidade que o Vibe Coding proporciona na criação e implementação de soluções para aplicativos gera ganhos de tempo, economia de recursos e possibilita a execução destas tarefas por leigos em tecnologia.
    
  - O que não funcionou como o esperado?
    > Na primeira interação o programa foi criado com o chat com IA mas não estava fazendo os inputs corretamente no sistema. Quando solicitei a correção ele eliminou o chat e criou uma aba para inserção manual dos dados. Este problema não foi corrigido por falta de créditos na versão demo do Lovable.
    
  - O que aprendeu sobre conversar com IAs?
    > A experiência foi extremamente positiva com a descoberta da possibilidade de utilizar a IA para nortear as implementações computacionais necessárias para solucionar problemas diários com o uso de prompts, aplicativos, agentes de IA e chatbots.
