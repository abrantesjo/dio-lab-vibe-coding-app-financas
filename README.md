# 💰 Seu Dinheiro Fácil

> **Organize suas finanças conversando.**

Seu Dinheiro Fácil é um aplicativo de organização de finanças pessoais voltado principalmente para pessoas que estão começando a cuidar da própria vida financeira.

O projeto nasceu como um exercício prático de **Vibe Coding**, utilizando IA durante o processo de definição, planejamento, implementação e refinamento do produto.

A proposta é reduzir o atrito existente em ferramentas tradicionais de controle financeiro: em vez de preencher diversos formulários ou manter planilhas, o usuário pode simplesmente conversar com o aplicativo.

Por exemplo:

> 👤 "Ontem gastei R$ 32,90 com Uber."

O aplicativo interpreta a mensagem, identifica o valor, a data e a categoria e registra a movimentação.

---

## 🎬 Demonstração

No vídeo abaixo, apresento a jornada principal do **Seu Dinheiro Fácil**, desde o registro de uma movimentação em linguagem natural até sua visualização no Dashboard.

---

# 📋 PRD utilizado

## 1. Visão do Produto

Criar um aplicativo de organização de finanças pessoais voltado para iniciantes, no qual a principal forma de interação seja uma conversa em linguagem natural.

Em vez de depender de formulários extensos ou planilhas, o usuário poderá registrar gastos e receitas por mensagens, acompanhar suas finanças e receber orientações simples de um **Agente Financeiro**.

O objetivo do MVP é validar se uma experiência conversacional torna o hábito de registrar e acompanhar movimentações financeiras mais simples e acessível.

---

## 2. Problema

Muitas pessoas têm dificuldade em manter o controle das próprias finanças porque precisam registrar informações manualmente, categorizar gastos e interpretar relatórios financeiros.

Para usuários iniciantes, esse processo pode parecer trabalhoso ou complexo.

O produto busca reduzir essa dificuldade permitindo registrar movimentações usando frases naturais, como:

> "Gastei R$ 42 no almoço hoje."

O sistema interpreta a mensagem e transforma a informação em uma transação financeira estruturada.

---

## 3. Público-Alvo

Pessoas iniciantes em organização financeira que:

- querem entender melhor para onde vai seu dinheiro;
- desejam registrar receitas e despesas de forma simples;
- não querem depender de planilhas;
- buscam criar o hábito de acompanhar seus gastos;
- possuem pouco conhecimento sobre gestão financeira.

---

## 4. Proposta de Valor

> **Organize suas finanças conversando.**

O usuário descreve suas movimentações naturalmente e o aplicativo transforma essas conversas em informações financeiras organizadas e fáceis de entender.

---

## 5. Ação Principal do Produto

A principal ação do usuário é registrar uma movimentação financeira pelo chat.

### Exemplo

**Usuário:**

> "Gastei R$ 85 no mercado hoje."

**Sistema:**

> "Registrei R$ 85 em Alimentação > Mercado."

Quando as informações necessárias estiverem presentes, a transação é registrada imediatamente e o usuário pode posteriormente corrigir ou desfazer o lançamento.

O valor informado pelo usuário é obrigatório. Caso ele não esteja presente na mensagem, o agente deve solicitar essa informação em vez de tentar deduzi-la.

---

## 6. Funcionalidades do MVP

### 💬 Chat financeiro

Permitir o registro de movimentações em linguagem natural.

O sistema deve identificar, quando disponíveis:

- valor;
- descrição;
- categoria;
- data;
- tipo da movimentação, como receita ou despesa.

Exemplo:

> "Ontem gastei R$ 32,90 com Uber."

Resultado esperado:

- **Valor:** R$ 32,90
- **Categoria:** Transporte
- **Descrição:** Uber
- **Data:** ontem, convertida para a data correspondente
- **Tipo:** despesa

---

### 🏷️ Classificação automática

Classificar as despesas automaticamente em categorias simples, como:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Assinaturas
- Outros

O usuário pode corrigir a classificação posteriormente.

---

### 📑 Histórico de transações

Permitir consultar os lançamentos registrados, exibindo:

- descrição;
- valor;
- categoria;
- data;
- tipo.

O usuário deve poder buscar, editar e excluir movimentações.

---

### 📊 Dashboard financeiro

Apresentar uma visão simples das finanças do usuário, incluindo:

- entradas do mês;
- despesas do mês;
- saldo;
- gastos por categoria;
- movimentações recentes;
- evolução financeira;
- progresso das metas.

A prioridade é clareza, evitando excesso de gráficos ou informações.

---

### 🎯 Metas financeiras

Permitir a criação e o acompanhamento de metas.

Exemplo:

> "Quero juntar R$ 5.000 para uma viagem."

Cada meta pode possuir:

- nome;
- valor objetivo;
- valor acumulado;
- prazo opcional;
- percentual de progresso.

O chat também deve interpretar aportes realizados em uma meta.

---

### 🤖 Agente Financeiro

O assistente utiliza os dados registrados para apresentar observações simples sobre a situação financeira do usuário.

Exemplos:

> "Seus maiores gastos registrados neste mês estão em Alimentação."

> "Você já alcançou 60% da sua meta Viagem."

As mensagens possuem caráter educativo e informativo.

O agente não atua como consultor financeiro e não realiza recomendações específicas de investimentos.

---

### 📚 Educação financeira

Apresentar pequenas orientações relacionadas à organização financeira, utilizando conteúdos curtos e contextualizados.

Temas iniciais:

- orçamento;
- controle de despesas;
- reserva de emergência;
- definição de metas;
- diferença entre necessidade e desejo.

---

## 7. Principais Telas

O MVP possui quatro áreas principais:

### Chat
Principal ponto de interação com o aplicativo.

### Resumo
Dashboard com visão consolidada das finanças.

### Transações
Histórico e gerenciamento das movimentações.

### Metas
Criação e acompanhamento de objetivos financeiros.

Antes dessas áreas, o usuário passa por uma apresentação inicial e pela autenticação.

---

## 8. Jornada Principal

A principal jornada do produto é:

```text
Onboarding
     ↓
Autenticação
     ↓
Chat
     ↓
Mensagem em linguagem natural
     ↓
Interpretação
     ↓
Registro da transação
     ↓
Confirmação visual
     ↓
Histórico atualizado
     ↓
Dashboard atualizado
