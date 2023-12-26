# DIO - Trilha .NET - Fundamentos
www.dio.me

### Estacionamento Manager

## Descrição do Projeto

Este projeto foi desenvolvido como parte do Bootcamp Decola Tech da Avanade, no módulo de fundamentos da trilha .NET da Digital Innovation One (DIO). O objetivo é criar um sistema simples para gerenciar um estacionamento, permitindo a adição de veículos, remoção com cálculo do valor cobrado e listagem dos veículos presentes.

## Funcionalidades Implementadas

Classe "Estacionamento"
A classe "Estacionamento" foi criada com as seguintes características:

precoInicial: Variável do tipo decimal, representa o preço base para estacionamento.
precoPorHora: Variável do tipo decimal, representa o preço por hora de estacionamento.
veiculos: Lista de string, contendo as placas dos veículos estacionados.

## Métodos

AdicionarVeiculo(placa: string): Adiciona um veículo à lista de veículos estacionados, recebendo a placa como parâmetro.

RemoverVeiculo(placa: string, horas: int): Verifica se o veículo com a placa fornecida está estacionado. Se sim, solicita a quantidade de horas que ele permaneceu no estacionamento, calcula o valor cobrado (precoInicial * precoPorHora * horas) e exibe para o usuário.

ListarVeiculos(): Lista todos os veículos presentes no estacionamento. Se não houver nenhum, exibe a mensagem "Não há veículos estacionados".

##Menu Interativo

Implementação de um menu interativo com as seguintes opções:

Cadastrar veículo
Remover veículo
Listar veículos
Encerrar

##Como Usar

<code>git clone https://github.com/seu-usuario/nome-do-repositorio.git</code>

Abra o projeto no ambiente de desenvolvimento .NET.

Execute o programa e interaja com o menu para gerenciar o estacionamento.


<code>dotnet run</code>

Siga as opções do menu para cadastrar, remover e listar veículos.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias, corrigir bugs ou adicionar novas funcionalidades. Basta abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT.
