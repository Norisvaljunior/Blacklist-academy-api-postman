
## Projeto de testes de API's com Postman - Qa.Coders Academy T11
Introdução 

Este projeto tem como objetivo demonstrar o uso do Postman para testes de API's do sistema ERP do Qa.Coders Academy.
Durante as sprints, realizamos os testes conforme as features disponibilizadas no Azure, atendento as regras de negócio pré estabelecidas. 

### A API-Academy foi desenvolvida para estudos de Quality Assurance. <br>
O Swagger (também conhecido como OpenApi) é uma biblioteca muito conhecida no universo backend, disponível para diversas linguagens e frameworks.
Ele gera um site interno no seu backend que descreve, com muitos detalhes, cada endpoint e estrutura de entidades presentes na sua aplicação.

### <span style="color:green">Endpoint's testados
       • Auth
       • Users
       • Company
       • Board
       • CostCenter
       • Department
       • Client


Para executar os testes, siga as instruções abaixo : <br>

### Instalar o node
```bash
https://nodejs.org/en/download
```
### Instalar o newman (prompt de comando)
```bash
    npm install -g newman
    npm install -g newman-reporter-htmlextra
```
### Instalar da dependência dos relatórios
```bash
    npm install -g newman-reporter-htmlextra
```



### Clonar o repositório para o seu ambiente local <br>
```bash
git clone https://github.com/norisvaljunior/Blacklist-academy-api-postman.git
```
### Próximo passo é rodar os testes <br>

Opção 1 : <br>
Abrir a pasta das variáveis globais, de  ambientes e as collection's.<br>
Abrir o terminal ou prompt de comando na pasta e executar o comando : <br> 
    • newman run erp-academy.json -e .\local-env.json -g .\global-env.json --delay-request 1 --reporters cli , -r htmlextra

Opção 2 :
1.	Abra o Postman. <br>
2.	Importe a coleção de testes: <br>
•	Clique no botão "Import" no canto superior esquerdo do Postman.<br>
•	Selecione o arquivo QA.Coders_Backend_Tests.postman_collection.json dentro da pasta do repositório clonado.<br>
3.	Importe as variáveis de ambiente:<br>
•	Clique no botão "Import" no canto superior esquerdo do Postman.<br>
•	Selecione os arquivos com extensão JSON dentro da pasta do repositório clonado.<br>
4.	Selecione a variável de ambiente importada na barra lateral do Postman.<br>
5.	Execute a coleção de testes:<br>
•	Clique no botão "Runner" no canto superior esquerdo do Postman.<br>
•	Selecione a coleção "QA.Coders Backend Tests".<br>
•	Clique em "Start Run" e aguarde a execução dos testes.<br>
6.	Visualize os resultados dos testes na aba "Test Results" do Postman.<br>





## Tecnologias 

Aqui estão as tecnologias utilizadas neste projeto.

* Postman
* Node (v20.11.0)
* Newman (v6.1.1)
* Newman reporter-htmlextra

## Serviços usados

* Azure
* Github


## Time Blacklist

  * **Norisval Nascimento Júnior** <BR><br>
####  Techlead.... :    Cleberson Osorioti <br>
####  Assistente. :              Pamela Colombo
                
<BR>
<BR>
<BR>
<span style="color:green">“Se eu tivesse 8 horas para cortar uma árvore, gastaria 6 horas afiando meu machado” – Abraham Lincoln.</span>






