# API Demo - Spring Boot
Estou estudando Spring Boot e desenvolvi este projeto para praticar meus conhecimentos. Qualquer feedback ou sugestão será muito bem-vindo.

### Tecnologias
- Java 17
- Spring Boot 3.3.3
- maven

### Requisitos
- Uma IDE (preferencialmente IntelliJ IDEA)
- Java 17 instalado
- Maven instalado

### Configuração Inicial
Não é necessário configurar nada antes de rodar o projeto. As credenciais de autenticação estão definidas em memória.

### Como Rodar Localmente:
1. **Clone o repositório:**
```bash
git clone https://github.com/marcola-dev/api-demo.git
```
2. **Navegue até o diretório do projeto:**
```bash
cd api-demo
```
3. **Gere o arquivo JAR:**
```bash
mvn clean package
```
4. **Execute a aplicação:**
```bash
java -jar target/api-demo-0.0.1-SNAPSHOT.jar
```

- A aplicação será iniciada e estará disponível em [http://localhost:8080](http://localhost:8080).

### Uso Básico
- Acesse a página de login em [http://localhost:8080/login](http://localhost:8080/login) com o usuário padrão `user` e a senha `user123`.
- Após o login, você será redirecionado para a página inicial `/home`.

### Contribuição
Se você encontrar problemas ou tiver sugestões de melhorias, sinta-se à vontade para abrir um problema ou enviar uma solicitação de pull.

---

Sinta-se à vontade para ajustar quaisquer seções ou adicionar detalhes adicionais conforme necessário!
