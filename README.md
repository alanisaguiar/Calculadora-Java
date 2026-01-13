# Calculadora-Java
Este projeto consiste no desenvolvimento de uma calculadora simples em Java, criada com o objetivo de aplicar conceitos fundamentais de Programação Orientada a Objetos (POO) e Programação Orientada a Aspectos (AOP).

Além de implementar operações matemáticas básicas, o sistema utiliza AspectJ para realizar o log automático das operações, separando responsabilidades e promovendo um código mais limpo, modular e de fácil manutenção.

## Funcionalidades
A calculadora oferece suporte às seguintes operações:

➕ Soma de três valores

➖ Subtração de dois valores

✖️ Multiplicação de dois valores

➗ Divisão de dois valores, com tratamento de erro para divisão por zero

Além disso, todas as operações realizadas são registradas automaticamente no console por meio de um aspecto de logging.

## Programação Orientada a Aspectos (AOP)
O projeto utiliza AspectJ para implementar um aspecto de Logging, responsável por:
- Interceptar a execução dos métodos da classe Calculadora
- Registrar no console:
- O nome da operação executada
- Os valores utilizados na operação

### Essa abordagem permite:
- Separação clara de responsabilidades
- Evitar repetição de código de log nos métodos
- Maior facilidade de manutenção e extensão do sistema
