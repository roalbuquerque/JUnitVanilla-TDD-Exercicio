# dsJUnit-Exercicio-JUnitVanilla
Test on a Financing class


Teste sobre uma classe "Financiamento"

Regras básicas:

O valor da entrada deve ser 20% do montante.
O valor da prestação deve ser os 80% restantes do montante, divididos pelo número de meses do financiamento.
O valor da prestação não pode ser maior que metade da renda do cliente. Tanto o construtor com argumentos, quando os métodos setTotalAmount (double), setIncome (double), e setMonths (int) devem lançar uma exceção caso os valores devidos não respeitem esta regra

EXEMPLO VÁLIDO:
-------------------------
TotalAmount = 100000
income = 2000
months = 80

entry() = 20000

quota() = 1000 (80000 restante do montante / 80 prestações)
      
===================================================
EXEMPLO INVÁLIDO:
-------------------------
TotalAmount = 100000
income = 2000
months = 79

entry() = 20000

quota() = 1012.66 (80000 restante do montante / 79 prestações)
