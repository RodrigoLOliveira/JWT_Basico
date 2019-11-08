# JWT_Basico
Tutorial simples de como aplicar Json Web Token simples em um projeto Asp.Net Core.

O JWT nada mais é que o armazenamento das informações do token no formato JSON.
O processo de autenticação inicia-se em uma aplicação (Normalmente frontend) fazendo uma requisição para sua API.

Nesta requisição serão enviados o usuário e senha. Neste momento, suas aplicações PRECISAM trafegar sobre HTTPS, isto é uma exigência do Google para indexar seu site.

Com o usuário e senha, é feito o processo normal de verificação do login, e caso tudo ocorra bem, sua API utiliza uma chave **PRIVADA**, que só ela tem para gerar um **TOKEN** contendo as informações que você desejar, no formato JWT.

Neste momento, você tem uma chave enorme, com todas as informações que colocou previamente (Nunca armazene informações sensíveis nos tokens), encriptada com uma chave privada que só a API utilizará, e no formato JSON.

Abaixo temos um processo básico para de como implementar JWT em uma aplicação Asp.net Core, lembrando que o foco deste projeto é abordar apenas o JWT sem se aprofundar tanto nas métricas e padrões, poderiamos ser muito mais profundos porem fugiria do publico alvo que são aplicações simples de programadores Jr.

___

## Como Começamos?
Vamos partir do pressuposto que um projeto com Entity e Identity já foram criados e configurados. Tem um outro repositório onde criamos um projeto e configuramos.

1. Novo Projeto
2. Aplicativo Web ASP.NET Core
3. API
4. Criar
5. Configure seu projeto para receber trabalhar com Entity Framework Core e Identity.

E então podemos começar a implementar o Json Web Token.

> Em breve termino de escrever...

