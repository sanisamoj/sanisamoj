# Olá, Pessoas! ☕

```javascript
import BackendDeveloper from "JoaoMario";

class AboutMe extends Developer {
    name = "João Mário";
    area = "Backend/Android Developer";
    work = "Searching";
    local = "Null";
}

class Skills extends Developer {
    Language = ["Javascript/Typescript", "Kotlin"];
    frameworks = [
        "Spring Boot", "Spring Web", "Spring Data JPA",
        "JUnit", "Ktor", "Fastify", "Express", "JWT", "Whatsapp-web.js"
    ];
    databases = ["Postgresql", "MongoDB", "Redis"]
}
```
Outra forma de enxergar o mundo...
```kotlin
data class AboutMe : Developer(
    val name: String = "João Mário",
    val area: String = "Backend/Android Developer",
    var work: String = "Searching",
    var local: String? = null
)

data class Skills : Developer(
    var language: MutableList<String> = mutableListOf("Javascript/Typescript", "Kotlin"),
    var frameworks: MutableList<String> = mutableListOf(
        "Spring Boot", "Spring Web", "Spring Data JPA", "JUnit",
        "Ktor", "Fastify", "Express", "JWT", "Whatsapp-web.js"
    ),
    var databases: MutableList<String> = mutableListOf("PostgreSQL", "MongoDB", "Redis")
)
```
## Sobre mim 👨🏻‍💻
Comecei a programar na pandemia, quando quis fazer um jogo na Unity. Foi aí que conheci o **C#**, uma linguagem orientada a objetos que me ensinou os fundamentos da programação.

Fui explorando outras áreas e me apaixonei pelo **Backend** com o **Nodejs**. Aprendi a criar API’s, implementar segurança nas rotas, organizar os projetos e outros conceitos pertinentes.

Hoje, estou enfrentando um novo desafio: *aprender uma nova linguagem de programação para ampliar meus conhecimentos*. Escolhi o **Kotlin**, Com o Kotlin, eu posso fazer API’s e aplicações robustas para servidores… e também para **Aplicatovos Android!**

## Formação 📚

- Técnologia em Análise e Desenvolvimento de Sistemas - Senac

## Projetos em Produção/Deploy 🚀

- [**API Loteria Federal**](https://www.loteriajogosapi.com/api/megasena/latest) - API que retorna todos os resultado dos jogos da loteria federal.

- [**Servidor de armazenamento de mídias**](https://www.sanisamojrepository.com/) - Servidor de armazenamento de mídias.

- [**BOT Medusa**](https://github.com/sanisamoj/Lily--web-bot.js) - Um bot de interação de grupos de whatsapp.

## Tecnologias/Conhecimentos 💻

- Linguagens: JavaScript | Typescript, Kotlin.
- Sistemas Operacionais: Windows/Linux
- Frameworks/API's com JS: Nodejs, Fastify, Express, ORM Prisma, Whatsapp-web.js , Reactjs, Redis, SocketIO, JsonWebToken, Mercado Pago, Asass, JEST.
- Frameworks/API's com Kotlin : SpringBoot, Data JPA, Ktor, JetPack Compose, MongoDB.
- Banco de dados: SQL (PostgreSQL) and noSQL (MongoDB)
- Cloud Services: Using AWS Ec2 service, and Microsoft Azure for personal projects.
- Certificados: Scrum e Manutenção de Hardwares.

## Contato 📞

[![Meu Linkedln](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joao-mario-silva-nascimento/) [![Meu E-mail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:marioartec39@gmail.com)

