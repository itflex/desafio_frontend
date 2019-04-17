# Desafio Frontend iTFLEX Tecnologia

O desafio é criar uma aplicação de previsão do tempo, consumindo a [API de consulta da previsão do tempo do OpenWeatherMap](https://openweathermap.org/forecast5). A API é free, mas é necessário se [registrar](https://openweathermap.org/appid) para criar uma chave para usar a API. Favor **não incluir a sua chave no repositório**, por motivos de segurança.

A interface deve ser responsiva (desktop e mobile), deve utilizar Material Design e permitir
pesquisar a previsão do tempo para uma cidade pelo nome da cidade. Devem ser exibidos os seguintes
items na previsão:

- A previsão dos próximos 5 dias (utilizando a API de consulta da previsão)
- Temperatura mínima e máxima de cada dia
- Status da previsão (nublado, ensolarado, etc)
- Umidade (percentual)

O visual e as formas de interação com o webapp também serão utilizados como parte da avaliação.
O mapeamento dos códigos de status da previsão podem ser vistos [aqui](https://openweathermap.org/weather-conditions).

Requisitos:

- Utilizar Material Design
- Utilizar algum framework SPA (Single Page Application)
  - Preferencialmente com VueJS, mas não é obrigatório
- Criar um repositório no github com o código da aplicação
- Descrever no README como subir a aplicação

Para ganhar alguns pontos extras, podem ser implementadas as funcionalidades abaixo:

- Autocompletar com as capitais do Brasil
- Salvar cidades favoritas (em memória, não é necessário ser permanente)
- Exibir as informações de tempo atuais utilizando a [API específica](https://openweathermap.org/current)
- Testes de código
