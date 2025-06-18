#### FINANCIAMENTO [[geral](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/config-financiamento/geral) e [funil](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/config-financiamento/funil)]

Tela de configuração de financiamento no Solaryum, com formulário contendo:

- Aba Geral
    - Status
        - Ativo
    - Valor mínimo do pedido
    - Valor máximo do pedido
- Aba Simulação
    - [ ] Usar controle de tarefas
    - Enviar para a célula quando
        - Múltipla seleção de tarefas
        - [ ] Disponibilizar propostas pré-aprovadas automaticamente
    - [ ] Usar termo de uso
        - Campo rich html para edição do termo de uso

Além disso, há o bloco com CRUD para cadastro das financeiras que podem ser usadas para financiamento de pedidos. O
formulário aberto em modal contém os seguintes campos:

- Imagem
- Nome
- Gateway
    - [ lista de gateways ]
- [ ] Ativo
- Configuração geral
    - Forma de pagamento
        - [ lista de formas de pagamento ]
    - Análise de integradores
        - Gateway
        - Manual
    - Prazo para reanalisar integrador (dias)
    - Carências
        - [ lista de carências ]
    - Parcelas
        - [ lista de parcelas ]
    - URL termos de uso
