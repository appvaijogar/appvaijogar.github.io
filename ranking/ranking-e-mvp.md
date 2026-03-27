---
title: Como Funciona o Ranking
layout: default
parent: Ranking e MVP
nav_order: 1
---

# Como Funciona o Ranking
{: .no_toc }

<details open markdown="block">
  <summary>Nesta página</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## Pontuação por resultado

A cada partida finalizada, os atletas recebem pontos conforme o resultado do seu time:

| Resultado | Pontos |
|-----------|--------|
| Vitória | 4 pontos |
| Empate | 2 pontos |
| Derrota | 1 ponto |

{: .note }
> Apenas atletas com status **Mensalista** entram no ranking. **Convidados** participam das partidas, mas não acumulam pontos.

---

## O que aparece no ranking

A tabela de ranking mostra, por atleta:

| Coluna | Descrição |
|--------|-----------|
| **Posição** | Classificação atual na temporada |
| **Nome** | Nome do atleta |
| **Pontos** | Total de pontos acumulados na temporada |
| **V / E / D** | Vitórias, Empates e Derrotas |
| **Média** | Média geral de avaliações na temporada |
| **MVPs** | Quantas vezes foi eleito MVP |

---

## Histórico de ranking

Cada atleta pode ver a **evolução da sua posição** ao longo da temporada — um gráfico de linha que mostra como a classificação mudou após cada partida.

Para acessar: na tela do clube, clique no nome do atleta no ranking.

---

## Parcerias

Na aba **Parcerias** do clube, há um mapa de calor mostrando quantas vezes cada par de atletas jogou no mesmo time. Quanto mais jogaram juntos, mais quente a cor.

Use para identificar duplas frequentes ou para variar os times nas próximas peladas.

---

## Eleição de MVP

O MVP (Most Valuable Player) é eleito automaticamente quando o Admin **encerra a votação** de uma partida, desde que a opção **"Habilitar MVP"** esteja ativa nas configurações do clube.

O sistema aplica os seguintes critérios em **cascata** até encontrar um único vencedor:

### Critério 1 — Maior média na partida
O atleta com a maior média calculada é o candidato principal.

### Critério 2 — Único no time vencedor
Em caso de empate no critério 1: se apenas **1** dos empatados pertence ao time vencedor, ele leva. Se a partida empatou, ou se mais de um empatado está no time vencedor, passa para o próximo critério.

### Critério 3 — Menor média pessoal histórica
Se ainda houver empate: vence quem tem a **menor média pessoal** no clube (média de todas as partidas anteriores). A ideia é premiar quem mais superou seu próprio desempenho habitual.

### Critério 4 — Maior média do time adversário
Se ainda houver empate: vence quem jogou contra o **time com maior média** na partida. Um bom desempenho contra um time mais forte vale mais.

### Critério 5 — Maior média do próprio time
Por último: vence quem pertence ao **time com maior média** na partida.

{: .note }
> Se após todos os critérios ainda houver empate absoluto, **nenhum MVP** é eleito para aquela partida.

---

## Onde o MVP aparece

- **Na partida:** badge 🏆 ao lado do nome do atleta eleito
- **No ranking:** coluna "MVPs" com o total de vezes eleito na temporada
- **No perfil do atleta:** lista de partidas em que foi MVP

---

## Recalcular o ranking

Se algum dado parecer incorreto (ex.: placar editado retroativamente), você pode forçar o recálculo:

Painel Admin → aba **Temporadas** → ícone 🔄 ao lado da temporada → **Confirmar**.

→ Veja mais em: [Gerenciar Temporadas](../temporadas/gerenciar-temporadas)
