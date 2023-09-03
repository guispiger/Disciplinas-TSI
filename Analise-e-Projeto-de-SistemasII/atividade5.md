HISTÓRIAS DE USUÁRIOS:
1. Como prestador de serviço, eu gostaria de poder visualizar o valor que receberei de um serviço antes de aceita-lo, para que possa decidir se é viável realizá-lo.<br>

    #### RF - Ordenar as solicitações de transporte por valor
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Ordenar as solicitações de transporte disponíveis por valor em ordem decrescente.|
    | Why?   | Para que o prestador de serviço possa visualizar primeiro as solicitações que oferecem um valor maior.|
    | Who?   | O prestador de serviço.|
    | When?  | Quando o prestador de serviço estiver visualizando os serviços disponíveis. |
    | Where? | No aplicativo, na pagina de selecionar um serviço, selecionando a função de ordenar por valor decrescente. |
        Descrição: Quando o prestador de serviço estiver visualizando os serviços disponíveis, ele poderá odenar as solicitações de transporte disponíveis por valor em ordem decrescente para que possa visualizar primeiro as solicitações que oferecem um valor maior, selecionando a função de ordenar por valor decrescente, na pagina de selecionar um serviço.

    #### RN - Ordenar solicitações de transporte
    Descrição: A funcionalidade de ordenar as solicitações por valor estará disponível após pagamento de taxa.<br>
    Referencia requisitos:
    - RF - Ordenar as solicitações de transporte por valor.

    #### RNF - Ordem de apresentação de solicitações de transporte
    Descrição: Por padrão os serviços são ordenados na tela do prestador de serviço pela data e hora da solicitação.

2. Como cliente, eu gostaria de visualizar o valor de um serviço antes confirmar a contratação, para que possa decidir se vou contratálo ou não.<br>
    #### RNF - Exibição valor do serviço para o cliente
    Descrição: O valor do serviço deve ser exibido para o usuário antes de ele o contratar.

    #### RF - Aderir a clube de beneficios
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Aderir ao clube de beneficios.|
    | Why?   | Para obter descontos em serviços contratados, mediante pagamento de mensalidade.|
    | Who?   | O usuário cliente.|
    | When?  | Quando desejar aderir ao clube de benefícios. |
    | Where? | No aplicativo ou página da web. |
        Descrição: No aplicativo ou página da web, o usuário cliente poderá aderir ao clube de beneficios para obter descontos em serviços contratados, mediante pagamento de mensalidade, quando ele desejar aderir ao clube de benefícios.

    #### RN - Oferta de clube de benefícios
    Descrição: Será ofertado aos usuários clientes a possibilidade de adesão a clube de beneficos mediante a uma assinatura mensal. Essa adesão garante aos usuários descontos nos serviços contratados.<br>
    Referencia requisitos:
    - RF - Aderir a clube de beneficios.

    #### RN - Beneficio sobre os serviço ao aderir ao plano de assinatura
    O cliente terá desconto de 2% do valor do serviço se aderir ao clube de benefícios.<br>
    Referencia requisitos:
    - RF - Aderir a clube de beneficios

3. Como usuário cliente do sistema, eu gostaria de visualizar quais prestadores de serviço estão disponíveis na área, para saber se o serviço que desejo pode ser atendido.<br>
   
    #### RNF - Localização do usuário
    Descrição: A localização atual do usuário deve ser obtida através do receptor de GPS do aparelho no qual o usuário está logado.

    #### RNF - Exibição de serviços disponíveis
    Descrição: São exibidos para o usuário cliente os prestadores de serviço que atendem num raio de 15km da sua localização atual.
