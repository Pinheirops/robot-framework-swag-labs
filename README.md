# Robot Framework - Sauce Demo
 
Projeto de automação de testes end-to-end para o site [Swag Labs (SauceDemo)](https://www.saucedemo.com/), utilizando Robot Framework e SeleniumLibrary.
 
> Para objetivo, escopo e estratégia dos testes, consulte o [Plano de Testes](TEST_PLAN.md).
 
## Configuração do Ambiente
 
### Verificar se o Python e o pip estão instalados
```bash
python --version
pip --version
```
 
### Clonar o repositório
```bash
git clone git@github.com:Pinheirops/Swag_Labs_Automation.git
```
 
### Instalar dependências
Instalar o Robot Framework:
```bash
pip install robotframework
```
 
Instalar a biblioteca Selenium:
```bash
pip install robotframework-seleniumlibrary
```
 
## Executar os Testes
 
Para executar todos os testes, rode o comando abaixo:
```bash
robot tests/
```
 
Ou execute um teste específico:
```bash
robot tests/nome_do_teste.robot
```
 
## Relatórios de Teste
 
Este projeto utiliza o **Allure Report** para geração de relatórios detalhados da execução dos testes.
 
Para executar os testes gerando os dados para o Allure, rode o comando abaixo:
```bash
robot -d output --listener allure_robotframework:results tests/
```
 
Utilize o comando abaixo para gerar o relatório:
```bash
allure generate results -o allure-report --clean
```
 
Para abrir o relatório, utilize o comando abaixo:
```bash
allure open allure-report
```
