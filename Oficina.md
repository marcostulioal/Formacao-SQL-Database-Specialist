# Sistema de Controle e Gerenciamento de Execução de Ordens de Serviço

## Descrição
Este projeto é um sistema de controle e gerenciamento de execução de ordens de serviço para uma oficina mecânica. Ele permite que clientes levem seus veículos para consertos ou revisões periódicas, e gerencia todo o processo desde a criação da ordem de serviço até a conclusão dos trabalhos.

## Funcionalidades
- **Cadastro de Clientes**: Armazena informações como nome, endereço, CPF e telefone dos clientes.
- **Cadastro de Veículos**: Registra detalhes dos veículos, incluindo marca e modelo, associados aos clientes.
- **Cadastro de Mecânicos**: Mantém informações sobre os mecânicos, como código, nome, endereço e especialidade.
- **Gestão de Ordens de Serviço (OS)**: Cria e gerencia ordens de serviço com informações como número, data de emissão, valor, status e data de entrega.
- **Serviços e Peças**: Registra os serviços a serem executados e as peças utilizadas, calculando os valores correspondentes.

## Modelagem do Banco de Dados
A modelagem do banco de dados inclui as seguintes entidades e seus relacionamentos:
- **Cliente**: Um cliente pode ter vários veículos.
- **Veículo**: Cada veículo pode ter várias ordens de serviço.
- **Ordem de Serviço**: Uma ordem de serviço pode incluir múltiplos serviços e ser atribuída a vários mecânicos.
- **Serviços**: Cada serviço pode utilizar várias peças.
- **Mecânico**: Um mecânico pode realizar vários serviços e estar associado a várias ordens de serviço.

## Diagrama Entidade-Relacionamento (ER)
![oficina](https://github.com/user-attachments/assets/878fcbf6-06b2-494d-a4a9-6b658d3beafc)


