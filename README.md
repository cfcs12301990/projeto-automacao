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

## Escopo Inicial do Projeto
| Etapa | Descrição | Status |
|-------|------------|--------|
| 1 Definir objetivo do software | Documentar propósito e público-alvo |  Concluído |
| 2 Mapear funcionalidades principais | Listar funções e recursos do sistema | Concluído |
| 3 Criar fluxograma de navegação | Visualizar o fluxo de interação do usuário |  Pendente |
| 4 Modelar banco de dados MySQL | Estruturar tabelas e relacionamentos |  Pendente |

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
| Planejamento | Definir objetivo e público-alvo | X 12/11/2025 | Cleyton Cardoso |
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

____________________________________________________________________________________
18-11-2025
Resumo Geral dos Estudos – SOLID (Módulos 1 ao 6)

Hoje percorri todos os módulos do curso de SOLID, revisando conceitos fundamentais de arquitetura de software e aplicando cada princípio em exercícios práticos focados no meu projeto de Automação de Leads.

 Módulo 1 – SRP (Single Responsibility Principle)

Entendi que cada classe deve possuir uma única responsabilidade e um único motivo para mudar.

Analisei impactos positivos: manutenção simples, menor acoplamento e maior clareza.

Fiz exercícios sobre identificar múltiplas responsabilidades em classes e dividir de forma correta.

Compreendi como sistemas monolíticos sofrem quando ignoram SRP.

 Módulo 2 – OCP (Open/Closed Principle)

Estudei como criar classes abertas para extensão e fechadas para modificação.

Aprendi a usar polimorfismo e abstrações para adicionar funcionalidades sem alterar código existente.

Fiz exercícios sobre implementação de cálculo distinto de taxas/valores usando classes estendidas.

Compreendi que OCP evita regressões e torna o software escalável.

 Módulo 3 – LSP (Liskov Substitution Principle)

Aprendi que subclasses devem poder substituir suas classes base sem alterar o comportamento esperado.

Analisei exemplos clássicos (Quadrado x Retângulo) e como isso quebra LSP.

Resolvi exercícios comparando comportamentos de subclasses e detectando inconsistências.

Consegui visualizar como violações de LSP geram bugs que só aparecem em cenários específicos.

 Módulo 4 – ISP (Interface Segregation Principle)

Estudei a importância de criar interfaces pequenas, específicas e sem métodos desnecessários.

Aprendi que classes não devem ser forçadas a implementar métodos que não usam.

Fiz testes e perguntas para identificar interfaces gordas e como quebrá-las.

Analisei exemplos reais envolvendo serviços grandes e mal segmentados.

 Módulo 5 – DIP (Dependency Inversion Principle)

Compreendi que módulos de alto nível devem depender de abstrações, não de implementações concretas.

Aprendi a diferença entre inversão de dependência e injeção de dependência.

Resolvi exercícios mostrando como desacoplar classes e facilitar testes.

Explorei como DIP reduz impactos quando um módulo muda.

 Módulo 6 – Revisão Geral e Exercícios Avançados

Passei por uma bateria de perguntas para consolidar os 5 princípios.

Analisei um exercício prático envolvendo serviços de banco de dados, envio de relatórios e abstrações.

Identifiquei pontos onde há acoplamento excessivo e como reestruturar usando SOLID.

Reforcei entendimentos com exemplos em Python para aplicar no meu projeto real.

 Resumo Final

Estudei profundamente os princípios SOLID com foco na prática.

Corrigi respostas, entendi conceitos que estavam confusos e consolidai com exemplos reais.

Deixei preparado o terreno para revisar todo o curso amanhã, fixando definitivamente os cinco pilares da arquitetura limpa.

Todo esse aprendizado será aplicado diretamente no desenvolvimento da Automação de Leads, tornando o código mais robusto, escalável e profissional.
_____________________________________________________________________________

Segundo Curso de SOLID – Revisão e Fixação dos Princípios Fundamentais

Este segundo curso de SOLID teve como objetivo reforçar e aprofundar o entendimento dos cinco princípios fundamentais da programação orientada a objetos, garantindo um código mais limpo, modular, flexível e preparado para mudanças. Cada módulo foi estudado individualmente, com explicações teóricas, exemplos práticos em Python e exercícios aplicados para validar o aprendizado antes de avançar.

Os princípios revisados foram:

S — Single Responsibility Principle (SRP)
Cada classe deve ter apenas uma responsabilidade, evitando acoplamento excessivo e facilitando manutenção.

O — Open/Closed Principle (OCP)
Classes devem estar abertas para extensão, mas fechadas para modificação, permitindo evoluir o software sem alterar código já testado.

L — Liskov Substitution Principle (LSP)
Subclasses devem ser totalmente substituíveis por suas classes pai, mantendo comportamento consistente.

I — Interface Segregation Principle (ISP)
Interfaces devem ser específicas, evitando forçar classes a implementar métodos que não utilizam.

D — Dependency Inversion Principle (DIP)
Módulos de alto nível não devem depender de módulos de baixo nível, mas sim de abstrações — favorecendo baixo acoplamento.

Além dos princípios, o curso também revisou relacionamentos essenciais da POO (Associação, Agregação e Composição) e diversos exemplos reais para consolidar o uso correto de cada conceito.

Este estudo aprofundado faz parte da preparação para criar um software de automação mais robusto, escalável e profissional, aplicando boas práticas de desenvolvimento em cada etapa do projeto.

______________________________________________________________________________________________________________________________

26-11
Hoje avançamos significativamente na Feature 4 – Criação do Modelo ER (Entidade-Relacionamento) do sistema de Automação de Leads. Foi realizado:

1. Abertura e preparação do MySQL Workbench

Instalação e abertura do MySQL Workbench.

Criação de um novo EER Diagram para modelagem do banco.

2. Criação das tabelas principais do sistema

Foram criadas 10 tabelas profissionais, seguindo boas práticas de desenvolvimento:

usuarios

clientes

buscas

leads

logs_leads

tags

leads_tags

configuracao

api_chaves

sessoes_login

Cada tabela foi criada com:

Tipos de dados adequados

Chaves primárias

Chaves estrangeiras

Defaults inteligentes

Campos de auditoria (criado_em, atualizado_em)

Regras de integridade

3. Normalização e relacionamento entre entidades

Todas as relações foram adicionadas:

1:N entre usuários → leads

1:N entre usuários → buscas

N:N entre leads ↔ tags

1:N entre usuários → sessões

etc.

____________________________________________________________________________________________________________________

27-11

Começando a criar as FK pelo MySQL Workbench.
Aprendendo como ligá-las e configurá-las atravé das abas Relationship e Forein Key.
PRetendo terminar essa task do scrum amanhã sem falta, pois, tem bastante FK para fazer.

____________________________________________________________________________________________________________________

Configuração inicial do MySQL e criação da base do projeto

Conteúdo:

Hoje foi realizada a configuração completa do ambiente MySQL necessário para o backend do projeto de automação de leads. Primeiro, foi instalado e configurado o MySQL Server 8.0 e o Workbench, ajustando corretamente os módulos "Type and Networking", "Authentication Method", "Accounts and Roles", "Windows Service" e "Apply Configuration". Depois da instalação, foi testada a conexão local com o servidor e validado que o Workbench estava comunicando corretamente com o MySQL.

Em seguida, foi criado o schema principal do projeto, denominado automacao_leads, utilizando o SQL Editor. Após a criação do schema, foi executado o script responsável por estruturar todas as tabelas do banco, incluindo usuários, clientes, leads, buscas, integrações, sessões de login, logs de busca, configurações, tags e tabelas intermediárias de relacionamento. Na execução surgiram alguns warnings normais (tabelas já existentes e avisos de depreciação), mas nada que afetasse o funcionamento. A única mensagem real de erro foi uma chave estrangeira duplicada, causada pela reexecução do script, e que não comprometeu a estrutura final.

Por fim, foi confirmado que o banco de dados está funcionando corretamente, com todas as tabelas criadas — totalizando 11 tabelas — e pronto para receber dados de teste e evoluir para as próximas etapas de desenvolvimento.

Esse avanço marca a conclusão da base de dados do projeto, permitindo seguir para a inserção de registros de teste, criação dos primeiros SELECTs e validação dos relacionamentos.

______________________________________________________________________________________________________________________________________________

04-12

Revisão das Tabelas, FKs e Validação da Estrutura do Banco

Hoje foi iniciada uma revisão criteriosa do schema automacao_leads, garantindo que toda a modelagem estivesse coerente, íntegra e livre de inconsistências que poderiam gerar futuros bugs.

Primeiro, foram executados os comandos para verificar a criação de cada tabela via SHOW CREATE TABLE. Também foi revisado o comportamento do MySQL com \G e ;, entendendo que ambos funcionam, mas \G apenas altera o formato visual da saída.

Em seguida, foram analisadas todas as chaves estrangeiras do banco. A consulta retornou exatamente 13 FKs, todas corretamente associadas aos relacionamentos previstos no modelo lógico original. Cada uma foi verificada individualmente e todas apareceram com o status OK.

Também foi feita a verificação dos tipos e compatibilidade entre colunas relacionadas (ex.: INT → INT, mesmo tamanho, mesma assinatura). O resultado final foi:

Tipos OK — Nenhuma inconsistência encontrada entre colunas pai/filho.

Nenhuma duplicata — As tabelas não possuem chaves estrangeiras duplicadas nem relacionamentos redundantes.

Nenhuma FK faltando — Todas as FKs esperadas estão presentes.

A análise completa garante que o banco está em um estado estável, íntegro e pronto para as próximas etapas do projeto, sem risco de herdar problemas estruturais.

Hoje também foi reforçada a prática de desenvolvimento profissional:
testar, validar, confirmar e só então avançar, mantendo o banco e o código sempre sincronizados.

____________________________________________________________________________________________________________________________________________

9-12

O projeto avançou na estruturação completa do banco de dados, criação das tabelas principais e implementação das relações necessárias para o sistema de automação de leads. As tabelas usuarios, leads, buscas e leads_busca foram criadas com chaves primárias e estrangeiras corretamente definidas, seguindo boas práticas de modelagem relacional. Também foi criada a tabela log_erro para registrar mensagens de erro geradas pela aplicação ou pelo processo automatizado.

Na etapa de testes, foram realizados inserts manuais para garantir que todas as relações estavam funcionando. Inicialmente surgiram erros relacionados a nomes de colunas e à ausência de valores obrigatórios (NOT NULL), mas todos foram corrigidos com ajustes na modelagem e inclusão dos campos corretos nos inserts. Testamos com sucesso a inserção no relacionamento N:N entre leads e buscas, comprovado pela mensagem “1 row(s) affected”, que confirmou a operação.

Com isso, toda a estrutura básica do banco que sustentará o sistema está consolidada e testada, permitindo avançar para a Parte 5, onde iniciaremos a lógica de automação e integração com as ferramentas externas.

______________________________________________________________________________________________________________________________________________
11-12-25


Configuração e validação completa do ambiente Python

Hoje finalizei toda a preparação do ambiente de desenvolvimento do projeto Automação de Leads. As etapas concluídas foram:

1. Verificação da instalação do Python

Confirmei que o Python 3.12.8 estava instalado e acessível via terminal.

Confirmei o pip e o path via:

python --version

pip --version

Get-Command python

Tudo operacional.

2. Criação do ambiente virtual (venv)

Criei o diretório do projeto.

Ativei o ambiente virtual com:

python -m venv venv

.\venv\Scripts\activate

O prefixo (venv) apareceu corretamente no terminal, confirmando ativação.

3. Instalação das bibliotecas essenciais

Instalei e validei os seguintes pacotes:

pandas → manipulação de planilhas (CSV/Excel)

openpyxl → leitura/escrita de arquivos Excel

requests → comunicação com APIs externas

python-dotenv → leitura de variáveis de ambiente (.env)

106 dependências foram instaladas automaticamente — isso é normal e desejado, pois são libs internas usadas por esses pacotes.

4. Teste 1 — Execução básica do Python

Criei e rodei o arquivo src/main.py para validar o ambiente.

Resultado:
Ambiente Python OK. venv ativo e funcional!

5. Teste 2 — Validação da biblioteca requests

Criei teste2_requests.py e testei a comunicação HTTP simulada.

Resultado: sucesso.

6. Teste 3 — Teste de importação geral

Criei teste3_imports.py para garantir que todas as bibliotecas essenciais funcionam.

Resultado:
Todas as bibliotecas foram importadas com sucesso!

7. Teste 4 — Configuração e validação do arquivo .env

Criei o arquivo .env contendo:

MYSQL_HOST=localhost
MYSQL_USER=root
MYSQL_PASSWORD=senha123
MYSQL_DATABASE=automacao_leads


E testei com teste4_env.py.

Resultado:
Todas as variáveis foram lidas corretamente pelo Python.

✔️ Finalização do dia

O ambiente Python do projeto está completamente configurado, testado e funcional.
Agora estamos prontos para iniciar a integração com o MySQL (Teste 5 em diante).


__________________________________________________________________________________________________________________________________________

15-12-25

Etapa: Integração Python + MySQL (Fundação do MVP)

Nesta etapa do projeto foi iniciada a preparação do ambiente Python para integração com o banco de dados MySQL, com foco em aprendizado, estabilidade e boas práticas desde o início.

Foram realizados os seguintes passos e testes:

Verificação da instalação correta do Python (3.12) e do pip, garantindo que o interpretador estivesse acessível via terminal.

Criação e ativação de um ambiente virtual (venv) para isolar dependências do projeto.

Instalação das bibliotecas necessárias para o MVP:

requests (consumo de APIs)

pandas e openpyxl (manipulação e exportação de dados)

mysql-connector-python (integração com MySQL)

python-dotenv (leitura segura de variáveis de ambiente)

🐞 Bugs encontrados e aprendizados

Durante os testes iniciais de conexão com o MySQL, foram identificados e analisados diversos problemas comuns em ambientes Windows:

Erro de conexão via Named Pipe (2017 HY000)

O Python tentou se conectar ao MySQL usando Named Pipe por padrão.

Correção: forçar conexão via TCP/IP utilizando host=127.0.0.1 e port=3306.

Erro de acesso negado (1045 – user 'ODBC')

O conector estava utilizando variáveis de ambiente do próprio Windows (USER, PASSWORD).

Correção: adoção de variáveis com prefixo DB_ no arquivo .env.

Arquivo .env não sendo carregado

O load_dotenv() não encontrou automaticamente o arquivo .env devido à estrutura do projeto (src/).

Correção: carregamento explícito do caminho do .env usando Path(__file__).

Execução sem saída no terminal

Scripts rodavam sem retorno por falta de print() ou arquivo não salvo corretamente.

Correção: criação de scripts de debug para validar execução e leitura de variáveis.

Esses problemas foram tratados como parte do processo de aprendizado, garantindo uma base sólida para evitar falhas futuras em produção.

Status atual

Ambiente Python funcional

Ambiente virtual ativo

Bibliotecas essenciais instaladas

MySQL Server validado e operacional

Debug em andamento para validação final da leitura do .env e conexão com o banco

Próximo passo:
➡ Finalizar teste de conexão MySQL via Python
➡ Executar SELECT real nas tabelas
➡ Iniciar o fluxo básico da automação (MVP)

E descobri que não tinha salvado o .env no VS Code, depois apareceu outro erro que estou estudando o que pode ser.

______________________________________________________________________________________________________________________________________
16-12-25

Bloco C — Integração Python ↔ MySQL (C2 até C3)
🔹 Contexto

Nesta etapa do projeto, iniciei a integração real entre o Python e o MySQL, utilizando um banco funcional já validado anteriormente (EER, FKs, ENUMs e integridade). O objetivo foi garantir que o software consiga ler e escrever dados no banco com segurança, respeitando regras de negócio e integridade.

✅ TESTE C2 — SELECT simples via Python
🎯 Objetivo

Validar se:

o Python consegue se conectar ao MySQL

a query SQL é executada corretamente

o retorno do banco é interpretado pelo Python

🧪 Query testada
SELECT COUNT(*) FROM usuarios;

📄 Script Python

Arquivo: teste_c2_conexao.py

Uso de:

mysql-connector-python

variáveis carregadas do .env

cursor + fetchone()

📤 Resultado
Total de usuários cadastrados: 3

📌 Conclusão

✔ Conexão estabelecida com sucesso
✔ Banco correto sendo utilizado
✔ SELECT funcional
✔ Cadeia Python → MySQL → Python validada

Esse teste confirmou que o ambiente está pronto para operações reais de leitura.

✅ TESTE C3 — INSERT controlado via Python (com prevenção de duplicidade)
🎯 Objetivo

Garantir que:

o sistema não insira usuários duplicados

a regra de unicidade do email seja respeitada

erros de banco sejam tratados corretamente

🧠 Regra aplicada

Antes de inserir:

SELECT id FROM usuarios WHERE email = %s;


Se existir → cancelar INSERT

Se não existir → realizar INSERT

🧪 Script

Arquivo: teste_c3_conexao.py

Uso de:

placeholders %s

commit() explícito

tratamento de erro com try/except

fechamento correto de conexão

🧨 Problema encontrado (esperado)

Erro:

1205 (HY000): Lock wait timeout exceeded

📌 Diagnóstico

Lock causado por sessões abertas no MySQL Workbench / testes anteriores

Comportamento normal do InnoDB em ambiente de testes intensivos

🛠️ Solução aplicada

Reinício do MySQL Server

Boas práticas reforçadas:

fechar conexões

commits explícitos

evitar sessões penduradas

📤 Resultado final
Usuário inserido com sucesso!

📌 Conclusão

✔ INSERT via Python funcionando
✔ Regras de negócio aplicadas
✔ Tratamento de erro validado
✔ Primeiro cenário real de lock compreendido

Este teste valida que o sistema escreve dados de forma segura, sem quebrar integridade.

🧠 Aprendizados importantes desta etapa

%s é placeholder do Python, não do MySQL puro

Erros de duplicidade (1062) são proteção, não bug

Locks fazem parte de sistemas reais

Reiniciar o MySQL é aceitável em testes, não em produção

Código bem escrito evita locks futuros

🏁 Status do Bloco C

✅ Ambiente Python funcional
✅ .env carregando corretamente
✅ MySQL conectado
✅ SELECT validado
✅ INSERT validado
✅ Tratamento de erro aplicado
✅ Base pronta para automações reais