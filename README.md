# Conversor de Moedas

## Descrição
Bem-vindo ao projeto Conversor de Moedas! Este projeto foi desenvolvido como parte de um desafio do curso de Java oferecido pela Alura em parceria com a Oracle One. O Conversor de Moedas permite a conversão de diferentes moedas utilizando a API ExchangeAPI para obter as taxas de câmbio atualizadas.

## Funcionalidades
- Conversão entre Dólar, Peso Argentino, Real Brasileiro e Peso Colombiano.
- Interface de linha de comando (CLI) amigável.
- Taxas de câmbio atualizadas em tempo real através da API ExchangeAPI.

## Tecnologias Utilizadas
- Java
- API ExchangeAPI
- Biblioteca Scanner para entrada de dados

## Pré-requisitos
Antes de começar, você vai precisar ter instalado em sua máquina:
- [Java JDK 8+](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Maven](https://maven.apache.org/install.html) (opcional, mas recomendado para gerenciamento de dependências)

## Instalação
1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/conversor-moedas.git
    cd conversor-moedas
    ```

2. Adicione sua chave de API da ExchangeAPI:
    - Registre-se no site da [ExchangeAPI](https://www.exchangeapi.io/) e obtenha uma chave de API.
    - No código, localize a parte onde a chave de API é necessária e insira a sua chave. Exemplo:
    ```java
    String apiKey = "SUA_CHAVE_DE_API";
    ```

3. Compile e execute o projeto:
    ```bash
    javac -d bin src/br/com/juancunha/modelos/*.java
    java -cp bin br.com.juancunha.modelos.Main
    ```

## Uso
Ao executar o programa, você verá o menu principal no terminal:

```plaintext
-----------------------------------------------------
Bem vindo ao Conversor de Moeda !
------------------------------------------------------

        1) [USD] para [BRL]
        2) [EUR] para [BRL]
        3) [ARS] para [BRL]
        4) [BRL] para [USD]
        5) [BRL] para [EUR]
        6) [BRL] para [ARS]
        7) Sair
-------------------------------------------------------
