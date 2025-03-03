<h1 align="center">Microservices</h1>

https://github.com/user-attachments/assets/22274e6b-142d-4179-908e-f578dab90f76

<p align="center">
  <img alt="atividade microservices" src="microservices-java.png" width="100%">
</p>

`POST` - http://localhost:8081/users

```json
{
  "name": "Eduardo",
  "email": "eduardo.augustopp@gmail.com"
}
```

## ⚠️ Problema enfrentado

`Ainda não consegui descobrir porque não está chegando o email na caixa de entrada.`

https://customer.cloudamqp.com/login

Para criar a senha app: https://support.google.com/accounts/answer/185833

    server.port=8082

    spring.datasource.url=jdbc:postgresql://localhost:5432/ms-email
    spring.datasource.username=postgres
    spring.datasource.password=banco123
    spring.jpa.hibernate.ddl-auto=update

    spring.rabbitmq.addresses= amqps://coztduhu:nMqrQJfqVT1rdWLutld8p7VmwO-zN5yr@seal.lmq.cloudamqp.com/coztduhu

    broker.queue.email.name=default.email

    spring.mail.host=smtp.gmail.com
    spring.mail.port=587
    spring.mail.username=eduardo.augustopp@gmail.com
    spring.mail.password=
    spring.mail.properties.mail.smtp.auth=true
    spring.mail.properties.mail.smtp.starttls.enable=true

---

<div>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original-wordmark.svg" width="40" height="40"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original-wordmark.svg" width="40" height="40"/>     
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original-wordmark.svg" width="40" height="40"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rabbitmq/rabbitmq-original-wordmark.svg" width="40" height="40"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" width="40" height="40"/>                    
</div>
