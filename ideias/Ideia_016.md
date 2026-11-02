# Ideia 016 — Responsabilidade de quem desenvolve e treina IA

**Bloco:** D — responsabilidade e infraestrutura
**Origem:** proposta nova
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Criar uma figura de responsabilidade própria para **quem desenvolve e treina o sistema**, distinta da responsabilidade de quem publica o conteúdo ou de quem opera o serviço — inclusive com agravante quando o desenho ou o treinamento **viabiliza** o dano.

Hoje, no direito brasileiro, o desenvolvedor de um modelo não é sujeito do regime de responsabilidade das plataformas: o Marco Civil fala em provedor de aplicações, e a LGPD fala em controlador e operador de dados pessoais. Quem treina o modelo e não o publica fica fora dos dois.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| Turquia | PL 2/3358, MADDE 2 | **Agravante penal** para o desenvolvedor que, pelo desenho ou treinamento, viabiliza a prática do crime |
| União Europeia | AI Act (Reg. 2024/1689), art. 25 | Deslocamento de papel: quem põe nome, modifica substancialmente ou muda a finalidade **passa a ser** o provedor |
| União Europeia | AI Act, art. 27 | Avaliação de impacto sobre direitos fundamentais a cargo de quem **implanta** o sistema |
| Coreia do Sul | Lei nº 20.676/2025 (Lei-Quadro de IA), art. 2º, 7, "a" e "b" | Separa **desenvolvedor** de **operador usuário** na definição, com deveres por categoria |
| Coreia do Sul | Lei-Quadro de IA, art. 34 | Deveres do operador quanto a gestão de risco, plano de explicação, plano de proteção e supervisão humana |
| China | Medidas de IA Antropomórfica (2026), arts. 9º e 10 | "Responsabilidade principal pela segurança" do provedor, em **todo o ciclo de vida** do serviço |

### Turquia — a única imputação penal direta ao desenvolvedor no acervo

PL 2/3358, MADDE 2, que insere § 6º ao art. 125 do Código Penal turco:

> "O usuário que direcionar sistemas de inteligência artificial à prática de fato tipificado como crime nos termos desta lei é considerado autor do crime e é punido nessa qualidade. **Quanto ao desenvolvedor que, pelo desenho ou pelo treinamento do sistema, viabilizar a prática desses crimes, a pena aplicável é aumentada pela metade.**"

Fonte: `fontes/Turquia/2025-turquia-esas-2-3358-teklif-texto-extraido.md` (MADDE 2)

**Duas observações sobre o desenho:**

1. O dispositivo é **projeto**, não lei — e foi apresentado em 07/11/2025.
2. Tecnicamente, foi inserido no art. 125 do Código Penal turco, que tipifica o **crime de injúria**. A agravante, portanto, nasce dentro de um tipo específico e não na parte geral — o que limita o alcance material a esse crime. É exemplo de formulação, não de arquitetura.

### União Europeia — a responsabilidade por deslocamento de papel

O AI Act não cria um "dever do desenvolvedor" genérico. Ele resolve o problema da cadeia de valor por **reatribuição de papel**: quem interfere no sistema assume as obrigações do provedor.

Art. 25, § 1º:

> "Qualquer distribuidor, importador, implementador ou outro terceiro será considerado provedor de um sistema de IA de alto risco [...] nas seguintes circunstâncias: (a) **colocar seu nome ou marca** em um sistema de IA de alto risco já colocado no mercado; (b) **modificar substancialmente** um sistema de IA de alto risco já colocado no mercado; (c) **modificar a finalidade** de um sistema de IA [...] de modo que o sistema passe a ser de alto risco."

E o § 2º determina que o provedor inicial deixa de ser provedor daquele sistema, mas deve **cooperar estreitamente** com o novo provedor, fornecendo informações, acesso técnico e assistência.

Fonte: `fontes/UE/2024-regulamento-ue-2024-1689-ai-act.pdf`

**A lógica é diferente da turca:** não se pune o desenvolvedor pelo que o sistema viabiliza — transfere-se
a ele o regime inteiro de obrigações quando ele assume o controle do produto.

O art. 27 acrescenta o outro lado da cadeia: quem **implanta** sistema de alto risco — órgão público, entidade privada que presta serviço público e os casos dos pontos 5(b) e (c) do Anexo III — deve realizar avaliação de impacto sobre direitos fundamentais **antes** da implantação.

### Coreia do Sul — a distinção que o Brasil não tem

A Lei-Quadro de IA coreana (Lei nº 20.676/2025), no art. 2º, 7, define "operador de negócio de IA" e logo em seguida separa duas figuras:

> "(a) **Desenvolvedor de inteligência artificial**: pessoa que desenvolve e fornece inteligência artificial; (b) **Operador usuário de inteligência artificial**: pessoa que fornece produtos ou serviços de inteligência artificial usando inteligência artificial fornecida por um operador nos termos da alínea (a)."

E o art. 34 concentra os deveres no operador, para IA de alto impacto:

> "O operador de negócio de inteligência artificial deverá implementar medidas que incluam: 1. formular e operar um **plano de gestão de riscos**; 2. formular e implementar um **plano de explicação** dos resultados finais, dos principais critérios utilizados e da **visão geral dos dados de aprendizado** usados no desenvolvimento; 3. formular e operar **planos de proteção do usuário**; 4. designar **supervisão humana**; 5. preparar e manter documentos que comprovem as medidas adotadas."

Fonte: `fontes/Coreia/2025-framework-act-ai-EN.pdf`

**O que acrescenta:** a definição cria a figura do desenvolvedor — mas os deveres ficam no operador. A
separação existe no vocabulário, não na imputação.

### China — a responsabilidade do provedor por todo o ciclo de vida

Medidas de IA Antropomórfica (2026), art. 9º:

> "O provedor deve cumprir a **responsabilidade principal pela segurança do serviço**, estabelecendo e aperfeiçoando sistemas de revisão do mecanismo algorítmico, de exame de ética em ciência e tecnologia, de gestão de conteúdo informacional, de segurança de rede e de dados e de planos de risco e resposta a emergências[...]"

Art. 10:

> "O provedor deve cumprir a responsabilidade de segurança em **todo o ciclo de vida** do serviço, definindo requisitos de segurança para implantação, operação, atualização e encerramento, garantindo que as medidas de segurança sejam implantadas e usadas simultaneamente às funcionalidades."

Fonte: `fontes/China/2026-medidas-ia-antropomorfica-pt.md`

**O que acrescenta:** o ciclo de vida é o eixo — a obrigação alcança implantação, operação, atualização e
**encerramento**. Não há figura autônoma do desenvolvedor: quem responde é o "provedor", expressão que absorve o desenvolvimento.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Marco Civil, arts. 18 e 19** — responsabilidade do **provedor de aplicações** por conteúdo de terceiros. Não alcança quem desenvolve o modelo.
- **LGPD, art. 42** — responsabilidade do **controlador e do operador** por dano decorrente de tratamento de dados pessoais. Alcança o desenvolvedor apenas quando há tratamento de dados pessoais e apenas nessa dimensão.
- **LGPD, art. 20** — direito à revisão de decisão automatizada. É direito do titular perante o controlador, não regime de responsabilidade do desenvolvedor.
- **ECA Digital (Lei 15.211/2025)** — deveres do **provedor de aplicações de internet**, não do desenvolvedor de modelo.
- **Código Penal, art. 13** — nexo causal e omissão penalmente relevante. É a base genérica que hoje teria de ser usada para alcançar o desenvolvedor.

**Falta:**

1. **Figura jurídica do desenvolvedor de sistema de IA.** Não existe em lei brasileira.
2. **Cadeia de valor.** Nenhuma norma brasileira em vigor atribui obrigações a quem fornece modelo ou componente para outro desenvolver produto.
3. **Agravante por desenho.** Nenhuma previsão de que o sistema ter sido **concebido** para viabilizar o ilícito altere a pena.
4. **Dever de informação entre elos.** Não há obrigação de o desenvolvedor informar capacidades, limitações e uso pretendido a quem integra o modelo.
5. **Encerramento.** Nenhuma norma trata do ciclo de vida — descontinuação, atualização e seus efeitos.

---

## 4. O que a comparação revela

**É a proposta do bloco com o menor número de precedentes vigentes.** O único dispositivo do acervo que responsabiliza diretamente o desenvolvedor é um **projeto de lei turco**, e com alcance limitado por um detalhe de técnica legislativa: a agravante foi inserida dentro do tipo de injúria.

A UE não imputa ao desenvolvedor pelo que o sistema viabiliza: **reatribui o papel** de provedor a quem interfere no sistema. É uma solução mais segura juridicamente, mas exige definir o que é "modificação substancial" — e essa definição fica em regulamento, não em lei.

A Coreia mostra o custo de separar os dois vocabulários sem separar as obrigações: a figura do desenvolvedor existe na definição e desaparece na parte de deveres.

A China resolve por absorção: um único sujeito — o "provedor" — responde por todo o ciclo de vida, do treinamento ao encerramento.

**Conclusão descritiva:** há quatro arquiteturas possíveis e nenhuma delas é dominante no acervo. A
escolha brasileira não tem precedente consolidado a importar.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Quem é o sujeito** | desenvolvedor × provedor que absorve o desenvolvimento × ambos por etapas | Definir "desenvolvedor" em lei é o passo mais difícil: modelos são treinados, ajustados e integrados por sujeitos distintos |
| **Natureza da responsabilidade** | civil × administrativa × penal | Penal exige tipo fechado; administrativa depende de órgão; civil depende de vítima |
| **Nexo** | dolo ou culpa × risco da atividade × falha sistêmica | Responsabilidade objetiva para desenvolvimento de IA é tese sem precedente no acervo |
| **Agravante** | pelo desenho × pelo treinamento × pelos dois | "Viabilizar" é conceito aberto — a formulação turca não o define |
| **Cadeia de valor** | reatribuição de papel (UE) × dever de informação entre elos × os dois | Reatribuição sem dever de informação entre elos deixa o integrador sem os dados de que precisa |
| **Escopo material** | alto risco × IA generativa × todo sistema | Quanto mais amplo, maior o custo de conformidade e menor a chance de aprovação |
| **Encerramento** | silêncio × dever de comunicar descontinuação | Nenhum precedente brasileiro; o modelo chinês é o único do acervo que trata |

---

## 6. Lacunas de pesquisa

1. **Não há, no acervo, o PL 2338/2023** nem o texto do PL 4218/2025 — os dois veículos brasileiros que já tratam de responsabilidade de sistemas de IA. Sem eles, a seção 3 descreve apenas o direito **vigente**, não o que está em tramitação.
2. Não localizei, no acervo, **lei nacional que responsabilize penalmente o desenvolvedor** de IA. A Turquia é projeto.
3. Não verifiquei se há **regulamento do AI Act** definindo "modificação substancial" além do considerando — e a definição é o que decide o alcance do art. 25.
4. Falta o **CDC** no acervo: qualquer discussão sobre responsabilidade objetiva por produto no Brasil passa por ele.
5. Não há dados sobre **litígios brasileiros** em que o desenvolvedor de modelo tenha sido parte.

---

## 7. Perguntas abertas

1. A lei define **desenvolvedor** — e como trata quem apenas ajusta (*fine-tuning*) um modelo de terceiro?
2. A responsabilidade do desenvolvedor é **autônoma** ou subsidiária à de quem publica?
3. A agravante depende de **dolo específico** ou basta a viabilização pelo desenho?
4. O regime alcança **todo** sistema de IA ou só alto risco e IA generativa?
5. Há dever de **informação entre elos** da cadeia — e quem responde se a informação não é prestada?
6. O **encerramento** do serviço entra no regime, como no modelo chinês, ou fica fora?
