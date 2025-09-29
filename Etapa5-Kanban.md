# Guia para Construção de Quadro Kanban no GitHub Projects

## Estrutura do Backlog com 3 colunas
No seu Kanban, o backlog será dividido em três colunas principais:  
- **Backlog Propose** → (Draft) casos de usos ainda não aprovadas para desenvolvimento.  
- **Backlog In Progress** → (Issue) Casos de uso aprovadas e em planejamento ou desenvolvimento.  
- **Backlog Done** → Casos de Uso concluídos e entregues.


---

## 2. Criação das Labels
1. Vá para **Issues → Labels**.  
2. Crie labels para organizar as tarefas, por exemplo:  
   - **Por ator/tipo de tarefa**: `Vendedor`, `Gerente`, `Pedido`, `Produto`, `Fornecedor`  
   - **Por prioridade**: `Alta`, `Média`, `Baixa`  
   - **Por tamanho/complexidade**: `P` (Pequeno), `M` (Médio), `G` (Grande)  

---

## 3. Criação dos Milestones
1. Vá para **Issues → Milestones → New Milestone**.  
2. Crie milestones para representar **sprints ou objetivos maiores**, por exemplo:  
   - Sprint 1: Cadastro de clientes e pedidos  
   - Sprint 2: Gestão de produtos e fornecedores  
   - Sprint 3: Relatórios e consultas  
3. Atribua os Draft Issues aos milestones correspondentes.

---

## 4. Transformação de Draft para Issue
1. Abra cada **Draft Issue** que você deseja iniciar.  
2. Clique em **Convert to Issue** para transformar o rascunho em issue ativa.  
3. Atribua **labels** (atores, prioridade, tamanho), **milestone** e, se desejar, **assignees**.  
4. Mova a issue para **Backlog In Progress** quando estiver aprovada para desenvolvimento.

---

## 5. Planejamento da Sprint
1. Defina o **período da sprint** (ex.: 2 semanas).  
2. Selecione as issues do backlog que serão trabalhadas na sprint.  
3. Verifique prioridades, dependências e estimativas de tamanho (`P`, `M`, `G`).  
4. Atualize as issues com **labels de prioridade e tamanho**, e mova para **Backlog In Progress**.
5. Crie novos issues baseado em User Stories na coluna **To Do**
6. Rotule todas as novas issues
7. Associe os Issue do Backlog com os Issues do Todo (sub-issue do backlog)
---

## 6. Criação do Sprint Backlog
1. Crie colunas para o fluxo de trabalho durante a sprint:  
   - **To Do** → tarefas prontas para iniciar  
   - **In Progress** → tarefas em desenvolvimento  
   - **Blocked** → tarefas temporariamente bloqueadas  
   - **Review / QA** → tarefas em revisão ou testes  
   - **Done** → tarefas concluídas  
2. Atualize o quadro sempre que novos eventos acontecerem, movendo as issues conforme o progresso:  
   - **To Do → In Progress → Review / QA → Done**  
   - Se houver bloqueio, mova para **Blocked** até a resolução.

---

## 7. Manutenção do Quadro
- Revise diariamente durante o stand-up.  
- Ajuste prioridades, dependências, tamanho estimado e status de bloqueio quando necessário.  
- No final da sprint, mova todas as tasks concluídas para **Backlog Done**.  
- Prepare a próxima sprint repetindo os passos de planejamento e criação do backlog.
