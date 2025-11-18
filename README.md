#  Software de Automação de Leads

##  Propósito do Projeto
O objetivo principal do software é **automatizar a busca e gestão de leads de CRM**, permitindo que pequenas empresas e autônomos encontrem **clientes e fornecedores de forma rápida e inteligente**, sem a necessidade de sistemas complexos ou processos manuais.

---

##  Público-Alvo
- **MEIs (Microempreendedores Individuais)**
- **EPPs (Empresas de Pequeno Porte)**
- **Autônomos e prestadores de serviço**

O foco está em profissionais e empresas que desejam **otimizar o tempo de prospecção de clientes** e **aumentar sua produtividade**, reduzindo custos com ferramentas CRM completas e dispendiosas.

---

##  Problemas Que o Software Resolve
1. **Economia de tempo** – elimina a necessidade de buscar leads manualmente.  
2. **Redução de custos** – dispensa o uso de sistemas complexos e caros de CRM.  
3. **Eficiência operacional** – automatiza a coleta e organização dos leads.  
4. **Facilidade de uso** – interface simples, acessível a usuários não técnicos.  
5. **Escalabilidade** – projetado para evoluir junto com o crescimento da empresa.

---

## ⚙️ Escopo Inicial do Projeto
| Etapa | Descrição | Status |
|-------|------------|--------|
| 1️⃣ Definir objetivo do software | Documentar propósito e público-alvo |  Concluído |
| 2️⃣ Mapear funcionalidades principais | Listar funções e recursos do sistema | Concluído |
| 3️⃣ Criar fluxograma de navegação | Visualizar o fluxo de interação do usuário |  Pendente |
| 4️⃣ Modelar banco de dados MySQL | Estruturar tabelas e relacionamentos |  Pendente |

---

##  Estrutura do Projeto
automacao-de-leads/
│
├── docs/ # Documentações, ideias e anotações (Obsidian, fluxogramas etc.)
├── src/ # Códigos-fonte do projeto (frontend/backend)
├── database/ # Scripts e modelos do banco de dados MySQL
├── assets/ # Imagens, ícones e elementos visuais
└── README.md # Documento principal do projeto

yaml
Copiar código

---

##  Tecnologias Previstas
| Categoria | Tecnologia |
|------------|-------------|
| Banco de Dados | MySQL |
| Linguagem Backend | Python / Node.js *(a definir)* |
| Frontend | HTML, CSS, JavaScript |
| Integrações | APIs de CRM, planilhas Excel, automação de e-mail |
| Gerenciamento de Projeto | Azure DevOps (Scrum) |
| Controle de Versão | Git + GitHub |

---

##  Cronograma Inicial
| Fase | Tarefa | Prazo Estimado | Responsável |
|------|--------|----------------|--------------|
| Planejamento | Definir objetivo e público-alvo | ✅ 12/11/2025 | Cleyton Cardoso |
| Planejamento | Mapear funcionalidades principais | 14/11/2025 | Cleyton Cardoso |
| Planejamento | Criar fluxograma de navegação | 16/11/2025 | Cleyton Cardoso |
| Planejamento | Modelar banco de dados MySQL | 20/11/2025 | Cleyton Cardoso |

---

## Histórico de Versões
| Versão | Data | Descrição |
|---------|------|-----------|
| 0.1 | 12/11/2025 | Criação do propósito e definição do público-alvo (PBI 1) |

---

##  Próximos Passos
- [ ] Finalizar o **mapeamento de funcionalidades principais**
- [ ] Criar **fluxograma de navegação do usuário**
- [ ] Iniciar a **modelagem do banco de dados MySQL**
- [ ] Estruturar o **repositório de código fonte**

---

##  Autor
**Cleyton Cardoso**  
Desenvolvedor independente e idealizador do projeto de Automação de Leads.  
> "Automatizar é dar tempo para o que realmente importa."



---



 Feature 2 — Mapear Funcionalidades Principais
 Objetivo da Feature

Identificar, organizar e priorizar todas as funcionalidades que o software precisa ter para cumprir seu propósito: automatizar a busca, coleta, armazenamento e organização de leads via API, banco de dados e planilhas.

 Funcionalidades Obrigatórias (Core do Sistema)
1. Buscar informações via API Google

Coletar: telefone, e-mail, endereço, site e dados complementares.

Impacto: Alto

Complexidade: Alta

2. Coletar e salvar no Banco de Dados

Armazenar dados brutos recebidos da API.

Impacto: Alto

Complexidade: Média

3. Organizar dados coletados

Ajustar estrutura, corrigir formatação e preparar para exportação.

Impacto: Alto

Complexidade: Média

4. Editar informações

Permitir ao usuário alterar telefones, e-mails e outros campos.

Impacto: Alto

Complexidade: Baixa

5. Exportar dados para Google Sheets ou Excel

Gerar tabela visível e organizada.

Impacto: Alto

Complexidade: Baixa

 Funcionalidades Importantes (P1)
6. Entrar em contato via WhatsApp

Abrir link direto com número coletado.

Impacto: Médio

Complexidade: Baixa

7. Agenda otimizada

Transformar leads em cards de agenda (Excel, Sheets, Outlook).

Impacto: Médio

Complexidade: Média

8. Marcar contato com ou sem sucesso

Controle de tentativas de contato + retorno.

Impacto: Médio

Complexidade: Baixa

 Funcionalidades Opcionais (P2)
9. Atalho para PABX

Enviar o número direto para o sistema de telefonia.

Impacto: Baixo

Complexidade: Alta

10. Integração de calendário avançada

Sincronização completa com Google Calendar / Outlook.

Impacto: Baixo

Complexidade: Média

 Mapa de Dependência da Feature 2
Nível 1 — API / Entrada de Dados

Buscar informações via API (P0)

Nível 2 — Armazenamento

CRUD no Banco de Dados (Create, Read, Update, Delete)
→ CRUD = operações fundamentais para manipular dados.

Nível 3 — Organização e Disponibilização

Organizar dados

Editar informações

Exportar para Excel/Sheets

Nível 4 — Comunicação / Funcionalidades Extras

WhatsApp

Agenda

Contato com sucesso/sem sucesso

PABX

Integração de calendário

Resumo técnico do fluxo:
API → Banco de Dados → Organização → Planilha → Comunicação/Agenda

 Conclusão da Feature 2

Toda a modelagem conceitual da funcionalidade foi definida:

Funções obrigatórias e opcionais mapeadas

Priorização por impacto e complexidade

Mapa de dependência técnico pronto

Base pronta para planejamento da próxima etapa (Feature 3)

Versionamento
Versão atual do projeto: v0.2.0
Descrição da versão: Finalização da Feature 2 (funcionalidades, prioridades e mapa de dependência)
Data: 2025-11-15

_______________________________________________________________________

1. Ambiente de Desenvolvimento Preparado

Hoje foram instaladas, configuradas e testadas todas as ferramentas necessárias para o backend:

✔ Node.js

Instalado com sucesso

Testado com:

node -v → funcional

npm -v → funcional após liberar execução de scripts no PowerShell

✔ Python 3.12

Instalado corretamente (versão 3.14 removida)

Testado com:

python --version

Execução de script simples

pip --version

Instalação funcional de pacotes (pip install requests)

Tudo funcionando de forma estável.

✔ Git

Git instalado e testado

git --version, git init e git status funcionando

Repositório local criado

2. GitHub e VS Code

Projeto configurado no VS Code

README.md começado

Ambiente preparado para sincronizar com GitHub via push

3. Azure DevOps – Organização e Planejamento


4. Novas PBIs Criadas Hoje no Backlog

Todas registradas e organizadas corretamente no Kanban do Azure DevOps.

5. Backend – Preparação Final Antes da Codificação (Feature 3 → 4 → 5)

Com o ambiente 100% funcional (Python, Node, NPM, Git), agora o projeto está pronto para:

Diagramar o fluxo de navegação (Feature 3)

Criar o Modelo ER (Feature 4)

Iniciar codificação do backend (Features 5 a 9)

6. Status Geral do Projeto

✔ Ambiente configurado
✔ Ferramentas funcionando
✔ Git ok
✔ Azure DevOps organizado
✔ Backlog estruturado profissionalmente
✔ Pronto para iniciar codificação real do backend

____________________________________________________________________________

Resumo do Progresso – 18/11/2025

Hoje foram concluídas todas as tasks da Feature 3 – Navegação do Usuário, responsável por criar o fluxograma principal do software e definir visualmente o fluxo de uso do sistema.

1. Criação do Fluxograma (Draw.io)

A estrutura inicial do fluxograma foi definida com base no documento feature3-navegacao.md.

Criado um novo diagrama no Draw.io com layout do zero.

Exportado o código XML gerado e importado no diagrama corretamente.

2. Construção Visual do Fluxo

Foram definidos e inseridos os elementos visuais correspondentes a cada etapa do sistema:

Início do Usuário

Tela Inicial

Buscar Leads

Inserir Palavra-Chave

API retorna dados

Salvar no Banco de Dados

Base de Dados

Configurações

Fim (dados salvos)

Todos os elementos foram padronizados com formas e cores apropriadas (elipses para início/fim, retângulos para ações do usuário, processos para operações internas).

3. Exportação e Salvamento

O fluxograma foi exportado em .drawio e .png.

Os arquivos foram organizados dentro da pasta:
/fluxograma

Ambos foram adicionados ao Git e enviados ao GitHub via bash com sucesso.

4. Revisão de Consistência

Foi realizada uma revisão completa para garantir que o fluxograma:

Representa corretamente as funcionalidades da Feature 2

Não possui etapas fora do escopo atual

Segue a ordem técnica correta

Está claro e compreensível para o usuário final

Pode servir como base direta para a Feature 4 (modelagem do banco)

Resultado: Fluxograma aprovado e finalizado.

Status Final do Dia:
Feature 3 concluída com sucesso.
A partir de amanhã será iniciada a Feature 4 – Modelagem do Banco de Dados (MySQL ERD).
