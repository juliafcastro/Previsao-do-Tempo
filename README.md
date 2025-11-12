# 🌦️ Previsão do Tempo

![Badge](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Badge](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Badge](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Badge](https://img.shields.io/badge/OpenWeather-API-FF6F00?style=for-the-badge&logo=openweathermap&logoColor=white)
![Badge](https://img.shields.io/badge/license-MIT-blue.svg)

> Uma aplicação simples para consultar o clima de qualquer cidade em tempo real, utilizando a API da OpenWeatherMap.

## ✨ Funcionalidades

* **Pesquisa por Cidade:** Permite ao usuário digitar o nome de uma cidade e buscar os dados climáticos.
* **Dados em Tempo Real:** Exibe a temperatura atual (em Celsius), a descrição do tempo (ex: "Céu limpo") e a umidade.
* **Ícones Dinâmicos:** Mostra um ícone que representa visualmente a condição climática atual.

## 🛠 Tecnologias Utilizadas

* **HTML5:** Estrutura da aplicação.
* **CSS3:** Estilização (incluindo Flexbox, opacidade e imagem de fundo).
* **JavaScript (Vanilla):** Utilizado para:
    * Capturar eventos de clique.
    * Fazer chamadas `async/await` para a API.
    * Manipular o DOM para exibir os dados na tela.
* **OpenWeatherMap API:** Fonte dos dados de previsão do tempo.

## 🏃 Como Rodar o Projeto

### 🔑 Chave da API

Para que este projeto funcione, você precisa de uma chave (key) da API da OpenWeatherMap.

1.  Crie uma conta gratuita no site [OpenWeatherMap](https://openweathermap.org/price).
2.  Obtenha sua chave de API no seu painel de controle.
3.  No arquivo `script.js`, substitua o valor da variável `key` pela sua chave:

```javascript
const key = "SUA_CHAVE_API_VEM_AQUI";
```

### Rodando Localmente

Como é um projeto front-end puro, basta clonar e abrir o `index.html`:

```bash
# 1. Clone este repositório
$ git clone [URL_DO_REPOSITORIO]

# 2. Acesse a pasta do projeto
$ cd [NOME_DO_PROJETO]

# 3. Abra o arquivo 'index.html' no seu navegador
```

## 📄 Licença

Este projeto está sob a licença MIT.



# 🌦️ Weather App

![Badge](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Badge](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Badge](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Badge](https://img.shields.io/badge/OpenWeather-API-FF6F00?style=for-the-badge&logo=openweathermap&logoColor=white)
![Badge](https://img.shields.io/badge/license-MIT-blue.svg)

> A simple application to check the real-time weather for any city using the OpenWeatherMap API.

## ✨ Features

* **Search by City:** Allows the user to type a city name and fetch weather data.
* **Real-Time Data:** Displays the current temperature (in Celsius), weather description (e.g., "Clear sky"), and humidity.
* **Dynamic Icons:** Shows an icon that visually represents the current weather condition.

## 🛠 Tech Stack

* **HTML5:** Application structure.
* **CSS3:** Styling (including Flexbox, opacity, and background images).
* **JavaScript (Vanilla):** Used for:
    * Capturing click events.
    * Making `async/await` calls to the API.
    * Manipulating the DOM to display data on the screen.
* **OpenWeatherMap API:** Source of the weather forecast data.

## 🏃 Getting Started

### 🔑 API Key

For this project to work, you need an API key from OpenWeatherMap.

1.  Create a free account on the [OpenWeatherMap](https://openweathermap.org/price) website.
2.  Get your API key from your dashboard.
3.  In the `script.js` file, replace the value of the `key` variable with your own key:

```javascript
const key = "YOUR_API_KEY_GOES_HERE";
```

### Running Locally

Since this is a pure front-end project, just clone and open the `index.html`:

```bash
# 1. Clone this repository
$ git clone [REPOSITORY_URL]

# 2. Navigate to the project folder
$ cd [PROJECT_NAME]

# 3. Open the 'index.html' file in your browser
```

## 📄 License

This project is licensed under the MIT License.
