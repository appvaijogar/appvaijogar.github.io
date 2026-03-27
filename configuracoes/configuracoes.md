---
title: Opções de Configuração
layout: default
parent: Configurações do Clube
nav_order: 1
---

# Opções de Configuração
{: .no_toc }

<details open markdown="block">
  <summary>Nesta página</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## Onde fica

Painel do Administrador → aba **Config**.

Após fazer qualquer alteração, clique em **Salvar Alterações** no final da página para aplicar as mudanças.

![Aba de configurações](../assets/screenshots/configuracoes.png)
*Placeholder — adicione um screenshot da aba Config*

---

## Equipes — Nomes e cores dos times

Personalize como os times aparecem em todas as telas do clube.

| Campo | O que faz |
|-------|-----------|
| **Nome do Time A** | Nome exibido no placar, lista de presença e tela de partida. Ex.: *Amarelo*, *Bicho Papão*, *Time do Zé* |
| **Cor do Time A** | Cor usada na borda dos cards e no cabeçalho do time. Clique no círculo colorido para abrir o seletor. |
| **Nome do Time B** | Idem para o segundo time. |
| **Cor do Time B** | Idem para o segundo time. |

{: .tip }
> Escolha cores bem contrastantes entre si para facilitar a leitura — ex.: verde escuro e laranja, ou azul e vermelho.

---

## Regras de Avaliação

Controla como as notas dos atletas são coletadas e calculadas.

### Ignorar autoavaliação
{: .no_toc }

**O que faz:** Quando ativado, a nota que um atleta dá a si mesmo não entra no cálculo da sua média.

**Quando usar:** Recomendado na maioria dos casos — evita que jogadores inflem ou desinflam a própria nota.

---

### Remover extremos
{: .no_toc }

**O que faz:** Quando um atleta recebe **3 ou mais avaliações**, a nota mais alta e a nota mais baixa são descartadas antes de calcular a média.

**Exemplo:**
```
Notas recebidas: 2 | 3 | 4 | 5 | 5
Após remover extremos (2 e 5): 3 | 4 | 5
Média final: 4,0
```

**Quando usar:** Grupos com rivalidades ou avaliações tendenciosas — reduz o impacto de notas extremas intencionais.

---

### Prazo para avaliar (dias)
{: .no_toc }

**O que faz:** Define quantos dias após a data da partida as avaliações ainda são aceitas.

**Exemplo:** Prazo de 3 dias → partida de segunda → avaliações aceitas até quinta.

**Deixe em branco** para sem limite de tempo (as avaliações ficam disponíveis enquanto a votação estiver aberta).

---

## Links Externos

Adicione links úteis que aparecem para todos os membros do clube.

| Campo | O que faz |
|-------|-----------|
| **URL da playlist do YouTube** | Link para o canal ou playlist de vídeos das partidas. Aparece com ícone do YouTube. |
| **URL da planilha do caixa** | Link para uma planilha de controle financeiro (ex.: Google Sheets). Aparece com ícone de planilha. |

{: .note }
> Esses links ficam visíveis para todos os membros — não use para documentos internos ou privados.

---

## Funcionalidades

Ative ou desative recursos específicos do clube.

### Contar gols e assistências
{: .no_toc }

**O que faz:** Quando ativado, a tela de edição de partida exibe controles para registrar quantos gols e assistências cada atleta fez.

**Onde aparece:** Na edição da partida (botões + e - ao lado de cada atleta) e nos detalhes da partida (ícones ⚽ e ✨ ao lado do nome).

---

### Habilitar MVP
{: .no_toc }

**O que faz:** Quando ativado, ao encerrar a votação de uma partida, o sistema elege automaticamente o MVP usando o algoritmo de 5 critérios em cascata.

O MVP recebe o badge 🏆 na tela da partida e acumula MVPs no ranking da temporada.

**Quando desativar:** Se o clube preferir não ter MVP ou quiser eleger manualmente de outra forma.

→ Veja o algoritmo completo em: [Ranking e MVP](../ranking/ranking-e-mvp)

---

### Notificações push
{: .no_toc }

**O que faz:** Controla se o clube envia **notificações push** para os membros. As notificações são disparadas em eventos como:

- Votação de uma partida aberta (hora de avaliar!)
- Votação encerrada e MVP eleito

**Pré-requisito:** Cada membro precisa aceitar as notificações individualmente no perfil deles. Desativar aqui impede que o clube envie qualquer notificação, independente da preferência dos membros.

---

## Salvar as configurações

Após fazer qualquer alteração, clique no botão **Salvar Alterações** (verde, no final da página). O botão fica desabilitado enquanto salva e exibe *"Salvando..."*.

Uma mensagem de confirmação aparece indicando se a operação foi bem-sucedida.
