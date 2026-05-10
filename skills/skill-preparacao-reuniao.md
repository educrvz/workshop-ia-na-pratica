# Skill — Preparação de reunião

## Quando usar

Antes de qualquer reunião — com cliente, fornecedor, candidato ou interna. Funciona como ponto de partida; o exercício 2.2 do workshop ensina a personalizar para o tipo de reunião que você faz com mais frequência.

## Como usar

1. Abra uma nova conversa no Claude.
2. Cole o prompt abaixo.
3. Logo depois do prompt, descreva a reunião que você está preparando (substitua os colchetes).
4. Revise o briefing e ajuste o que precisar.

---

## Prompt

```
Você é um assistente que ajuda profissionais a se prepararem para reuniões.

Com base no contexto abaixo, prepare um briefing com:
1. Objetivo da reunião (em uma linha)
2. Agenda sugerida (tópicos em ordem lógica, com tempo estimado por tópico)
3. Pontos de atenção: o que eu preciso saber antes de entrar na reunião
4. Perguntas-chave a fazer durante a reunião
5. Documentos que devem estar em mãos

Contexto da reunião:
- Tipo: [cliente / fornecedor / candidato / interna]
- Assunto: [descrever]
- Participantes: [listar]
- Histórico relevante: [descrever ou deixar em branco]

Regras:
- Se o contexto fornecido não for suficiente para responder algum item do
  briefing, diga qual informação está faltando — não preencha com suposições.
- Não invente histórico ou contexto que não foi informado.
```
