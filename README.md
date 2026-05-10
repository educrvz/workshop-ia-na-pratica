# Workshop de IA — site adaptado

Site de exercícios para o workshop, gerado a partir das 3 respostas do questionário pré-workshop.

## Arquivos

- `index.html` — landing com links para as 3 sessões
- `sessao-1.html` — Confiança e fundamentos
- `sessao-2.html` — Produtividade na prática
- `sessao-3.html` — Indo além
- `style.css` — estilos compartilhados (charcoal / cinza / dourado / branco)
- `skills/` — arquivos `.md` das skills disponibilizadas para download

## Como publicar no GitHub Pages

1. Crie um repositório novo no seu GitHub.
2. Suba todos os arquivos (incluindo a pasta `skills/`) na raiz do repo.
3. Settings → Pages → Source: branch `main`, folder `/ (root)` → Save.
4. URL fica `https://[seu-usuário].github.io/[nome-do-repo]/`.

---

## Cohort lido do formulário (revisado)

| # | Quem | Indústria | Estágio com IA | Office | Apps MS | Conta Claude |
|---|------|-----------|----------------|--------|---------|--------------|
| 1 | Caio Bezerra (Gmail) | Imobiliária / corretagem | **Iniciante absoluto** | M365 | Excel + outros | Convite enviado — paga |
| 2 | (recrutador) | Recrutamento de executivos | **Iniciante absoluto** (Nunca usei) | M365 | Excel + Word + PowerPoint | Convite enviado — paga |
| 3 | Vitor Junqueira | Construção civil (empresário) | **Iniciante absoluto** (Tentou, não pegou) | (provável M365) | (provável Excel/Word/PowerPoint) | Convite enviado — paga |

**Implicações para o workshop:**

- **Cohort 100% iniciante.** Manter os fundamentos completos da Sessão 1 (LLM, tokens, contexto, memória, prompt). NÃO comprimir.
- **Todos com Claude pago.** O Edu mandou convite para os três — todos terão plano pago durante o workshop. Isso simplifica a Sessão 1 (sem PII / sem comparação entre ferramentas pessoais e corporativas), mas **mantém o exercício 1.2** porque o plano pago do Claude **não desliga o treinamento por padrão** — precisa entrar e desligar manualmente. Exercício é Claude-only agora, não mais multi-ferramenta.
- **Todos com Gmail.** Vitor já foi avisado e ou já tem conta ou está criando. Logo: o exercício 1.3 (NotebookLM) roda para todos sem fricção.
- **Setor misto.** Imobiliária + recrutamento + construção. Exemplos universais de negócio, não específicos de uma vertical.
- **M365-pesado.** Sessão 3 mantém a seção sobre Claude dentro do Office — agora com demos concretos de Excel, Word e PowerPoint.

---

## Principais adaptações vs. o template HRSA

### Sessão 1
- **Fundamentos:** mantidos integralmente.
- **Exercício 1.1 (três personagens):** trocados Pontes/Marco Aurélio/Galvão por **Mano Brown / Cebolinha / Galvão Bueno**. Conceitos: LGPD / ROI / Funil de vendas. Prompt detalhado para a IA capturar a voz de cada um (incluindo o rotacismo do Cebolinha — R→L em todas as palavras).
- **Exercício 1.2:** mantido, simplificado para Claude-only. Toggle "Help improve Claude" em `claude.ai/settings/data-privacy-controls`. Inclui aviso sobre 👍/👎 enviarem feedback explícito mesmo com toggle desligado.
- **Removido:** seção C (segurança de dados / comparação entre ferramentas). Sem PII discussion.
- **Mantidos:** A (fundamentos), B (prompt), 1.1, 1.2, 1.3 NotebookLM, D (alucinações).

### Sessão 2
- **Conceitos (skill, plugin, project):** mantidos.
- **2.1 (notas → ata):** mantido. Skill genérica para qualquer profissional.
- **2.2 (personalização):** mantida. Generaliza-se para qualquer tipo de reunião que o aluno faz.
- **Biblioteca de skills:** trocada para o cohort.
  - Skill A — Preparação de reunião (mantida)
  - Skill B — **NOVA: Resposta a e-mail delicado** (cliente irritado, cobrança, dar feedback difícil)
  - Skill C — **NOVA: Briefing executivo** (resumir documento longo em 1 página)
  - Skill D — Revisão estruturada de documento (mantida — útil em proposta, orçamento, contrato curto, descrição de vaga)

### Sessão 3
- **Demos do Claude no Chrome (duas, ambas no Gmail/LinkedIn que todos têm):**
  - Demo 1 — Pesquisa de pessoa no LinkedIn antes de uma reunião.
  - Demo 2 — Limpeza de inbox: Claude identifica e clica em "unsubscribe" em e-mails promocionais.
- **3.1 (texto → deck):** repensado. Saiu OKRs (jargão que o cohort não conhece). Entrou: **a própria proposta comercial do aluno**. Cada um traz uma proposta sua (real ou hipotética em 2 linhas) e o Claude transforma em deck pronto para apresentar ao cliente. Estrutura prevista no prompt: capa, diagnóstico, escopo, entregáveis, investimento, diferenciais, próximos passos. Mais útil e mais relacionável que um conceito abstrato.
- **Seção B — Claude dentro do Office:** agora com demos concretos:
  - **Excel:** análise rápida de planilha de leads / vendas / orçamento — pergunte "quais 5 são prioritários" e o Claude devolve a tabela ranqueada.
  - **Word:** abrir uma proposta de fornecedor de 10+ páginas e pedir os 3 pontos mais arriscados — Claude lê, devolve em 30 segundos.
  - **PowerPoint:** abrir um deck antigo, pedir "me prepara para apresentar isso em 15 min — me dá um script de fala por slide".

---

## Skills (arquivos `.md` em `skills/`)

| Arquivo | Para quê serve |
|---|---|
| `skill-preparacao-reuniao.md` | Briefing antes de qualquer reunião — agenda, perguntas-chave, pontos de atenção. |
| `skill-resposta-email-delicado.md` | Responder a e-mail de cliente irritado, cobrança difícil, feedback que a gente quer evitar. |
| `skill-briefing-executivo.md` | Pegar um documento longo e devolver um resumo executivo de 1 página, com pontos de decisão claros. |
| `skill-revisao-documento.md` | Revisar proposta, orçamento, contrato curto ou descrição de vaga — semáforo de risco e sugestões de ajuste. |

Todos os arquivos têm o prompt completo + uma seção curta no topo explicando "quando usar" e "como usar".

---

## O que ainda falta antes de publicar

1. **NotebookLM 1.3:** notebook **"Negociação Harvard — Workshop IA"** já criado e compartilhado (anyone with link). 9 fontes em português sobre Harvard / Fisher e Ury / BATNA / ZOPA / posições vs. interesses / ganha-ganha.
   URL: <https://notebooklm.google.com/notebook/55f906ba-b227-4eda-af3d-2be4a6c63e9b>
2. **Branding mantido:** DC Cruz · Workshop · Maio 2026.
