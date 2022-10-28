# Shiny Agency

[🇺🇸] English Version

This repo contains the API code you'll need for the Shiny Agency application for the OpenClassrooms course ------.
It goes hand in hand with [the frontend repository](https://github.com/Wayd26/shiny-agency.git).

## Run the API locally

To take the course, you will need to install the API locally on your machine. To do this:
1. Make a `git clone https://github.com/Wayd26/shiny-agency-backend.git`
2. Install the `node_modules` with `yarn`.
3. Run the API with `yarn start`.


## Consume the API locally
Once launched, this API provides you with several routes:

- The route to get the freelancers profiles:
`GET /freelances`

- The route to get the details of a freelance profile:
`GET /profile/?id={id}`

- The route to get the survey:
`GET /survey/`

- The route to get the result of the survey:
`GET /results/?a1={answer1}&a2={answer2}&a3={answer3}...`


## Consuming the online API

- The route to get the freelancers' profiles:
`GET https://shiny-agency-backend.herokuapp.com/freelances`

- The route to get the details of a freelance profile:
GET https://shiny-agency-backend.herokuapp.com/profile/?id={id}`

- The route to get the survey:
`GET https://shiny-agency-backend.herokuapp.com/survey/`

- The route to get the result of the survey:
`GET https://shiny-agency-backend.herokuapp.com/results/?a1={answer1}&a2={answer2}&a3={answer3}...`


===============================================================================================================


[🇫🇷] Version Française
Ce repo contient le code de l'API dont vous aurez besoin pour l'application Shiny Agency du cours de OpenClassrooms ------.
Il va de paire avec [le repository de la partie frontend](https://github.com/Wayd26/shiny-agency.git).

## Lancer l'API en local

Pour suivre le cours, vous aurez besoin d'installer l'API en local sur votre machine. Pour cela :
1. Faites un `git clone https://github.com/Wayd26/shiny-agency-backend.git`
2. Installez les `node_modules` avec `yarn`
3. Faites tourner l'API avec `yarn start`


## Consommer l 'API en local
Une fois lancée, cette API met plusieurs routes à votre disposition :

- La route pour récupérer les profils des freelances :
`GET /freelances`

- La route pour avoir le détail d'un profil de freelance :
`GET /profile/?id={id}`

- La route pour avoir le questionnaire :
`GET /survey/`

- La route pour obtenir le résultat du questionnaire :
`GET /results/?a1={answer1}&a2={answer2}&a3={answer3}...`


## Consommer l 'API en ligne

- La route pour récupérer les profils des freelances :
`GET https://shiny-agency-backend.herokuapp.com/freelances`

- La route pour avoir le détail d'un profil de freelance :
`GET https://shiny-agency-backend.herokuapp.com/profile/?id={id}`

- La route pour avoir le questionnaire :
`GET https://shiny-agency-backend.herokuapp.com/survey/`

- La route pour obtenir le résultat du questionnaire :
`GET https://shiny-agency-backend.herokuapp.com/results/?a1={answer1}&a2={answer2}&a3={answer3}...`

