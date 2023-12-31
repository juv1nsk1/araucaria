# Oráculo do Tesouro Nacional - Smart Contract

Este repositório contém o código-fonte do smart contract de Oráculo do Tesouro Nacional. O contrato é projetado para fornecer informações sobre os preços dos títulos públicos e o volume de transações.

## Arquitetura do Contrato

![Arquitetura](https://github.com/juv1nsk1/araucaria/blob/main/contracts/Arquitetura%20do%20Smart%20contract.png?raw=true)

## Código fonte

O código do contrato está organizado em vários arquivos para facilitar a leitura e manutenção:

### TesouroOracle.sol
Reúne as funções principais que retornam os preços dos títulos públicos e informações sobre o volume de transações.

### Assinaturas.sol
Fornece funções para gerenciamento e armazenamento dos assinantes do serviço de Oráculo.

### Titulos.sol
Contém funções para gerenciamento e armazenamento dos preços e transações dos títulos públicos.

### Auditor.sol
Fornece a verificação dos dados enviados pelas corretoras antes de serem registrados no contrato.

### Corretoras.sol
Contém funções para o cadastro e gerenciamento das corretoras autorizadas a enviar dados de transações.

### Pagamento.sol
Reúne funções para o gerenciador do oráculo definir valores, regras e realizar pagamentos aos nós da rede.

### Biblioteca.sol
Contém funções adicionais para otimização do contrato, incluindo o controle de códigos ISIN.

### Bibliotecas openzeppelin utilizadas
Ownable, ReentrancyGuard e Context


## Como Usar

1. Clone o Repositório:

```bash
Copy code
git clone https://github.com/seu-usuario/oraculo-tesouro.git
```

2. Instale as dependências necessárias (hardhat e openZeppelin)

3. Integre o contrato com outras aplicações, como UI, DApps ou scripts seguindo a documentação de integração.
