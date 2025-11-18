# Feature 3 — Diagrama de Navegação do Usuário

## Telas (lista)
- Login: autenticação do usuário.
- Dashboard: resumo de buscas e acessos rápidos.
- Nova Busca: formulário para criar busca automática.
- Histórico de Buscas: lista de buscas e status.
- Leads: listagem, filtro, detalhes, editar.
- Importação: upload de XLSX/CSV e relatório de erros.
- Exportação: filtros + botão exportar.
- Automação: criar/editar regra de automação.
- Agendamentos: listar/agendar execuções.
- Usuários: CRUD (admins).
- Configurações: perfil, billing, integrations.

## Fluxo principal (Mermaid)
```mermaid
flowchart TD
  Login --> Dashboard
  Dashboard --> NovaBusca
  NovaBusca --> JobQueued[Job na fila]
  JobQueued --> Historico
  Historico --> Leads
  Leads --> Exportar
  Leads --> Importar
  Leads --> EditarLead
  Dashboard --> Automacao
  Automacao --> Agendamentos
