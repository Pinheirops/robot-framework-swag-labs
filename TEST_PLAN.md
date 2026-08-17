# Plano de Testes
 
## 1. Objetivo
Este projeto tem como objetivo praticar automação de testes em aplicações web, utilizando o site Swag Labs (SauceDemo) como ambiente de estudo.
 
O projeto é voltado para estudos e prática de QA/Automação de Testes, servindo como referência para quem deseja aprender sobre:
- Estruturação de testes automatizados;
- Automação com Robot Framework;
- Automação web com SeleniumLibrary;
- Boas práticas em organização de testes.

## 2. Escopo
 
### 2.1 Funcionalidades testadas
- Login
- Produtos
- Carrinho
- Checkout
### 2.2 Cenários cobertos
- Login válido e inválido;
- Navegação pelos produtos;
- Adição e remoção de itens no carrinho;
- Finalização da compra.

## 3. Ambiente e Ferramentas
- **Ferramenta de automação:** Robot Framework
- **Bibliotecas utilizadas:** SeleniumLibrary e Collections
- **Navegador utilizado:** Chrome
- **Ambiente sob teste:** https://www.saucedemo.com/
- **Ferramenta de relatório:** Allure Report

## 4. Estrutura do Projeto
- **DATA** – Variáveis utilizadas nos testes
- **LOCATORS** – Elementos da página (xpaths, ids, etc.)
- **PAGE** – Keywords e regras de interação com as páginas
- **TEST** – Casos de teste
- **UTIL** – Arquivos de integração e imports