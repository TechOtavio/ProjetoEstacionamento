# Projeto Estacionamento - Trilha .NET da DIO

Nesse desafio da trilha .NET da DIO, desenvolvi um sistema simples para gerenciar um estacionamento, aplicando os conceitos que aprendi no módulo de fundamentos.

Criei uma classe chamada **Estacionamento**, que controla os veículos que entram e saem. Essa classe tem três variáveis principais: 

- O preço inicial para estacionar,  
- O preço por hora,  
- E uma lista que guarda as placas dos veículos que estão no estacionamento.

Implementei três métodos importantes:

- **AdicionarVeiculo**: para cadastrar um veículo novo no estacionamento, a partir da placa que o usuário digita.
- **RemoverVeiculo**: para remover um veículo que já está estacionado, calculando o valor a ser cobrado com base no tempo que ele ficou.
- **ListarVeiculos**: para mostrar quais veículos estão atualmente no estacionamento. Caso não tenha nenhum, exibe uma mensagem avisando que não há veículos estacionados.

Além disso, criei um menu interativo para o usuário escolher a ação que deseja: cadastrar, remover, listar veículos ou encerrar o programa.
