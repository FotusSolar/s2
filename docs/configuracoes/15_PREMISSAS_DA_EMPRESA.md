[Voltar](./00_INDEX.md)
---

## PREMISSAS DA EMPRESA [[link](https://sandbox.solaryum.com.br/fotus-yfe/configuracoes/premissas)]

Painel central de configurações que define os parâmetros de operação. Este módulo estabelece as diretrizes operacionais,
comerciais e financeiras que regem o funcionamento da plataforma, determinando prazos de negociação, políticas de
preços, margens de lucro e regras de relacionamento com integradores. As premissas configuradas impactam diretamente no
comportamento sistêmico da aplicação e nos cálculos automáticos de valores, servindo como centro de comando para
implantação de políticas corporativas e estratégias.

**Aba GERAL**

- Geral
- Prazo de expiração do orçamento (dias)
- Prazo de confirmação do pedido (dias)
- Usuário dos contratos
- [ lista de usuários ]
- Percentual de retenção de repasse - CIF
- Percentual de retenção de repasse - FOB
- Limite do repasse (%)
- Nome do documento de termo ou contrato cadastro
- Mensagem para endereço adicional
- Bloqueio automático de acesso
- Nunca
- 1 mês
- 3 meses
- 6 meses
- [ ] Inscrição Estadual obrigatória nos cadastros
- [ ] Cadastrar orçamento somente pelo CRM
- [ ] Bloquear sistema para manutenção de produtos
- Alíquota de Imposto Referencial
- [ ] Buscar endereço somente pela Receita
- Prazo para atualizar endereço na receita

    - Avulso
        - Nome a ser exibido no menu Avulso

    - Fretes
        - [ ] Utilizar tabela de frete
        - [ ] Integrador pode alterar tipo de frete
        - Botão para cadastrar faixas de frete, abre modal com
            - Valor inicial
            - Valor final
        - Botão para cadastrar descargas, abre modal com
            - De
            - Até
            - Valor
    - Arquivos
        - Botão para upload de arquivos de proposta, abre modal com
            - Upload proposta de orçamento
            - Upload proposta de pedido
            - Opção de baixar modelo
            - Lista de variáveis que podem ser aplicadas na proposta
    - Carteira de integradores
        - Botão "Itens da conversa" que abre modal com
            - Lista de itens da conversa e botão pra formulário de novo, com campo "Descrição"

- Kits
    - [ ] Validar kit customizado
    - Nome a ser exibido nos kits prontos
    - Nome a ser exibido no menu Monte seu kit
    - Nome a ser exibido no novo menu Kit Pronto
    - Nome a ser exibido no novo menu Kit Plus 2
    - Quantidade de kits sugeridos
    - Marca
    - Descrição inicial dos kits gerados
    - [ ] Mostrar inersor e painel
    - [ ] Gerar descrição do kit em maiúsculo
    - [ ] Atualizar automaticamente os kits montados
    - [ ] Ordenar painéis em Montar Kit por valor do painel / Potencia do painel
    - Quantidade de painéis por fileira (Montar kit)
    - Quantidade de painéis por fileira (Gestão de kit)
    - Visualização padrão dos kits
        - Cards
        - Lista
        - Agrupamento Painel e Inversos
- Voucher
    - Modelo de e-mail do vendedor
        - [ lista dos modelos de email ]
    - Modelo de email do integrador
        - [ lista dos modelos de email ]
- Fidelidade
    - [ ] Ativo
    - Nome
    - Regra
        - Desconto
        - Valor venda
    - Botão "Produtos", abre modal com
        - Lista de produtos fidelidade
        - Botão adicionar com:
            - Foto
            - Produto
            - Pontos
            - Prazo de entrega (dias)
            - [ ] Ativo
    - Botão "Pontos", abre modal com
        - Lista de pontos de fidelidade
        - Botão adicionar com:
            - De (%)
            - Até (%)
            - Pontos (% do valor pedido)
            - Validade (meses)
    - Botão de adicionar banner (upload imagem)
- Atualização de produtos de centros de distribuição
    - Botão "Valores e estoque", abre modal com
        - Centros de Distribuição
            - [ lista dos CDs ]
        - Agrupamentos
            - [ lista de agrupamentos ]
        - Status
            - Ativo
            - Bloqueado
- Questionário de entrega
    - [ ] Usar questionário de entrega
    - [ ] Obrigar preenchimento do questionário de entrega
    - Botão "Cadastro de questionário", que abre um modal com:
        - Lista das perguntas
        - Botão "Nova pergunta", que abre formulário com:
            - Descrição
            - Tipo
                - Sim ou não
                - Texto
                - Ambos
            - Status
                - Ativo
                - Bloqueado

**Aba EMAIL**

Formulário para configura'dcão do serviço de e-mail

- Servidor SMTP
- Porta
- [ ] SSL
- [ ] TSL
- Usuário
- Senha
- Assinatura do e-mail

**Aba SIMULADOR FINANCEIRO**

Cadastro dos tipos de simulação financeira

- Banco ou financeira
    - [ lista de bancos ]
- Detalhes
- Número de parcelas
- Desconto
- Taxa
- [ ] IOF

**Aba IDENTIDADE VISUAL**

Configuração das variáveis de configuração do layout

- Fundo Menu/Background(Login, Recuperar senha, Cadastro)
- Default
- Primary
- Success
- Info
- Warning
- Danger
- Rose
- Gráficos
- [ ] Usar cores personalizadas acima
- Upload Logo principal
- Upload Logo menu
- Upload logo menu menor
- Background (imagem de fundo do l ogin e do cadastro)

**Aba CRM**

- [ ] Somente o dono do card pode visualizar o valor
- [ ] Somente o dono da atividade pode editá-la
- [ ] Confirmar mucança de etapa
- [ ] Alterar atividades
