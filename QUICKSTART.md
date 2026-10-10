# CAP v0.3 — Quick start

This is the shortest path to trying CAP without needing to understand the wider El Canal corpus.

## 1. Start a new conversation

Open `activacion.md` and paste it into a new conversation with the LLM you want to use.

CAP is model-agnostic: it does not require a specific provider, memory feature, agent framework or integration.

## 2. Declare the working state

After activation, give the minimum context needed for the actual task.

Synthetic example:

```text
Estado:
Estoy preparando una nota comparativa sobre tres alternativas de software.

Objetivo:
Quiero llegar a una decisión razonada, no recibir una recomendación automática.

Contexto disponible:
Tengo requisitos, costes y dos informes técnicos.

Restricciones:
- distingue hechos, interpretación, hipótesis y propuesta;
- no cierres la decisión por mí;
- señala qué información falta antes de comparar;
- mantén la salida abierta si aparece una alternativa mejor.
```

The point is not the wording. The point is to make the state, objective and limits explicit.

## 3. Add context only when it reduces ambiguity

Use `contexto.md` when background information is necessary to understand the current work.

Do not load context simply because it exists.

## 4. Use history only when continuity matters

Use excerpts from `log.md` only when a past decision, observation or unresolved question materially affects the present task.

CAP does not require exhaustive conversation history.

## 5. Close deliberately

At the end of a meaningful work cycle, separate:

- what became a stable fact;
- what remains an interpretation or hypothesis;
- what was proposed but not decided;
- what the human actually decided;
- what, if anything, deserves to enter the log.

## What you should notice

A useful CAP session should make it easier to see:

- which statements are facts and which are interpretations;
- where the model is proposing rather than deciding;
- what context is actually necessary;
- whether a theory is expanding beyond the evidence;
- whether the work can continue with another model without losing its structure.

## What CAP does not do

CAP does not automate judgment, guarantee correctness or replace human review.

It provides a small operational structure so that the relationship remains inspectable and portable.

## Next

- Core activation: [activacion.md](activacion.md)
- Context template: [contexto.md](contexto.md)
- Log template: [log.md](log.md)
- Wider ecosystem map: [github.com/ulaulaygpt](https://github.com/ulaulaygpt)
- Canonical public release: [DOI 10.5281/zenodo.23138399](https://doi.org/10.5281/zenodo.23138399)
