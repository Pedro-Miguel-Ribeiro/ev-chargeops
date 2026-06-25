# EV ChargeOps

## Integrante

- Pedro Miguel Ribeiro – RM 569768

---

# Enterprise Challenge 2026 – GoodWe

## Descrição do Problema

Com o crescimento dos veículos elétricos, condomínios, empresas e universidades passaram a utilizar carregadores compartilhados. Entretanto, muitos desses locais não possuem sistemas capazes de identificar usuários, medir o consumo individual e realizar cobranças justas.

Dessa forma, surge a necessidade de uma plataforma capaz de gerenciar as sessões de recarga, organizar os dados gerados e fornecer informações úteis para usuários e gestores.

---

## Objetivo da Solução

Desenvolver uma plataforma chamada **EV ChargeOps**, capaz de:

- Registrar sessões de recarga;
- Identificar usuários;
- Calcular o consumo individual;
- Realizar o rateio automático da energia;
- Gerar relatórios;
- Utilizar Inteligência Artificial para análise dos dados.

---

# Frente 1 – Contexto e Problema

## Contexto

Nos últimos anos, o mercado de veículos elétricos apresentou um crescimento significativo no Brasil e no mundo. Com isso, aumentou também a necessidade de infraestrutura de recarga em condomínios, empresas e instituições de ensino.

Em muitos desses ambientes, os carregadores são compartilhados entre vários usuários, gerando dificuldades no controle de consumo e na divisão dos custos de energia.

## Problema Identificado

Os principais problemas encontrados são:

* Falta de identificação dos usuários que realizam as recargas;
* Dificuldade em medir o consumo individual de energia;
* Ausência de um sistema de rateio automático;
* Falta de relatórios e indicadores de utilização;
* Dificuldade na gestão dos carregadores compartilhados.

## Proposta de Solução

O projeto EV ChargeOps propõe o desenvolvimento de uma plataforma capaz de registrar as sessões de recarga, armazenar informações de consumo, gerar relatórios e utilizar Inteligência Artificial para fornecer análises e previsões sobre o uso dos carregadores.


---

# Frente 2 – Base Técnica e Regulatória

## Resolução Normativa ANEEL nº 1.000/2021

A Resolução Normativa nº 1.000/2021 da ANEEL estabelece as condições gerais para o fornecimento de energia elétrica no Brasil. Em relação aos veículos elétricos, a norma permite a instalação de infraestrutura de recarga e a exploração comercial do serviço, desde que sejam observadas as exigências da distribuidora de energia e as normas técnicas vigentes.

A regulamentação também incentiva o uso de tecnologias que permitam a medição individualizada do consumo e o monitoramento das sessões de recarga, fatores essenciais para o funcionamento da plataforma EV ChargeOps.

---

## Carregador GoodWe HCA G2

O carregador GoodWe HCA G2 possui diversas interfaces de comunicação que possibilitam a integração com sistemas de gerenciamento.

| Interface | Função                                                   |
| --------- | -------------------------------------------------------- |
| Wi-Fi     | Comunicação com a internet e envio de dados para a nuvem |
| LAN       | Conexão por rede cabeada                                 |
| Bluetooth | Configuração local do equipamento                        |
| RFID      | Identificação e autenticação de usuários                 |
| RS-485    | Comunicação com outros equipamentos e sistemas externos  |

Essas interfaces permitem que os dados das sessões de recarga sejam coletados e utilizados pela plataforma.

---

## API GoodWe (SEMS Portal)

A API do SEMS Portal disponibiliza informações importantes para o gerenciamento do carregador, como:

* Status do carregador;
* Potência instantânea;
* Energia consumida;
* Histórico de sessões;
* Eventos e registros de operação.

Esses dados podem ser utilizados pelo EV ChargeOps para gerar relatórios, calcular o rateio de energia e alimentar os modelos de Inteligência Artificial.

---

## Opção de Aprofundamento Escolhida

### Exploração da API GoodWe

A plataforma utilizará a API do SEMS Portal para coletar automaticamente os dados de carregamento.

Os principais dados utilizados serão:

* Identificação da sessão;
* Horário de início e término;
* Energia consumida (kWh);
* Potência de carregamento;
* Identificação do usuário.

Essas informações serão armazenadas em banco de dados e utilizadas para geração de faturas e análises inteligentes.


---

# Frente 3 – Arquitetura e IA

(Esta seção será preenchida após as pesquisas.)

---

# Plano da Sprint 2

(Esta seção será preenchida após as pesquisas.)

---

# Referências

(Esta seção será preenchida ao final do projeto.)
