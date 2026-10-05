# 💸 App de Organização de Finanças Pessoais com Vibe Coding - VELA - Arthur Câmara

# PRD - Agente Financeiro Conversacional

## Produto

Agente Financeiro Conversacional

## Visão do Produto

Criar um aplicativo de finanças pessoais baseado em conversação que permita ao usuário registrar gastos, acompanhar metas e receber recomendações financeiras de maneira simples e natural, sem depender de formulários complexos ou planilhas.

A solução deve priorizar simplicidade, acessibilidade e Design Universal, garantindo uma experiência de qualidade para o maior número possível de usuários, independentemente de idade, familiaridade com tecnologia, nível de educação financeira ou necessidades de acessibilidade.

## Problema

Muitas pessoas desejam controlar melhor suas finanças, mas abandonam aplicativos tradicionais porque:

- Exigem muitas etapas de preenchimento manual.
- Possuem interfaces complexas para usuários iniciantes.
- Oferecem pouca personalização.
- Não geram insights claros e acionáveis.

O resultado é baixa adesão e falta de consistência no acompanhamento financeiro.

## Objetivo

Permitir que qualquer pessoa organize sua vida financeira através de conversas em linguagem natural, reduzindo o esforço necessário para registrar informações e aumentando o engajamento por meio de recomendações personalizadas.

## Público-Alvo

### Primário

- Adultos entre 18 e 45 anos.
- Pessoas iniciando educação financeira.
- Usuários que nunca utilizaram aplicativos de controle financeiro.

### Secundário

- Pessoas que já utilizam planilhas, mas procuram uma solução mais prática.
- Usuários que desejam criar metas financeiras simples.

## Proposta de Valor

"Controle suas finanças conversando com um assistente inteligente, sem precisar preencher planilhas ou navegar por telas complexas."

---

## Funcionalidades do MVP

### 1. Registro de Gastos via Chat

#### Descrição

O usuário informa um gasto em linguagem natural.

#### Exemplos

- Gastei R$ 35 no almoço.
- Paguei R$ 120 de combustível hoje.
- Assinei Netflix por R$ 39,90.

#### Resultado Esperado

O sistema extrai automaticamente:

- Valor
- Categoria
- Data
- Descrição

---

### 2. Classificação Automática

O sistema categoriza automaticamente as despesas.

#### Categorias Iniciais

- Alimentação
- Transporte
- Moradia
- Lazer
- Saúde
- Educação
- Assinaturas
- Outros

#### Regra

O usuário poderá corrigir a categoria caso a classificação esteja incorreta.

---

### 3. Metas Financeiras

#### Exemplos

- Economizar R$ 5.000
- Criar reserva de emergência
- Juntar dinheiro para viagem

#### Funcionalidades

- Criar metas.
- Editar metas.
- Acompanhar progresso.
- Mostrar percentual atingido.

---

### 4. Agente Financeiro

Assistente responsável por gerar recomendações simples e acionáveis.

#### Exemplos

- Você gastou 20% mais com alimentação este mês.
- Reduzindo R$ 10 por dia em refeições externas, sua meta pode ser alcançada mais rapidamente.
- Seus gastos com assinaturas representam 12% das despesas mensais.

---

### 5. Relatórios Simplificados

#### Dashboard Principal

Exibir:

- Gastos do mês.
- Categoria com maior gasto.
- Evolução mensal.
- Progresso das metas.

#### Visualizações

- Gráfico por categoria.
- Resumo mensal.
- Tendências de gastos.

---

## Fluxos Principais

### Fluxo 1: Registrar gasto

Usuário:
"Gastei R$ 42 no mercado."

Sistema:
"Registrei R$ 42 em Alimentação. Deseja adicionar alguma observação?"

### Fluxo 2: Criar meta

Usuário:
"Quero economizar R$ 3.000."

Sistema:
"Meta criada. Qual o prazo desejado?"

### Fluxo 3: Solicitar análise

Usuário:
"Como estão meus gastos?"

Sistema:
"Seus gastos este mês totalizam R$ 1.850. Alimentação representa 35% das despesas."

---

## Princípios de Design Universal e Inclusão

A solução deverá seguir princípios de Design Universal para oferecer uma experiência eficiente, intuitiva e acessível ao maior número possível de usuários.

### Diretrizes

- Interface intuitiva para usuários iniciantes.
- Linguagem simples e livre de termos financeiros complexos.
- Navegação consistente em todas as telas.
- Compatibilidade com leitores de tela.
- Contraste adequado para usuários com baixa visão.
- Componentes com tamanho apropriado para toque.
- Feedback claro após cada ação do usuário.
- Possibilidade de corrigir informações registradas incorretamente.
- Redução máxima da entrada manual de dados.
- Experiência otimizada para dispositivos móveis.
- Ícones acompanhados por textos explicativos.
- Mensagens de erro claras e orientadas à solução.
- Funcionalidades principais acessíveis em no máximo dois cliques a partir da tela inicial.
- Não depender exclusivamente de cores para transmitir informações.
- Priorizar clareza e compreensão em vez de elementos visuais decorativos.

### Critérios de Aceitação de UX

- Usuário consegue registrar um gasto em menos de 15 segundos.
- Usuário iniciante compreende o fluxo principal sem treinamento.
- Aplicação mantém boa usabilidade em smartphones, tablets e desktops.
- Todos os elementos interativos possuem rótulos acessíveis.
- Nenhuma funcionalidade crítica depende exclusivamente de cor, ícone ou gesto.

---

## Requisitos Não Funcionais

### Usabilidade

- Interface simples e amigável.
- Linguagem acessível.
- Experiência otimizada para dispositivos móveis.
- Experiência consistente entre diferentes dispositivos.

### Performance

- Resposta do chat em menos de 3 segundos.
- Registro de transações instantâneo.
- Carregamento rápido das telas principais.

### Segurança

- Autenticação de usuário.
- Dados financeiros protegidos.
- Boas práticas de privacidade e proteção de dados.
- Criptografia de informações sensíveis.

---

## Principais Telas do MVP

### 1. Login e Cadastro

Objetivo:
Permitir acesso seguro ao sistema.

### 2. Dashboard

Objetivo:
Apresentar visão geral da situação financeira.

Conteúdos:

- Gastos do mês.
- Categorias.
- Metas.
- Insights rápidos.

### 3. Chat do Agente Financeiro

Objetivo:
Principal interface de interação do usuário com o sistema.

Permitir:

- Registrar gastos.
- Criar metas.
- Consultar análises financeiras.
- Receber recomendações.

### 4. Histórico de Transações

Objetivo:
Visualizar, editar e excluir registros.

### 5. Metas Financeiras

Objetivo:
Gerenciar objetivos financeiros e acompanhar evolução.

### 6. Configurações

Objetivo:
Gerenciar perfil, preferências e categorias.

---

## Critérios de Sucesso do MVP

Após 30 dias de uso:

- 70% dos usuários registram pelo menos uma despesa por semana.
- 50% dos usuários criam ao menos uma meta financeira.
- 40% dos usuários retornam semanalmente ao aplicativo.
- NPS acima de 30.
- Tempo médio de registro de uma despesa inferior a 15 segundos.

---

## Validação Inicial

### Hipótese Principal

Usuários preferem registrar gastos através de conversação em vez de preencher formulários tradicionais.

### Experimento

Construir MVP com:

- Chat conversacional.
- Registro de despesas.
- Classificação automática.
- Metas financeiras.
- Dashboard básico.

### Métricas

- Número de transações registradas.
- Frequência de uso.
- Tempo até o primeiro registro.
- Retenção após 7 dias.
- Retenção após 30 dias.
- Feedback qualitativo dos usuários.
- Taxa de criação de metas.

---

## Entregável Esperado da IA

Gerar um MVP funcional contendo:

- Arquitetura inicial da aplicação.
- Principais telas.
- Fluxos de usuário.
- Componentes reutilizáveis.
- Sistema de chat conversacional.
- Dashboard financeiro.
- Gestão de metas.
- Relatórios básicos.

Utilizar:

- Linguagem em português do Brasil.
- Design moderno e minimalista.
- Abordagem mobile-first.
- Princípios de Design Universal.
- Boas práticas de UX e acessibilidade.
- Estrutura preparada para futuras evoluções.

---

## Prompt Consolidado para Lovable

Crie um aplicativo web responsivo chamado "Agente Financeiro".

Objetivo:
Permitir que usuários controlem suas finanças pessoais usando linguagem natural através de um chat inteligente.

Funcionalidades:
- Registrar gastos via conversa.
- Extrair automaticamente valor, categoria, descrição e data.
- Permitir edição das transações.
- Criar e acompanhar metas financeiras.
- Dashboard com resumo financeiro.
- Relatórios mensais básicos.
- Assistente financeiro que gere insights automáticos.

Telas:
1. Login/Cadastro
2. Dashboard
3. Chat do Agente Financeiro
4. Histórico de Transações
5. Metas Financeiras
6. Configurações

Princípios de UX:
- Aplicar Design Universal desde o MVP.
- Interface simples, intuitiva e inclusiva.
- Linguagem acessível para pessoas sem conhecimento financeiro.
- Mobile-first.
- Alto contraste e excelente legibilidade.
- Compatibilidade com leitores de tela.
- Botões e áreas de toque amplas.
- Fluxos que exijam o mínimo possível de esforço cognitivo.
- Priorizar clareza acima de elementos decorativos.
- Seguir boas práticas de acessibilidade e UX.

UI:
- Moderna e minimalista.
- Mobile-first.
- Visual que transmita confiança, organização e simplicidade.
- Componentes reutilizáveis e acessíveis.

Idioma:
Português do Brasil.

Prioridade:
Construir MVP validável rapidamente antes de funcionalidades avançadas.

INTERAÇÕES COM O LOVABLE

Crie um app de finanças pessoais com base no seguinte PRD



