O projeto mychart deve possuir uma aplicação criada com helm:

- O nome do chart deve ser exam-chart
- A versão do chart deve ser 0.3.2
- A imagem deve ser docker.io/leandropantoja/cars-api
- A versão da imagem deve ser 3.0
- A porta do container deve ser 8080
- A porta do serviço deve ser 8080
- A aplicação deve ter 2 réplicas
- O liveness probe de usar a porta 8080 no contexto /cars/isAlive
- O readness probe de usar a porta 8080 no contexto /cars/list

Sua aplicação deve responder na seguinte URL:

http://cars-api-mychart.apps.desenv.com/cars/list
