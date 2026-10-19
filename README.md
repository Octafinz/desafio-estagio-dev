# Desafio técnico | Estágio em Desenvolvimento

**Simulador de Empréstimo Consignado** · Startup de tecnologia financeira

## 1. Contexto e objetivo

Desenvolva um MVP de uma aplicação que permita a um cliente solicitar uma simulação de empréstimo consignado e consultar o resultado da avaliação em diferentes bancos.

O foco é a construção de um serviço que consome e interpreta respostas de serviços de terceiros.

## 2. Requisitos mínimos

- **Entrada de dados:** nome, e-mail, CPF, salário, CNPJ do empregador e outros campos que considerar pertinentes.
- **Avaliação bancária:** simular chamadas a APIs externas de pelo menos dois bancos, com respostas de aprovação ou reprovação.
- **Processamento:** interpretar, consolidar e apresentar o resultado individual de cada instituição financeira.
- **Interface:** permitir realizar a simulação e visualizar os resultados de forma compreensível.

## 3. Liberdade de implementação

Você pode utilizar qualquer linguagem e framework, preferencialmente **TypeScript**.

O uso consciente de ferramentas de IA é permitido, desde que você compreenda e saiba explicar sua solução.

Não serão fornecidos protótipos, arquitetura ou componentes visuais. Utilize apenas dados fictícios; não são necessárias APIs bancárias reais.

### Espaço para propor

Os requisitos da seção 2 são o ponto de partida, não o teto. Queremos ver o que você faria se este produto fosse seu.

Um caminho para pensar: coloque-se no lugar de quem usa e de quem depende deste serviço. De um lado, o cliente, que preenche os dados e fica esperando a resposta. Do outro, a empresa, que depende de bancos que ela não controla.

No `README.md`, apresente cada proposta assim:

1. **Problema:** o que você identificou.
2. **Proposta:** o que você fez ou faria.
3. **Por quê:** o que isso muda para o cliente ou para a operação.

Separe o que foi **implementado** do que ficou só **planejado**. As planejadas vão em **ordem de prioridade**: o que você faria primeiro se tivesse mais uma semana.

Avaliamos a coerência das propostas com o problema, não a quantidade. Uma proposta bem justificada vale mais do que dez soltas.

## 4. Critérios de avaliação (100 pontos)

| Critério | Pontos |
| --- | :-: |
| **Arquitetura:** estrutura da solução, separação de responsabilidades e desenho das integrações. | 30 |
| **Controle e qualidade do código:** organização, legibilidade, validações e tratamento de falhas. | 30 |
| **Implementação funcional:** execução da simulação, consumo das APIs simuladas e exibição dos resultados. | 20 |
| **Capacidade propositiva:** melhorias coerentes além do mínimo, considerando usabilidade, segurança, qualidade ou infraestrutura. | 20 |

## 5. Entrega

Disponibilize o código em um repositório Git com um `README.md` contendo:

- instruções de execução;
- decisões técnicas;
- limitações.

Descreva também as melhorias e proposições realizadas ou planejadas para o contexto do problema, explicando como facilitam o uso pelo cliente ou ampliam a segurança, a qualidade e a infraestrutura do serviço, no formato descrito em **Espaço para propor**.

### Prazo

**5 dias corridos**, contados a partir do recebimento deste desafio.

### Como enviar

Envie o link do seu repositório para **elias.santos@octafin.com.br** com o assunto **"Estágio Dev"**.

Crie o seu próprio repositório: não abra pull request neste aqui, para que a sua solução não fique visível para os outros candidatos.

---

> **Lembre-se:** este é um MVP com o simples propósito de avaliar suas habilidades dentro do contexto da nossa operação. Não se preocupe em entregar um produto completo, integrar bancos reais ou montar uma infraestrutura complexa. Priorize uma solução funcional, clara, bem estruturada e que você consiga explicar.
