# Enriquecimento de dados TJAL

Através do número do processo, podemos encontrar o nome do autor e dos advogados.

Um simples webscrapper usando python, jupyter notebook e selenium

Para utilizar esse projeto você vai precisar:

1. Clonar esse repositório para uma pasta no seu computador.
2. Plugar um certificado digital.
3. Fazer o download do chromedriver.

# Configurando o ambiente

## Download do chromedriver  
Cole o seguinte endereço na sua barra de navegação:  
chrome://settings/help  
A versão do seu chromedriver é o que aparece no lugar do xxx.  

O Chrome está atualizado  
Versão xxx.0.5060.134 (Versão oficial) 64 bits  
 
Acesse:  
https://chromedriver.chromium.org/downloads  
Faça download da release da sua versão.  

Extraia o arquivo para uma pasta do seu computador e copie o caminho do executável  
No meu caso é "C:/Projetos/env/chromedriver/chromedriver.exe" (não se esqueça de inverter as barras)

## Clonando o repositório e criação do ambiente virtual

Abra um terminal e navegue até a pasta onde você clonou o repositório (não acesse a pasta do repositório propriamente dita)

```
git clone [url desse repositório]
```

## Instale o ambiente virtual

```
pip install virtualenv
```

## Crie o ambiente que vamos trabalhar

```
virtualenv -p python3 tjal-webscrapper
```

## Instale o jupyter notebook

```
pip install jupyter notebook
```

## Crie um kernel específico para nosso projeto

```
ipython kernel install --name tjal-webscrapper --user
```

# Utilizando os notebooks
Os passos até aqui são para instalação, para utilizar o projeto posteriormente, basta iniciar por aqui:

## Ative o ambiente e abra o jupyter notebook

```
scripts\activate
jupyter notebook
```

Quando terminar, aperte Ctrl+C 2x para encerra o jupyter e saia do ambiente virtual

```
scripts\deactivate
```
