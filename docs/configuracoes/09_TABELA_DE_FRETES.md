[Voltar](./00_INDEX.md)
---

## TABELA DE FRETES [[link](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/tabela-de-fretes)]

Sistema de gestão logística para registro dos custos e prazos de transporte de equipamentos fotovoltaicos. Este módulo
permite configurar regras personalizadas de frete baseadas em segmentação geográfica com granularidade até nível
municipal. A plataforma gerencia interações com transportadoras homologadas, definindo SLAs de entrega, coleta e
despacho por território, fundamental para previsibilidade de prazos e cálculos automáticos de custos logísticos em
orçamentos.

Para cadastrar uma nova tabela, deve-se preencher os campos:

- Região
- UF
- Filtro de cidade (ou deixar vazio para todas)
- Transportadora [lista com transportadoras cadastradas]
- Com a transportadora selecionada, clicar no botão "Vincular cidades". Isso fará com que a transportadora seja
  vinculada àquela cidade.
- Com a lista de cidades, clicar no botão de edição, que abre o modal com os campos:
    - Prazo de entrega (dias)
    - Prazo de coleta (dias)
    - Prazo de despacho (dias)
    - Frete mínimo
    - Taxa rural
    - TDA
    - Transportadora
    - Somente FOB
        - Sim
        - Não
    - Faixas
        - Percentual por faixa de valor

_Importante: Somente é permitido vincular uma transportadora por cidade._
