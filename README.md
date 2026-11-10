# 💸 App de Finanças Pessoais de Alexandre Torres com Vibe Coding

PRD Refinado no Copilot Web

***markdown
# PRD — FINANÇAS PESSOAIS INTELIGENTES

**Versão:** 1.0  
**Status:** Aprovado para especificação do MVP  
**Idioma:** Português brasileiro (pt-BR)  
**Produto:** Aplicação web responsiva  
**Abordagem:** AI First / Vibe Coding  
**Público:** Pessoas que desejam organizar suas finanças pessoais de maneira simples e inteligente.

---

# 1. INTRODUÇÃO

## 1.1. Visão estratégica do produto

O Finanças Pessoais Inteligentes é uma aplicação web de organização financeira pessoal que utiliza inteligência artificial para simplificar o controle de receitas, despesas, orçamentos e metas financeiras.

A proposta é substituir a experiência tradicional de preenchimento manual de formulários por uma experiência conversacional, na qual o usuário pode registrar movimentações financeiras, consultar informações e receber orientações personalizadas por meio de um Agente Financeiro Inteligente.

O produto combina organização financeira, visualização de dados e inteligência artificial em uma única plataforma.

## 1.2. Público-alvo

O produto é direcionado a:

- Pessoas que desejam começar a organizar suas finanças.
- Jovens adultos que estão desenvolvendo hábitos financeiros.
- Profissionais autônomos e freelancers.
- Pessoas que possuem dificuldade em controlar despesas recorrentes.
- Usuários que desejam economizar e estabelecer metas financeiras.
- Pessoas que preferem interagir por conversas em vez de utilizar planilhas e formulários complexos.

**Perfil principal:** usuário iniciante ou intermediário em educação financeira, que procura praticidade, clareza e orientação para tomar decisões melhores sobre seu dinheiro.

## 1.3. Objetivo do MVP

Entregar uma experiência funcional de organização financeira que permita:

1. Registrar receitas e despesas por linguagem natural.
2. Classificar automaticamente movimentações financeiras.
3. Consultar o panorama financeiro em um dashboard.
4. Criar metas e acompanhar orçamentos.
5. Receber análises e recomendações de economia por meio de IA.
6. Visualizar relatórios financeiros simples e compreensíveis.

O MVP deverá validar se uma experiência conversacional reduz o esforço necessário para manter o controle financeiro e incentiva o uso recorrente do aplicativo.

---

# 2. DECLARAÇÃO DO PROBLEMA

Muitas pessoas enfrentam dificuldades para organizar suas finanças pessoais porque os aplicativos tradicionais exigem o preenchimento manual de diversas informações, apresentam interfaces complexas e oferecem pouca personalização.

Além disso, a criação de orçamentos e o acompanhamento de metas financeiras são percebidos como atividades trabalhosas, fazendo com que muitos usuários abandonem o controle financeiro.

O Finanças Pessoais Inteligentes resolve esse problema por meio de uma experiência conversacional com inteligência artificial, permitindo que o usuário registre movimentações, acompanhe seus resultados e receba recomendações personalizadas de maneira simples e acessível.

## 2.1. Hipótese do produto

Se o usuário conseguir registrar suas movimentações financeiras por meio de conversas naturais e receber informações úteis sobre seus hábitos de consumo, então o esforço de organização financeira será reduzido e a frequência de utilização do aplicativo poderá aumentar.

---

# 3. VISÃO GERAL DA SOLUÇÃO

O produto funcionará como um assistente financeiro pessoal inteligente, centralizando registros financeiros, planejamento, metas e análises.

A interface terá o chat como um dos principais pontos de interação, sem eliminar a possibilidade de realizar operações manualmente.

## 3.1. Funcionalidades principais

**F01 — Registro financeiro conversacional**

Permitir que o usuário informe receitas e despesas utilizando linguagem natural.

Exemplo:
"Hoje gastei R$ 45 no almoço."

O agente deverá interpretar o valor, identificar a natureza da movimentação, sugerir uma categoria e solicitar confirmação quando houver ambiguidade.

**F02 — Classificação inteligente**

Classificar automaticamente receitas e despesas em categorias como:

- Alimentação.
- Transporte.
- Moradia.
- Saúde.
- Educação.
- Lazer.
- Compras.
- Salário.
- Investimentos.
- Outros.

O usuário poderá alterar a classificação.

**F03 — Dashboard financeiro**

Apresentar um resumo da situação financeira, incluindo saldo, receitas, despesas, evolução mensal e distribuição de gastos.

**F04 — Planejamento e metas**

Permitir a criação de objetivos financeiros, definição de limites por categoria e acompanhamento do progresso.

**F05 — Agente Financeiro Inteligente**

Interpretar informações financeiras, identificar padrões de consumo e sugerir estratégias de economia.

**F06 — Relatórios e insights**

Apresentar análises de receitas, despesas, categorias de gastos e evolução financeira.

**F07 — Gestão de perfil e configurações**

Permitir que o usuário personalize suas preferências, gerencie sua conta e configure o comportamento do aplicativo.

---

# 4. HISTÓRIAS DE USUÁRIO

## 4.1. Cadastro e acesso

**US01:** Como visitante, quero criar uma conta para acessar meu ambiente financeiro pessoal.

**US02:** Como usuário cadastrado, quero entrar na plataforma com segurança para consultar meus dados.

**US03:** Como usuário, quero recuperar minha senha caso não consiga acessar minha conta.

## 4.2. Dashboard

**US04:** Como usuário, quero visualizar meu saldo consolidado para compreender minha situação financeira.

**US05:** Como usuário, quero comparar receitas e despesas para identificar meu comportamento financeiro.

**US06:** Como usuário, quero visualizar minhas últimas movimentações para acompanhar minhas atividades recentes.

## 4.3. Agente Financeiro

**US07:** Como usuário, quero registrar despesas conversando com o agente para evitar preenchimentos manuais.

**US08:** Como usuário, quero registrar receitas por linguagem natural.

**US09:** Como usuário, quero receber sugestões de categorias para classificar automaticamente minhas movimentações.

**US10:** Como usuário, quero consultar meu saldo e meus gastos por meio de perguntas.

**US11:** Como usuário, quero receber sugestões de economia baseadas nos meus registros.

**US12:** Como usuário, quero revisar e confirmar movimentações interpretadas pela inteligência artificial.

## 4.4. Transações

**US13:** Como usuário, quero visualizar todas as minhas receitas e despesas em uma lista organizada.

**US14:** Como usuário, quero editar movimentações para corrigir informações.

**US15:** Como usuário, quero excluir movimentações registradas incorretamente.

**US16:** Como usuário, quero filtrar movimentações por período, categoria e tipo.

## 4.5. Planejamento e metas

**US17:** Como usuário, quero criar metas financeiras com valores e prazos definidos.

**US18:** Como usuário, quero acompanhar o progresso das minhas metas.

**US19:** Como usuário, quero estabelecer limites de gastos por categoria.

**US20:** Como usuário, quero receber alertas quando estiver próximo de ultrapassar meu orçamento.

## 4.6. Relatórios e configurações

**US21:** Como usuário, quero visualizar relatórios mensais para entender minha evolução financeira.

**US22:** Como usuário, quero receber insights sobre padrões de consumo.

**US23:** Como usuário, quero personalizar meu perfil e minhas preferências.

---

# 5. ESQUEMA DO BANCO DE DADOS

## 5.1. Diretrizes gerais

O banco de dados deverá utilizar PostgreSQL, preferencialmente por meio do Supabase.

Todos os registros financeiros devem estar associados ao usuário proprietário.

Identificadores devem utilizar UUID. Datas devem ser armazenadas em timestamps com timezone quando representarem instantes. Valores monetários devem utilizar NUMERIC, nunca FLOAT ou DOUBLE PRECISION.

O armazenamento de valores monetários deverá utilizar duas casas decimais e moeda padrão BRL.

## 5.2. Tabela: profiles

Armazena informações complementares do usuário autenticado.

- id: UUID, obrigatório, chave primária e FK → auth.users.id.
- nome: VARCHAR(100), obrigatório.
- email: VARCHAR(255), obrigatório.
- avatar_url: TEXT, opcional.
- moeda: VARCHAR(3), obrigatório, padrão BRL.
- timezone: VARCHAR(50), obrigatório, padrão America/Sao_Paulo.
- criado_em: TIMESTAMPTZ, obrigatório.
- atualizado_em: TIMESTAMPTZ, obrigatório.

## 5.3. Tabela: transactions

Armazena receitas e despesas.

- id: UUID, obrigatório, chave primária.
- usuario_id: UUID, obrigatório, FK → profiles.id.
- tipo: ENUM(receita, despesa), obrigatório.
- descricao: VARCHAR(200), obrigatório.
- valor: NUMERIC(14,2), obrigatório, maior que zero.
- categoria_id: UUID, obrigatório, FK → categories.id.
- data_transacao: DATE, obrigatório.
- observacao: TEXT, opcional.
- origem: ENUM(manual, chat), obrigatório.
- status: ENUM(confirmada, pendente), obrigatório.
- criado_em: TIMESTAMPTZ, obrigatório.
- atualizado_em: TIMESTAMPTZ, obrigatório.

## 5.4. Tabela: categories

Armazena categorias de receitas e despesas.

- id: UUID, obrigatório, chave primária.
- usuario_id: UUID, opcional, FK → profiles.id.
- nome: VARCHAR(80), obrigatório.
- tipo: ENUM(receita, despesa), obrigatório.
- icone: VARCHAR(50), opcional.
- cor: VARCHAR(20), opcional.
- categoria_padrao: BOOLEAN, obrigatório, padrão false.
- criado_em: TIMESTAMPTZ, obrigatório.

Categorias padrão poderão ser compartilhadas logicamente entre usuários. Categorias personalizadas deverão pertencer ao usuário que as criou.

## 5.5. Tabela: budgets

Armazena orçamentos por categoria e período.

- id: UUID, obrigatório, chave primária.
- usuario_id: UUID, obrigatório, FK → profiles.id.
- categoria_id: UUID, obrigatório, FK → categories.id.
- nome: VARCHAR(100), obrigatório.
- limite: NUMERIC(14,2), obrigatório, maior que zero.
- periodo: ENUM(mensal, semanal, anual), obrigatório.
- data_inicio: DATE, obrigatório.
- data_fim: DATE, opcional.
- ativo: BOOLEAN, obrigatório, padrão true.
- criado_em: TIMESTAMPTZ, obrigatório.

## 5.6. Tabela: goals

Armazena metas financeiras.

- id: UUID, obrigatório, chave primária.
- usuario_id: UUID, obrigatório, FK → profiles.id.
- titulo: VARCHAR(120), obrigatório.
- descricao: TEXT, opcional.
- valor_objetivo: NUMERIC(14,2), obrigatório, maior que zero.
- valor_atual: NUMERIC(14,2), obrigatório, padrão zero.
- data_limite: DATE, opcional.
- status: ENUM(em_andamento, concluida, cancelada), obrigatório.
- criado_em: TIMESTAMPTZ, obrigatório.
- atualizado_em: TIMESTAMPTZ, obrigatório.

## 5.7. Tabela: chat_messages

Armazena o histórico de conversas.

- id: UUID, obrigatório, chave primária.
- usuario_id: UUID, obrigatório, FK → profiles.id.
- sessao_id: UUID, obrigatório.
- papel: ENUM(user, assistant), obrigatório.
- conteudo: TEXT, obrigatório.
- criado_em: TIMESTAMPTZ, obrigatório.

Não armazenar tokens secretos, credenciais bancárias ou informações de autenticação no histórico.

## 5.8. Tabela: ai_insights

Armazena recomendações e análises produzidas pelo agente.

- id: UUID, obrigatório, chave primária.
- usuario_id: UUID, obrigatório, FK → profiles.id.
- titulo: VARCHAR(150), obrigatório.
- descricao: TEXT, obrigatório.
- tipo: ENUM(economia, alerta, comportamento, planejamento), obrigatório.
- prioridade: ENUM(baixa, media, alta), obrigatório.
- lido: BOOLEAN, obrigatório, padrão false.
- criado_em: TIMESTAMPTZ, obrigatório.

## 5.9. Tabela: notifications

Armazena notificações do usuário.

- id: UUID, obrigatório, chave primária.
- usuario_id: UUID, obrigatório, FK → profiles.id.
- titulo: VARCHAR(150), obrigatório.
- mensagem: TEXT, obrigatório.
- tipo: VARCHAR(40), obrigatório.
- lida: BOOLEAN, obrigatório, padrão false.
- criado_em: TIMESTAMPTZ, obrigatório.

## 5.10. Relacionamentos

- profiles → transactions (1:N).
- profiles → categories (1:N, para categorias personalizadas).
- profiles → budgets (1:N).
- profiles → goals (1:N).
- profiles → chat_messages (1:N).
- profiles → ai_insights (1:N).
- profiles → notifications (1:N).
- categories → transactions (1:N).
- categories → budgets (1:N).

## 5.11. Integridade e segurança do banco

- Utilizar Row Level Security (RLS) nas tabelas que armazenam dados de usuários.
- Permitir leitura e alteração somente pelo proprietário dos registros.
- Validar todas as operações no backend.
- Criar índices para usuario_id, data_transacao e categoria_id nas tabelas apropriadas.
- Utilizar políticas específicas para registros de categorias compartilhadas.
- Evitar exclusões em cascata que possam remover dados financeiros acidentalmente.
- Registrar datas de criação e atualização de maneira consistente.

---

# 6. ESTÉTICA E IDENTIDADE VISUAL

## 6.1. Direção criativa

A identidade visual deverá transmitir inovação, inteligência, confiança e sofisticação.

O produto seguirá uma estética AI First / Futurista, inspirada em plataformas modernas de inteligência artificial e fintechs premium.

A interface deverá combinar fundos escuros, gradientes sutis, elementos translúcidos, iluminação em tons de roxo e azul e componentes com cantos arredondados.

O resultado deverá ser moderno sem comprometer a legibilidade e a facilidade de utilização.

## 6.2. Paleta visual

- Background principal: #090B16.
- Background secundário: #111426.
- Superfícies e cards: #181B30.
- Roxo principal: #8B5CF6.
- Azul de destaque: #3B82F6.
- Ciano complementar: #22D3EE.
- Verde positivo: #22C55E.
- Vermelho negativo: #F87171.
- Texto principal: #F8FAFC.
- Texto secundário: #94A3B8.

## 6.3. Tipografia

Utilizar uma fonte moderna sem serifa, preferencialmente Inter ou Geist.

- Títulos: peso 600 ou 700.
- Subtítulos: peso 500 ou 600.
- Textos: peso 400.
- Valores financeiros: peso 600 ou 700, com destaque visual.

## 6.4. Componentes visuais

- Cards com cantos arredondados.
- Bordas discretas e superfícies em camadas.
- Gradientes sutis em elementos de destaque.
- Gráficos modernos e legíveis.
- Ícones consistentes.
- Feedback visual em ações e estados.
- Animações sutis de transição.
- Indicadores de progresso para metas e orçamentos.

## 6.5. Responsividade

A aplicação deverá funcionar em:

- Desktop.
- Tablets.
- Smartphones.

No desktop, utilizar navegação lateral persistente.

No mobile, utilizar navegação adaptada, com acesso simplificado às seis áreas principais.

A interface deverá priorizar acessibilidade, contraste adequado, navegação por teclado e áreas de toque confortáveis.

---

# 7. ESQUEMA DE TELAS E AÇÕES

# UI01 — DASHBOARD FINANCEIRO

**Rota:** /dashboard

## Objetivo

Apresentar uma visão consolidada da situação financeira do usuário.

## Elementos

- Saudação personalizada.
- Nome do usuário.
- Indicador de notificações.
- Seletor de período.
- Card de saldo total.
- Card de receitas do período.
- Card de despesas do período.
- Card de economia líquida.
- Gráfico de receitas versus despesas.
- Gráfico de distribuição de gastos por categoria.
- Lista de últimas transações.
- Resumo das metas financeiras.
- Card com insight destacado do Agente Financeiro.
- Atalho para iniciar uma conversa com o agente.

## Ações

**CA01 — Selecionar período**

Ao alterar o período, atualizar todos os indicadores e gráficos utilizando as movimentações correspondentes.

**CA02 — Visualizar transação**

Ao selecionar uma movimentação, abrir seus detalhes.

**CA03 — Abrir assistente**

Ao selecionar o atalho do agente, navegar para /assistant.

**CA04 — Visualizar relatórios**

Ao selecionar um gráfico ou link de análise, navegar para /reports com o período correspondente.

## Regras de negócio

- Saldo consolidado = total de receitas confirmadas - total de despesas confirmadas.
- Receitas e despesas devem considerar o período selecionado.
- Economia líquida = receitas - despesas.
- Transações pendentes não entram nos totais confirmados.
- Valores devem utilizar a formatação brasileira: R$ 1.250,00.
- Na ausência de movimentações, apresentar estado vazio com orientação para registrar a primeira transação.

---

# UI02 — CHAT COM O AGENTE FINANCEIRO

**Rota:** /assistant

## Objetivo

Permitir que o usuário interaja com seu assistente financeiro utilizando linguagem natural.

## Elementos

- Cabeçalho com identificação do Agente Financeiro.
- Indicador de disponibilidade.
- Histórico de conversas.
- Mensagens do usuário.
- Mensagens do agente.
- Campo de entrada de texto.
- Botão de envio.
- Indicador de processamento.
- Sugestões de perguntas.
- Cards de confirmação de transações.
- Atalho para consultar saldo.
- Atalho para consultar metas.

## Exemplos de interação

**Exemplo 1 — Registro de despesa**

Usuário:
"Gastei R$ 80 no supermercado hoje."

Agente:
"Identifiquei uma despesa de R$ 80,00 na categoria Alimentação. Deseja registrar essa movimentação?"

Ações:
- Confirmar registro.
- Editar informações.
- Cancelar.

**Exemplo 2 — Consulta financeira**

Usuário:
"Quanto gastei com alimentação este mês?"

Agente:
"Você gastou R$ 650,00 com alimentação no período consultado."

**Exemplo 3 — Planejamento**

Usuário:
"Quero economizar R$ 3.000 até dezembro."

Agente:
"Vamos estruturar essa meta! Para alcançar R$ 3.000, precisamos considerar o prazo e sua capacidade atual de economia."

O agente deverá coletar informações adicionais quando necessário, sem inventar renda, despesas ou condições financeiras.

## Ações

**CA05 — Enviar mensagem**

- Validar se a mensagem possui conteúdo.
- Enviar a mensagem ao backend.
- Processar a solicitação utilizando o contexto financeiro autorizado.
- Exibir a resposta.
- Salvar o histórico da conversa.

**CA06 — Confirmar transação**

- Validar os dados interpretados.
- Criar a transação no banco de dados.
- Atualizar os indicadores financeiros.
- Informar o resultado ao usuário.

**CA07 — Editar transação sugerida**

Permitir corrigir valor, descrição, categoria e data antes da confirmação.

**CA08 — Cancelar operação**

Descartar a operação ainda não confirmada, sem criar movimentação financeira.

## Regras de negócio

- Toda transação criada por IA deve passar por confirmação explícita.
- Mensagens não podem criar movimentações financeiras sem autorização do usuário.
- O agente só pode consultar dados pertencentes ao usuário autenticado.
- Se houver ambiguidade, solicitar esclarecimento.
- Se a IA estiver indisponível, informar o erro e permitir o registro manual.
- O histórico deverá respeitar as permissões do usuário.
- A IA não deverá realizar transferências bancárias, pagamentos ou movimentações de dinheiro.

---

# UI03 — TRANSAÇÕES

**Rota:** /transactions

## Objetivo

Permitir a consulta e administração das receitas e despesas.

## Elementos

- Título "Transações".
- Resumo de receitas.
- Resumo de despesas.
- Saldo do período.
- Botão "Nova transação".
- Botão "Registrar com IA".
- Campo de pesquisa.
- Filtro por tipo.
- Filtro por categoria.
- Filtro por período.
- Lista de transações.
- Identificação visual de receitas e despesas.
- Paginação ou carregamento progressivo.

## Formulário de transação

Campos:

- Tipo: Receita ou Despesa.
- Descrição: obrigatório, máximo 200 caracteres.
- Valor: obrigatório, maior que zero.
- Categoria: obrigatória.
- Data: obrigatória.
- Observação: opcional, máximo 1.000 caracteres.

## Ações

**CA09 — Criar transação**

Validar os campos e salvar a movimentação.

**CA10 — Editar transação**

Permitir atualizar os dados da movimentação.

**CA11 — Excluir transação**

Solicitar confirmação antes da exclusão.

**CA12 — Filtrar transações**

Atualizar a lista conforme os filtros selecionados.

**CA13 — Registrar com IA**

Direcionar o usuário para /assistant.

## Regras de negócio

- O valor deve ser positivo.
- A descrição é obrigatória.
- Toda transação deverá possuir uma categoria compatível com seu tipo.
- O usuário só poderá editar ou excluir suas próprias movimentações.
- Uma exclusão não deverá ser executada sem confirmação.
- Alterações deverão atualizar os indicadores financeiros.

---

# UI04 — PLANEJAMENTO E METAS FINANCEIRAS

**Rota:** /planning

## Objetivo

Permitir que o usuário estabeleça objetivos financeiros e acompanhe seus limites de gastos.

## Elementos

- Título "Planejamento financeiro".
- Resumo dos orçamentos.
- Lista de metas financeiras.
- Progresso de cada meta.
- Valor objetivo.
- Valor acumulado.
- Valor restante.
- Data limite.
- Orçamentos por categoria.
- Indicadores de utilização do orçamento.
- Sugestões de planejamento do agente.
- Botão "Nova meta".
- Botão "Novo orçamento".

## Formulário de meta

Campos:

- Nome da meta: obrigatório, máximo 120 caracteres.
- Descrição: opcional.
- Valor objetivo: obrigatório, maior que zero.
- Valor atual: inicia em zero.
- Data limite: opcional.

Exemplos:

- Reserva de emergência.
- Viagem.
- Compra de um veículo.
- Quitação de dívida.
- Compra de um imóvel.

## Formulário de orçamento

Campos:

- Nome: obrigatório.
- Categoria: obrigatória.
- Limite financeiro: obrigatório.
- Periodicidade: semanal, mensal ou anual.
- Data inicial: obrigatória.

## Ações

**CA14 — Criar meta**

Salvar a meta financeira.

**CA15 — Atualizar progresso**

Permitir registrar aportes ou ajustes no valor acumulado, mantendo o histórico da alteração quando houver movimentação.

**CA16 — Editar meta**

Atualizar informações da meta.

**CA17 — Criar orçamento**

Definir limite de gastos para uma categoria.

**CA18 — Acompanhar orçamento**

Comparar despesas confirmadas da categoria com o limite definido.

**CA19 — Receber recomendação**

Solicitar ao agente uma sugestão de planejamento.

## Regras de negócio

- O progresso percentual será calculado por valor atual dividido pelo valor objetivo, multiplicado por 100.
- Metas concluídas não poderão receber novos aportes sem reativação.
- Orçamentos devem considerar somente despesas confirmadas.
- Alertas devem ser apresentados quando o usuário atingir 80% e 100% do limite.
- O aplicativo não deverá alterar valores de metas automaticamente com base em recomendações da IA.
- Metas e orçamentos devem pertencer ao usuário autenticado.

---

# UI05 — RELATÓRIOS E INSIGHTS

**Rota:** /reports

## Objetivo

Apresentar informações que ajudem o usuário a compreender seu comportamento financeiro.

## Elementos

- Título "Relatórios e insights".
- Seletor de período.
- Resumo de receitas.
- Resumo de despesas.
- Evolução do saldo.
- Gráfico de receitas versus despesas.
- Gráfico de despesas por categoria.
- Comparação entre períodos.
- Ranking de categorias de gastos.
- Lista de insights gerados pelo agente.
- Indicadores de economia.

## Ações

**CA20 — Filtrar relatório**

Atualizar os dados conforme o período selecionado.

**CA21 — Consultar categoria**

Apresentar o detalhamento de gastos da categoria selecionada.

**CA22 — Comparar períodos**

Comparar os resultados do período atual com o período anterior equivalente.

**CA23 — Consultar insight**

Abrir a recomendação completa do agente.

## Regras de negócio

- Os relatórios devem utilizar transações confirmadas.
- Comparações devem considerar períodos equivalentes.
- Não apresentar tendências com dados insuficientes.
- Identificar claramente o período analisado.
- Não inventar valores ou percentuais.
- Insights devem possuir referência aos dados utilizados em sua elaboração.
- Caso não existam movimentações suficientes, apresentar orientação para começar a registrar transações.

---

# UI06 — PERFIL E CONFIGURAÇÕES

**Rota:** /settings

## Objetivo

Permitir a administração da conta e das preferências do usuário.

## Elementos

- Avatar.
- Nome.
- Email.
- Moeda.
- Fuso horário.
- Preferências de notificações.
- Preferências do agente.
- Opção para alterar senha.
- Opção para sair da conta.
- Opção para excluir conta.

## Ações

**CA24 — Editar perfil**

Permitir atualizar nome e avatar.

**CA25 — Alterar preferências**

Permitir configurar moeda e fuso horário.

**CA26 — Configurar notificações**

Permitir ativar ou desativar notificações disponíveis no produto.

**CA27 — Configurar agente**

Permitir escolher preferências de comunicação, como respostas mais objetivas ou mais explicativas.

**CA28 — Sair da conta**

Encerrar a sessão autenticada.

**CA29 — Excluir conta**

Solicitar confirmação reforçada e executar o processo de exclusão dos dados conforme a política de retenção e privacidade.

## Regras de negócio

- O email deverá respeitar as regras de autenticação.
- Dados pessoais só poderão ser atualizados pelo proprietário.
- A alteração de senha deverá utilizar o fluxo seguro do provedor de autenticação.
- A exclusão de conta deverá possuir confirmação explícita.
- Não armazenar senhas em texto puro.
- Preferências do usuário deverão ser persistidas.

---

# 8. REGRAS DE NEGÓCIO GERAIS

**RN01 — Autenticação**

Somente usuários autenticados poderão acessar informações financeiras pessoais.

**RN02 — Isolamento de dados**

Um usuário nunca poderá visualizar ou modificar dados financeiros de outro usuário.

**RN03 — Valores financeiros**

Todos os valores deverão utilizar BRL e precisão decimal.

**RN04 — Registro por IA**

Nenhuma movimentação interpretada pela IA será persistida sem confirmação explícita.

**RN05 — Consistência**

Os indicadores do dashboard, relatórios e planejamento deverão utilizar a mesma fonte de dados.

**RN06 — Exclusão**

Toda exclusão de movimentação deverá solicitar confirmação.

**RN07 — Datas**

O aplicativo deverá respeitar o fuso horário configurado pelo usuário.

**RN08 — Dados insuficientes**

O aplicativo deverá apresentar estados vazios em vez de inventar informações.

**RN09 — Operações duplicadas**

O backend deverá utilizar mecanismos de idempotência para evitar duplicação de registros em tentativas repetidas de confirmação.

**RN10 — Privacidade**

As informações financeiras não deverão ser utilizadas para finalidades incompatíveis com a finalidade informada ao usuário.

---

# 9. ESPECIFICAÇÃO DO AGENTE FINANCEIRO INTELIGENTE

## 9.1. Identidade

Nome: Agente Financeiro.

Personalidade: amigável, inteligente, organizado, empático e educativo.

Tom de voz: simples, humano, positivo e objetivo.

O agente deverá transmitir confiança e nunca constranger o usuário por seus hábitos financeiros.

## 9.2. Responsabilidades

- Interpretar mensagens em linguagem natural.
- Identificar receitas e despesas.
- Sugerir categorias.
- Consultar dados financeiros autorizados.
- Identificar padrões de consumo.
- Apoiar a criação de metas.
- Sugerir estratégias de economia.
- Explicar resultados financeiros.
- Identificar possíveis inconsistências.

## 9.3. Limites de atuação

- Não executar pagamentos.
- Não realizar transferências.
- Não acessar contas bancárias sem integração autorizada.
- Não inventar informações financeiras.
- Não prometer resultados financeiros.
- Não recomendar investimentos específicos como se fosse consultor financeiro habilitado.
- Não apresentar recomendações como garantias.
- Não executar operações sem autorização do usuário.

## 9.4. Prompt de sistema do agente

Você é o Agente Financeiro do aplicativo Finanças Pessoais Inteligentes.

Sua missão é ajudar o usuário a organizar suas finanças pessoais de forma simples, educativa e acessível.

Você deve:

1. Interpretar mensagens financeiras em linguagem natural.
2. Identificar valores, datas, descrições e categorias.
3. Solicitar esclarecimentos quando houver informações ambíguas.
4. Consultar somente dados financeiros autorizados do usuário.
5. Apresentar informações com precisão.
6. Sugerir estratégias de economia baseadas nos dados disponíveis.
7. Utilizar português brasileiro.
8. Ser amigável, empático e objetivo.
9. Explicar cálculos quando solicitado.
10. Solicitar confirmação antes de criar ou alterar registros financeiros.

Nunca invente receitas, despesas, saldos ou metas.

Nunca realize pagamentos ou transferências.

Nunca exponha informações de outros usuários.

Nunca afirme que uma transação foi registrada antes de receber a confirmação de sucesso do backend.

Quando não houver informações suficientes, faça perguntas objetivas.

Seu papel é apoiar a educação e a organização financeira, não substituir profissionais habilitados.

## 9.5. Processamento de linguagem natural

O agente deverá interpretar mensagens e produzir uma estrutura de dados validável pelo backend.

Exemplo conceitual:

Mensagem:
"Gastei 45 reais no almoço hoje."

Interpretação:

- tipo: despesa.
- valor: 45.00.
- descrição: almoço.
- categoria sugerida: alimentação.
- data: data atual no fuso do usuário.
- origem: chat.
- status: pendente.

O backend deverá validar a estrutura antes de apresentar a confirmação.

A IA não deverá possuir acesso irrestrito ao banco de dados. Consultas e alterações deverão ocorrer por serviços controlados, autenticados e autorizados.

---

# 10. REQUISITOS NÃO FUNCIONAIS

**RNF01 — Responsividade**

A aplicação deverá funcionar em desktop, tablet e smartphone.

**RNF02 — Desempenho**

As telas principais deverão apresentar conteúdo inicial em até 3 segundos em condições normais de conexão e infraestrutura.

**RNF03 — Segurança**

Utilizar autenticação segura, RLS, validação no backend e proteção de dados.

**RNF04 — Usabilidade**

As operações principais deverão exigir poucos passos e apresentar instruções claras.

**RNF05 — Disponibilidade da IA**

Falhas do serviço de IA não poderão impedir o registro manual de transações.

**RNF06 — Acessibilidade**

Respeitar contraste, navegação por teclado, identificação de campos e mensagens acessíveis.

**RNF07 — Compatibilidade**

Suportar as versões atuais dos principais navegadores modernos.

**RNF08 — Integridade financeira**

Evitar erros de arredondamento e inconsistência nos cálculos monetários.

**RNF09 — Privacidade**

Adotar princípios de minimização de dados e proteção desde a concepção, em conformidade com a LGPD.

**RNF10 — Segurança de credenciais**

Chaves de API e segredos deverão permanecer exclusivamente no backend ou em serviços seguros de configuração.

---

# 11. ARQUITETURA E TECNOLOGIAS SUGERIDAS

## 11.1. Frontend

- React.
- TypeScript.
- Vite.
- Tailwind CSS.
- Biblioteca de componentes acessíveis.
- Recharts para visualizações financeiras.
- Lucide para ícones.

## 11.2. Backend e infraestrutura

- Supabase.
- PostgreSQL.
- Supabase Auth.
- Supabase Edge Functions.
- Row Level Security.
- Serviço de IA acessado pelo backend.

## 11.3. Integração de inteligência artificial

A integração deverá ser realizada por uma camada de serviço no backend.

A chave do provedor de IA nunca deverá ser exposta no frontend.

O serviço deverá receber o contexto autorizado, interpretar a mensagem e retornar uma resposta estruturada.

A resposta deverá passar por validação antes de qualquer alteração persistente.

## 11.4. Diretrizes de implementação

- Componentizar elementos reutilizáveis.
- Centralizar tokens de design.
- Padronizar componentes de formulário.
- Centralizar formatação monetária.
- Manter separação entre apresentação e regras de negócio.
- Utilizar tratamento padronizado de erros.
- Implementar estados de carregamento e estados vazios.
- Evitar dados financeiros fictícios em ambientes de produção.
- Utilizar dados demonstrativos somente quando identificados como demonstração.

---

# 12. PRIORIZAÇÃO DO MVP

## 12.1. Prioridade P0 — Essencial

- Cadastro e autenticação.
- Dashboard financeiro.
- Registro manual de receitas e despesas.
- Chat com Agente Financeiro.
- Registro de movimentações por IA com confirmação.
- Classificação de transações.
- Listagem, edição e exclusão de transações.
- Criação de metas financeiras.
- Orçamentos por categoria.
- Relatórios básicos.
- Perfil e configurações.
- Isolamento de dados com RLS.

## 12.2. Prioridade P1 — Evolução

- Insights financeiros automáticos.
- Comparação avançada entre períodos.
- Alertas personalizados.
- Histórico de recomendações.
- Preferências avançadas do agente.
- Exportação de relatórios.

## 12.3. Fora do escopo inicial

Para evitar crescimento excessivo do MVP, não implementar inicialmente:

- Integração bancária via Open Finance.
- Sincronização automática de cartões.
- Pagamentos e transferências.
- Compra e venda de investimentos.
- Gestão empresarial.
- Múltiplos usuários compartilhando uma carteira.
- Consultoria financeira profissional automatizada.

---

# 13. CRITÉRIOS DE ACEITAÇÃO

**AC01 — Cadastro**

Dado um visitante, quando preencher corretamente os campos de cadastro, então deverá conseguir criar sua conta.

**AC02 — Autenticação**

Dado um usuário cadastrado, quando informar credenciais válidas, então deverá acessar seu ambiente financeiro.

**AC03 — Dashboard**

Dado um usuário com movimentações confirmadas, quando acessar o dashboard, então deverá visualizar corretamente receitas, despesas e saldo.

**AC04 — Registro manual**

Dado um usuário autenticado, quando registrar uma despesa válida, então a movimentação deverá ser salva e refletida nos indicadores.

**AC05 — Registro por IA**

Dado um usuário que informe uma despesa por chat, quando o agente interpretar os dados, então deverá apresentar uma proposta para confirmação.

**AC06 — Confirmação**

Dada uma proposta pendente, quando o usuário confirmar, então o backend deverá persistir a transação e retornar o resultado.

**AC07 — Ambiguidade**

Dada uma mensagem com valor ou data ambígua, quando o agente processá-la, então deverá solicitar esclarecimento.

**AC08 — Edição**

Dada uma transação existente, quando o usuário editar seus dados, então os novos valores deverão ser persistidos.

**AC09 — Exclusão**

Dada uma transação existente, quando o usuário solicitar sua exclusão, então o sistema deverá exigir confirmação.

**AC10 — Metas**

Dado um usuário autenticado, quando criar uma meta válida, então ela deverá aparecer na tela de planejamento.

**AC11 — Orçamentos**

Dado um orçamento configurado, quando as despesas atingirem 80% do limite, então o aplicativo deverá apresentar um alerta.

**AC12 — Relatórios**

Dado um período selecionado, quando acessar os relatórios, então os dados deverão corresponder às transações confirmadas daquele período.

**AC13 — Isolamento**

Dado dois usuários diferentes, quando cada um acessar a plataforma, então nenhum deles poderá visualizar os dados financeiros do outro.

**AC14 — Falha da IA**

Dada uma indisponibilidade do serviço de IA, quando o usuário tentar registrar uma despesa, então deverá continuar disponível a alternativa de registro manual.

**AC15 — Responsividade**

Dado qualquer uma das seis telas principais, quando acessada por smartphone, então deverá apresentar layout adaptado e funcionalidades utilizáveis.

---

# 14. PLANO DE VALIDAÇÃO DO MVP

## 14.1. Objetivo

Validar se a experiência conversacional facilita o controle financeiro e aumenta a intenção de uso recorrente.

## 14.2. Público de teste

Realizar testes com aproximadamente 10 a 20 usuários que possuam interesse em organizar suas finanças pessoais.

## 14.3. Cenários de validação

**TV01 — Primeiro acesso**

O usuário consegue compreender a proposta e navegar pelo aplicativo?

**TV02 — Registro conversacional**

O usuário consegue registrar uma despesa utilizando linguagem natural?

**TV03 — Correção de dados**

O usuário consegue corrigir uma interpretação incorreta da IA?

**TV04 — Planejamento**

O usuário consegue criar uma meta financeira?

**TV05 — Análise financeira**

O usuário consegue identificar suas principais categorias de despesas?

**TV06 — Experiência geral**

O usuário considera a experiência mais simples do que utilizar uma planilha ou formulário tradicional?

## 14.4. Indicadores de sucesso

Metas iniciais de validação, a serem ajustadas após os testes:

- 80% dos participantes conseguem registrar uma despesa pelo chat sem ajuda.
- 90% das movimentações interpretadas corretamente são confirmadas sem necessidade de correção.
- 80% dos participantes conseguem criar uma meta financeira.
- 80% conseguem localizar seus gastos por categoria.
- Nota média de usabilidade igual ou superior a 4 em uma escala de 1 a 5.

Esses indicadores são metas experimentais, não resultados já alcançados.

---

# 15. ORIENTAÇÕES FINAIS PARA A IA DE DESENVOLVIMENTO

A implementação deverá seguir rigorosamente os requisitos deste documento.

## 15.1. Consistência visual

Todas as telas devem compartilhar:

- Mesma paleta de cores.
- Mesma tipografia.
- Mesmo sistema de espaçamento.
- Mesmos padrões de cards.
- Mesmos estilos de botões.
- Mesmos padrões de formulários.
- Mesmos comportamentos de navegação.
- Mesmos padrões de feedback visual.

Não criar telas com identidades visuais diferentes.

## 15.2. Consistência funcional

- Utilizar componentes reutilizáveis.
- Compartilhar a mesma fonte de dados entre dashboard e relatórios.
- Garantir que transações atualizem os indicadores.
- Garantir que metas e orçamentos apresentem valores consistentes.
- Manter validações equivalentes no frontend e backend.
- Não simular persistência quando o backend estiver indisponível.
- Não apresentar operações como concluídas sem confirmação do servidor.

## 15.3. Estratégia de desenvolvimento

Implementar progressivamente:

1. Estrutura visual e navegação.
2. Autenticação e banco de dados.
3. Cadastro e gerenciamento de transações.
4. Dashboard e relatórios.
5. Planejamento e metas.
6. Chat e integração com IA.
7. Segurança, validações e testes.

Cada etapa deverá ser validada antes de avançar para a seguinte.

## 15.4. Regra de ouro

Não inventar funcionalidades, dados financeiros, integrações ou comportamentos que não estejam definidos neste PRD.

Quando houver ambiguidade técnica, priorizar a alternativa mais simples que preserve os requisitos do produto e solicitar esclarecimento quando a decisão alterar significativamente o escopo.

O objetivo é construir uma aplicação funcional, consistente, segura, responsiva e centrada na experiência do usuário.

---

# 16. RESULTADO ESPERADO

Ao final do MVP, o usuário deverá conseguir acessar uma plataforma de organização financeira pessoal na qual possa:

- Visualizar sua situação financeira.
- Registrar receitas e despesas.
- Conversar com um agente de inteligência artificial.
- Criar metas e orçamentos.
- Acompanhar seus hábitos de consumo.
- Consultar relatórios e recomendações.
- Gerenciar suas preferências.

**Resultado esperado:** transformar o controle financeiro em uma experiência simples, conversacional e inteligente, reduzindo a complexidade de organização e incentivando hábitos financeiros mais conscientes.

**FIM DO DOCUMENTO — PRD FINANÇAS PESSOAIS INTELIGENTES v1.0**
 ***

Interações com o Lovable:
>CRIE UM APP DE FINANÇAS PESSOAIS INTELIGENTES COM BASE NO PRD( PRODUCT REQUIREIMENTS DOCUMENT): (PRD)

>É possível quando eu quiser criar uma despesa ou um crédito eu tirar uma foto exemplo: cupom fiscal do Supermercado e o meu agente já criar? Extraindo as informações do próprio cupom?

>Sim(Deseja que eu implemente essa funcionalidade adicionando o botão de upload/captura de cupom fiscal com extração automática via IA? Posso alternar para o modo de construção para criar essa rotina.)

Resultado Final no Lovable: https://jornada-da-grana.lovable.app

<img width="1876" height="855" alt="image" src="https://github.com/user-attachments/assets/b1d186c9-0242-498e-80a6-9fcd9eee2386" />

# 💰 Finanças Inteligentes

## 📌 Sobre o Projeto

O **Finanças Inteligentes** é uma aplicação web de organização e planejamento financeiro pessoal que utiliza Inteligência Artificial para tornar o controle das finanças mais simples, prático e acessível.

Por meio de um Agente Financeiro com IA, o usuário pode registrar receitas e despesas usando linguagem natural, acompanhar sua situação financeira, definir metas de economia e receber recomendações personalizadas para melhorar sua saúde financeira.

**Objetivo:** ajudar as pessoas a entender melhor para onde vai seu dinheiro, organizar seus gastos e alcançar seus objetivos financeiros.

## 🚀 Funcionalidades

### 1. 📊 Dashboard Financeiro

Painel principal com uma visão geral da situação financeira do usuário.

- Visualização do saldo disponível.
- Resumo de receitas e despesas.
- Gráficos de evolução financeira.
- Distribuição de gastos por categoria.
- Histórico das últimas transações.
- Acompanhamento do progresso das metas financeiras.

### 2. 🤖 Chat com Agente Financeiro (IA)

Assistente inteligente que permite interagir com as finanças por meio de conversas em linguagem natural.

- Registro de receitas e despesas por mensagens.
- Identificação automática de valores, descrições e categorias.
- Consulta de informações financeiras por meio de perguntas.
- Sugestões personalizadas para economizar dinheiro.
- Orientações para organização financeira.
- Apoio na criação de metas e planejamento financeiro.
- Confirmação do usuário antes de registrar qualquer transação.

**Exemplos de interação:**

| Mensagem do usuário | Ação do agente |
|---|---|
| "Gastei R$ 50 no almoço." | Prepara o registro de uma despesa. |
| "Recebi R$ 3.500 de salário." | Prepara o registro de uma receita. |
| "Quanto gastei este mês?" | Apresenta o resumo das despesas do período. |
| "Quero economizar R$ 5.000." | Ajuda a estruturar uma meta financeira. |
| "Onde estou gastando mais?" | Analisa os gastos por categoria. |
| "Como posso economizar?" | Apresenta recomendações com base nos dados financeiros. |

### 3. 💳 Gestão de Transações

Área destinada ao controle de todas as movimentações financeiras.

- Cadastro manual de receitas e despesas.
- Registro de transações por meio do chat com IA.
- Classificação por categorias.
- Edição e exclusão de transações.
- Pesquisa e filtragem por período, tipo e categoria.
- Consulta ao histórico financeiro.

### 4. 🎯 Planejamento e Metas Financeiras

Ferramentas para ajudar o usuário a organizar seu orçamento e alcançar objetivos financeiros.

- Criação de metas de economia.
- Definição de valores e prazos.
- Acompanhamento visual do progresso das metas.
- Criação de limites de gastos por categoria.
- Monitoramento dos orçamentos.
- Alertas quando os gastos atingirem 80% e 100% do limite definido.

### 5. 📈 Relatórios e Insights

Análises para ajudar o usuário a compreender seus hábitos financeiros.

- Relatórios mensais de receitas e despesas.
- Comparação entre períodos.
- Análise de gastos por categoria.
- Identificação das categorias com maiores despesas.
- Visualização de padrões de consumo.
- Recomendações inteligentes geradas pela IA.

### 6. ⚙️ Perfil e Configurações

Área para personalização da experiência do usuário.

- Gerenciamento dos dados do perfil.
- Configuração de moeda e preferências regionais.
- Gerenciamento de notificações.
- Personalização do comportamento do Agente Financeiro.
- Configurações de segurança e conta.

## 🎨 Identidade Visual

O projeto utiliza uma identidade visual moderna, tecnológica e futurista, inspirada em produtos digitais e plataformas financeiras inteligentes.

**Características visuais:**

- Tema escuro (Dark Mode).
- Gradientes em roxo, azul e ciano.
- Elementos com efeito Glassmorphism.
- Interface moderna, intuitiva e responsiva.
- Gráficos e indicadores visuais interativos.
- Tipografia moderna e excelente legibilidade.

## 🧠 Diferencial do Projeto

O principal diferencial do Finanças Inteligentes é transformar o controle financeiro em uma experiência conversacional.

Em vez de depender exclusivamente de formulários e lançamentos manuais, o usuário pode conversar com um Agente Financeiro que interpreta suas solicitações, organiza informações e oferece recomendações com base nos dados registrados.

**A proposta é ir além de simplesmente controlar despesas: ajudar o usuário a tomar decisões financeiras melhores.**

## 🎯 Público-Alvo

- Pessoas que desejam começar a organizar suas finanças.
- Jovens adultos que buscam maior controle financeiro.
- Profissionais autônomos e freelancers.
- Pessoas que desejam economizar e alcançar objetivos financeiros.
- Usuários que procuram uma maneira simples e inteligente de acompanhar receitas e despesas.

## 🔐 Segurança e Confiabilidade

- Autenticação individual dos usuários.
- Proteção dos dados financeiros.
- Isolamento dos dados de cada usuário.
- Confirmação antes de efetivar registros realizados pelo Agente Financeiro.
- A IA não deve inventar informações ou movimentações financeiras.
- O agente atua como assistente de organização financeira, não como executor de pagamentos ou transferências.

## 💡 Proposta de Valor

**Seu dinheiro, sua estratégia.**

O Finanças Inteligentes combina organização financeira, inteligência artificial e planejamento pessoal para ajudar cada usuário a compreender seus hábitos, controlar seus gastos e construir um futuro financeiro mais organizado.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## Reflexão
### O que funcionou bem?
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas três interações.

### O que não funcionou como esperado?
Esperava interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Coding.
### O que Aprendeu sobre conversar com IAs?
Como não é o primeiro APP que eu desenvolvo não tive dificuldades, mas aprendo mais com cada APP que crio.

