# Deploy

## Passos para o Deploy

### Deploy do Back-end

#### 1. Criar Repositório
- Acesse o painel do **Clever Cloud** e crie um novo repositório para o back-end da sua aplicação.
- Conecte esse repositório ao **Git** para facilitar o gerenciamento e versionamento do código.

#### 2. Configurar Variáveis de Ambiente
- No painel do Clever Cloud, adicione as variáveis de ambiente necessárias para sua aplicação. Isso pode incluir:
  - URL do banco de dados
  - Chaves de API (se houver)

#### 3. Realizar o Deploy
- Após configurar as variáveis de ambiente, utilize o painel do Clever Cloud para iniciar o processo de deploy. O serviço irá configurar automaticamente o ambiente do servidor e disponibilizará seu back-end online.

### Deploy do Banco de Dados na Nuvem

#### 1. Criar uma instância de MySQL
- No Clever Cloud, crie uma instância de **MySQL** para hospedar o banco de dados da sua aplicação.

#### 2. Conectar o Back-end ao Banco de Dados
- Utilize as credenciais que o Clever Cloud fornecerá para conectar seu back-end à instância de MySQL. Isso garantirá que seu back-end tenha acesso ao banco de dados para realizar operações de leitura e escrita.

### Deploy do Front-end

#### Usando Netlify
1. **Fazer o Upload da Pasta `build`**:
   - Acesse o **Netlify** e faça o upload da pasta `build` gerada pelo seu projeto front-end. O Netlify cuidará do processo de hospedagem e deixará sua aplicação online em poucos minutos. 
