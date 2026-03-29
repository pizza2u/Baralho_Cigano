# 🔮 Baralho Cigano

> Experimento gerado com IA — criado inteiramente numa conversa com o [Claude](https://claude.ai) (Anthropic), sem escrever uma linha de código manualmente.

---

## Sobre o projeto

Este é um jogo de **Baralho Cigano Lenormand** interativo, feito como teste pessoal para explorar o que é possível criar usando apenas o Claude como ferramenta de desenvolvimento.

A ideia era simples: pedir ao Claude que construísse um app funcional e visualmente elaborado, iterando em cima dele através de conversa — sem IDE, sem framework, sem setup.

## Como funciona

- Todas as **36 cartas Lenormand** estão implementadas com símbolos e palavras-chave
- O baralho é **embaralhado aleatoriamente** a cada tiragem
- Há **3 tipos de tiragem** disponíveis:
  - 🕯️ Carta do Momento — 1 carta
  - ⏳ Passado · Presente · Futuro — 3 cartas
  - ✡️ Cruz Cigana — 5 cartas
- A **interpretação é gerada localmente**, sem chamadas a APIs — cada carta tem textos próprios e o motor monta a leitura com base no conjunto sorteado
- Funciona como um **arquivo HTML único**, sem dependências, sem servidor

## Tecnologias

- HTML + CSS + JavaScript puro
- Zero dependências externas (exceto fontes do Google Fonts)
- Roda direto no navegador, offline

## Como usar
Clique:
[Baralho Cigano](https://pizza2u.github.io/Baralho_Cigano/)

## Contexto do experimento

O objetivo não era criar o melhor app de tarot do mundo — era testar **até onde o Claude consegue ir** numa única conversa, partindo do zero:

- Layout e visual foram gerados pelo Claude com direção estética própria
- A lógica de interpretação foi construída e depois refatorada (versão original usava a API da Anthropic; depois migrei para modo offline por sugestão do próprio Claude)
- Iterações foram feitas em linguagem natural, sem escrever código

É um protótipo. Funciona. Foi divertido.

---

*Feito com Claude · 2025*
