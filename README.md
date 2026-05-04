# 🏭 FÁBRICA DE CONTEÚDO

![Status](https://img.shields.io/badge/Status-Ativo-brightgreen)
![GitHub repo size](https://img.shields.io/github/repo-size/guitriloco/fabrica-conteudo)
![GitHub last commit](https://img.shields.io/github/last-commit/guitriloco/fabrica-conteudo)
![GitHub](https://img.shields.io/github/license/guitriloco/fabrica-conteudo)

> Sistema de geração e organização de conteúdo para infoprodutos, dropshipping e vendas digitais.

---

## 🎯 O QUE É

Uma **"fábrica"** que ingere materiais existentes, extrai insights e gera novos conteúdos de vendas:

```
📥 INPUT          →  ⚙️ PROCESSO        →  📤 OUTPUT
materias-primas       análise IA           landing-pages
listas de nicho       extração              copies-venda  
copies antigos        geração               emails
dados fornecedores    curadoria             scripts
```

---

## 📁 ESTRUTURA

```
fabrica-conteudo/
├── README.md
├── .github/
│   ├── workflows/           ← automações GitHub Actions
│   │   └── validate-content.yml
│   └── ISSUE_TEMPLATE/      ← templates de requisição
│       ├── solicitar-copy.md
│       └── bug-report.md
├── materias-primas/         ← seus PDFs, textos, materiais
├── nichos/                 ← organizados por nicho
│   ├── ganhos-online/
│   ├── fitness/
│   └── pets/
├── copias-geradas/         ← output da fábrica
│   ├── landing-pages/
│   ├── copies-venda/
│   ├── emails/
│   └── scripts/
└── fornecedores/           ← listas e dados
```

---

## 🚀 COMO USAR

### 1. Solicitar Novo Copy
Vá em **Issues → New Issue → Solicitar Novo Copy**
```markdown
- Nicho/Produto: [seu produto]
- Plataforma: [Facebook/TikTok/Email/etc]
- Formato: [copy curto/longo/landing]
- Tom: [urgente/educativo/emocional]
```

### 2. Workflow Automático
A cada push em `copias-geradas/`, o GitHub Actions valida automaticamente:
- ✅ Formato Markdown
- ✅ Presença de título (#)
- ✅ Existência de CTA
- ✅ Gera relatório de status

### 3. Status da Fábrica
```bash
# Copies gerados: 1
# Landing Pages: 1  
# Scripts: 1
# Fornecedores: 1
```

---

## 🔥 NICHIOS ATIVOS

- 💰 Ganhos Online
- 🏋️ Fitness / Emagrecimento  
- 🐕 Pets
- 🏠 Casa e Decoração
- 🎮 Gamer / Tech

---

## 🤖 AUTO-MANUTENÇÃO

| Arquivo | Função | Status |
|---------|--------|--------|
| `validate-content.yml` | Valida formato dos MD | ✅ |
| `solicitar-copy.md` | Template Issue Copy | ✅ |
| `bug-report.md` | Template Issue Bug | ✅ |

---

## 📊 METRICAS

![Validation](https://github.com/guitriloco/fabrica-conteudo/actions/workflows/validate-content.yml/badge.svg)

---

*⚡ Mantido por CTO.new | Atualizado: 2025*
