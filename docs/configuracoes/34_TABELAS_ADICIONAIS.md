[Voltar](README.md)
---

## TABELAS ADICIONAIS

Conjunto de cadastros auxiliares que fornecem estruturas de dados para o funcionamento integrado da plataforma. Este
módulo centraliza a gestão de tabelas de referência utilizadas em diversos pontos do sistema, permitindo personalizar
nomenclaturas, categorias e classificações conforme suas necessidades operacionais específicas. A configuração adequada
destas tabelas de apoio é essencial para garantir a flexibilidade do sistema, possibilitando adaptações às
particularidades do processo comercial da empresa sem necessidade de desenvolvimento adicional.

- Etapas [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/etapas)]
    - [ lista de etapas com checkbox para seleção múltipla ]
- Modelos de download [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/modelos-de-download)]
    - CRUD para cadastro do modelo, somente descrição no formulário.
    - Após cadastrado, exibido na lista botão para upload do arquivo
- Status de orçamento [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/orc-status)]
    - CRUD, com formulário com campo descrição
- Status de contato [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/contato-status)]
    - CRUD, com formulário com campo descrição
- Status de repasse [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/repasse-status)]
    - CRUD, com formulário com campo descrição
- Motivos de perda [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/motivo-perda)]
    - CRUD
        - Descrição
        - Grupo
            - Alteração
            - Desistência
            - Estorno
            - Pagamento
            - Substituição de pedido pago
- Tags de pedido [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/tags)]
    - CRUD
        - Tag
        - [ ] somente API
        - Ícone
            - [ lista de ícones pré-cadastrados ]
        - Cor
            - [ color picker ]
        - Tipo
            - Normal
            - Comprovante de pagamento
- Classificação personalizada [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/tabela-personalizada)]
    - CRUD
        - Tipo
            - Seleção única
            - Seleção múltipla'
            - Texto
        - Nome da tabela personalizada
        - Aplica-se para
            - Integrador
            - Pedido
            - Produto
            - Análise de desconto - solicitação
            - Análise de desconto - conclusão positiva
            - Análise de desconto - conclusão negativa
            - Opções
                - Formulário com campo "Descrição"
- Classificação integrador [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/classificacao-integrador)]
    - CRUD
        - Imagem
        - Descrição
        - Desconto na tabela de frete (%)
        - [ ] Exibir menu de kit fechado
        -
- Tipos de ocorrência [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/ocorrencia-tipo)]
    - CRUD
        - Descrição
        - Setor
            - Vendas
            - SDR
            - Backoffice
            - ADM de vendas - Triagem
            - Logística
            - CX
            - CS
            - Suporte tecnico
            - Adm de vendas - pendência
            - Adm de vendas - financeiro
            - Adm de vendas - conferência
            - Adm de vendas - outros
        - Prioridade
            - Sem prioridade
            - Baixa
            - Média
            - Alta
- Setores [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/setores)]
    - CRUD, com formulário com campo descrição
- Pendências [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/pendencias)]
    - CRUD
        - Descrição
        - [ ] Ativo
        - Ícone
            - [ lista de ícones pré-cadastrados ]
- Embalagem [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/embalagem)]
    - CRUD
        - Descrição
        - Tipo de embalagem
            - Pallet
            - Caixa
            - Cilindro
        - Status
            - Ativo
            - Bloqueado
        - Largura (cm)
        - Altura máxima (cm)
        - Comprimento (cm)
        - Margem de segurança (%)
        - Peso (Kg)
- Grupo motivo de perda [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/grupo_motivo_perda)]
    - CRUD, com formulário com campo descrição
- Etapa da ocorrência [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/etapa-ocorrencia)]
    - CRUD
        - Descrição
        - Status
            - Ativo
            - Bloqueado
        - Enviar e-mail
            - Sim
            - Não
        - Setor
            - [ lista de setores ]
        - Tipo de ocorrência
            - [ lista dinâmica a partir da seleção do setor ]
        - Tempo estimado (horas)
- Etapas do rastreio [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/etapa-rastreio)]
    - CRUD
        - Descrição
        - Ícone
            - [ lista de ícones pré-cadastrados ]
        - Status
            - Ativo
            - Bloqueado
- Tipo de anexo [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/geral/tipos-anexo)]
    - CRUD
        - Nome
        - Status
            - Ativo
            - Bloqueado
        - Descrição
- Objetivo [[solaryum](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/geral/objetivos)]
    - CRUD
        - Nome
        - Situação
            - Ativo
            - Bloqueado
        - Descrição
        - Tipo
            - Anexo
            - Checklist
