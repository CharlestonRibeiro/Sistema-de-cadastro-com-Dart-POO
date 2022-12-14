# Sistema de cadastro com Dart POO.



## Descrição do desafio - Todos o itens foram atingidos.

### Desafio Módulo Dart.

Foi solicitado a criação de um sistema de registros de empresas. Toda empresa nesse sistema deve ter um sócio associado a ela, que pode ser uma Pessoa Física ou uma Pessoa Jurídica. Sobre as entidades: 

- Uma Empresa no sistema tem os seguintes dados: ID, Razão Social, Nome Fantasia, CNPJ, Endereço (Logradouro, Número, Complemento, Bairro, Estado e CEP), Telefone, Horário do Cadastro e Sócio.

- Uma Pessoa Física tem os seguintes dados: Nome, CPF e Endereço (Logradouro, Número, Complemento, Bairro, Estado e CEP).

- Uma Pessoa Jurídica tem os seguintes dados: Razão Social, Nome Fantasia, CNPJ, Endereço (Logradouro, Número, Complemento, Bairro, Estado e CEP).

O sistema ao ser executado deve oferecer as seguintes opções:

 Cadastrar uma nova empresa;
 
- [x] Buscar Empresa cadastrada por CNPJ;
- [x]  Buscar Empresa por CPF/CNPJ do Sócio;
- [x]  Listar Empresas cadastradas em ordem alfabética (baseado na Razão Social);
- [x]  Excluir uma empresa;
- [x]  Sair.


## Requisitos:

- Toda pessoa seja física ou jurídica, devem saber validar seu documento (CPF/CNPJ);
- O programa deve ser criado considerando os recursos disponíveis da Orientação à Objetos e boas práticas;
- O programa deve ter no mínimo uma herança;
- CPF e CNPJ são do tipo String, mas o input do usuário será apenas números;
- Telefone é do tipo String, mas o input do usuário será apenas números, ex.: 11987654321;
- CEP é do tipo String, mas o input do usuário será apenas números;
- O ID deve ser único, para cada Empresa cadastrada;
- O horário de cadastro deve ser obtido automaticamente pelo sistema;
- A impressão do conteúdo de uma empresa deve atender no mínimo a seguinte formatação:

<p align="center">
<img src="https://camo.githubusercontent.com/e5d02cac2a8ae42eb654bdafdab0e6bc15950f880fbfb25ee117d9d920403635/68747470733a2f2f692e696d6775722e636f6d2f727878686e34552e706e67" width="900" height="600" />|

</p>


