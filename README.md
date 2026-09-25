# 🚚 LogiFlow — Controle Logístico Inteligente

> **Dashboard web para acompanhamento de entregas, frota e desempenho de transportadoras.**

O **LogiFlow** é um protótipo de aplicação web desenvolvido para demonstrar uma solução de gestão logística com foco em **visibilidade operacional, indicadores, segurança e apoio à tomada de decisão**.

O projeto foi inicialmente prototipado no **Lovable** e posteriormente convertido para uma versão independente em **HTML, CSS e JavaScript**, permitindo sua execução diretamente no navegador, sem necessidade de instalação de dependências.

---

## 🎯 Objetivo do projeto

Empresas que trabalham com entregas e transporte precisam acompanhar diferentes informações operacionais, como:

- Entregas em andamento;
- Atrasos;
- Desempenho das rotas;
- Frota disponível;
- Desempenho das transportadoras;
- Indicadores de pontualidade;
- Eventos que exigem atenção;
- Controle de acesso às informações.

O **LogiFlow** reúne essas informações em uma interface única, permitindo uma visão executiva da operação.

---

## 💡 Proposta de valor

A proposta do LogiFlow é transformar informações logísticas em uma visão simples e acionável:

**Dados → Indicadores → Insights → Decisão**

O dashboard permite acompanhar os principais indicadores e identificar rapidamente situações que merecem atenção.

---

## 🖥️ Funcionalidades

### 📊 Dashboard

O dashboard apresenta uma visão geral da operação, incluindo:

- OTD (On-Time Delivery);
- Entregas ativas;
- Frota monitorada;
- Número de atrasos;
- Performance das entregas;
- Status da operação;
- Entregas críticas;
- Insights operacionais.

### 🚚 Entregas

Área destinada ao acompanhamento dos pedidos logísticos.

Informações apresentadas:

- Número do pedido;
- Origem;
- Destino;
- Data;
- Transportadora;
- Status da entrega.

Status utilizados no protótipo:

- 🟡 Em trânsito;
- 🟢 Entregue;
- 🔴 Atrasado.

### 🚛 Frota

Área para acompanhamento dos veículos monitorados.

Indicadores:

- Veículos ativos;
- Veículos em rota;
- Veículos disponíveis;
- Veículos em manutenção.

Também são apresentados dados fictícios de veículos, motoristas e rotas.

### 🏢 Transportadoras

Permite visualizar indicadores de desempenho dos parceiros logísticos.

Métricas demonstradas:

- Número de entregas;
- OTD;
- Quantidade de atrasos;
- Situação em relação à meta.

### 🛡️ Central de Segurança

O projeto também contempla uma camada conceitual de segurança.

Funcionalidades demonstradas:

- Autenticação;
- Perfis de acesso;
- Controle de permissões;
- Registro de atividades;
- Alertas de segurança;
- Bloqueio de acesso fora do perfil autorizado.

### 📁 Dados

Área destinada à gestão da base utilizada pelos indicadores.

O protótipo demonstra:

- Dataset operacional;
- Quantidade de registros;
- Quantidade de colunas;
- Data de atualização;
- Estrutura dos dados;
- Validação e importação simulada.

---

# 🤖 Aplicação de IA

O projeto foi pensado para evoluir para um **Copiloto de Inteligência Artificial aplicado à logística**.

Na versão demonstrativa atual, a interface apresenta insights operacionais contextualizados.

Exemplos:

> 💡 Uma determinada rota concentra parte dos atrasos atuais.

> 📈 Uma rota com alto OTD pode servir como referência para outras operações.

A evolução planejada é permitir que o usuário converse diretamente com os dados utilizando linguagem natural.

### Exemplos de perguntas futuras

```text
Por que os atrasos aumentaram?

Quais rotas apresentam maior risco operacional?

Qual transportadora apresenta melhor desempenho?

Quais entregas precisam de atenção?

Quais regiões possuem maior índice de atraso?

Que ações poderiam melhorar o OTD?
