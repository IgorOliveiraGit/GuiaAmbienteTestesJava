# Guia Ambiente de Testes

 ## Tecnologias utilizadas:
>  * **Java** - Linguagem de programação orientada a objetos
>  * **Maven** - Ferramenta usada para indicar as dependências necessárias para o projeto, e baixar elas automaticamente de repositórios oficiais do Maven
>  * **Selenium** - Framework desenvolvido para executar interações e testes funcionais em paginas web 
>  * **JUnit** - Framework desenvolvido para criar automações de testes

---

## Estrutura de diretórios e arquivos do projeto:

![Estrutura](/imagens/estrutura.png "estrutura criada com o comando tree(linux)")

## Explicação da estrutura:

> ## Pacote core:
> * Pacote onde são adicionados classes que servem de base para o projeto
>   * BasePage.java - classe base para criação das page objects
>   * BaseTest.java - classe base para criação das classes de teste
>   * DriverFactory.java - classe criada para facilitar a instanciação de um WebDriver(Ferramenta para controlar o navegador simulando um usuário)
>   * Propriedades.java - classe criada para selecionar o navegador utilizado nos testes

---

> ## Pacote enums:
> * Pacote onde são adicionados classes enumeradas(estrutura de dados constantes) de acordo com a necessidade do projeto
>   * TurnoEnum.classe - estrutura contendo todos os turnos manhã, tarde, noite e integral(**exemplo**)

---

> ## Pacote pages:
> * Pacote onde são adicionadas todas as page objects do projeto

---

> ## Pacote testes:
> * Pacote onde são adicionadas todos os testes automatizados do projeto

---

> ## Diretório resources:
> * Diretório usado para adicionar bibliotecas e artefatos externos do java/maven, como os drivers dos navegadores

---

> ## Arquivo pom.xml:
> * Arquivo contendo informações e configurações usadas pelo maven para criar o projeto, tais como suas dependências

---

> ## Arquivo README.md:
> * arquivo usado pelo git para gerar uma pagina de informações sobre o projeto na linguagem de marcação markdown

---

