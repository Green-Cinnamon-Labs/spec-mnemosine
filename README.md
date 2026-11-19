# spec-mnemosine

> Mnemósine, a deusa grega da memória, mãe das nove Musas.

Linha de pesquisa do [Green Cinnamon Labs](https://github.com/Green-Cinnamon-Labs) sobre engenharia de AI: treinar modelos, aperfeiçoá-los e aprender os frameworks.

## O que sei hoje

- Quero praticar AI: treinar redes, aperfeiçoar modelos, aprender frameworks.
- Existe o problema da memória latente que eu queria explorar ([`lab-latent-memory`](https://github.com/Green-Cinnamon-Labs/lab-latent-memory)).
- Antes disso, talvez eu precise de uma leitura do estado da arte do tema. Ainda não sei o suficiente.

Isto muda conforme eu avanço.

## Repositórios

Ficam lado a lado em `C:\Projetos\gclabs\`, e o workspace é o [`mnemosine.code-workspace`](mnemosine.code-workspace).

| Repositório | Papel |
| --- | --- |
| [`lab-latent-memory`](https://github.com/Green-Cinnamon-Labs/lab-latent-memory) | Laboratório de memória latente |

## Livro

[`book/`](book/)

---

## Memória latente: a especificação inicial

This repository defines the research direction, mathematical premises,
and experimental strategy of the Latent Memory project.

It serves as the authoritative source of research assumptions,
design decisions, and project evolution.

---

### Objective

Build a long-term memory object for LLMs that persists state across sequences
without reinjecting all prior tokens — investigating latent and compressed memory
representations grounded in mathematics.

---

### Research Interest

**TOPIC 2 — LLM Context & Memory**

**Primary:** context compression methods for LLMs, latent/persistent memory across long sequences, memory-augmented transformers, efficient token representation.

**Secondary:** efficient attention mechanisms (linear, sparse, sliding-window), KV cache compression, in-context learning mechanics, long-context architecture design.

---

### Core Research Question

Can long-term memory be maintained in a compact latent object such that,
given a new token sequence, the model does not need to reprocess all prior tokens
to recover relevant context?

---

### Related Repositories

- [`lab-latent-memory`](https://github.com/Green-Cinnamon-Labs/lab-latent-memory/tree/main)
  Experimental lab for latent memory implementations and probes.
  Active workspace for testing memory compression approaches in practice.
