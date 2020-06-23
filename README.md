
# Beanstalk - Queue
Beanstalk é um serviço de fila simples e rápido.
Sua interface é genérica, mas foi originalmente projetada para reduzir a latência das visualizações de página em aplicativos da Web de alto volume executando tarefas demoradas de forma assíncrona.

#### Iniciando Stack Dev
```
$ docker-compose up -d --build
```
### Acessando Beanstalk Console
http://localhost:2080

#### Configurando aplicação para usar o beanstalk
```
localhost:11300
beanstalkd.stack.dev:11300
```

#### Uso sem console
```
$ docker run -d -p 11300:11300 codeviewconsultoria/beanstalkd
```
