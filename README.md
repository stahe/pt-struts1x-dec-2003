# Introdução ao framework Struts 1.x

👉 **Curso online:**
[Introdução ao framework Struts 1.x através de exemplos (dezembro de 2003)](https://stahe.github.io/pt-struts1x-dec-2003/)

---

## Objetivos

O objetivo deste projeto é explorar o framework de desenvolvimento **Struts 1.x**, que tem a sua origem no projeto Jakarta Struts da **Apache Software Foundation**.

O Struts fornece um framework padrão para desenvolver aplicações web Java baseadas no padrão arquitetónico **MVC (Modelo-Vista-Controlador)**.

Os objetivos educativos são:

* Compreender os princípios do modelo MVC
* Estruturar corretamente uma aplicação web Java
* Separar claramente a apresentação, a lógica da aplicação e o acesso aos dados
* Implementar esta arquitetura utilizando Servlets e JSP

---

## O modelo MVC

O modelo **MVC (Modelo-Vista-Controlador)** tem como objetivo separar:
| Camada             | Função                  |
| ------------------ | --------------------- |
| **Vista (V)**        | Interface do utilizador |
| **Controlador (C)** | Lógica da aplicação |
| **Modelo (M)**     | Acesso aos dados     |

Esta arquitetura também é conhecida como **arquitetura de três camadas**.

### 1️⃣ Vista – Interface do utilizador

* Normalmente, um navegador web
* Também pode ser uma aplicação independente
* Envia pedidos HTTP e formata os resultados

### 2️⃣ Controlador – Lógica da aplicação

* Processa os pedidos dos utilizadores
* Coordena as tarefas de processamento
* Recorre a classes de negócio e fontes de dados

### 3️⃣ Modelo – Fontes de dados

Pode consistir em:
*
* Bases de dados
* Ficheiros simples
* Serviços web
* Diretório LDAP
* Qualquer outra fonte persistente
*
* O objetivo principal do modelo MVC é manter uma **forte independência** entre estas três camadas, com o intuito de limitar o impacto das alterações.
*
*
---

## MVC com Servlets e JSP

Ao aplicar o MVC com tecnologias Java EE tradicionais (Servlets + JSP), a arquitetura é organizada da seguinte forma:

### 🔹 Controlador
* Um **Servlet** atua como ponto de entrada da aplicação
* Centraliza os pedidos HTTP

### 🔹 Lógica de negócio
* Conjunto de **classes de negócio**
* Implementa as regras funcionais

### 🔹 Acesso aos dados

* **Classes de acesso aos dados (DAO)**
* Interagem com bases de dados ou outros sistemas

### 🔹 Visualizações

* Páginas **JSP**
* Responsáveis pela apresentação

---

## Porquê o Struts?

O Struts formaliza esta organização através de:

* A centralização do controlo das solicitações
* A padronização da gestão de ações
* A facilitação da separação de responsabilidades
* Estruturação de aplicações web Java de forma industrial

Desta forma, proporciona uma estrutura robusta para desenvolver aplicações web que sigam rigorosamente a arquitetura MVC.

---

## Destinatários

* Estudantes de informática
* Desenvolvedores web Java
* Pessoas que desejam compreender a arquitetura MVC aplicada a aplicações web

---

## Tecnologias abordadas:

* Java
* Servlets
* JSP
* Arquitetura MVC
* Framework Struts 1.x

---

## Licença

Material educativo destinado a uso académico.

Serge Tahé, dezembro de 2003