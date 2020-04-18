# PWA Spotcode Rails React

Desafio do [OneBitCode](https://onebitcode.com/) para a semana Super Full Stack, que ocorreu entre os dias 13 a 19 de Abril / 2020.

Foi proposto um minicurso gratuito, criando uma PWA inspirado no Spotify utilizando o Rails para backend e React para frontend, vulgo **Spotcode**.

## Dependências

### Instalar o Ruby

```bash
sudo apt install ruby-full
```

Ou utilizar o [Rbenv](https://github.com/rbenv/rbenv) para instalar o Ruby.

### Instalar a lib SQLite 3

```bash
sudo apt-get install libsqlite3-dev
```

### Instalar a gem do sqlite3

```bash
gem install sqlite3 -v '1.4.2' --source 'https://rubygems.org/'
```

### Instalar Node.js

A aplicação requer uma versão Node.js >= 8.16.0. Utiliza [NVM](https://github.com/nvm-sh/nvm) para instalar a versão desejada do Node.js

### Instalar o Rails

Para fins de manter a compatibilidade, será necessário instalar a versão 6.0.2.1

```bash
gem install rails -v '6.0.2.1'
```

### Criar a aplicaçao

```bash
rails _6.0.2.1_ new pwa-spotcode-rails-react
```
