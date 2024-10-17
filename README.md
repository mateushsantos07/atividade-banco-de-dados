# Atividade Avaliativa II - Prática

- Curso - Desenvolvimento de Sistemas
- Unidade Curricular - Programação de Aplicativos
- Docente - Gustavo Roberto de Souza

## Orientações Gerais
- A avaliação deverá ser realizada individualmente.
- Não é permitido o uso do celular durante a realização da atividade.
- Conceitos de POO (Programação Orientado ao Objeto)
- A entrega deverá ser feita no AVA. Deve ser enviado apenas o link do repositório do github.

## Passo-a-Passo (Clonar e Entrega)
1. Você deve fazer um fork desse repositório, na parte superior dessa página clique na botão de fork. 
2. Depois disso, você deve clonar o repositório para o seu computador, usando o seguinte comando.
   1. Selecione uma pasta no computador.
   2. Abra o CMD (Terminal).
   3. Execute o seguinte comando `git clone <url_do_repositório>`
3. Abra no seu VS Code a pasta do projeto.
4. Desenvolva os exercícios.
5. Ao finalizar você precisa comittar e enviar novamente para o github suas modificações.
   1. Primeiro precisamos adicionar as alterações ao stage, usando o comando  `git add .`.
   2.  Depois disso, você vai de fato commitar, usando o comando `git commit -m "sua mensagem"`.
   3.  Por fim, você precisa fazer push para o github, com o comando `git push origin master`.
6. Por fim, você deve copiar o link do seu repositório e fazer o envio no AVA. 
   1. Você deve adicionar como comentário na entrega do AVA.

## Contexto
Você foi contratado para desenvolver o banco de dados de uma revendedora de veículos que deseja gerenciar seus veículos, vendedores, clientes e as vendas realizadas. A revendedora também quer registrar os fabricantes e os serviços de manutenção dos veículos vendidos.

Requisitos do sistema:
- Veículos: A revendedora possui uma variedade de veículos para venda. Cada veículo tem um número de chassi, modelo, ano de fabricação, cor, quilometragem e preço de venda.
Cada veículo é fabricado por um único Fabricante, mas um fabricante pode produzir vários modelos de veículos.
Um veículo pode ter várias manutenções registradas, mesmo antes de ser vendido.

- Fabricantes: Cada fabricante tem um nome, país de origem e ano de fundação.
Um fabricante pode produzir vários veículos, mas cada veículo pertence a apenas um fabricante.

- Vendedores:A revendedora conta com uma equipe de vendedores. Cada vendedor tem um nome, CPF, telefone, e-mail e data de contratação.
Um vendedor pode realizar várias vendas, mas cada venda é realizada por um único vendedor.

- Clientes: Os clientes são as pessoas que compram veículos na revendedora. Para cada cliente, o sistema deve registrar nome, CPF, telefone, e-mail e endereço.
Um cliente pode comprar vários veículos, e cada veículo pode ser vendido apenas para um único cliente.

- Vendas: O sistema precisa registrar as vendas de veículos, incluindo a data da venda, o valor total e o método de pagamento. Cada venda é realizada por um único vendedor e é associada a um único cliente, mas um cliente pode comprar vários veículos em diferentes vendas.
Uma venda envolve apenas um veículo.

- Manutenções: O sistema precisa registrar os serviços de manutenção realizados nos veículos vendidos. Cada manutenção tem a data do serviço, descrição do serviço e o custo.
Um veículo pode passar por várias manutenções, e cada manutenção está associada a apenas um veículo.

# Instruções:
Desenhe o Modelo Entidade-Relacionamento (MER) e o Diagrama Entidade-Relacionamento (DER) com base nas informações fornecidas.