# Calculadora
Meu primeiro projeto de uma calculadora feita com códigos HTML, javascript e css

Projeto: Calculadora de uso pessoal

Especificações Técnicas Obrigatórias

Desenvolvimento de uma calculadora básica. A calculadora deve ter uma tela de exibição para a entrada e o resultado, com botões para os dígitos de 0 a 9, ponto decimal e as quatro operações básicas. É obrigatório um botão para limpar a tela (C) e outro para calcular o resultado (=). O design precisa ser responsivo, centralizado e apresentar uma grade de botões com sombreamento. A funcionalidade de cálculo deve incluir um tratamento de erros, exibindo a mensagem "Erro" para expressões inválidas. A tela de exibição deve ser desabilitada para evitar a edição direta pelo usuário.

Tecnologias utilizadas:

HTML;
Javascript;
CSS

O que aprendi:

Aprendi a gerenciar o estado da aplicação utilizando o JavaScript para manipular o valor exibido na tela. O valor atual da calculadora é armazenado no display.value e é alterado com base nas interações do usuário, como a adição de números ou a chamada da função de cálculo.

Embora este projeto seja simples, a estrutura do HTML já sugere uma forma básica de componentização. A calculadora inteira pode ser vista como um componente principal (div.calculadora), e os botões (button) são componentes menores e reutilizáveis. Isso permite organizar o código e o design de forma modular.

O conceito de props pode ser visto na forma como os dados são passados para as funções JavaScript. Por exemplo, a função adicionar(valor) recebe o valor do botão clicado como um argumento, que é o dado necessário para atualizar o estado do display.

A renderização condicional é implementada de forma simples com o bloco try...catch na função calcular(). Se a expressão for válida e a avaliação for bem-sucedida, o resultado é exibido. Se ocorrer um erro (por exemplo, uma expressão inválida), a condição de erro é tratada, e a mensagem "Erro" é renderizada na tela em vez de um resultado numérico.
