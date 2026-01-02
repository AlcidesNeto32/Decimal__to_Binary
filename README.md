# 🔢 Conversor Decimal para Binário

Um projeto simples e funcional desenvolvido em PHP para converter números decimais em seus respectivos valores binários. Este projeto foi criado como parte dos meus estudos de lógica de programação e manipulação de arrays.

## 🚀 Sobre o Projeto

O objetivo deste desafio foi implementar o algoritmo de **divisões sucessivas** para encontrar a representação binária de um número inteiro positivo, focando na compreensão de como a base binária funciona por baixo dos panos.



### 🛠️ Funcionalidades

-   Converte números inteiros decimais para binário.
-   Tratamento especial para o número zero.
-   Interface minimalista e responsiva.
-   Lógica pura em PHP (sem uso de funções nativas de conversão como `decbin`).

## 💻 Tecnologias Utilizadas

-   **PHP**: Lógica de conversão e processamento.
-   **HTML5**: Estrutura e formulário.
-   **CSS3**: Estilização e layout.

## 📖 Como funciona a lógica?

A conversão é feita através da função `binario($numero)`, que segue o seguinte fluxo:
1.  Recebe um número decimal do usuário.
2.  Enquanto o número for diferente de 0, armazena o resto da divisão por 2 (0 ou 1) em um array.
3.  Divide o número por 2 (convertendo para inteiro) para continuar o loop.
4.  Inverte o array de restos para obter a ordem correta dos bits.
5.  Une os elementos com `implode` para exibir o resultado final.

## ⚙️ Como executar

1.  Tenha um ambiente PHP instalado (XAMPP, Laragon, ou PHP CLI).
2.  Crie um arquivo chamado `index.php`.
3.  Cole o código do projeto no arquivo.
4.  Inicie o servidor e acesse via navegador (ex: `http://localhost/index.php`).

---
Desenvolvido por Alcides Neto.
