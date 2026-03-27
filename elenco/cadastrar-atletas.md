---
title: Cadastrar Atletas
layout: default
parent: Elenco e Membros
nav_order: 1
---

# Cadastrar Atletas
{: .no_toc }

<details open markdown="block">
  <summary>Nesta página</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## Onde fica

Painel do Administrador → aba **Elenco**.

---

## Cadastrar um atleta manualmente

Use esta opção para adicionar jogadores que não têm conta no app, ou para preparar o elenco antes de os jogadores se cadastrarem.

1. Na aba **Elenco**, clique em **+ Atleta** (canto superior direito).
2. Preencha o formulário:
   - **Nome do atleta** *(obrigatório)*
   - **Status** — escolha entre Mensalista, Convidado ou Inativo (veja tabela abaixo)
   - **Características de posição** — marque as que se aplicam ao jogador
3. Clique em **Cadastrar Atleta**.

![Adicionar atleta](../assets/screenshots/cadastrar-atleta.png)
*Placeholder — adicione um screenshot do modal de cadastro*

---

## Status do atleta

| Status | Significado |
|--------|------------|
| **Mensalista** | Membro fixo do clube. Entra no ranking da temporada e acumula pontos. |
| **Convidado** | Participa das partidas, mas **não** aparece no ranking e não acumula pontos. |
| **Inativo** | Afastado do clube. Não aparece na lista de presença das partidas. |

{: .tip }
> Use **Convidado** para jogadores que aparecem esporadicamente, como amigos convidados para um jogo específico.

---

## Características de posição

As posições são usadas pelo algoritmo de sorteio de times para equilibrar as equipes:

| Ícone | Posição | Quando usar |
|-------|---------|-------------|
| 🧤 | **Goleiro** | O jogador joga entre os paus. No sorteio, cada time recebe exatamente 1 goleiro. |
| 🛡️ | **Ajuda na Defesa** | Jogador com perfil mais defensivo. |
| 🎯 | **Armador / Meia** | Jogador criativo, que arma as jogadas. |
| 🚀 | **Vai bem no Ataque** | Jogador ofensivo, que avança e finaliza. |

{: .note }
> Um jogador pode ter **mais de uma característica** marcada — por exemplo, um meia que também ajuda na defesa. Deixe em branco para jogadores sem posição definida.

---

## Editar um atleta

1. Na lista do elenco, clique no card do atleta.
2. O modal de edição abre com os dados atuais.
3. Faça as alterações e clique em **Salvar Alterações**.

---

## Filtrar e ordenar o elenco

Use os botões de **Filtro** e **Ordenar** no topo da lista para encontrar atletas rapidamente:

**Filtros disponíveis:**
- Por status: *Ativos*, *Todos*, *Mensalista*, *Convidado*, *Inativo*
- Por posição: Goleiro, Defesa, Armador, Ataque

**Ordenação:**
- A–Z por nome
- Por nota (maior média primeiro)

---

## A cor da borda identifica o status

Na lista de atletas, cada card tem uma borda colorida na esquerda:

| Cor | Status |
|-----|--------|
| Verde | Mensalista |
| Amarelo | Convidado |
| Vermelho | Inativo |

---

## Próximo passo

Após cadastrar o elenco, aprove os usuários que solicitaram entrada: [Aprovar Membros →](aprovar-membros)
