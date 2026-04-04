---
title: Criar uma Partida
layout: default
parent: Partidas
nav_order: 1
---

# Criar uma Partida
{: .no_toc }

<details open markdown="block">
  <summary>Nesta página</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## Como acessar

Na tela do clube, vá para a aba **Partidas** e clique em **+ Nova Partida** (ou no botão equivalente). A criação de partida tem **dois passos**.

---

## Passo 1 — Quem compareceu hoje?

Selecione os atletas que estão presentes na pelada:

- Toque/clique no nome do atleta para marcá-lo. O card fica destacado com borda colorida.
- Use **Selecionar Todos** para marcar o elenco inteiro de uma vez.
- A lista mostra apenas atletas com status **Mensalista** ou **Convidado** (inativos não aparecem).

![Seleção de presença](../assets/screenshots/criar-partida-passo1.png)
*Placeholder — adicione um screenshot do passo 1*

Após selecionar, você tem duas opções:

| Botão | O que faz |
|-------|-----------|
| **Próximo: Montar Times** | Vai para o passo 2 — você organiza os times manualmente ou usa o sorteio. |
| **Sortear Times** | Sorteia automaticamente e já vai para o passo 2 com os times montados. |

{: .note }
> É necessário selecionar ao menos **2 atletas** para avançar.

---

## Passo 2 — Dividir os times e registrar o placar

### Organizar os times

Os atletas selecionados aparecem divididos em **Time A** e **Time B**.

- **Mover jogador:** Toque no nome do atleta para movê-lo para o outro time.
- **Sortear novamente:** Clique em **Sortear** (ícone de embaralhar) para redistribuir aleatoriamente.
- Abaixo de cada time aparece a **média de notas** do grupo — útil para verificar o equilíbrio.

![Montagem dos times](../assets/screenshots/criar-partida-passo2.png)
*Placeholder — adicione um screenshot do passo 2*

### Como o sorteio funciona

O algoritmo tenta montar os times mais equilibrados possível. Ele considera:

- **Goleiros:** cada time recebe exatamente 1 goleiro (quando há 2).
- **Posições:** distribui jogadores defensivos e ofensivos de forma equilibrada entre os times.
- **Histórico de parcerias:** evita repetir as mesmas duplas de jogadores sempre juntos.
- **Distribuição de habilidade:** usa *snake draft* — os jogadores são ordenados por nota e distribuídos no padrão A, B, B, A, A, B… para que o melhor de cada rodada vá para times opostos. A qualidade do sorteio é medida comparando as distribuições posição a posição (melhor × melhor, 2º × 2º, etc.), não apenas a média geral.

O algoritmo gera 200 combinações e escolhe a mais equilibrada.

### Data da partida

Por padrão, a data é definida como **hoje**. Clique no campo de data para alterar (útil para registrar partidas retroativamente).

### Placar

Digite o número de gols de cada time nos campos centrais:

```
Time A  [2]  ×  [1]  Time B
```

O placar pode ser deixado em 0×0 e editado depois, já dentro da partida.

### Compartilhar os times

Clique em **Compartilhar** para gerar uma imagem com os dois times e o nome do clube. Ideal para enviar no grupo do WhatsApp antes da pelada começar.

### Salvar a partida

Clique em **Salvar Partida**. A partida é criada e você é levado automaticamente para a tela de **Detalhes da Partida**.

---

## Próximo passo

[Gerenciar a Partida →](gerenciar-partida) — editar placar, abrir e encerrar a votação
