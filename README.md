# Cadastro de carro

**Requisitos funcionais - RF**
- Deve ser possível cadastrar um novo carro.


**Regra de negócio - RN**
- Não deve ser possível cadastrar um carro com uma placa já existente.
- O carro deve ser cadastrado, por padrão, com disponibilidade.
* O usuário responsável pelo cadastro deve ser um usuário administrador.

# Listagem de carros

**Requisitos funcionais - RF**
- Deve ser possível listar todos os carros disponíveis.
- Deve ser possível listar todos os carros disponíveis pelo nome da categoria.
- Deve ser possível listar todos os carros disponíveis pelo nome da marca.
- Deve ser possível listar todos os carros disponíveis pelo nome da carro.

**Regra de negócio - RN**
- O usuário não precisa estar logado no sistema.

# Cadastro de especificação do veículo

**Requisitos funcionais - RF**
- Deve ser possível cadastrar uma especificação para um carro.

**Regra de negócio - RN**
- Não deve ser possível cadastrar uma especificação para um carro não cadastrado.
- Não deve ser possivel cadastrar uma especificação já existente para o mesmo carro.
- O usuário responsável pelo cadastro deve ser um usuário administrador.

# Cadastro de imagens do carro

**Requisitos funcionais - RF**
- Deve ser possível cadastrar a imagem do carro.

**Requisitos não funcionais - RNF**
- Utilizar o multer para upload dos arquivos.

**Regra de negócio - RN**
- O usuário deve poder cadastrar mais de uma imagem para o mesmo carro.
- O usuário responsável pelo cadastro deve ser um usuário administrador.

# Aluguel de carro

**Requisitos funcionais - RF**
- Deve ser possível cadastro um aluguel

**Regra de negócio - RN**
- O aluguel deve ter duração mínima de 24 horas.
- Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo usuario.
- Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo carro.
- O usuario deve estar logado na aplicação
