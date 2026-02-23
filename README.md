# 🚀 Agent Boilerplate Template

Template pré-configurado com **rules**, **workflows** e **skills** para projetos usando Gemini Code Assist.

## 📦 Como Usar

### Opção 1 — GitHub Template
1. Clique em **"Use this template"** → **"Create a new repository"**
2. Nomeie seu novo projeto e crie
3. Clone o novo repositório e comece a desenvolver

### Opção 2 — Copiar manualmente
```bash
# Clone este template
git clone https://github.com/IgvxI/agent-boilerplate-template.git

# Copie a pasta .agent para o seu projeto
xcopy ".agent" "C:\seu-projeto\.agent" /E /I /H /Y
```

---

## 📁 Estrutura

```
.agent/
├── rules/                    # Conditional rules (ativadas por contexto)
│   ├── backend-architect.md
│   ├── code-reviewer.md
│   ├── frontend-developer.md
│   ├── payment-integration.md
│   ├── react-optimizer.md
│   ├── screenshot-analyzer.md
│   ├── security-auditor.md
│   ├── seo-specialist.md
│   ├── superpowers-rules.md
│   └── uiux-designer.md
├── skills/                   # Skills reutilizáveis
│   ├── superpowers-brainstorm/
│   ├── superpowers-debug/
│   ├── superpowers-finish/
│   ├── superpowers-plan/
│   ├── superpowers-python-automation/
│   ├── superpowers-rest-automation/
│   ├── superpowers-review/
│   ├── superpowers-tdd/
│   └── superpowers-workflow/
└── workflows/                # Workflows automatizados
    └── deploy.md
```

## 🔧 Rules Disponíveis

| Rule | Descrição |
|------|-----------|
| `backend-architect` | Arquitetura de backend e design de APIs |
| `code-reviewer` | Revisão de código com foco em qualidade e segurança |
| `frontend-developer` | Desenvolvimento frontend multi-framework |
| `payment-integration` | Integração com sistemas de pagamento |
| `react-optimizer` | Otimização de performance React |
| `screenshot-analyzer` | Análise de screenshots |
| `security-auditor` | Auditoria de segurança |
| `seo-specialist` | Otimização SEO |
| `superpowers-rules` | Regras gerais do Superpowers |
| `uiux-designer` | Design UI/UX com feedback baseado em pesquisa |

## ⚡ Skills Disponíveis

| Skill | Descrição |
|-------|-----------|
| `superpowers-plan` | Plano de implementação com verificação |
| `superpowers-review` | Revisão de código com severidade |
| `superpowers-tdd` | TDD com red/green/refactor |
| `superpowers-brainstorm` | Brainstorming estruturado |
| `superpowers-debug` | Debug sistemático |
| `superpowers-finish` | Finalização e summary |
| `superpowers-python-automation` | Automação com Python |
| `superpowers-rest-automation` | Automação REST API |
| `superpowers-workflow` | Workflow engine |

## 🔄 Workflows

| Workflow | Comando | Descrição |
|----------|---------|-----------|
| Deploy | `/deploy` | Deploy rápido na Vercel |