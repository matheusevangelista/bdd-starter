# bdd-starter
Stack para teste automatizado web, utilizando Cucumber, Capybara e SitePrism.

## Setup
### Instalar o RBENV
[https://github.com/rbenv/rbenv](https://github.com/rbenv/rbenv)

### Instalar o BUNDLER
Na pasta desejada, execute o seguinte comando:  
```gem install bundler```
   
### Instalar as GEMS 💎
Na raiz do projeto de teste, execute o seguinte comando:  
```bundle install```

### Instalar os DRIVERS
* [Chrome Driver](https://github.com/SeleniumHQ/selenium/wiki/ChromeDriver)
* [Internet Explorer Driver](http://www.seleniumhq.org/download/)
* [PhantonJS](http://phantomjs.org/)

## Executando os testes
Na raiz do projeto de teste, execute o seguinte comando:  
```bundle exec cucumber```

### Executando o teste com argumentos
Para executar o teste especificando o profile(navegador, ambiente ou tipo de relatório), execute o seguinte comando:
```bundle exec cucumber -p firefox -p dev```  
No arquivo /config/cucumber.yml, está a lista de perfis disponíveis.

## Referências
[https://github.com/samycici/cucumber-capybara-site_prism](https://github.com/samycici/cucumber-capybara-site_prism)
