---
title: Avaliações
layout: default
parent: Partidas
nav_order: 3
---

# Avaliações
{: .no_toc }

<details open markdown="block">
  <summary>Nesta página</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## Como funciona

Após cada partida, os membros que participaram podem **avaliar os outros atletas** com uma nota de **0 a 5**. As notas são usadas para calcular a média de cada atleta na partida e alimentar o histórico de desempenho.

---

## Quem pode avaliar?

- Apenas atletas que **participaram da partida** podem enviar avaliações.
- Cada membro avalia todos os outros (não avalia a si mesmo, se essa opção estiver ativa nas configurações).
- A votação fica disponível somente enquanto o status da partida for **"Finalizada — votação aberta"**.

---

## Como avaliar (visão do membro)

1. Acesse a partida pela aba **Partidas** do clube.
2. Se você participou e a votação está aberta, a seção **"Atletas e Avaliações"** aparece na parte inferior da tela.
3. Para cada atleta, mova o **slider** para a nota desejada.

| Nota | Significado |
|------|------------|
| 0 | Comprometeu o desempenho da equipe |
| 1 | Não foi bem no jogo |
| 2 | Participou pouco do jogo |
| 3 | Fez o básico e ajudou a equipe |
| 4 | Jogou bola, foi importante |
| 5 | Chamou a responsabilidade e decidiu o jogo |

4. Após avaliar todos, clique em **Enviar Avaliações**.

![Tela de avaliações](../assets/screenshots/avaliacoes.png)
*Placeholder — adicione um screenshot da tela de avaliações*

{: .tip }
> Você pode enviar as avaliações em partes — o app salva as notas enviadas. Se voltar depois, as notas já enviadas aparecem como "Sua nota: X" e as pendentes continuam disponíveis.

---

## Como a média é calculada

Após cada envio de nota, o app recalcula automaticamente a média do atleta naquela partida:

**Cálculo padrão:**
```
Média = soma de todas as notas ÷ quantidade de avaliações
```

**Com "Remover Extremos" ativado** (configurável pelo Admin):
- Se o atleta tiver **3 ou mais avaliações**, a nota mais alta e a nota mais baixa são descartadas antes de calcular a média.
- Isso reduz o impacto de avaliações tendenciosas ou injustas.

---

## Prazo para avaliar

O Admin pode definir um **prazo em dias** após a data da partida. Após esse prazo, novas avaliações não são aceitas.

Exemplo: prazo de 3 dias → partida de segunda → avaliações aceitas até quinta.

Se o prazo estiver em branco, não há limite de tempo (enquanto a votação estiver aberta).

---

## O que acontece ao encerrar a votação

Quando o Admin/Moderador encerra a votação:

1. As médias finais são registradas para cada atleta.
2. O MVP é eleito (se habilitado).
3. O ranking da temporada é atualizado com os pontos da partida.

→ Veja como funciona o MVP: [Ranking e MVP](../ranking/ranking-e-mvp)
