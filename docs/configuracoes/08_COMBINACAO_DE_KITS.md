#### COMBINAÇÃO DE KITS [[link](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/combinacao-de-kits)]

`TODO: (avaliar funcionalidade da página)`

Sistema no Solaryum para gerenciar combinações de kits.

*OBS*: Há um botão crítico nessa página, que é o "Gerar combinações automaticamente." O botão não possui uma confirmação
e, se clicado, inicia automaticamente a gerar os kits.

Há necessidade de validar se o processo acontece em background ou se, ao carregar a página, o processo é interrompido.

Parece uma página para gerenciar as combinações possíveis de kits. A página contém as seguintes abas:

- Inversores
    - Fase
        - Todos
        - Monofásico
        - Trifásico
    - Descrição
    - Quantidade
    - Status
        - Ativo
        - Bloqueado
    - Lista com as combinações de inversores pré-cadastradas
- Micro inversores
    - Apresenta uma lista accordion com os micro inversores cadastrados. Ao expandir o item, é exibida uma lista com os
      produtos e suas regras, além de um botão para adicionar uma combinação.
    - O botão de adicionar combinação abre um modal com um botão para busca de um produto e o campo texto para regra.
- Cabos
    - Apresenta uma lista dos cabos cadastrados e um botão para adicionar um novo cabo. Ao expandir o item, é exibida
      uma lista com os produtos e suas regras, além de um botão para adicionar um cabo.
    - O botão de adicionar cabo abre um modal com um formulário com os campos:
        - Cabo (lista de cabos)
        - Tipo de ligação
            - Monofásico
            - Trifásico
        - Tipo inversor
            - String
            - Micro
            - Híbrido
        - Quantidade por painel
        - Múltiplo (metros)
- Combos
    - Na página há um botão "Adicionar combo", que quando clicado abre um modal com um formulário com os campos:
        - Botões "Selecionar produto principal" e "Selecionar produto adicional"
            - Ao clicar nos botões, um novo modal é sobreposto sendo o conteúdo com as abas que exibem as listas de
              acordo com seu conteúdo:
                - Painel
                - Inversor
                - Cabo
                - Stringbox
                - Estrutura
                - Bateria
                - Outro
            - É permitido selecionar somente um dos produtos, independente da aba
            - Ao selecionar o item o botão é substituído pelo produto que foi selecionado.
        - Quantidade
- Fórmula geral
    - Aberto um modal com as abas:
        - Kit
        - Painel
        - Inversor
        - Cabo
        - Stringbox
        - Estrutura
        - Transformador
        - Bateria
        - Outro
    - É permitido selecionar um produto de cada aba e no final abre-se um novo modal com um campo de texto livre "Fórmula", que possui botões de ajuda para compor um texto com variáveis e funções, que definirão a fórmula gerada.
