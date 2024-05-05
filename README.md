# Projeto de Estacionamento - Desafio de código DIO bootcamp

## Sobre o desafio:

O desafio criado pela DIO é um sistema de estacionamento, onde utilizaremos para gerenciar os veículos cadastrados, realizando o cadastro deles, calculando o tempo que o veículo ficou no estacionamento e cobrando o preço final.

O desafio tem uma classe `Estacionamento`, onde nela temos as funções para adicionar o veículo, listar os veículos, remover um veículo e encerrar o programa. Todas as funções estão dentro do arquivo da classe `Estacionamento`.

## Updates adicionados:

- Atualização para o NET 8.0
    - O código foi originalmente escrito em .NET 6.0 

-  Verificação de carro estacionado para remover um veículo.  
    - Originalmente, não era feita a verificação para saber se havia algum carro estacionado quando a função de remover um veículo no código, ou seja, quando não haviam veículos e o usuário inseria '2', ele pedia para inserir a placa mesmo se não tivesse nenhum carro registrado.

## Uptades futuros:
- Verificação de placas válidas com padrão 'ABC-1234' ou Mercosul: 'RIO-2A24'

---

O [repositório original](https://github.com/digitalinnovationone/trilha-net-fundamentos-desafio) pode ser localizado acima no github, e também está linkado aqui no README, além disso, você pode encontrar mais sobre o desafio [aqui](desafio.md). 