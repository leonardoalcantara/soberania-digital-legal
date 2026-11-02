# Ideia 005 — Integridade de métricas: engajamento externo e automação

**Bloco:** A — desenho da distribuição de conteúdo
**Origem:** ideias originais 5 e 6, aglutinadas
**Estado:** proposta de trabalho

---

## 1. Formulação

**Original 5 (engajamento estrangeiro):**

> "No caso do usuário optar pela linha do tempo priorizada o algoritmo de priorização deve desconsiderar
> para efeito de cálculo de relevância o engajamento obtido pela postagem de usuários de fora do país.
> Para tal efeito, a plataforma deve utilizando técnicas de geolocalização e informações de topologia de
> rede, identificar a origem do usuário."

**Original 6 (anti-bots):**

> "A plataforma deve publicar uma política de combate a produção de conteúdo e engajamento falseado
> utilizando-se bots. Anualmente a plataforma deve revisar esta política e publicar as métricas de
> sucesso da aplicação da mesma no ciclo anterior."
>
> "É permitido que a plataforma faculte aos usuários a utilização de bots… Tais bots devem estar
> sinalizados dentro da plataforma… Quaisquer engajamentos gerados por estes bots devem ser
> desconsiderados para qualquer efeito de priorização do algoritmo."

**Por que aglutinadas:** as duas tratam do mesmo objeto — a **validade do sinal que alimenta a
priorização**. Uma ataca a origem geográfica do engajamento; a outra, a origem automatizada. O
instrumento é o mesmo: excluir do cálculo o sinal espúrio e documentar a política.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| Brasil | Res. TSE 23.755/2026, art. 38-A | Remoção de perfil comprovadamente falso, apócrifo ou **automatizado/robô** |
| China | Provisões sobre contas públicas (2021), art. 12 | Dever de prevenir **fraude em dados**: assinantes, atenção, cliques, compartilhamentos |
| China | Notificação de 2023, ponto 10 | Remoção de seguidores obtidos por violação; vedação de ganhar seguidores durante silenciamento; proibição de transferir seguidores |
| União Europeia | DSA | Não localizei dispositivo sobre engajamento estrangeiro ou bots |

### Brasil — o único dispositivo vigente sobre automação

Resolução TSE nº 23.755/2026, art. 38-A:

> "A remoção de perfil será feita quando se tratar de usuário comprovadamente falso, apócrifo ou
> vinculado a pessoa que sequer exista fora do universo digital (**perfil automatizado ou robô**), cujas
> publicações configurem a reiterada prática: I — de crime eleitoral; II — de publicação de fatos
> notoriamente inverídicos…"

E o § 2º limita a atuação da plataforma:

> "É permitida a exclusão pelos provedores de aplicação **apenas** nas hipóteses de perfis falsos,
> automatizados ou robô."

Fonte: `fontes/Brasil/2026-resolucao-tse-23755-Resolução TSE 23.755 - texto.md`

### China — o modelo de integridade de métricas

Provisões sobre contas públicas (2021), art. 12:

> "A plataforma deve estabelecer mecanismo de monitoramento e avaliação de contas públicas, prevenindo
> **fraude em dados** como número de assinantes, atenção de usuários, taxa de cliques e volume de
> compartilhamentos e comentários."

Fonte: `fontes/China/2021-provisoes-contas-publicas-pt.md`

Notificação de 2023, ponto 10:

> "Os seguidores obtidos por 'self-media' em razão de conduta infratora devem ser verificados e
> eliminados tempestivamente pela plataforma. Durante o silenciamento, o 'self-media' não pode ganhar
> novos seguidores… As plataformas não podem oferecer serviço de transferência de seguidores."

Fonte: `fontes/China/2023-notificacao-automidia-pt.md`

**É o modelo mais próximo da proposta:** a China trata métrica como objeto de regulação — inclusive a
métrica que alimenta a priorização — e não apenas o conteúdo.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **TSE 23.755/2026, art. 38-A** — remoção de perfil falso ou robô, com dois limites: só na hipótese de
  prática reiterada e só em contexto eleitoral.
- **Lei 9.504/1997, art. 57-H, §§ 1º e 2º** — criminaliza a contratação de grupo de pessoas para emitir
  mensagens contra candidato ("milícia digital").
- **Marco Civil, art. 15** — guarda de registros de acesso, que permite rastrear origem de acessos.

**Falta:**

1. **Nenhuma regra sobre engajamento estrangeiro.** Não existe, no direito brasileiro, nada que trate da
   origem geográfica do sinal de relevância.
2. **Política anti-bots obrigatória e pública**, com métricas anuais — não há.
3. **Selo de automação** para bots legítimos — a Resolução do TSE autoriza exclusão de robôs, mas não
   cria registro nem rotulagem de automação declarada.
4. **Consequência fora do período eleitoral** — toda a matéria é eleitoral.

---

## 4. O que a comparação revela

**A parte sobre engajamento estrangeiro não tem precedente em nenhuma jurisdição do acervo.** É a
proposta mais original das duas — e a de maior risco técnico.

Dois problemas concretos, que o texto precisa enfrentar:

1. **Atribuição de origem é frágil.** VPN, CDN, nós de borda e bots tornam "usuário do exterior" um
   critério difícil de provar. A própria formulação reconhece isso ao exigir geolocalização e topologia
   de rede — mas essas técnicas são falíveis e a norma transferiria o ônus da prova para a plataforma.
2. **O incentivo é perverso.** Se engajamento estrangeiro não conta, comprar engajamento no exterior
   deixa de ter efeito — mas também deixa de ser detectável como anomalia, porque a plataforma não
   precisa mais medi-lo.

**A parte sobre bots tem precedente sólido** — chinês, no desenho; brasileiro-eleitoral, na sanção. E o
ponto do Leonardo que nenhum dos dois tem: **permitir bots legítimos com selo**. É a distinção que
resolve o problema de atingir automação benéfica (alertas públicos, monitoramento de transparência).

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Escopo do engajamento externo** | só na timeline priorizada (proposta) × também em métricas públicas × nenhum | Restringir só à priorização deixa o problema do número público inflado |
| **Método de atribuição** | geolocalização + topologia (proposta) × declaração × auditoria | Definir método no texto cria litígio técnico; deixar em aberto deixa a plataforma definir |
| **Bots legítimos** | permitidos com selo (proposta) × proibidos × tolerados | O selo exige registro de automação — obrigação nova e verificável |
| **Documentação** | política anual publicada (proposta) × relatório ao regulador | Relatório ao regulador é mais auditável que publicação no site |
| **Sanção** | não prevista na formulação | Sem consequência, política anual vira peça de marketing |

---

## 6. Lacunas de pesquisa

1. **Não há dado público no acervo** sobre quanto do engajamento em circulação no Brasil vem do exterior.
2. Não verifiquei se a China aplica a regra de métricas a plataformas estrangeiras.
3. Não há, no acervo, nenhuma norma que trate de **selo de automação** — a proposta seria inédita nesse
   ponto específico.

---

## 7. Perguntas abertas

1. A vedação de contabilizar engajamento externo vale **só para priorização** ou também para números
   públicos de curtidas e compartilhamentos?
2. Quem define o que é "engajamento do exterior" — a plataforma, com metodologia declarada, ou o
   regulador?
3. O selo de bot é obrigatório para toda automação, ou só para a que interage com usuários?
