# FinTrack Pro - TODO

## Fase 1: Schema e Banco de Dados
- [x] Criar schema Prisma com todas as tabelas (Users, Accounts, Transactions, Categories, CreditCards, Statements, Goals, Budgets, Reports, Notifications)
- [x] Gerar migrations e aplicar via webdev_execute_sql
- [ ] Criar seed de dados para testes

## Fase 2: Layout Base e Temas
- [x] Configurar Dark Mode e Light Mode com CSS variables
- [x] Implementar Sidebar fixa com navegação entre módulos
- [x] Criar layout base com DashboardLayout
- [x] Adicionar suporte a tema switchable
- [ ] Implementar micro animações e transições

## Fase 3: Dashboard
- [x] Criar cards de saldo total, receitas, despesas, fluxo de caixa, patrimônio
- [x] Implementar gráfico de evolução financeira
- [x] Criar gráfico de gastos por categoria
- [x] Implementar comparativo mensal
- [x] Adicionar top despesas
- [x] Exibir últimas movimentações
- [x] Mostrar contas a vencer
- [x] Exibir faturas próximas
- [ ] Implementar filtros por período
- [ ] Adicionar drill-down nos gráficos
- [x] Criar skeleton loading para dashboard

## Fase 4: Módulo Transações
- [x] Criar CRUD de transações (receitas, despesas, transferências)
- [ ] Implementar suporte a parcelamentos
- [ ] Adicionar suporte a recorrências
- [ ] Criar sistema de etiquetas
- [ ] Implementar categorias e subcategorias
- [x] Criar filtros por data, valor, conta, categoria, tipo
- [x] Implementar formulário de nova transação
- [ ] Adicionar edição e exclusão de transações
- [x] Criar skeleton loading para transações
- [ ] Implementar paginação/scroll infinito

## Fase 5: Módulo Contas
- [x] Criar CRUD de contas
- [x] Implementar tipos: conta corrente, poupança, dinheiro, carteira, investimentos, conta internacional
- [x] Adicionar saldo inicial e atual
- [x] Criar formulário de nova conta
- [ ] Implementar edição e exclusão
- [x] Exibir saldo por conta
- [x] Criar skeleton loading

## Fase 6: Módulo Cartões
- [x] Criar CRUD de cartões de crédito
- [x] Implementar controle de limite
- [x] Adicionar limite disponível
- [x] Criar gerenciamento de faturas
- [ ] Implementar compras parceladas
- [x] Adicionar datas de fechamento e vencimento
- [x] Criar histórico de faturas
- [x] Implementar indicadores visuais de uso de limite
- [x] Criar skeleton loading

## Fase 7: Módulo Orçamentos
- [x] Criar CRUD de orçamentos por categoria
- [x] Implementar orçamento mensal
- [x] Adicionar alertas de excedente
- [x] Criar indicadores visuais de progresso (progress bars)
- [x] Implementar controle de excedentes
- [ ] Adicionar comparativo com período anterior
- [x] Criar skeleton loading

## Fase 8: Módulo Metas
- [x] Criar CRUD de metas financeiras
- [x] Implementar tipos: reserva de emergência, viagens, investimentos, personalizadas
- [x] Adicionar percentual concluído
- [ ] Implementar projeções
- [ ] Criar simuladores de metas
- [x] Adicionar data-alvo
- [ ] Implementar contribuições regulares
- [x] Criar skeleton loading

## Fase 9: Módulo Relatórios
- [x] Criar geração de relatórios de receitas
- [x] Implementar relatórios de despesas
- [x] Adicionar relatórios de fluxo de caixa
- [x] Criar relatórios por categoria
- [x] Implementar relatórios de patrimônio
- [ ] Adicionar exportação PDF
- [ ] Implementar exportação Excel
- [ ] Adicionar exportação CSV
- [x] Criar filtros de período
- [x] Implementar gráficos nos relatórios

## Fase 10: Módulo Planejamento Financeiro
- [x] Implementar simulação de gastos
- [x] Adicionar simulação de investimentos
- [ ] Criar planejamento anual
- [x] Implementar planejamento de aposentadoria
- [x] Adicionar cenários financeiros
- [x] Criar visualização de projeções
- [ ] Implementar calculadoras financeiras

## Fase 11: UI/UX Refinement
- [x] Adicionar micro animações em transições
- [x] Implementar loading states em todos os módulos
- [x] Adicionar skeleton loading em todas as páginas
- [x] Testar responsividade em desktop, tablet e mobile
- [x] Refinar cores e tipografia
- [x] Adicionar hover states e feedback visual
- [ ] Implementar empty states
- [ ] Adicionar tooltips e help text

## Fase 12: Testes e Entrega
- [x] Testar fluxos principais
- [x] Validar responsividade
- [x] Testar Dark/Light Mode
- [x] Verificar performance
- [x] Criar checkpoint final
- [x] Entregar projeto completo
