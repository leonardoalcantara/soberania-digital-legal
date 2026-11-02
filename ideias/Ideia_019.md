# Ideia 019 — Processamento local e hospedagem no país

**Bloco:** D — responsabilidade e infraestrutura
**Origem:** proposta nova
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Exigir que **parte do processamento** ou da **hospedagem** de dados ocorra em território nacional.

A formulação parece simples e não é: sob o mesmo nome cabem três exigências diferentes, com efeitos
distintos.

| Objeto da exigência | O que se exige | O que se controla |
|---|---|---|
| **Localização física** | o servidor está no País | Onde o dado está guardado |
| **Processamento local** | parte do processamento ocorre no País | Onde o dado é trabalhado |
| **Controle do provedor** | o provedor é nacional ou aceita condições de controle | Quem manda em quem guarda |

As três são tratadas no debate como "soberania digital", e nenhuma delas substitui as outras. É a
proposta do conjunto em que a diferença entre o nome e o mecanismo é maior.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| Austrália | Hosting Certification Framework (2021) | Duas certificações com base em **controle societário**, não em território |
| Brasil | Lei 15.504/2026 (Redata), art. 11-B, § 1º, I | **10% do fornecimento efetivo** de processamento, armazenagem e tratamento ao mercado interno, como contrapartida de benefício fiscal |
| Brasil | Lei 9.504/1997, art. 57-B, I e II | Sítio de candidato ou partido deve ser hospedado "em provedor de serviço de internet **estabelecido no País**" |

### Austrália — soberania sem território

O Hosting Certification Framework é o instrumento mais elaborado do acervo sobre o tema — e o mais
inesperado. O documento **não contém nenhuma exigência de que o data center esteja em território
australiano**. A definição de soberania está no texto:

> "Durante a consulta realizada durante a elaboração deste Marco de Certificação, ficou evidente que a
> terminologia original usada na Estratégia de Hospedagem para descrever os dois níveis de certificação se
> beneficiaria de clareza adicional. Em particular, o termo **soberano** foi tomado como excluindo
> qualquer nível de investimento ou controle estrangeiro em um provedor de hospedagem. Sob tal
> interpretação, dada a possibilidade de um nível de investimento estrangeiro, qualquer provedor de
> hospedagem de capital aberto seria inelegível para o nível mais alto de certificação."
>
> "Para clareza, **soberania se refere à capacidade do governo de especificar e manter condições rigorosas
> de propriedade e controle**. O nível mais alto de certificação destina-se a estar disponível apenas a
> provedores de hospedagem que atendam ao limiar rigoroso de avaliação de adequação e permitam que o
> Governo especifique e faça cumprir condições de propriedade e controle que não sejam afrouxadas em
> momento algum."

Fonte: `fontes/Australia/2021-hosting-certification-framework.pdf`

E os dois níveis:

> "**Certified Strategic Hosting Provider** representa o nível mais alto de garantia e está disponível
> apenas a provedores que permitam ao Governo especificar condições de propriedade e controle."
>
> "**Certified Assured Hosting Provider**: os arranjos protegem contra os riscos de mudança de propriedade
> ou controle por meio de **penalidades ou incentivos financeiros**, visando minimizar os custos de
> transição arcados pela Commonwealth caso um provedor de data center altere seu perfil."

E o âmbito de aplicação, quanto ao uso:

> "Sistemas PROTECTED e de governo como um todo devem ser hospedados em Data Centre **Certified Strategic**
> ou **Certified Assured**."

**A inversão que o documento faz:** a pergunta não é *onde* o dado está, é *quem controla quem guarda* — e
o instrumento para isso é contratual. O Governo não exige território; exige o poder de impor condições de
propriedade e controle, com sanção financeira se o perfil do provedor mudar.

### Brasil — a única obrigação de processamento local vigente

Redata, art. 11-B, § 1º, I, um dos compromissos cumulativos para fruir do benefício fiscal:

> "disponibilizar para o **mercado interno**, no mínimo, **10% (dez por cento) do fornecimento efetivo de
> processamento, armazenagem e tratamento de dados** a ser instalado com os benefícios do Redata, vedada
> sua destinação para exportação ou uso próprio na ausência de demanda doméstica."

Fonte: `fontes/Brasil/2026-lei-15504-Redata - texto.md` (art. 11-B, § 1º, I)

E o § 4º define como a cota é **medida** — detalhe que costuma escapar ao debate:

> "A destinação do fornecimento efetivo [...] será apurada [...] considerando-se a **razão entre o
> faturamento anual bruto originado no mercado doméstico e o faturamento anual bruto total**, ambos
> decorrentes da venda dos serviços de *datacenter* instalados com benefícios do regime."

Ou seja: a exigência não é sobre onde o dado fica — é sobre **de onde vem a receita**.

E a sanção pelo descumprimento (art. 11-H): suspensão dos benefícios em novas aquisições, convertida
automaticamente em **cancelamento da habilitação** se a infração não for sanada em 180 dias, com
impedimento de nova adesão por 2 anos para a empresa **e seu grupo econômico**.

**A natureza do instrumento é o ponto:** é contrapartida de benefício fiscal, exigível apenas de quem pede
habilitação. Empresa que não adere ao Redata não tem nenhuma obrigação de processar no Brasil.

### Brasil — a exigência de hospedagem que já existe desde 2009

Lei 9.504/1997, art. 57-B, I:

> "em sítio do candidato, com endereço eletrônico comunicado à Justiça Eleitoral e **hospedado, direta ou
> indiretamente, em provedor de serviço de internet estabelecido no País**."

Idem no inciso II, para sítio do partido ou da coligação.

**Por que este dispositivo importa:** é uma exigência de localidade **em lei**, vigente desde 2009, fora do
regime tributário e sem relação com benefício. É o único precedente brasileiro de obrigação de hospedagem
no País dirigida a particular, e o acervo não registra debate sobre sua constitucionalidade ou eficácia.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Lei 9.504, art. 57-B, I e II** — hospedagem, direta ou indireta, em provedor estabelecido no País, para
  sítios de campanha eleitoral.
- **Redata, art. 11-B, § 1º, I** — 10% do fornecimento efetivo ao mercado interno, condicionado a
  benefício fiscal, com sanção escalonada no art. 11-H.
- **Marco Civil, art. 11, caput e § 2º** — a lei brasileira se aplica a quem oferta serviço ao público
  brasileiro, inclusive pessoa jurídica sediada no exterior. É **jurisdição**, não localização.
- **Marco Civil, art. 15** — guarda de registros de acesso por seis meses, por quem exerce a atividade de
  forma organizada, profissionalmente e com fins econômicos. Exige estrutura no País, mas não define onde.
- **LGPD, arts. 33 a 36** — transferência internacional por hipóteses fechadas, avaliação do nível de
  proteção do país de destino e possibilidade de suspensão da transferência. É **controle de fluxo**, não
  exigência de permanência.
- **Lei do Governo Digital (14.129/2021)** — não menciona computação em nuvem, não estabelece requisitos de
  hospedagem nem de residência de dados. A contratação federal de nuvem é regida por norma infralegal
  (IN SGD/ME nº 94/2022), que exige portabilidade e "disponibilidade para transferência de localização",
  mas não residência.
- **PNCiber, art. 2º, I** e **E-Ciber, art. 1º, IV** — soberania como princípio e eixo, sem instrumento.

**Falta:**

1. **Dever geral de processamento local.** Não existe — a única norma é condição de benefício fiscal.
2. **Definição legal de "processamento" e de "hospedagem"** para fins de exigência territorial.
3. **Regra sobre controle societário de provedor** — o modelo australiano não tem equivalente brasileiro.
4. **Exigência de certificação de provedor** por nível de garantia.
5. **Critério de proporcionalidade por criticidade do dado** — hoje a única gradação existente é a do
   Redata, que é econômica, não de segurança.
6. **Dados públicos e estratégicos** — a LAI autoriza classificar como sigilosa a informação que possa pôr
   em risco a defesa e a soberania (art. 23, I), mas não diz onde essa informação pode ser processada.

---

## 4. O que a comparação revela

**É a proposta com a base comparada mais fraca do acervo — e isso é uma constatação, não um juízo.**

O acervo tem onze jurisdições e **nenhuma norma europeia, britânica, americana, japonesa, coreana,
indiana ou latino-americana** que exija processamento ou hospedagem em território nacional. A UE regula
transferência (restrição de fluxo), não localização. Os instrumentos que tratam do tema no acervo são
dois: um australiano, que **não** usa território, e um brasileiro, que usa território **como preço de
benefício fiscal**.

Duas leituras possíveis, ambas compatíveis com o material:

1. **A exigência territorial é anacrônica** — o instrumento moderno de soberania é o controle contratual e
   societário, como na Austrália.
2. **A exigência territorial não foi testada** porque os países que a adotaram (China, Rússia, Índia,
   Vietnã, Indonésia) não estão no acervo — e a ausência é falha de levantamento, não evidência de
   desuso.

O acervo **não permite decidir entre as duas**. E o fato de a única norma brasileira de processamento local
ser condicionada a benefício fiscal significa que ela nunca foi testada como dever geral.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Objeto** | localização física × processamento × controle societário | São três instrumentos distintos; escolher um não entrega os outros |
| **Escopo material** | todos os dados × dados de menores × dados públicos × dados estratégicos | Universo amplo é inexequível e caro; escopo estreito é verificável |
| **Tipo de norma** | dever geral × condição de benefício (Redata) × exigência contratual (Austrália) | Dever geral alcança quem não quer benefício; condição de benefício pode ser simplesmente ignorada |
| **Gradação** | por criticidade do dado × por volume × sem gradação | Sem gradação, um serviço pequeno e um data center recebem a mesma exigência |
| **Certificação** | auto declaração × certificação por nível × auditoria | Certificação por nível é o que torna a exigência verificável |
| **Controle societário** | exigir nacionalidade × exigir condições de controle × silêncio | Modelo australiano é o único do acervo que trata disso |
| **Sanção** | multa × cancelamento de habilitação × impedimento de operar | Sem sanção, a exigência é declaração de intenção |
| **Compatibilidade** | com o princípio da neutralidade de rede × com acordos de comércio × com a LGPD | Exigência territorial pode conflitar com compromissos de serviços assumidos pelo Brasil |

---

## 6. Lacunas de pesquisa

**Esta é a proposta com o maior déficit de fontes no acervo.** O que falta, especificamente:

1. **China** — Lei de Segurança Cibernética, Lei de Proteção de Dados Pessoais (arts. 38 a 43) e Lei de
   Segurança de Dados: o regime chinês de localização é o mais citado no debate e não está no acervo em
   texto integral.
2. **Índia** — o DPDP Act 2023 e as regras de localização setorial.
3. **Rússia** — Lei 242-FZ, o precedente mais antigo de localização obrigatória.
4. **Vietnã** — Decreto 53/2022.
5. **Indonésia** — Regulamento 71/2019.
6. **União Europeia** — não há instrumento de localização no acervo, mas falta verificar o **Regulamento
   NIS2** e o **Data Act**, que não estão arquivados.
7. **IN SGD/ME nº 94/2022** — não está no acervo; é citada de segunda mão no índice analítico.
8. **Constitucionalidade** — não localizei, no acervo, análise sobre a compatibilidade de exigência de
   localização com o art. 174 da CF e com os compromissos assumidos pelo Brasil em acordos de comércio.
9. **Custo** — nenhum dado no acervo sobre o efeito econômico de exigências de localização.

---

## 7. Perguntas abertas

1. A proposta exige **localização física**, **processamento local** ou **condições de controle** do
   provedor? (são três coisas diferentes)
2. A exigência é **dever geral** ou **condição para contratar com o poder público**?
3. O escopo é por **criticidade do dado** ou por tipo de serviço? Quais entram?
4. Há **gradação** — exigência mais forte para dados estratégicos e mais fraca para o resto?
5. A empresa estrangeira pode cumprir por **subsidiária no País** ou a exigência é de controle nacional?
6. Há **certificação de provedor**, como no modelo australiano, ou basta declaração?
7. A exigência convive com o **Redata** ou o substitui?
8. Vale a pena investir no levantamento dos países que adotaram localização (China, Rússia, Índia, Vietnã,
   Indonésia) antes de fechar a proposta?
