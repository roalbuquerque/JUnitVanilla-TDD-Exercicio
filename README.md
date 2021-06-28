# Exercício JUnit Vanilla 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/roalbuquerque/exercicio-JUnitVanilla/blob/master/LICENSE) 

# Sobre o Exercício

O Exercício JUnit Vanilla é uma simples aplicação Java desenvolvida no início do módulo de Teste, organizado pela [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").

O objetivo do exercício foi de seguir o princípio do TDD (escrevendo os testes antes de desenvolver a classe Financing).

## Modelo conceitual
![Modelo Conceitual](https://github.com/roalbuquerque/exercicio-JUnitVanilla/blob/master/assets/ModeloConceitualExecJUnit.png)

## Enunciado e Regras
O financiamento armazena o seguinte: 
- O montante total do financiamento (totalAmount)
- Renda mensal do cliente que está contratando o financiamento (income) 
- Número de meses do financiamento (months). 
O método entry() retorna o valor de entrada e quota() retorna a prestação mensal.

Regras:
1. O valor da entrada deve ser 20% do montante.
2. O valor da prestação deve ser os 80% restantes do montante, divididos pelo número de meses do financiamento.
3. O valor da prestação não pode ser maior que metade da renda do cliente. Tanto o construtor com argumentos, quanto os métodos setTotalAmount(double), setIncome(double), e setMonths(int) devem lançar uma exceção caso os valores atribuídos não respeitem esta regra.

⚡ Observação: Os testes a serem criados são para validar os métodos entry e quota, e também o construtor e os setters. Cobrir cenários quando satisfazem e não satisfazem a terceira regra. (para o construtor e setters).

## Exemplo de Teste
![Teste de requisitção](https://github.com/roalbuquerque/exercicio-JUnitVanilla/blob/master/assets/financingTests.png)

# Tecnologias utilizadas
- Java
- Biblioteca: JUnit 5

# Autor

Rafael de Oliveira Albuquerque

📫 Você pode me encontrar aqui:
<p align="left">
  <a href="https://www.linkedin.com/in/rafaeloliveiraalbuquerque/" alt="Linkedin">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rafaeloliveiraalbuquerque/" /></a>





