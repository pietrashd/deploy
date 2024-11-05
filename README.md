# Deploy

## Passos para o Deploy
## Deploy do Back-end

## 1. Criar o Repositório
-Acesse o painel do Clever Cloud e crie um novo repositório para o back-end da sua aplicação.
-Conecte esse repositório ao Git para facilitar o gerenciamento e versionamento do código.
## 2. Configurar Variáveis de Ambiente
-No painel do Clever Cloud, adicione as variáveis de ambiente necessárias para sua aplicação.
## 3. Realizar o Deploy
-Após configurar as variáveis de ambiente, utilize o painel do Clever Cloud para iniciar o processo de deploy. 
-O serviço irá configurar automaticamente o ambiente do servidor e disponibilizará seu back-end online.

# Deploy do Banco de Dados na Nuvem
## 1. Criar uma Instância de MySQL
-No Clever Cloud, crie uma instância de MySQL para hospedar o banco de dados da sua aplicação.

## 2. Conectar o Back-end ao Banco de Dados
-Utilize as credenciais que o Clever Cloud fornecerá para conectar seu back-end à instância de MySQL. Isso garantirá que seu back-end tenha acesso ao banco de dados para realizar operações de leitura e escrita. 
-Conexão usando Node.js:
const mysql = require('mysql2');

const connection = mysql.createConnection({
  host: 'seu_host_mysql',
  user: 'seu_usuario',
  password: 'sua_senha',
  database: 'seu_banco_de_dados'
});

connection.connect((err) => {
  if (err) {
    console.error('Erro ao conectar ao banco de dados:', err);
    return;
  }
  console.log('Conexão bem-sucedida ao banco de dados!');
});

# Deploy do Front-end usando Netlify
## Fazer o Upload da Pasta build:
-Acesse o Netlify e faça o upload da pasta build gerada pelo seu projeto front-end. O Netlify cuidará do processo de hospedagem e deixará sua aplicação online em poucos minutos.
-Exemplo de como gerar a pasta build com React: npm run build

## Publicar a Aplicação:
-Após o upload, siga as instruções do Netlify para publicar sua aplicação.
