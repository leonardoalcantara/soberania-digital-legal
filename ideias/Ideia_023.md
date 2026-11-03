# Ideia 023 — Transparência da ponderação

**Bloco:** D — responsabilidade e infraestrutura
**Origem:** proposta nova, formulada em conversa
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Publicar **o efeito e o peso de cada ação do usuário** na ponderação do sistema de recomendação — curtir, comentar, compartilhar, assistir até o fim, seguir.

É a proposta mais específica do conjunto em matéria de transparência algorítmica: não pede "os parâmetros", pede **o valor de cada sinal**. E é justamente essa especificidade que cria o problema, porque o que existe no direito comparado chega a "parâmetros principais" e para aí.

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Nível de detalhe exigido |
|---|---|---|
| **União Europeia** | DSA, art. 27, §§ 1º e 2º | Os **principais parâmetros** e **as razões da importância relativa** entre eles |
| União Europeia | DSA, art. 26, § 1º, "d" | Principais parâmetros usados para determinar **a quem** um anúncio é apresentado |
| União Europeia | AI Act, art. 86 | Explicação "clara e significativa" do papel do sistema e dos elementos principais da decisão — individual, alto risco |
| **Brasil** | LGPD, art. 20, §§ 1º e 2º | **Critérios e procedimentos** da decisão automatizada, sob requerimento do titular |

### União Europeia — o teto do acervo

DSA, art. 27:

> "§ 1º Os prestadores de plataformas online que utilizem sistemas de recomendação deverão indicar, nos seus termos e condições, em linguagem simples e inteligível, **os principais parâmetros** utilizados nos seus sistemas de recomendação, bem como quaisquer opções de que os destinatários disponham para modificar ou influenciar esses principais parâmetros."
>
> "§ 2º Os principais parâmetros[…] deverão explicar **por que** determinada informação é sugerida ao destinatário. Deverão incluir, no mínimo: (a) os critérios mais significativos; (b) **as razões da importância relativa desses parâmetros**."

Fonte: `fontes/UE/2022-regulamento-ue-2022-2065-dsa.pdf`

**Veja o que o § 2º, "b", pede e o que não pede:** pede as **razões** da importância relativa — explicadas em prosa. Não pede coeficiente, não pede número, não pede o peso de cada ação do usuário uma por uma.

### Brasil — o direito individual que existe

LGPD, art. 20, § 1º:

> "O controlador deverá fornecer, sempre que solicitadas, informações claras e adequadas a respeito dos **critérios e dos procedimentos** utilizados para a decisão automatizada, observados os segredos comercial e industrial."

E o § 2º:

> "Em caso de não oferecimento de informações[…] baseado na observância de segredo comercial e industrial, a autoridade nacional poderá realizar **auditoria** para verificação de aspectos discriminatórios em tratamento automatizado de dados pessoais."

**É direito de perguntar, não dever de declarar** — e só alcança decisão sobre dados pessoais, não curadoria de conteúdo.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **LGPD, art. 20, §§ 1º e 2º** — critérios e procedimentos, a requerimento do titular, com auditoria pela ANPD quando oposto segredo.
- **LGPD, art. 6º** — princípio da transparência.
- **Marco Civil, art. 7º, XI** — publicidade e clareza das políticas de uso.
- **TSE, Res. 23.755/2026, art. 28, § 1º-C** — veda ranquear ou recomendar candidatos, sem exigir declaração de parâmetros.
- **Capítulo IV-A, art. 23-C** (redigido na Onda 2, não é lei) — critérios significativos, direção do efeito e ordem de importância relativa.

**Falta:**

1. **Dever de publicação** — o Brasil só tem direito individual de perguntar.
2. **Direção do efeito** de cada critério — o que aumenta e o que reduz a entrega.
3. **Ordem de importância relativa**, com justificativa.
4. **Atualização** obrigatória quando a ordem muda.
5. **Verificação** — confronto entre o que foi declarado e o que o sistema faz.

---

## 4. O que a comparação revela

**Três problemas de exequibilidade, e nenhum deles é jurídico:**

**1. Peso não é um número — é uma interação.** "Curtida pesa 0,3" pressupõe modelo linear. Recomendação real combina sinais de forma não separável: o peso de uma curtida depende de quem curtiu, do horário, do histórico e do próprio item. Publicar "o peso de cada ação" produz um número que não corresponde ao sistema.

**2. Peso muda.** Retreino, teste A/B e ajuste contínuo fazem a tabela publicada envelhecer em semanas. A norma precisaria dizer com que frequência republicar — e toda republicação é uma foto desatualizada por definição.

**3. Divulgar peso ensina a otimizar para ele.** É a lógica do SEO aplicada ao feed: quem conhece o coeficiente produz para o coeficiente, não para o leitor. A transparência total pode degradar exatamente o que se quer proteger.

**A tradução que preserva o sentido** — e que o art. 23-C adotou: lista ordenada de sinais, direção do efeito de cada um, ordem de importância com justificativa e faixas de magnitude em vez de coeficientes. Entrega a resposta que o usuário precisa — "por que vi isso" — sem o mapa da manipulação.

**E há um ganho que a comparação mostra:** a transparência só vale se for **verificável**. O DSA combina o art. 27 com a auditoria do art. 37 e o acesso a dados do art. 40. Declarar sem verificar produz documento que ninguém confere.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Granularidade** | coeficiente por ação × lista ordenada com direção × só os parâmetros principais | Coeficiente é inexato e ensina a manipular; lista ordenada é verificável |
| **Público** | público × só à autoridade × público com versão completa à autoridade | Público permite escrutínio; só à autoridade reduz o efeito |
| **Atualização** | a cada alteração × anual × por versão do modelo | "A cada alteração" é inexequível se o modelo muda continuamente |
| **Sigilo** | segredo comercial preservado × presunção de publicidade | Sem regra, o dever vira litígio sobre o que é segredo |
| **Verificação** | auditoria independente × acesso a pesquisadores × nenhuma | Declaração sem verificação é declaração |
| **Escopo** | todo provedor com recomendação × só acima de 1 milhão de usuários | Custo de conformidade recai sobre quem tem estrutura |
| **Explicação individual** | por item exibido × só sob requerimento | Por item é mais útil e mais caro |
| **Sanção** | infração autônoma × sanção do art. 12 | Depende da redação do art. 12 |

---

## 6. Lacunas de pesquisa

1. O **modelo de documento** que o AI Office adota para o resumo do art. 53, § 1º, "d", não está no acervo.
2. Não há no acervo o **Regulamento P2B (UE) 2019/1150**, que trata de parâmetros de ranqueamento em relações comerciais.
3. Não há **estudo de caso** de publicação de parâmetros por plataforma que permita avaliar o efeito real.
4. Não há dado sobre **quantas plataformas no Brasil** usam sistema de recomendação acima do corte que se venha a fixar.
5. Não verifiquei se a **ANPD** já regulamentou o art. 20 da LGPD de forma a exigir formato.

---

## 7. Perguntas abertas

1. Publica-se **coeficiente**, **ordem com direção** ou **só os parâmetros principais**?
2. O documento é **público** ou apenas acessível à autoridade?
3. Com que **frequência** é atualizado?
4. Há **verificação** — auditoria, acesso a pesquisadores, ou nenhuma?
5. A transparência alcança **todo** provedor com recomendação ou só acima de um corte?
6. A proposta **substitui** o art. 23-C do Capítulo IV-A ou o detalha em regulamento?
