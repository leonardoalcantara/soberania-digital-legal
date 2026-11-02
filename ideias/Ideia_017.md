# Ideia 017 — Transparência de datasets e de treinamento

**Bloco:** D — responsabilidade e infraestrutura
**Origem:** proposta nova
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Criar deveres de **governança e de transparência sobre os dados de treinamento**: origem lícita, limpeza e
rotulagem, avaliação de diversidade e de viés, registro do processo — e, para modelos de uso geral, um
**resumo público do conteúdo usado no treinamento**.

É a proposta que ataca a etapa anterior ao produto. A LGPD regula o dado pessoal durante o tratamento; não
regula o **conjunto** de dados que forma o modelo, nem a obrigação de descrevê-lo.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| União Europeia | AI Act, art. 10 | Governança de dados para sistemas de alto risco: oito tópicos obrigatórios, da origem à correção de vieses |
| União Europeia | AI Act, art. 53, § 1º, "d" | **Resumo público e suficientemente detalhado** do conteúdo usado no treinamento de modelos de uso geral, conforme modelo da Comissão |
| União Europeia | AI Act, Anexo XI, item 2(c) | Documentação técnica com tipo e proveniência dos dados, metodologias de curadoria, número de pontos de dados, escopo e características |
| Turquia | PL 2/3358, MADDE 4 | Data sets devem observar anonimato, proibição de discriminação e legalidade; uso de data set discriminatório **é violação de segurança de dados** |
| Turquia | PL 2/3358, MADDE 6 | Dever de assegurar transparência e auditabilidade dos data sets de treinamento |
| China | Medidas de IA Antropomórfica (2026), art. 11 | Seis exigências sobre dados de pré-treinamento e de otimização |
| Coreia do Sul | Lei-Quadro de IA, art. 34, § 1º, 2 | Plano de explicação deve conter "a visão geral dos dados de aprendizado" |

### União Europeia — a lista fechada de governança de dados

AI Act, art. 10, § 2º:

> "Os conjuntos de dados de treinamento, validação e teste devem estar sujeitos a práticas de governança e
> gestão de dados adequadas à finalidade pretendida do sistema de IA de alto risco. Tais práticas devem
> concernir, em particular: (a) as escolhas de projeto pertinentes; (b) os processos de coleta de dados e
> a **origem dos dados** e, no caso de dados pessoais, a finalidade original da coleta; (c) as operações
> de preparação de dados pertinentes, como **anotação, rotulagem, limpeza, atualização, enriquecimento e
> agregação**; (d) a formulação de premissas, em particular quanto à informação que os dados devem medir e
> representar; (e) a avaliação da disponibilidade, quantidade e adequação dos conjuntos de dados; (f) o
> exame de **vieses** suscetíveis de afetar a saúde e a segurança das pessoas, ter impacto negativo sobre
> direitos fundamentais ou levar a discriminação; (g) as medidas para detectar, prevenir e mitigar os
> vieses identificados; (h) a identificação de **lacunas de dados** relevantes e como suprimi-las."

E o § 4º acrescenta uma exigência que costuma faltar nas formulações genéricas:

> "Os conjuntos de dados devem levar em conta, na medida exigida pela finalidade pretendida, as
> características ou elementos **próprios do contexto geográfico, contextual, comportamental ou
> funcional** em que o sistema de IA de alto risco se destina a ser usado."

Fonte: `fontes/UE/2024-regulamento-ue-2024-1689-ai-act.pdf`

**O § 4º é o dispositivo mais diretamente relevante para o debate brasileiro:** um sistema treinado para
outro contexto geográfico e linguístico não é neutro — a lei europeia trata isso como requisito de
qualidade do dado.

Para modelos de uso geral, o art. 53, § 1º, "d" troca o detalhe pela publicidade:

> "[O provedor deverá] elaborar e tornar **publicamente disponível um resumo suficientemente detalhado**
> sobre o conteúdo usado para o treinamento do modelo de IA de uso geral, conforme modelo fornecido pelo
> Serviço de IA."

E o Anexo XI, item 2(c), define o que a documentação técnica precisa conter:

> "informações sobre os dados usados para treinamento, teste e validação, quando aplicável, incluindo o
> **tipo e a proveniência dos dados** e metodologias de curadoria (por exemplo, limpeza, filtragem), o
> **número de pontos de dados**, seu escopo e características principais; como os dados foram obtidos e
> selecionados, bem como todas as outras medidas para detectar a inadequação de fontes e métodos de dados
> e métodos para detectar vieses identificáveis."

### Turquia — a solução mais curta e mais dura

PL 2/3358, MADDE 4, que insere § 6º ao art. 12 da Lei de Proteção de Dados turca (Lei 6.698):

> "Os *data sets* utilizados em aplicações de inteligência artificial devem observar os princípios de
> anonimato, de **proibição de discriminação** e de legalidade. **O uso de data sets discriminatórios é
> considerado violação da segurança de dados.**"

E MADDE 6, sobre deveres de provedores de serviços de IA:

> "a) assegurar a **transparência e a auditabilidade dos data sets de treinamento**;[...]"

Fonte: `fontes/Turquia/2025-turquia-esas-2-3358-teklif-texto-extraido.md` (MADDE 4 e MADDE 6)

**O que o desenho tem de diferente:** não cria um dever novo de governança — **reclassifica** o uso de
data set discriminatório como violação de segurança de dados, o que o coloca sob o regime sancionatório
já existente da lei de proteção de dados. É economia legislativa: nenhuma estrutura nova, uma
qualificação a mais.

### China — seis exigências, incluindo a que quase ninguém põe em lei

Medidas de IA Antropomórfica (2026), art. 11:

> "Ao realizar atividades de tratamento de dados para pré-treinamento e treinamento de otimização, o
> provedor deve reforçar a gestão dos dados de treinamento, observando: I — que os dados tenham **origem
> lícita** e atendam às leis, regulamentos administrativos e aos valores socialistas essenciais; II — que
> os dados sejam **limpos e rotulados** conforme as disposições nacionais, ampliando sua transparência e
> confiabilidade e prevenindo **envenenamento e adulteração de dados**; III — que se amplie a
> **diversidade** dos dados de treinamento, elevando a segurança do conteúdo gerado por meio de amostragem
> negativa e treinamento adversário; IV — que se avalie a segurança de **dados sintéticos** quando usados
> para treinamento e otimização de capacidades críticas; V — que se reforcem as verificações cotidianas e
> a atualização periódica dos dados; VI — que se adotem medidas necessárias para garantir a segurança dos
> dados e prevenir vazamentos."

Fonte: `fontes/China/2026-medidas-ia-antropomorfica-pt.md`

**O item IV não aparece em nenhum outro instrumento do acervo:** avaliar a segurança de **dados
sintéticos** usados no treinamento. À medida que modelos passam a treinar sobre saída de outros modelos, a
questão deixa de ser teórica.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **LGPD, art. 6º** — princípios do tratamento, entre eles finalidade, adequação, necessidade,
  **qualidade dos dados** e transparência. Aplicam-se a dados pessoais, não ao conjunto de treinamento
  como tal.
- **LGPD, art. 9º** — direito de acesso facilitado a informações sobre o tratamento.
- **LGPD, art. 20, §§ 1º e 2º** — direito a informações sobre critérios e procedimentos da decisão
  automatizada, com poder de **auditoria pela autoridade nacional** quando oposto segredo comercial.
- **LGPD, art. 20** — é o dispositivo mais próximo de um dever de transparência algorítmica que o Brasil
  tem em vigor, e ele é **individual**: depende de requerimento do titular.
- **ECA Digital (Lei 15.211/2025), art. 31, VII** — relatórios semestrais devem detalhar "os métodos
  utilizados e a apresentação dos resultados das avaliações de impacto, identificação e gerenciamento de
  riscos", mas só para provedores com mais de um milhão de usuários na faixa etária.
- **ANPD** — a Lei 15.452/2026 converteu a autoridade em **Agência**, com competência para dispor sobre
  padrões de interoperabilidade e para editar normas (LGPD, arts. 40 e 55-J).

**Falta:**

1. **Dever de documentar o processo de treinamento.** Não existe — nem para alto risco, nem em geral.
2. **Resumo público do conteúdo de treinamento.** Não existe equivalente ao art. 53, § 1º, "d" do AI Act.
3. **Exigência de diversidade e de representatividade do conjunto de dados**, inclusive quanto ao
   contexto brasileiro.
4. **Avaliação de viés como obrigação documentada**, com medidas de mitigação — hoje só aparece como
   poder de auditoria da autoridade, reativo.
5. **Regra sobre dados sintéticos** no treinamento.
6. **Qualificação do uso de data set discriminatório** como infração autônoma.

---

## 4. O que a comparação revela

**É a proposta com o melhor caminho de transplante, por um motivo específico:** o Brasil já tem a
autoridade (ANPD como Agência) e já tem o gancho legal (LGPD art. 20, § 2º). O que falta é transformar um
poder reativo de auditoria em **dever prévio de documentação**.

A UE separa dois regimes que o debate brasileiro costuma misturar:

| | Sistemas de alto risco | Modelos de uso geral |
|---|---|---|
| Instrumento | Documentação técnica detalhada (Anexo XI) | Resumo **público** do conteúdo de treinamento |
| Destinatário | Autoridade e organismos notificados | Público |
| Nível de detalhe | Alto | "Suficientemente detalhado" |

**A lição turca** é de economia legislativa: qualificar o uso de data set discriminatório como violação de
segurança de dados não exige criar estrutura sancionatória nova — usa-se a que já existe.

**A lição chinesa** é a única, no acervo, que trata de **dados sintéticos** e de **envenenamento de
dados**. Nenhum outro instrumento menciona os dois.

**A lição europeia do art. 10, § 4º** é a que toca diretamente a soberania: exigir que o conjunto de dados
leve em conta o contexto geográfico, comportamental e funcional de uso é o que dá base legal para
argumentar que modelo treinado para outro país precisa de adaptação — não por preferência nacional, mas
por **requisito de qualidade**.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Quem é alcançado** | modelos de uso geral × sistemas de alto risco × ambos | Modelos de uso geral exigem resumo público; alto risco exige documentação detalhada |
| **Formato** | declaração pública × documentação à autoridade × as duas | Público permite escrutínio externo; autoridade permite detalhe sob sigilo |
| **Sigilo** | segredo comercial preservado × presunção de publicidade | Sem regra de sigilo, o dever de resumo vira litígio sobre o que é segredo |
| **Diversidade** | obrigação de resultado × obrigação de avaliação documentada | Resultado é inexigível; avaliação documentada é verificável |
| **Contexto brasileiro** | exigência de representatividade × referência ao art. 10, § 4º da UE × silêncio | Exigir representatividade sem definir o parâmetro é norma inaplicável |
| **Dados sintéticos** | incluir × excluir | Modelos que treinam sobre saída de modelos ficam fora se a regra não os mencionar |
| **Sanção** | infração autônoma (Turquia) × sanção já existente | Qualificar como violação de segurança usa o regime vigente; infração nova exige tipificação |
| **Retroatividade** | só modelos novos × também modelos já treinados | Alcançar modelos existentes cria problema de documentação que nunca existiu |

---

## 6. Lacunas de pesquisa

1. **Não há dados sobre a composição dos conjuntos de treinamento** usados em modelos disponíveis no
   Brasil. O acervo não tem nenhum estudo de proveniência.
2. Não verifiquei se a **ANPD** editou norma sobre dados de treinamento depois da conversão em Agência
   (Lei 15.452/2026).
3. Falta o **PL 2338/2023** no acervo — é onde a matéria provavelmente já está tratada no Brasil.
4. Não localizei, no acervo, **parâmetro técnico** de "representatividade" para dados em português
   brasileiro. Nenhum dos instrumentos comparados define o que seria.
5. Não verifiquei como a UE define o **modelo** de resumo do art. 53, § 1º, "d" — o *template* do AI Office
   não está no acervo.
6. Não há, no acervo, precedente de **aplicação sancionatória** da regra turca (é projeto).

---

## 7. Perguntas abertas

1. O dever é de **documentação** (para a autoridade) ou de **publicação** (para o público) — ou os dois,
   com níveis distintos de detalhe?
2. A lei exige **representatividade do contexto brasileiro** no conjunto de dados ou apenas que a avaliação
   seja documentada?
3. O uso de data set discriminatório vira **infração autônoma** ou é qualificado como violação de segurança
   de dados, como na Turquia?
4. **Dados sintéticos** entram no regime?
5. Modelos **já treinados** ficam sujeitos a algum dever de documentação retroativa?
6. Como se combina o resumo público com o **segredo comercial** já protegido pela LGPD, art. 20, § 1º?
