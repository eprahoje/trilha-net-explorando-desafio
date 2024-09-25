# 💻 Desafio de projeto - Trilha .NET - Explorando a linguagem C#

### Desafio de projeto
Para este desafio, usei meus conhecimentos adquiridos no módulo de explorando a linguagem C#, da trilha .NET da [DIO](https://www.dio.me).

## 💼 Contexto
Fui contratado para construir um sistema de hospedagem, que será usado para realizar uma reserva em um hotel. Irei precisar usar a classe Pessoa, que representa o hóspede, a classe Suíte, e a classe Reserva, que fará um relacionamento entre ambos.

O meu programa deverá cálcular corretamente os valores dos métodos da classe Reserva, que precisará trazer a quantidade de hóspedes e o valor da diária, concedendo um desconto de 10% para caso a reserva seja para um período maior que 10 dias.

## 📑 Regras e validações
1. Não deve ser possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.
2. O método ObterQuantidadeHospedes da classe Reserva deverá retornar a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria deverá retornar o valor da diária (Dias reservados x valor da diária).
3. Caso seja feita uma reserva igual ou maior que 10 dias, deverá ser concedido um desconto de 10% no valor da diária.


![Diagrama de classe estacionamento](diagrama_classe_hotel.png)

## ✅ Solução
Implementei a solução proposta pelo instrutor nos métodos presentes no código, além de realizar os testes para verificar se os cálculos do valor da diária correspondem ao esperado. 
