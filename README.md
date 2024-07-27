# <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"> Desafio Intermediário da DIO GFT 05 - Cofres Seguros: Dominando o Encapsulamento e Abstração


#### Desenvolvido na linguagem Java por:
- [Marcos Shirafuchi](https://github.com/marcosfshirafuchi)

# Principais Tecnologias

- <img width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original-wordmark.svg" title = "Java" /> Java 21 : Utilizaremos a versão LTS mais recente do Java para tirar vantagem das últimas inovações que essa linguagem robusta e amplamente utilizada oferece;
- <img width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/intellij/intellij-original.svg" title = "IntelliJ" /> IntelliJ : Usei o IntelliJ como a IDEA.

# Dominando Desafios de Códigos Intermediários em Java
## Desafio 05 / 05 - Cofres Seguros: Dominando o Encapsulamento e Abstração
### Descrição
Você foi contratado para desenvolver um sistema de cofres seguros. O objetivo é criar dois tipos de cofres: um Cofre Digital, que é aberto por senha, e um Cofre Físico, que é aberto por chave.

### Entrada

O programa irá solicitar ao usuário que digite o tipo de cofre a ser criado: "digital" ou "físico". Se for escolhido o tipo "digital", o programa irá solicitar a senha e a confirmação de senha do cofre digital (ambas com apenas números). Caso seja escolhido o tipo "físico", não é necessário nenhuma outra entrada.

### Saída
O programa irá exibir as informações do cofre criado. Para o Cofre Digital, será exibido o tipo e o método de abertura (senha). Para o Cofre Físico, será exibido apenas o tipo e o método de abertura (chave).


### Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.



<table>
  <thead>
    <tr align="left">
      <th>Entrada</th>
      <th>Saída</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>digital<br>
12345<br>
1234
      </td>
      <td>Tipo: Cofre Digital<br>
Metodo de abertura: Senha<br>
Senha incorreta!<br>
      </td>
    </tr>
    <tr>
      <td>fisico
      </td>
      <td>Tipo: Cofre Fisico<br>
Metodo de abertura: Chave</td>
    </tr>
    <tr>
      <td>digital<br>
2525<br>
2525
      </td>
      <td>Tipo: Cofre Digital<br>
Metodo de abertura: Senha<br>
Cofre aberto!
      </td>
    </tr>
  </tbody>
  <tfoot></tfoot>
</table>

