# Skill — Briefing executivo (resumo de doc longo)

## Quando usar

Quando você recebe um documento longo e precisa entender o que importa em 5 minutos: contrato, proposta de fornecedor, relatório, regulamento, plano de negócio. A skill devolve um briefing de uma página com pontos de decisão claros — e cita os trechos do original.

## Como usar

1. Abra uma nova conversa no Claude.
2. Anexe o documento OU cole o texto direto na conversa.
3. Cole o prompt abaixo.
4. Revise o briefing. Se faltou algo, peça o complemento — não comece de novo.

---

## Prompt

```
Você é um analista que prepara briefings executivos. Vou te mandar um
documento longo (contrato, proposta, relatório, regulamento, plano de
negócio). Devolva um briefing de UMA página com a seguinte estrutura:

BRIEFING EXECUTIVO

1. O QUE É (1-2 linhas)
   Diga em palavras simples o que é o documento e qual seu propósito.

2. PARTES ENVOLVIDAS
   Quem assina, quem paga, quem entrega, quem fiscaliza. Use os nomes que
   aparecem no documento.

3. NÚMEROS QUE IMPORTAM
   Liste os 3-5 números mais importantes (valores, prazos, multas, taxas,
   percentuais). Cite o trecho ou a cláusula de onde tirou cada um.

4. COMPROMISSOS
   O que CADA parte se compromete a fazer? Liste em bullets. Sinalize com
   ⚠ qualquer compromisso assimétrico (uma parte pega muito mais risco
   que a outra).

5. PONTOS DE ATENÇÃO (até 3)
   Cláusulas, condições ou números que merecem ser revisados ou
   negociados. Para cada um: trecho literal + por que está no radar.

6. PERGUNTAS QUE EU FARIA ANTES DE ASSINAR (até 3)
   Coisas que o documento NÃO esclarece e que você buscaria entender.

Regras:
- Cite trechos literais entre aspas onde for citar o documento.
- Não invente cláusula, valor ou parte que não esteja no texto.
- Se o documento for ambíguo em algum ponto, diga "ambíguo: [trecho]" em vez
  de chutar interpretação.
- O briefing inteiro deve caber em UMA página. Se está estourando, encurte.

Documento:
[cole ou anexe]
```
