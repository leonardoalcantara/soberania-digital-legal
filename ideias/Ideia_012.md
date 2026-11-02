# Ideia 012 — Restrições de desenho e tempo de uso para menores

**Bloco:** C — proteção de menores e conteúdo sintético
**Origem:** proposta nova
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Não regular o conteúdo, mas o **mecanismo que prolonga o uso**: reprodução automática, rolagem infinita, notificações de reengajamento, recompensas por tempo de uso. E, junto, fixar limites de tempo e bloqueios de horário para menores.

É a regulação que incide sobre o **produto**, não sobre a fala.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| EUA (Califórnia) | AB 1709 (vigência 01/01/2027) | **Proíbe** fornecer "recurso viciante" a menor de 16, sem rota de consentimento parental; multa de até US$ 50 mil por menor afetado |
| União Europeia | Proposta EU KIDS Act | Limite padrão de **uma hora por dia** para menores; vedações nominais de autoplay, rolagem infinita e notificações de reengajamento |
| Brasil | Lei 15.211/2025, art. 17, § 4º, II | As **configurações-padrão** das ferramentas de supervisão parental devem limitar recursos que estendam artificialmente o uso |
| Estados Unidos | Acordo Meta × procuradores-gerais | Limite padrão de 2h/dia e bloqueio noturno 0h–6h (acordo, não lei) |

### Califórnia — a proibição direta

A AB 1709 define "recurso viciante" como:

> "qualquer dos seguintes recursos psicologicamente exploratórios destinados a maximizar o engajamento que previsivelmente levem ao uso compulsivo…"

E proíbe fornecê-los a usuário menor de 16 anos, **sem qualquer rota de consentimento parental**.

Fonte: `fontes/EUA/2026-ca-ab1709-feed-algoritmico-menores.md`

**É o modelo mais duro:** proibição, não limitação; e sem escape por autorização dos pais.

### Brasil — o modelo de configuração padrão

Lei nº 15.211/2025, art. 17, § 4º:

> "As configurações-padrão das ferramentas de supervisão parental deverão adotar o mais alto nível de proteção disponível, assegurados, no mínimo: … II — limitação de recursos para aumentar, sustentar ou estender artificialmente o uso do produto ou serviço pela criança ou pelo adolescente, como **reprodução automática de mídia, recompensas pelo tempo de uso, notificações** e outros recursos que possam resultar em uso excessivo…"

Fonte: `fontes/Brasil/2025-lei-15211-ECA-Digital - texto.md`

**Diferença decisiva:** o Brasil não proíbe o recurso — exige que ele venha **desligado por padrão** nas
ferramentas de supervisão parental. É regulação de configuração, não de existência.

### União Europeia — o limite estatutário

A proposta do EU KIDS Act fixa que o tempo de uso diário não pode exceder uma hora, como padrão.

Fonte: `fontes/UE/2026-proposta-ue-eu-kids-act.pdf`

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Lei 15.211/2025, art. 17, § 4º** — configurações-padrão de supervisão parental com limitação de autoplay, recompensas por tempo e notificações.
- **Art. 18** — deveres das ferramentas de supervisão parental.
- **Art. 20** — vedação de caixas de recompensa (loot boxes) a menores.

**Falta:**

1. **Proibição** de recursos viciantes — o Brasil só exige que venham desligados.
2. **Limite de tempo de uso** fixado em lei. Não há.
3. **Bloqueio noturno.** Não há.
4. **Aplicação a usuários que não usam ferramenta de supervisão.** A regra brasileira depende de o responsável ativar a ferramenta.

---

## 4. O que a comparação revela

**Três modelos distintos, do mais fraco ao mais forte:**

| Modelo | Onde | Efeito |
|---|---|---|
| Configuração padrão em ferramenta parental | Brasil | Só alcança menor cuja família ativou a ferramenta |
| Limite estatutário de tempo | UE (proposta) | Alcança todos os menores, mas depende de verificação de idade |
| Proibição do recurso | Califórnia | Alcança todos, e não depende de configuração |

**O ponto cego do modelo brasileiro:** se a limitação está nas ferramentas de supervisão parental, o menor
cuja família não configura nada continua exposto. A regra protege quem já estava protegido.

**O ponto de risco do modelo californiano:** proibir o recurso sem rota de consentimento é restrição de
produto — e deve ser testada em tribunal, como já ocorreu com outras leis californianas de proteção de menores.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Técnica** | configuração padrão (Brasil) × limite de tempo (UE) × proibição (Califórnia) | A proibição é a única que não depende de configuração |
| **Universo** | só quem usa supervisão × todos os menores | O primeiro é quase simbólico |
| **Recursos alcançados** | lista fechada × categoria aberta ("recursos que estendam o uso") | Lista fechada envelhece rápido |
| **Consentimento parental** | rota prevista × vedada (Califórnia) | A rota reduz litígio e reduz eficácia |
| **Sanção** | multa × obrigação de redesenho | Obrigação de redesenho é mais eficaz e mais litigiosa |

---

## 6. Lacunas de pesquisa

1. Não há, no acervo, dado sobre **quantos menores** no Brasil usam ferramentas de supervisão parental — sem isso, não se sabe o alcance real do modelo brasileiro.
2. Não verifiquei se o Decreto 12.880/2026 detalha os recursos do art. 17, § 4º, II.
3. Não há decisão judicial sobre a AB 1709 — a vigência começa em 01/01/2027.

---

## 7. Perguntas abertas

1. A proposta adota configuração padrão, limite de tempo ou proibição?
2. Vale só para quem usa supervisão parental, ou para todos os menores?
3. A lista de recursos é fechada (autoplay, rolagem, notificações) ou definida por categoria?
