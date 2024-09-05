<p align="center">
<h3 align="center">AWS Step Functions</h3>
Este projeto é um desafio do curso Nexa - Engenharia de Prompts na AWS com Claude, cujo objetivo é explorar as funcionalidades da AWS Step Functions e Amazon Bedrock para criação de um assistente de delivery. Neste caso, este README aborda as ferramentas utilizadas, o problema que se propõe resolver, os benefícios oferecidos, além de outras curiosidades que foram parte do processo de aprendizagem nessa seção do curso.
</p>

## 📋 Índice

- [❓ O que é o AWS Step Functions?](#-o-que-é-o-aws-step-functions)
- [🎯 Qual o problema se propõe resolver?](#-qual-o-problema-se-propõe-resolver)
- [🧑🏽‍💻 Benefícios](#-benefícios)
- [👏🏽 Possíveis usos](#-possíveis-usos)
- [🧑🏽‍💼 Workflow Studio](#-workflow-studio)
- [📔 Exemplo da aula](#-exemplo-da-aula)

## ❓ O que é o AWS Step Functions?

É uma ferramenta de orquestração de serviços distribuídos que permite aos desenvolvedores criarem aplicativos através da coordenação de componentes de aplicativos e microsserviços usando um fluxo de trabalho visual. O Step Functions permite que se possa criar aplicações sem escrever código, bem como facilitar o gerenciamento dos microsserviços, administração de erros e automatização de fluxos de trabalho com outros produtos AWS.

## 🎯 Qual o problema se propõe resolver?

O Step Functions foi projetado para resolver diversos problemas, em especial aqueles relacionados à coordenação, automação e escalabilidade de processos complexos. Alguns problemas comumente percebidos na criação de aplicações e facilitados pelo Step Functions são:

- **Coordenação de serviços distribuídos**: O AWS Step Functions permite definir e executar fluxos de trabalho com uma série de etapas, garantindo que as dependências entre os serviços sejam gerenciadas de forma eficiente e confiável.

- **Automação de Processos Complexos**: É possível modelar fluxos de trabalho complexos usando a linguagem ASL (Amazon States Language), facilitando a automação e visualização do fluxo de execução.

- **Gerenciamento de Estado**: Os passos de cada fluxo de trabalho são gerenciados automaticamente pelo Step Functions, permitindo que os desenvolvedores não se preocupem com o rastreamento manual de cada estado.

## 🧑🏽‍💻 Benefícios

- **Integração rápida**: Desenvolver aplicações rapidamente usando o Workflow Studio, uma interface simples com o recurso de arrastar e soltar para expressar lógicas de negócios complexas.

- **Automação simples**: Automatize fluxos de trabalho em mais de 220 produtos da AWS sem necessidade de manutenção de código e mais de 10 mil APIs.

- **Processamento de dados sob demanda**: Use código para processar dados sob demanda com fluxos de trabalho paralelos de grande escala.

- **Visualização de arquitetura orientada por eventos**: Visualize e desenvolva fluxos de trabalho flexíveis para arquiteturas orientadas a eventos.

Fonte: [AWS Step Functions](https://aws.amazon.com/pt/step-functions/)

## 👏🏽 Possíveis usos

- **Processamento de dados**: Ex.: Pipeline de ETL

- **Machine learning**: Ex.: Treinamento de modelos

- **Orquestração de microsserviços**: Ex.: Processamento de pedidos no e-commerce

- **Automação de TI e Segurança**: Ex.: Resposta a incidentes de segurança

## 🧑🏽‍💼 Workflow Studio

Um workflow ou fluxo de trabalho é uma sequência de tarefas ou passos organizados para alcançar um objetivo específico. No AWS Step Functions, um workflow é chamado de "state machine" (máquina de estados). Ele modela o processo de execução como uma série de estados, onde cada estado representa uma etapa no fluxo de trabalho.

Componentes de um Workflow no Step Functions:

- **Estados**: Uma etapa do workflow; os mais comuns incluem task, choice, parallel, etc.
- **Transições**: Define como o workflow avança de um estado para o outro.
- **Entradas e Saídas**: Cada estado pode receber uma entrada (dado) e produzir uma saída, que é passada para o próximo estado.
- **Tratamento de erros**: Mecanismos nativos para lidar com falhas e exceções em cada estado.

## 📔 Exemplo da aula

Na aula do curso, foi mostrado o uso do AWS Step Functions e Amazon Bedrock para o desenvolvimento de um assistente de delivery usado para indicar sugestões de como fazer um jantar romântico.

1° prompt: "Estou programando um jantar romântico, nesse jantar irei pedir um macarrão. Me dê uma lista de três itens que combinam em uma experiência gastronômica."
2º prompt: "Liste duas bebidas que acompanhem um jantar romântico."
3° prompt: "Liste um lugar perfeito para um jantar romântico em Paris."
