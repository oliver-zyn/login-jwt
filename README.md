## Login JWT

Api rest para login e cadastro de usuários

### Como usar

Para usar essa api, primeiramente é necessário instalar alguns módulos:

- npm i express
- npm i dotenv
- npm i mongoose
- npm i bcryptjs
- npm i jsonwebtoken
- npm i @hapi/joi

Além disso, é necessário criar um arquivo .env (no mesmo diretório do app.js) e configurar as seguintes variáveis ambiente:

- PORT = <porta em que o servidor irá rodar>
- MONGO_CONNECTION_URL = <url de conexão do seu database mongodb>
- TOKEN_SECRET = <chave secreta para a geração do token>

Após isso, execute um "npm start" e seu projeto estará rodando!
