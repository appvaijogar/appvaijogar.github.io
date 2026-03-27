---
title: Gerenciar uma Partida
layout: default
parent: Partidas
nav_order: 2
---

# Gerenciar uma Partida
{: .no_toc }

<details open markdown="block">
  <summary>Nesta página</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## Status da partida

Toda partida tem um status que controla o que pode ser feito:

| Status | Exibição | O que está habilitado |
|--------|----------|-----------------------|
| **Em andamento** | ⏳ Amarelo | Edição de placar, elenco e data pelo moderador |
| **Finalizada — votação aberta** | ⭐ Azul | Membros podem avaliar os atletas |
| **Finalizada — votação encerrada** | ✅ Verde | MVP eleito (se habilitado), ranking atualizado |

---

## Editar a partida (placar, times, data)

Apenas **Admin** e **Moderador** podem editar.

1. Na tela da partida, clique no ícone de **lápis** (editar).
2. Em modo de edição você pode:
   - Alterar o placar (gols de cada time)
   - Alterar a data da partida
   - Mudar o status (Em andamento ↔ Finalizada)
   - Mover jogadores entre os times (clique no nome para mover)
   - Adicionar jogadores que faltaram na lista inicial (dropdown *"+ Adicionar jogador"*)
   - Remover jogadores (ícone ✕ vermelho ao lado do nome)
   - Incrementar gols e assistências de cada atleta (se a funcionalidade estiver ativa nas configurações)
3. Clique em **Salvar Alterações** para confirmar.

![Modo de edição da partida](../assets/screenshots/editar-partida.png)
*Placeholder — adicione um screenshot do modo de edição*

{: .warning }
> Alterar o placar ou o elenco de uma partida já finalizada **atualiza o ranking automaticamente**.

---

## Abrir a votação

A votação de avaliações fica disponível quando a partida é marcada como **Finalizada**:

1. Na barra de ações do moderador, clique no ícone de **cadeado aberto** (🔓).
2. A partida muda para o status *"Finalizada — votação aberta"*.
3. Os membros que participaram da partida já podem acessar a tela e enviar suas notas.

---

## Encerrar a votação

Quando quiser fechar as avaliações e eleger o MVP:

1. Clique no ícone de **cadeado fechado** (🔒).
2. Confirme a ação.
3. O sistema:
   - Bloqueia novas avaliações
   - Calcula o MVP (se a opção estiver ativa nas configurações)
   - Exibe o badge 🏆 ao lado do atleta eleito
   - Atualiza o ranking da temporada

{: .tip }
> **Quando encerrar?** Encerre a votação quando sentir que os membros já tiveram tempo suficiente para avaliar — geralmente 1 a 3 dias após a partida. Você pode configurar um prazo automático nas [Configurações do Clube](../configuracoes/configuracoes).

---

## Reabrir a votação

Se encerrou cedo demais:

1. Clique no ícone de **cadeado aberto** (🔓) que aparece quando a votação está encerrada.
2. A votação volta a ficar disponível para os membros.

{: .note }
> Reabrir a votação **remove o MVP** eleito anteriormente. Ele será recalculado quando você encerrar novamente.

---

## Excluir uma partida

Apenas **Admins** podem excluir partidas.

1. No modo de edição, clique no ícone de **lixeira** (🗑️, vermelho).
2. Confirme a exclusão.

{: .important }
> A exclusão é **permanente** e não pode ser desfeita. O ranking é recalculado automaticamente sem essa partida.

---

## Próximo passo

[Avaliações →](avaliacoes) — como os membros avaliam os atletas após cada partida
