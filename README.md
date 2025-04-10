# Exercicio 5

Este projeto é uma aplicação para calcular o Índice de Massa Corporal (IMC) de uma pessoa, desenvolvido como parte da lista de exercícios da disciplina de Introdução ao Desenvolvimento Web.

## Funcionalidades

A aplicação realiza as seguintes etapas:

1. Solicita o nome da pessoa.
2. Solicita a altura da pessoa em centímetros.
3. Solicita o peso da pessoa em quilogramas.
4. Converte os dados de entrada para o tipo `float` e a altura de centímetros para metros.
5. Calcula o IMC utilizando a fórmula:  
   **IMC = peso (kg) ÷ altura² (m²)**
6. Classifica o IMC em uma das seguintes faixas:
   - **Menor que 16**: Baixo peso muito grave
   - **Entre 16 e 16,99**: Baixo peso grave
   - **Entre 17 e 18,49**: Baixo peso
   - **Entre 18,50 e 24,99**: Peso normal
   - **Entre 25 e 29,99**: Sobrepeso
   - **Entre 30 e 34,99**: Obesidade grau I
   - **Entre 35 e 39,99**: Obesidade grau II
   - **Maior que 40**: Obesidade grau III
7. Exibe o resultado no seguinte formato:  
   `"<Nome> possui índice de massa corporal igual a <IMC>, sendo classificado como: <classificação>."`

## Como usar

1. Abra o arquivo `index.html` em um navegador.
2. Preencha os campos solicitados:
   - Nome
   - Peso (em kg)
   - Altura (em cm)
3. Clique no botão **Calcular IMC**.
4. O resultado será exibido na tela com o IMC calculado e sua classificação.

## Tecnologias utilizadas

- **HTML5**: Estrutura da aplicação.
- **CSS3**: Estilização da interface.
- **JavaScript**: Lógica de cálculo e manipulação do DOM.

## Estrutura do projeto
