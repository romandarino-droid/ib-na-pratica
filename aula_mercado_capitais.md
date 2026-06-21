# IB na Prática — Mercado de Capitais

---

## 1. O que é o Mercado de Capitais e para que serve

### Definição

O **mercado de capitais** é o conjunto de instituições, instrumentos e mecanismos que permitem que poupadores (investidores) direcionem recursos para quem precisa deles (empresas, governo, projetos). É o "sistema circulatório" da economia real.

Diferente do crédito bancário tradicional, no mercado de capitais o **risco é transferido diretamente ao investidor** — não fica no balanço de um banco. Isso permite:

- Volume maior de recursos mobilizados
- Prazo mais longo
- Custo potencialmente menor
- Diversificação de base de investidores

### Para que serve?

| Para quem capta | Para quem investe |
|---|---|
| Financiar crescimento (capex, expansão) | Rentabilizar capital acima do CDI |
| Alongar dívida | Acessar retornos de crédito privado |
| Reduzir custo financeiro | Diversificar portfólio |
| Monetizar ativos (securitização) | Ter exposição à economia real |
| Abrir capital / dar liquidez a sócios | Participar do upside de empresas |

### Estrutura do Sistema Financeiro Nacional (SFN)

```
Banco Central (regulador monetário)
CVM (regulador do mercado de capitais)
    ├── Mercado de renda fixa (debêntures, CRI, CRA, FIDC...)
    ├── Mercado de renda variável (ações, FIIs, BDRs...)
    └── Mercado de derivativos
```

---

## 2. Modalidades de Captação: Crédito vs. Equity

### 2.1 Dívida (Crédito)

A empresa toma dinheiro emprestado e se compromete a pagar juros + principal. **Não dilui os sócios.**

#### Dívida Bancária
- CCB (Cédula de Crédito Bancário)
- Capital de giro, desconto de recebíveis
- Rápido, mas costuma ser curto prazo e caro

#### Dívida no Mercado de Capitais
| Instrumento | Emissor | Típico uso |
|---|---|---|
| **Debênture** | S/A | Capex, refinanciamento, M&A |
| **Debênture Incentivada (Lei 12.431)** | S/A infraestrutura | Projetos de infra com isenção IR PF |
| **CRI** (Certificado de Recebíveis Imobiliários) | Securitizadora | Originadores do setor imobiliário |
| **CRA** (Certificado de Recebíveis do Agronegócio) | Securitizadora | Originadores do agronegócio |
| **FIDC** (Fundo de Invest. em Direitos Creditórios) | Fundo | Cedentes de recebíveis de qualquer setor |
| **CCP / CPR** | Produtor rural | Agro |

#### Características-chave da dívida
- **Seniority**: credores têm preferência sobre sócios em caso de liquidação
- **Covenants**: proteções contratuais (limite de alavancagem, EBITDA mínimo etc.)
- **Rating**: avaliação de risco de crédito por agências (S&P, Moody's, Fitch, Austin, SR)
- **Garantias**: real (alienação fiduciária, hipoteca), fidejussória (fiança, aval), cessão fiduciária de recebíveis

### 2.2 Equity (Capital Próprio)

A empresa vende uma fatia de si mesma. **Não há obrigação de pagamento**, mas o sócio participa dos lucros e das perdas.

#### Private (antes do IPO)
| Instrumento | Estágio | Características |
|---|---|---|
| **Seed / Angel** | Ideia / MVP | Ticket pequeno, altíssimo risco |
| **Venture Capital** | Crescimento | Foco em escala, valuation por múltiplos de receita |
| **Private Equity** | Empresa madura | Controle ou influência, valor por EBITDA |
| **PIPE** | S/A fechada/listada | Private Investment in Public Equity |

#### Public (mercado de capitais)
| Instrumento | Descrição |
|---|---|
| **IPO** (Initial Public Offering) | Primeira oferta de ações ao mercado |
| **Follow-on** | Oferta subsequente de ações |
| **BDR** | Brazilian Depositary Receipt — ação estrangeira listada no Brasil |
| **FII** | Fundo Imobiliário — equity em imóveis |
| **Debenture Conversível** | Dívida que pode virar ação (híbrido) |

#### Equity vs. Dívida — decisão do CFO

```
Custo de capital:  Dívida < Equity  (dívida tem escudo fiscal + menor risco)
Dilui sócio?       Não              Sim
Obrigação?         Sim (juros)      Não
Alavancagem:       Aumenta          Não altera
```

---

## 3. O Processo de IB: Originação → Estruturação → Distribuição

O banco de investimento (IB) funciona como intermediário especializado entre quem precisa de capital e quem tem capital. O processo tem três fases.

```
[EMPRESA/CEDENTE]
       |
  ORIGINAÇÃO
       |
  ESTRUTURAÇÃO
       |
  DISTRIBUIÇÃO
       |
[INVESTIDORES]
```

### 3.1 Originação

**O quê**: Identificar e conquistar o mandato do cliente.

**Quem faz**: Coverage bankers, equipe comercial, DCM/ECM originators.

**Atividades**:
- Prospecção de clientes (empresas, fundos, cedentes)
- Análise preliminar de viabilidade e tamanho de operação
- Pitch: apresentação da estrutura e estratégia ao cliente
- Negociação do mandato (engagement letter) e fee
- Due diligence inicial (entender o negócio, os recebíveis, os ativos)

**O que o banco entrega**: proposta de estrutura, benchmarks de mercado, indicativo de preço (spread / taxa).

> Pergunta-chave da originação: *"Há demanda de investidores para esse papel? A que preço?"*

### 3.2 Estruturação

**O quê**: Desenhar juridicamente e financeiramente a operação, com o objetivo de maximizar o rating e minimizar o custo para o emissor, garantindo proteção ao investidor.

**Quem faz**: Equipe de estruturação (DCM/Structured Finance), advogados, agência de rating, custodiante, agente fiduciário, auditor.

**Atividades**:
- Escolha do veículo (debênture, FIDC, CRI, CRA...)
- Modelagem financeira: fluxo de caixa, subordinação, gatilhos de liquidez
- Definição das garantias e covenants
- Processo de rating: apresentação à agência, Q&A, carta de rating
- Elaboração de documentos: escritura / regulamento / prospecto
- Registro na CVM (quando aplicável)
- Precificação final (bookbuilding ou taxa fixa)

> A estruturação é onde "o produto é fabricado". Cada detalhe do regulamento/escritura importa.

### 3.3 Distribuição

**O quê**: Vender os títulos aos investidores.

**Quem faz**: Mesa de distribuição, sales, wealth management, plataformas de investimento (XP, BTG, Itaú Private etc.).

**Atividades**:
- Roadshow: apresentações para investidores institucionais (fundos, seguradoras, family offices)
- Bookbuilding: coleta de ordens com taxa/preço e volume
- Alocação: definição de quem leva qual volume
- Liquidação: transferência dos títulos e dos recursos (via B3/CETIP)
- Aftermarket: acompanhamento do papel no mercado secundário

**Tipos de oferta**:
| Modalidade | Descrição |
|---|---|
| **ICVM 476** (esforços restritos) | Até 75 investidores profissionais, mais ágil, sem prospecto público |
| **ICVM 400** (oferta pública) | Qualquer investidor, prospecto completo, mais regulada |

---

## 4. FIDC — Fundo de Investimento em Direitos Creditórios

### 4.1 O que é

Um **FIDC** é um fundo de investimento cuja carteira é composta majoritariamente (mínimo 50%, na prática quase sempre > 80%) por **direitos creditórios** — recebíveis que uma empresa (cedente) tem a receber de seus clientes (devedores/sacados).

O FIDC é regulado pela **ICVM 356** (antiga) e hoje pela **Resolução CVM 175 + Anexo Normativo III** (resolução em vigor desde outubro/2023).

### 4.2 Para que serve

**Para o cedente (empresa que vende os recebíveis)**:
- Antecipar recebíveis → transformar crédito futuro em caixa presente
- Desalavancar o balanço (os recebíveis "saem" do ativo)
- Acesso a funding com custo competitivo (spread reflete o risco dos sacados, não do cedente)

**Para o investidor**:
- Rendimento acima do CDI com lastro em ativos reais
- Diversificação do portfólio de crédito privado
- Acesso a risco pulverizado (muitos sacados)

### 4.3 Estrutura de um FIDC

```
         Cedente (empresa)
              |
    Cessão dos direitos creditórios
              |
         [  FIDC  ]
        /          \
   Cota Sênior    Cota Subordinada
   (investidor     (cedente ou
    externo)        co-investidor)
```

#### Cotas

| Tipo | Quem compra | Característica |
|---|---|---|
| **Sênior** | Investidores externos | Prioridade de pagamento, menor risco, menor retorno |
| **Mezanino** | Investidores intermediários | Subordinada à sênior |
| **Subordinada** | Geralmente o próprio cedente | Absorve as primeiras perdas (skin in the game) |

A **subordinação mínima** é o percentual do patrimônio líquido que as cotas subordinadas devem representar. Ex: subordinação de 20% significa que os primeiros 20% de perdas da carteira são absorvidos pela cota subordinada antes de prejudicar a sênior.

### 4.4 Participantes do FIDC

| Participante | Função |
|---|---|
| **Cedente** | Vende os recebíveis ao fundo |
| **Administrador** | Responsável legal pelo fundo (CVM exige instituição autorizada) |
| **Gestor** | Toma decisões de investimento (análise e aquisição de recebíveis) |
| **Custodiante** | Guarda e valida os recebíveis (verificação de lastro) |
| **Agente de Cobrança** | Faz a régua de cobrança dos devedores inadimplentes |
| **Auditor** | Audita as demonstrações financeiras |
| **Agência de Rating** | Avalia risco de crédito das cotas sênior |
| **Distribuidor** | Distribui as cotas aos investidores |

### 4.5 Tipos de FIDC por originação

| Tipo | Recebíveis | Exemplos de cedente |
|---|---|---|
| **Performado** | Crédito já concedido, produto/serviço já entregue | Duplicatas, parcelas de cartão, CCB |
| **A performar** | Crédito ainda não performado (serviço futuro) | Mensalidades de escola, assinaturas |
| **Pulverizado** | Muitos sacados pequenos | Financeiras, fintechs de crédito |
| **Concentrado** | Poucos sacados grandes | Fornecedores de grandes varejistas/indústrias |

### 4.6 Tipos de recebíveis mais comuns

- **Duplicatas** (NF de compra e venda)
- **CCB** (Cédula de Crédito Bancário) — crédito pessoal, consignado, veículos
- **Precatórios**
- **Recebíveis de cartão**
- **CCI** (Cédula de Crédito Imobiliário)
- **Contratos de aluguel, mensalidades, utilities**

### 4.7 Processo de estruturação de um FIDC (passo a passo)

```
1. ORIGINAÇÃO DO MANDATO
   └─ Banco identifica cedente com volume de recebíveis
   └─ Análise preliminar: qualidade da carteira, histórico de inadimplência

2. DUE DILIGENCE DA CARTEIRA
   └─ Data tape: análise estatística dos recebíveis (vintage, PDD, concentração)
   └─ Visita operacional ao cedente
   └─ Auditoria de lastro (amostragem de NFs, CCBs etc.)

3. MODELAGEM FINANCEIRA
   └─ Projeção de fluxo de caixa da carteira
   └─ Stress test de inadimplência
   └─ Definição de subordinação mínima e gatilhos

4. RATING
   └─ Apresentação à agência
   └─ Q&A e ajuste de estrutura
   └─ Emissão da carta de rating

5. ELABORAÇÃO DO REGULAMENTO
   └─ Política de crédito (critérios de elegibilidade dos recebíveis)
   └─ Eventos de avaliação e liquidação antecipada
   └─ Critérios de substituição de recebíveis inadimplentes

6. REGISTRO CVM (se oferta pública)
   └─ Protocolo e aprovação

7. DISTRIBUIÇÃO
   └─ Roadshow e bookbuilding
   └─ Integralização das cotas

8. OPERAÇÃO CONTÍNUA
   └─ Cessão recorrente de novos recebíveis (FIDCs rotativos)
   └─ Relatórios mensais ao investidor
   └─ Gestão de inadimplência
```

### 4.8 Critérios de Elegibilidade

São as regras que determinam **quais recebíveis o cedente pode ceder ao FIDC**. Exemplos:

- Prazo máximo do recebível (ex: vencer em até 180 dias)
- Concentração máxima por sacado (ex: 5% do PL)
- Sacados não inadimplentes
- NFs com CNPJ válido e sem protestos
- Recebíveis originados no Brasil

### 4.9 Gatilhos (Eventos de Avaliação e Liquidação)

Métricas que, se violadas, disparam ações de proteção ao investidor:

| Gatilho | O que mede | Ação |
|---|---|---|
| Subordinação mínima | PL subordinado / PL total | Cessão de novas cotas subordinadas ou amortização sênior |
| Índice de inadimplência | % da carteira em atraso | Evento de avaliação → assembleia |
| Índice de liquidez | Caixa / obrigações de curto prazo | Restrição de novas aquisições |
| Concentração máxima | Exposição a 1 sacado / PL | Bloqueio de novos recebíveis do sacado |

### 4.10 FIDC vs. outras formas de antecipação

| Critério | Desconto bancário | CRI/CRA | FIDC |
|---|---|---|---|
| Setor | Qualquer | Imobiliário / Agro | Qualquer |
| Risco no balanço | Banco | Investidor | Investidor |
| Custo típico | CDI + 4-8% | CDI + 1-3% | CDI + 1.5-5% |
| Prazo | Curto | Longo | Médio/Longo |
| Estrutura | Simples | Complexa | Complexa |
| Volume mínimo | Pequeno | R$ 50M+ | R$ 20M+ |

### 4.11 Nova Regulação — Resolução CVM 175 (2023)

Principais mudanças relevantes:

- **Investidor de varejo pode acessar FIDC** (antes era restrito a qualificados)
- **Maior flexibilidade de estrutura** (cotas com diferentes direitos)
- **Mais rigor no custodiante** (verificação de lastro mais exigente)
- **FIDCs abertos** com liquidez diária passam a ser possíveis em certas condições
- **Segregação de administração e gestão** obrigatória em casos específicos

---

## Perguntas para Discussão em Aula

1. Por que uma empresa preferiria emitir uma debênture a pegar um empréstimo bancário?
2. Qual é o incentivo do cedente em manter as cotas subordinadas do FIDC?
3. Como o IB ganha dinheiro em cada etapa do processo?
4. O que acontece com um FIDC quando a inadimplência da carteira ultrapassa o esperado?
5. Por que o custo de capital de um FIDC pode ser menor do que o custo de crédito direto ao cedente?

---

*IB na Prática — Material de aula preparado em 21/06/2026*
