# Olá, Pessoas! ☕

```javascript
import BackendDeveloper from "JoaoMario";

class AboutMe extends Developer {
    name = "João Mário";
    area = "Backend/Android Developer";
    work = "D&OSistemas";
    local = null;
}

class Skills extends Developer {
    language = ["Javascript/Typescript", "Kotlin"];
    frameworks = [
        "Spring Boot", "Spring Web", "Spring Data JPA",
        "JUnit", "Ktor", "Fastify", "Express", "JWT", "Whatsapp-web.js"
    ];
    databases = ["PostgreSQL", "MongoDB", "Redis"];
}
```
Outra forma de enxergar o mundo...
```go
package main

import "fmt"

type AboutMe struct {
	Name string
	Area string
	Work string
	Local *string
}

type Skills struct {
	Language   []string
	Frameworks []string
	Databases  []string
}

func main() {
	joaoMarioAbout := AboutMe{
		Name: "João Mário",
		Area: "Backend/Android Developer",
		Work: "D&OSistemas",
		Local: nil,
	}

	joaoMarioSkills := Skills{
		Language: []string{"Javascript/Typescript", "Kotlin"},
		Frameworks: []string{
			"Spring Boot", "Spring Web", "Spring Data JPA",
			"JUnit", "Ktor", "Fastify", "Express", "JWT", "Whatsapp-web.js",
		},
		Databases: []string{"PostgreSQL", "MongoDB", "Redis"},
	}

	fmt.Println("--- Sobre Mim ---")
	fmt.Printf("Nome: %s\n", joaoMarioAbout.Name)
	fmt.Printf("Área: %s\n", joaoMarioAbout.Area)
	fmt.Printf("Trabalho: %s\n", joaoMarioAbout.Work)
	if joaoMarioAbout.Local != nil {
		fmt.Printf("Local: %s\n", *joaoMarioAbout.Local)
	} else {
		fmt.Println("Local: (não especificado)")
	}

	fmt.Println("\n--- Habilidades ---")
	fmt.Printf("Linguagens: %v\n", joaoMarioSkills.Language)
	fmt.Printf("Frameworks: %v\n", joaoMarioSkills.Frameworks)
	fmt.Printf("Bancos de Dados: %v\n", joaoMarioSkills.Databases)

	joaoMarioSkills.Language = append(joaoMarioSkills.Language, "Go")
	fmt.Printf("Linguagens (após adição): %v\n", joaoMarioSkills.Language)
}
```

## Sobre mim 👨🏻‍💻
Comecei a programar na pandemia, quando quis fazer um jogo na Unity. Foi aí que conheci o **C#**, uma linguagem orientada a objetos que me ensinou os fundamentos da programação.

Fui explorando outras áreas e me apaixonei pelo **Backend** com o **Nodejs**. Aprendi a criar API’s, implementar segurança nas rotas, organizar os projetos e outros conceitos pertinentes. Também encontrei
o ambiente Java/Kotlin que me agregaram outros conceitos.

Hoje, estou enfrentando um novo desafio: *aprender mais uma nova linguagem de programação para ampliar meus conhecimentos*. Escolhi o **Golang**, no qual tenho criado scripts e alguns projetos com a linguagem.
Também surgiu o interesse por cybersecurity, como testes de penetração, defesa, criptografia, conceitos Zero Knowledge e por ai vai....

## Projetos públicos em Deploy 🌎

- [Briefly](https://briefly.top/) - Encurtador de links.
- [Media-Repository](https://www.sanisamojrepository.com/image-repo/media?media=aQgM8v1OW7lMXJOioZovqqwPC9e1w3hT2P8r-giphy2.webp) - Repositório de mídias.
- LemBrago - Gerenciador e compartilhador de senhas criptografado com E2EE (criptografia de ponta a ponta).
  - [Repositório](https://github.com/sanisamoj/LBRAGO)
  - [Página para download](https://lembrago.sanisamojrepository.com/)

## Formação 📚

- Técnologia em Análise e Desenvolvimento de Sistemas - Senac

## Tecnologias/Conhecimentos 💻

- Linguagens: JavaScript | Typescript, Kotlin e GO.
- Sistemas Operacionais: Windows/Linux
- Runtime/Frameworks/API's com JS: Nodejs, Deno, Fastify, Express, Hono, ORM Prisma, Whatsapp-web.js , Reactjs, NextJs, SocketIO, Mercado Pago, Asass, JEST, Redux, Tailwind.
- Frameworks/API's com Kotlin : SpringBoot, Data JPA, Ktor, JetPack Compose, MongoDB, Redis, Kotlin Multiplatform, RabbitMQ.
- Ferramentas: Docker, Docker-compose, Kubernetes, Jira e Ngnix.
- Banco de dados: SQL (PostgreSQL) and noSQL (MongoDB E Redis)
- Cloud Services: Using AWS Ec2 service, and Microsoft Azure for personal projects.
- Certificados: Scrum e Manutenção de Hardwares.

## Contato 📞

[![Meu Linkedln](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joao-mario-silva-nascimento/) [![Meu E-mail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:marioartec39@gmail.com)

