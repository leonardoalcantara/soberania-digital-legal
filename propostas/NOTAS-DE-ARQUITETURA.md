# Notas de arquitetura

As decisões de desenho que valem para o conjunto e não pertencem a um instrumento isolado: por que a PEC é mínima, por que as propostas se dividem em dois projetos, por que os capítulos do Marco Civil são novos em vez de emendas, e quais veículos estavam errados.

Este arquivo não é proposta. É a justificativa que atravessa todas.

---

## 1. A regra de redação: mínimo de dispositivos, zero de detalhe

O molde é a **EC 115/2022**, que inseriu a proteção de dados na Constituição com três dispositivos e nenhum número: um direito no art. 5º, LXXIX ("nos termos da lei"), uma competência de execução no art. 21, XXVI, e uma competência legislativa no art. 22, XXX.

A PEC abaixo segue a mesma lógica com cinco dispositivos. **Nenhum prazo, percentual, procedimento ou valor.** Tudo isso fica na lei.

## 2. O achado que sustenta a PEC

O art. 21, XXIII, "d", da Constituição já contém exatamente o que a Ideia_024 quer:

> "d) a **responsabilidade civil por danos nucleares independe da existência de culpa**." *(Redação dada pela EC nº 49/2006)*

É precedente constitucional de **responsabilidade objetiva por comando direto da Constituição**, para um domínio de risco. O argumento de simetria fica pronto: se o dano nuclear é objetivamente imputável por determinação constitucional, o dano ao processo político-eleitoral causado por falha de plataforma também pode ser.

E o art. 170, I, já traz a **soberania nacional** como princípio da ordem econômica. A PEC não cria princípio novo — explicita a dimensão digital do que já está lá.

---

# PROPOSTA DE EMENDA À CONSTITUIÇÃO

*Altera os arts. 5º, 21, 22, 170 e 220 da Constituição Federal para dispor sobre soberania digital, integridade do processo político-eleitoral e deveres dos provedores de aplicações de internet.*

As Mesas da Câmara dos Deputados e do Senado Federal, nos termos do art. 60 da Constituição Federal, promulgam a seguinte Emenda ao texto constitucional:

**Art. 1º** O art. 5º da Constituição Federal passa a vigorar acrescido do seguinte inciso LXXX:

> "LXXX — a todos é assegurado o direito de conhecer os critérios de curadoria de conteúdo no ambiente digital, de escolher curadoria não personalizada e de contestar as medidas que restrinjam sua conta, seu conteúdo, seu alcance ou sua receita, nos termos da lei."

**Art. 2º** O art. 21 da Constituição Federal passa a vigorar acrescido do seguinte inciso XXVII:

> "XXVII — organizar e fiscalizar, nos termos da lei, os provedores de aplicações de internet e os sistemas de inteligência artificial, quanto aos deveres de transparência da curadoria, de integridade do processo político-eleitoral e de soberania digital."

**Art. 3º** O art. 22 da Constituição Federal passa a vigorar acrescido do seguinte inciso XXXI:

> "XXXI — soberania digital, provedores de aplicações de internet e sistemas de inteligência artificial."

**Art. 4º** O parágrafo único do art. 170 da Constituição Federal passa a ser § 1º, e o artigo passa a vigorar acrescido do seguinte § 2º:

> "§ 2º A soberania nacional de que trata o inciso I abrange a **soberania digital**, assim entendida a capacidade do Estado de definir e fazer cumprir condições sobre o controle, o processamento e a circulação de dados e de conteúdo no ambiente digital."

**Art. 5º** O art. 220 da Constituição Federal passa a vigorar acrescido do seguinte § 7º:

> "§ 7º A lei disporá sobre:
>
> I — o direito do usuário de conhecer os critérios de curadoria de conteúdo e de escolher curadoria não personalizada;
>
> II — o dever dos provedores de aplicações de internet de informar e fundamentar as medidas que restrinjam conteúdo, conta, alcance ou receita, e de assegurar o direito de contestação;
>
> III — o dever de prevenir e mitigar riscos à integridade do processo político-eleitoral e à soberania nacional, inclusive quanto à atividade de influência realizada em nome de principal estrangeiro;
>
> IV — a **responsabilidade civil objetiva** dos provedores pelos danos decorrentes do descumprimento dos deveres de que tratam os incisos II e III, independentemente da existência de culpa."

**Art. 6º** Esta Emenda Constitucional entra em vigor na data de sua publicação.

---

---

## 1. O mapa da Onda 1

| Ideia | Lei alterada | Dispositivo novo | Técnica |
|---|---|---|---|
| **001** curadoria não personalizada | Marco Civil | art. 7º, inciso XIV | direito novo em rol existente |
| **022** devido processo da moderação | Marco Civil | arts. 21-A a 21-E | capítulo novo |
| **015** notificação e ação | Marco Civil | art. 19-A | artigo novo ao lado do 19 |
| **013** representante legal | Marco Civil | art. 11, §§ 5º a 7º | parágrafos novos |
| **014** prazos de cooperação | Marco Civil | art. 22-A | artigo novo |
| **003** impulsionamento político | Lei 9.504 | art. 57-C, §§ 4º e 5º | parágrafos novos |
| **022 (parte eleitoral)** prazo de 4h | Lei 9.504 | art. 57-K | artigo novo |

**Uma decisão de arquitetura que a redação revelou:** o prazo de 4 horas **não cabe no Marco Civil**. Ele é eleitoral e vale para perfil politicamente relacionado durante o período de propaganda. Vai para a Lei 9.504. O Marco Civil fica com o prazo geral de 72 horas. Os dois relógios existem, mas em leis diferentes — e é isso que permite calibrá-los sem que um arraste o outro.

---

---

## 1. Por que um capítulo, e não emenda a dispositivo existente

O Marco Civil trata de **responsabilidade por dano já causado** (arts. 18 a 21) e de **guarda de registros** (arts. 10 a 17). Não trata de **conduta preventiva**: não há nele um dispositivo que obrigue o provedor a conhecer os riscos do próprio produto, documentá-los e submetê-los a verificação externa.

Isso não é lacuna de redação — é ausência de objeto. Daí o capítulo novo, e não a emenda a um artigo existente.

**O que ele transpõe:**

| Origem | Dispositivo de origem | O que se aproveita |
|---|---|---|
| ECA Digital, art. 8º, I | gerenciamento de riscos de recursos e funcionalidades | o dever em si, sem o recorte etário |
| ECA Digital, art. 31 | relatório semestral com métodos e resultados das avaliações | a estrutura do relatório |
| DSA, arts. 27 e 34 a 37 | transparência da recomendação, avaliação de risco sistêmico, auditoria independente | os parâmetros e as regras de conflito de interesse |
| TSE, Res. 23.755, art. 125-B | plano de conformidade com indicadores mensuráveis e trajetória | o desenho do plano |

---

---

## 1. Duas correções de veículo que a redação exigiu

**017 não cabe na LGPD.** A proposta trata de origem, limpeza, rotulagem e diversidade do **conjunto de treinamento** — que majoritariamente não é dado pessoal. A LGPD só alcança dado pessoal, e usá-la reduziria a proposta à fração de datasets que contém dado de pessoa natural. Vai para o **Capítulo IV-A do Marco Civil**, que a Onda 2 já criou, e alcança o desenvolvedor pela definição proposta na Ideia_016.

**018 não cabe na Lei 12.529.** Autopreferência e designação por escala de usuários não são infração da ordem econômica apurada caso a caso — são obrigações *ex ante* dirigidas a um universo designado. Não há como pendurá-las no direito antitruste sem descaracterizá-lo. Vira **lei nova**, a Lei de Mercados Digitais, no molde do DMA e da lei japonesa de software de smartphone.

**E uma ressalva de método:** a Lei 12.529 **não está no acervo**. Qualquer emenda a ela seria redigida às cegas, com números de artigo chutados. A lei nova evita isso.

---
