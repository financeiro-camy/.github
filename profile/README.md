# CAMY Growth Financial Manager
### CAMY Growth presents an intuitive application designed to streamline and organize the financial life of any student. It efficiently organizes finances based on user data, saving time and enabling the pursuit of useful projects.

> This project was developed as an evaluation requirement for the courses of Programming Language 1 (LP1) and Database (BDD) under the guidance of Professor Domingos Lucas Latorre.

# Appendix
### JavaFX Project using Maven
The desktop application was developed using:

- Programming Languages: SQL (Structured Query Language) and Java.
Interface Construction: JavaFX, incorporating components such as FXML markup language. This library enables seamless integration between the interface and Java code, while also supporting integration with CSS style sheets.

# Summary
### Repository Information
This repository contains codes for the financial manager project.

### System Structure
This application comprises the following main classes:

- Usuario
- Categoria
- ContasDinheiro
- Lancamento
- Parcela
- ProjetoCofrinho
- RelatorioPC
- Notificacao
- Meta
- Configuracao

Additionally, this application includes JDBC implementations to facilitate SQL code access. These implementations (code) are available in the src folder under "ImplementacaoJDBC", organized into folders named after methods, each containing possible necessary actions in the system.


# Authors
- @ca12loss: Carlos Alberto
- @LiceeIF: Alice Maria
- @MarinoYorinori: Marino Yorinori
- @gyyoshida: Guilherme Yuji

# Installation
Install financeiro-camy/interface-Jfx and open it in Visual Studio Code (VSCode):
> bash
Copy code
mkdir folder
cd folder
git clone https://github.com/financeiro-camy/interface-Jfx.git
code interface-Jfx

# How to Run
Clone the repository to your machine.
Remove the .git folder:
bash
Copy code
rm -rf .git
Don't forget to change the database address to allocate the code into your database.
In the same terminal where the proxy was configured, execute the command:
bash
Copy code
./mvnw javafx:run

# Additional Information
This desktop application utilizes Java and SQL languages.

> This project is currently undergoing a thorough review and enhancement process to improve its functionality and efficiency

