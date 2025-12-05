\# Documento de Requisitos

\*\*Sistema de Gestão de Biblioteca Universitária\*\*  

\*\*Versão:\*\* 1.0  

\*\*Data:\*\* 05/12/2025  

\*\*Responsáveis:\*\* Jonathan Silva Machado, Hellen Caroline Bueno



---



\## 1. Objetivo

Desenvolver um sistema para gerenciar empréstimos, devoluções e cadastro de livros e usuários em uma biblioteca universitária.



\## 2. Requisitos Funcionais



\*\*RF01:\*\* O sistema deve permitir cadastro de livros (título, autor, ISBN, quantidade).  

\*\*RF02:\*\* O sistema deve permitir cadastro de usuários (nome, RA, curso, e-mail).  

\*\*RF03:\*\* O sistema deve registrar empréstimos com prazo de 14 dias.  

\*\*RF04:\*\* O sistema deve calcular multas por atraso (R$ 2,00/dia).  

\*\*RF05:\*\* O sistema deve gerar relatórios de livros mais emprestados.



\## 3. Requisitos Não-Funcionais



\*\*RNF01:\*\* Interface web responsiva.  

\*\*RNF02:\*\* Banco de dados MySQL.  

\*\*RNF03:\*\* Tempo de resposta inferior a 2 segundos.  

\*\*RNF04:\*\* Disponibilidade de 99% durante horário de funcionamento.



\## 4. Regras de Negócio



\- Alunos podem emprestar até 3 livros simultaneamente.

\- Professores podem emprestar até 5 livros.

\- Livros de referência não podem ser emprestados.



\## 5. Casos de Uso Principais



1\. Realizar empréstimo

2\. Realizar devolução

3\. Renovar empréstimo

4\. Consultar disponibilidade

5\. Gerar relatórios gerenciais

