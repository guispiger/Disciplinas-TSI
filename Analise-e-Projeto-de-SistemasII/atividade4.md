3 RNF.
RNF1 - O FrontEnd deve ser desenvolvido com a linguagem JavaScript e o framework ReactNative.
RNF2 - O BackEnd deve ser desenvolvido na linguagem Java.
RNF3 - As informações sobre os logradouros(nome da rua, número, bairro) serão obtidos da API do Google Maps.
RNF4 - A determinação das rotas será feita usando a Directions na API Maps JavaScript.
RNF5 - O banco de dados deve criptografar os dados com o algoritimo AES256.
RNF6 - Será usado o banco de dados relacional PostgreSQL.
RNF7 - As informações sobre a situação da CNH do prestador de serviço serão obtidas da API WSDenatran.


5 Regras de negócio.
RN1 - O cliente deve efetuar um cadastro para solicitar um transporte.
	RF1 - Solicitar transporte
RN2 - O Prestador de serviço deve efetuar um cadastro para oferecer um serviço.
	Cadastrar-se para prestar um serviço.
	Adicionar/Remover um veículo.
	Gerenciar região de atendimento.
RN3 - O prestador de serviço deve ser habilitado para conduzir o tipo de veículo ofertado.
	Cadastrar-se para prestar um serviço.
RN4 - O valor do serviço é calculado com base na distância, horário e tipo de serviço ofertado.
	Gerenciar o valor base de cada tipo de serviço e horário.
RN5 - Motoristas com pontos na carteira nos últimos 12 meses não serão aceitos
	Cadastrar-se para prestar um serviço.