# bdd-starter
Stack para teste automatizado web, utilizando Cucumber, Capybara e SitePrism.  
* [Cucumber](https://docs.cucumber.io/)
* [Capybara](https://github.com/teamcapybara/capybara)
* [SitePrism](https://github.com/site-prism/site_prism)

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
* [Chrome Driver - Linux](https://makandracards.com/makandra/29465-install-chromedriver-on-linux)  
* [Internet Explorer Driver](http://www.seleniumhq.org/download/)
* [PhantonJS](https://github.com/teampoltergeist/poltergeist)
* [Firefox - GeckoDriver](https://github.com/mozilla/geckodriver/releases)
```
(Gecko Linux/Mac OS)
cd ~/Downloads/
wget https://github.com/mozilla/geckodriver/releases/download/v0.24.0/geckodriver-v0.24.0-linux64.tar.gz`
tar -zxvf geckodriver-v0.24.0-linux64.tar.gz
sudo mv geckodriver /usr/local/bin/
```

## Executando os testes
Na raiz do projeto de teste, execute o seguinte comando:  
```bundle exec cucumber```

### Executando o teste com argumentos
Para executar o teste especificando o profile(navegador, ambiente ou tipo de relatório), execute o seguinte comando:
```bundle exec cucumber -p firefox -p dev```  
No arquivo /config/cucumber.yml, está a lista de perfis disponíveis.

### Executando o teste com tags
Para executar o teste especificando a tag, execute o seguinte comando:
```bundle exec cucumber --tags @run```

## Referências
[https://github.com/samycici/cucumber-capybara-site_prism](https://github.com/samycici/cucumber-capybara-site_prism)

### Modo Headless no Chrome
Saiba mais sobre o modo headless do chrome  
[http://www.codeatest.com/chrome-headless-selenium-webdriver/](http://www.codeatest.com/chrome-headless-selenium-webdriver/)

### Saiba mais sobre o PhantomJS
[https://github.com/RefugeRestrooms/refugerestrooms/wiki/What-is-Capybara%3F-What-is-PhantomJS%3F-What-is-Poltergeist%3F](https://github.com/RefugeRestrooms/refugerestrooms/wiki/What-is-Capybara%3F-What-is-PhantomJS%3F-What-is-Poltergeist%3F)
