---
title: Aprovar Membros
layout: default
parent: Elenco e Membros
nav_order: 2
---

# Aprovar Membros
{: .no_toc }

<details open markdown="block">
  <summary>Nesta página</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## Onde fica

Painel do Administrador → aba **Membros**.

---

## Visão geral da tela

A aba Membros tem duas seções:

1. **Solicitações Pendentes** — jogadores que usaram o código de convite e aguardam aprovação (aparece só se houver solicitações).
2. **Usuários no Clube** — lista de todos os membros já aprovados com seus perfis e funções.

![Aba Membros](../assets/screenshots/membros.png)
*Placeholder — adicione um screenshot da aba Membros*

---

## Aprovar um novo membro

1. Na seção **Solicitações Pendentes**, localize o nome do jogador.
2. Clique no botão **✓** (verde) para aprovar ou no **✗** (vermelho) para recusar.
3. Se clicar em **✓**, um modal de aprovação abre.

### Opções na aprovação

**Status do atleta:**

| Opção | Quando usar |
|-------|------------|
| **Mensalista** | Jogador fixo — entra no ranking e acumula pontos. |
| **Convidado** | Jogador eventual — participa das partidas mas não entra no ranking. |

**Vincular ao atleta:**

| Opção | Quando usar |
|-------|------------|
| **Atleta novo (sem histórico)** | O jogador ainda não tinha ficha no clube. O app cria um atleta novo. |
| *Nome de atleta existente* | O jogador já tinha uma ficha criada manualmente. Vincule ao atleta correto para preservar o histórico de notas e partidas. |

{: .important }
> Se você já cadastrou o atleta manualmente antes do usuário se registrar, **sempre vincule ao atleta existente**. Isso preserva o histórico completo de partidas e avaliações.

**Renomear atleta (opcional):**

Se escolheu *"Atleta novo"*, você pode digitar um nome diferente do nome de usuário. Útil quando o jogador usa apelido no app mas o nome no elenco deve ser diferente. Deixe em branco para usar o nome da conta.

4. Clique em **Confirmar Aprovação**.

---

## Recusar um membro

1. Clique no botão **✗** (vermelho) ao lado do nome.
2. A solicitação é removida da lista.

O jogador pode tentar entrar novamente usando o código de convite — a solicitação será enviada de novo.

---

## Alterar a função de um membro

Você pode promover membros a Moderador ou Admin (ou rebaixar) a qualquer momento:

1. Na lista **Usuários no Clube**, clique no ícone de **lápis** ao lado do membro.
2. Selecione a nova função:
   - **Admin** — acesso total ao painel
   - **Moderador** — pode editar partidas, encerrar votação e gerenciar elenco
   - **Membro** — apenas avalia jogadores e vê o ranking
3. Clique em **Confirmar**.

{: .note }
> Você não pode alterar a própria função nem a função do dono do clube.

---

## Tabela de funções no clube

| Função | Nível | O que pode fazer |
|--------|-------|-----------------|
| **Admin** | 0 | Tudo: configurações, temporadas, membros, partidas |
| **Moderador** | 5 | Editar partidas, encerrar votação, gerenciar elenco |
| **Membro** | 10 | Avaliar jogadores, ver ranking e histórico |

---

## Próximo passo

Com o elenco aprovado, crie a primeira partida: [Criar uma Partida →](../partidas/criar-partida)
