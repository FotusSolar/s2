[Voltar](./00_INDEX.md)
---

## FINANCIAMENTO [[geral](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/config-financiamento/geral) e [funil](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/config-financiamento/funil)]

Módulo financeiro que democratiza o acesso a sistemas fotovoltaicos através de opções
personalizadas de parcelamento e crédito para clientes finais. Esta ferramenta permite configurar parâmetros de
elegibilidade para financiamentos, definir limites operacionais e estabelecer processos de
análise de crédito, viabilizando projetos solares que de outra forma seriam inacessíveis financeiramente. A plataforma
automatiza etapas do fluxo de aprovação junto a instituições financeiras parceiras, oferecendo aos integradores um
diferencial competitivo fundamental na conversão de vendas de sistemas de maior potência e valor agregado.

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
