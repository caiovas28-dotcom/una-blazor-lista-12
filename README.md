# EcoMonitor

Projeto desenvolvido para a disciplina de Interação Humano-Computador e UX.

O EcoMonitor é uma aplicação desenvolvida em Blazor que simula um sistema de gamificação de ações sustentáveis. O usuário acumula pontos ao realizar diferentes atividades ambientais.

## Identificação

- Nome: Caio Duraes Vasconcelos
- RA: 325132875
- Curso: Análise e Desenvolvimento de Sistemas
- Instituição: Centro Universitário UNA

## Como executar o projeto

Pré-requisitos:
- .NET SDK instalado

Executar o projeto:

dotnet run --launch-profile https

Acessar no navegador:
https://localhost:7122

## Estrutura do projeto

- Home.razor: página principal onde os componentes são exibidos
- EcoStatus.razor: componente reutilizável responsável pelo sistema de pontuação

## Explicação técnica

O projeto utiliza componentes reutilizáveis no Blazor.

O componente EcoStatus recebe dados via parâmetros utilizando o atributo [Parameter], permitindo reutilização com diferentes valores.

Exemplo:

<EcoStatus Titulo="Reciclagem de Plástico" Peso="1" />

## Heurísticas de Nielsen aplicadas

1. Visibilidade do status do sistema  
O sistema fornece feedback imediato ao usuário ao atualizar os pontos em tempo real após cada interação.

2. Feedback do usuário  
O usuário recebe resposta instantânea ao clicar nos botões, reforçando a ação realizada.

3. Consistência e padrões  
Todos os componentes seguem uma estrutura visual e comportamental consistente, facilitando o uso da interface.

## Funcionalidades

- Registro de ações sustentáveis
- Sistema de pontuação dinâmico
- Componentes reutilizáveis
- Atualização em tempo real dos dados
