# Cadatro de carro

**RF**
Deve ser possível cadastrar um novo carro.

**RN**
Não deve ser possível cadastrar um carro com uma placa já existente.
Por padrão, o carro deve ser cadastrado como disponível.
Somente um usuário administrador será responsável pelo cadastro de veículos.

# Listagem de carros

**RF**
Deve ser possível listar todos os carros disponíveis.
Deve ser possível listar todos os carros disponíveis pelo nome da categoria.
Deve ser possível listar todos os carros disponíveis pelo nome da marca.
Deve ser possível listar todos os carros disponíveis pelo nome do carro.

**RN**
O usuário não precisa estar logado no sistema.

# Cadastro de Especificação no carro

**RF**
Deve ser possível cadastrar uma especificação para o veículo.

**RN**
Não deve ser possível cadastrar uma especificação para um veículo não cadastrado.
Não deve ser possível cadastrar uma especificação já existente para o mesmo veículo.
Somente um usuário administrador será responsável pelo cadastro de veículos.

# Cadastro de imagens do carro

**RF**
Deve ser possível cadastrar a imagem do veículo.

**RNF**
Utilizar o multer para upload dos arquivos.

**RN**
O usuário poderá cadastrar mais de uma imagem para o mesmo veículo.
O usuário responsável pelo cadastro deve ser um administrador.

# Aluguel

**RF**
Deve ser possível cadastrar um aluguel


**RNF**

**RN**
O aluguel deve ter duração mínima de 24 horas.
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo usuário.
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo veículo.
O usuário deve estar logado na aplicação.
Ao concluir um aluguel, o status do carro escolhido deverá ser alterado para indisponível.

# Devolução de carro

**RF**
Deve ser possível realizar a devolução de um carro

**RN**
Se o carro for devolvido com menos de 24 horas, deverá ser cobrado diária completa.
Ao realizar a devolução, o carro deverá ser liberado para outro aluguel.
Ao realizar a devolução, o usuário também deverá ser liberado para outro aluguel.
Ao realizar a devolução, deverá ser calculado o total do aluguel.
Caso o horário de devolução seja superior ao horário previsto de entrega, deverá ser cobrado multa proporcional aos dias de atraso
Caso haja multa, deverá ser somado ao total de aluguel.
O usuário deve estar logado na aplicação.

# Listagem de Alugueis para usuário

**RF**
Deve ser possível realizar a busca de todos os aluguéis para o usuário.

**RN**
O usuário deve estar logado na aplicação.
