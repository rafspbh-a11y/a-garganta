titulo: Regra de Escrita da Ficha
versao: 2
atualizado: 2026-09-11
fonte: cânone aberto de A Garganta

# Regra de Escrita da Ficha

> **Nota.**
> **Versão 2, de 10/09/2026** — segunda rodada de conferência. Entraram três travas que estavam implícitas e não escritas: bônus condicional fica fora do Efetivo; bônus por item exige o item no equipamento; especialização exige a especialidade declarada.
> **Nenhuma ficha entra em mesa, e nenhuma alteração é homologada, fora deste formato.** Ele existe por um motivo concreto: uma ficha da campanha precisou ser reconstruída do zero para se descobrir que estava 22,5 pontos acima, porque não havia como saber quanto cada linha tinha custado. **Ficha que só mostra o nível não é auditável — é uma afirmação.**

# 1. A linha de perícia

Sete campos, nesta ordem:

```
Nome · Tipo/Dificuldade · relativo · pontos · NH comprado · bônus · NH efetivo
```

| Campo | O que é | Regra |
| --- | --- | --- |
| **Nome** | o nome **do livro**, nunca um apelido | se não está no `26`, não entra |
| **Tipo/Dificuldade** | Física ou Mental, e Fácil / Média / Difícil / Muito Difícil | vem do livro, **nunca de outra ficha** |
| **Relativo** | DX−1, IQ+2… | é o que a tabela de custo lê |
| **Pontos** | quanto foi gasto **nesta linha** | a soma tem que bater com a conta |
| **NH comprado** | atributo + relativo | **sem bônus nenhum** |
| **Bônus** | cada bônus **com a fonte escrita** | vantagem, item, magia, situação |
| **NH efetivo** | o número que se rola na mesa | comprado + bônus **permanentes**. Bônus condicional **fica fora** — ver abaixo |

**Exemplo:**

`Diplomacia · Mental/Difícil · IQ+1 · 6 pts · NH 15 · +2 Voz Melodiosa · efetivo 17`

`Esgrima · Física/Média · DX+2 · 8 pts · NH 14 · — · efetivo 14`

> **A regra de ouro: bônus nunca entra no NH comprado.**
> Se a Voz Melodiosa dá +2 em Diplomacia, a ficha escreve **15 comprado, +2 da vantagem, 17 efetivo** — e nunca "Diplomacia 17". Ficha que soma bônus dentro do nível esconde pontos e faz o jogador **pagar duas vezes pela mesma coisa**. Aconteceu, e foi assim que se descobriu.

## Fontes de bônus que precisam ser nomeadas

| Fonte | Como escrever | Entra no efetivo? |
| --- | --- | --- |
| Vantagem | `+2 Voz Melodiosa` | sim, é permanente |
| Item mágico | `+1 anel de Baukis` | **só com o item na mão** — e some em bolsão de mana nula |
| Item comum ou obra-prima | `+1 obra-prima` | sim, enquanto tiver o item |
| Magia ativa | `+2 Apressar` | **não** — é temporário, vai no Estado de Retomada |
| Status ou Reputação | `+1 Status 2, só em Ônfalos` | condicional: **escreva a condição** |
| Especialização | `+5 Comércio (armas), −1 fora` | escreva os dois lados |
| Equipamento de ofício | `+1 kit de primeiros socorros` | só com o kit |

**Bônus condicional escreve a condição.** "+2 só contra quem ouve a voz dele" é diferente de "+2", e o Mestre de Cena precisa saber qual dos dois sem perguntar.

> **Bônus condicional NÃO entra na coluna Efetivo.** Isto era convenção não escrita e passou a ser regra em 10/09/2026, porque as sete fichas já faziam assim e o texto não dizia. O Efetivo traz **NH + bônus permanentes** e mais nada; o condicional fica na coluna Bônus, com a condição, e o Mestre soma na hora em que a condição existir. Assim o número que se rola por padrão é o do Efetivo, e ninguém aplica por engano um +1 de kit que ficou em casa.

> **Bônus por item exige o item no equipamento.** Se a linha diz `+1 só com kit`, a linha de Equipamento tem que trazer o kit. Três fichas da mesa carregavam esse +1 **sem kit nenhum comprado** — descoberto na conferência de 10/09 e corrigido na cara, com o preço do kit escrito ao lado para o jogador decidir. **A ficha não empresta objeto que o personagem não comprou.**

> **Especialização exige a especialidade declarada.** `+5 numa mercadoria, −1 fora` sem dizer **qual** mercadoria é uma linha que só pode piorar: o −1 vale sempre e o +5 nunca. Enquanto a escolha não estiver escrita na ficha, **nenhum dos dois lados se aplica** e a perícia roda pelo NH limpo.

# 2. A linha de feitiço

```
Nome · escola · relativo ao IQ efetivo · pontos · NH · energia · pré-requisito
```

Toda mágica é **Mental/Difícil** salvo asterisco, então a dificuldade não vai na linha — mas **o IQ efetivo vai no cabeçalho do bloco**, porque é dele que sai o custo:

`IQ efetivo 16 (IQ 14 + Aptidão Mágica 2)`

`Silêncio · Som · IQ−2 · 1 pt · NH 14 · 2 básico × raio · ← Som ✓`

**O pré-requisito vai escrito, com o visto.** Foi a ausência disso que deixou nove das dezesseis mágicas de uma ficha ilegais sem ninguém perceber.

**A redução de energia entra como bônus, com a fonte:** `NH 15 · energia −1 (NH≥15)`. **O degrau seguinte é o NH 20, e vale −2** — não o 18, que muda o ritual e não a energia (`27`). Do andar 9 para baixo, o +2 da mana alta pode empurrar uma mágica de 13 para 15 efetivo — e aí a linha ganha `· no 9+: NH 15, energia −1, e metade da faixa alta`.

# 3. A linha de vantagem e de desvantagem

```
Nome · custo · o que dá na mesa, com os números
```

`Voz Melodiosa · 10 · +2 em Trovador, Diplomacia, Atuação, Política, Trato Social e Canto, e +2 na reação de quem ouve`

**Vantagem que dá bônus tem que dizer em quais perícias**, com os nomes de livro — senão a coluna de bônus não pode ser conferida.

Vantagem com componente variável escreve o cálculo:

`Reputação +1 entre quem leu seus escritos · 1 · 5 por +1, ×⅓ por grupo pequeno = 1`

`Aliado: arquivista de Ámenti · 5 · 76–100 pontos, aparece frequentemente (×1)`

# 4. A conta — obrigatória, no fim da ficha

> **A conta:** 65 atributos + 63 vantagens + 46 perícias + 21 feitiços − 40 desvantagens − 5 peculiaridades = **150**

**Ficha sem esta linha não é homologada.**

Quando o personagem ganha pontos em jogo, viram duas linhas:

> **A conta:** … = **150** de criação
> **Ganhos:** +3 (Semana 1, homologação da mesa conjunta) = **153 totais, 3 não gastos**

**Cada ponto ganho diz de onde veio**, com semana e homologação. Cada ponto gasto depois da criação vira linha nova, com data:

> **Semana 3:** 3 pontos em Jurisprudência, IQ+1 → IQ+2 (6 → 8 pts). Sobra 1.

# 5. Checklist de homologação

Antes de qualquer ficha entrar em mesa, nesta ordem:

1. **Todo nome está no `26`?** Nome que não está vira Pendência antes de virar linha.
2. **Toda linha tem os sete campos?** Sem exceção, inclusive as de ½ ponto.
3. **Todo bônus tem fonte nomeada?** Bônus sem fonte é bônus inventado.
4. **Nenhum bônus está dentro do NH comprado?**
5. **Toda mágica tem o pré-requisito escrito e comprado?** A cadeia inteira, até a raiz (`27`).
6. **Toda mágica fora do domínio da Casa tem acordo registrado?** Com dono, mesmo que o dono só exista na camada do Árbitro.
7. **A soma das linhas bate com a linha da conta?**
8. **A conta fecha no orçamento?** 150 na criação.
9. **Desvantagens dentro de −40, com o Dever da Marca lá dentro?** Peculiaridades até 5.
10. **Os derivados batem?** PV=HT · Fadiga=ST · Vel.=(DX+HT)÷4 · Deslocamento=Esquiva=Vel. arredondada · Aparar=perícia÷2, ou **⅔ em Esgrima e Bastão** · Bloquear=Escudo÷2.
11. **As Amarras estão preenchidas?** Dois NPCs, uma dívida, um segredo.

**Onze itens. Se um falhar, a ficha volta.** Vale para a ficha do Árbitro também — Carta, artigo 4.
