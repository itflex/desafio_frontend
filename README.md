## Desafio

### Objetivo

O desafio é criar uma aplicação de previsão do tempo, consumindo a [API de consulta da previsão do tempo do OpenWeatherMap](https://openweathermap.org/forecast5). A API é free, mas é necessário se [registrar](https://openweathermap.org/appid) para criar uma chave para usar a API. Favor **não incluir a sua chave no repositório**, por motivos de segurança.


Deve ser possivel pesquisar a previsão do tempo para uma cidade pelo nome da cidade.
Devem ser exibidos os seguintes items na previsão:

* A previsão dos próximos 5 dias (utilizando a API de consulta da previsão)
* Temperatura mínima e máxima de cada dia
* Status da previsão (nublado, ensolarado, etc)
* Umidade (percentual)

O visual e as formas de interação com o webapp também serão utilizados como parte da avaliação.
O mapeamento dos códigos de status da previsão podem ser vistos [aqui](https://openweathermap.org/weather-conditions).

### Requisitos

* A interface deve ser responsiva (desktop e mobile)
* Utilizar Material Design
* Utilizar algum framework SPA (Single Page Application)
  * A nossa stack é VueJS, mas pode ser feita em react ou angular
* Utilizar padrão FLUX (VUEX/REDUX) é um diferencial
* Componentização do código também é um diferencial
* Código com TEST (TDD)
* Criar um repositório no github com o código da aplicação
* Subir a aplicação em alguma plataforma (Exemplo Heroku)
* Descrever no README como subir a aplicação

### Diferencial

* Adicionar validações
* Utilizar JavaScript es6+
* Utilizar LINTER
* Criar um pequeno CI/CD para o TDD e Linter

### Plus
* Salvar cidades favoritas (em memória, não é necessário ser permanente)
* Exibir as informações de tempo atuais utilizando a [API específica](https://openweathermap.org/current)


