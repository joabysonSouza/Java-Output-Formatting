Java Output Formatting

Este projeto contém uma solução em Java para um desafio de formatação de saída.
O objetivo é ler 3 pares de valores (uma String e um int) e exibir os resultados formatados em colunas.

📌 Descrição do Problema

O programa deve:

Ler 3 linhas de entrada.

Cada linha contém:

Uma palavra (String)

Um número inteiro (int)

Exibir esses valores formatados com regras específicas:

A String deve ocupar 15 caracteres, alinhada à esquerda.

O número deve ter 3 dígitos, preenchido com zeros à esquerda caso necessário.

🧠 Conceitos Utilizados

Scanner para leitura de dados

System.out.printf para formatação de saída

Especificadores de formatação:

%-15s

%03d

Explicação dos especificadores
Formato	Significado
%-15s	String alinhada à esquerda com largura de 15 caracteres
%03d	Número inteiro com 3 dígitos, preenchido com zeros à esquerda

Como Executar
1️⃣ Compilar
javac Solution.java
2️⃣ Executar
java Solution