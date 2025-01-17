# aprendendo-maryui

**Aprendendo MaryUI** é um projeto desenvolvido com Laravel, focado em aprender e implementar o framework **MaryUI** para o desenvolvimento de interfaces de usuário modernas e responsivas.

## 🚀 Tecnologias Usadas

- **Laravel**: Framework PHP para desenvolvimento web.
- **MaryUI**: Framework de interface de usuário.
- **SQLite**: Banco de dados utilizado para armazenar informações do projeto.
- **NPM / Node.js**: Gerenciamento de pacotes para o front-end e compilação de assets.

## 📦 Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/usuario/aprendendo-maryui.git
cd aprendendo-maryui
```

### 2. Instale as dependências do PHP

Certifique-se de ter o [Composer](https://getcomposer.org/) instalado.

```bash
composer install
```

### 3. Configure o banco de dados

Certifique-se de configurar o banco de dados no arquivo `.env` e ter sqlite na maquina:

```env
DB_CONNECTION=sqlite
```

### 4. Instale as dependências do front-end

Certifique-se de ter o [Node.js](https://nodejs.org/) e o [NPM](https://www.npmjs.com/) instalados. Depois, instale as dependências do front-end:

```bash
npm install
```

### 5. Compile os assets

Compile os arquivos CSS e JavaScript para o ambiente de produção ou desenvolvimento:

```bash
npm run dev   # Para desenvolvimento
npm run build # Para produção
```
### 6. Instale depencia do bootecamp da maryui


```bash
php artisan mary:install
php artisan mary:bootcamp
php artisan migrate

```


### 7. Inicie o servidor

Com tudo configurado, inicie o servidor Laravel:

```bash
php artisan serve
```

Acesse o projeto no navegador em [http://localhost:8000](http://localhost:8000).

## 📄 Funcionalidades

- Interface moderna e responsiva usando o **MaryUI**.
- CRUD básico implementado.


## 🛠️ Licença

Este projeto está licenciado sob a [MIT License](LICENSE).





