# Fotus Distribuidora Solar

## Acesso ao sistema

Atualmente o sistema funciona com autenticação básica, sem implementações adicionais de segurança.

Há também acesso por API, com emissão de token JWT simplificado, com assinatura HS256.

## Telas, formulários e relatórios

### Gestão de Usuários

Lista de usuários e formulário para cadastro e edição. O formulário é composto pelos campos e opções abaixo:

- Foto
- CPF
- Nome
- Nome abreviado
- CEP
- Logradouro
- Número
- Complemento
- Bairro
- UF
- Cidade
- Pode ver Excel (Habilita um botão de excel em algumas telas)
- Pode editar venda direta (Dá autorização ao operador editar uma venda feita diretamente para o cliente final)
- Data admissão
- Data nascimento
- E-mail
- Perfil
    - Operador
    - Administrador
- Limite de desconto
- Tabela de comissão
- Código ERP
- Permissões e acesso
    - 1 Gerente
    - 2 Coordenador de Equipe
    - 3 Lider de Equipe
    - 4 Vendedor
    - 5 Suporte Técnico
    - 6 Backoffice
    - 7 Customer Experience
    - 8 Sales Development Representative (SDR)
    - 9 Célula de Financiamento
    - 9.1 Faturamento
    - 9.2 Logística
    - 9.3 BI
    - 9.4 TI
    - 9.5 Pricing
    - 9.6 Compras
    - 9.7 Customer Service
    - 9.8 Contador
    - 9.9 Marketing
- Acesso (permissões avulsas)
    - [ lista de telas ([lista](#permissões-de-acesso) ) ]
    - [ lista de relatórios ([lista](#permissões-de-acesso) ) ]
- Centro de distribuição padrão
    - CD Centro-Oeste
    - CD Nordeste
    - CD Norte
    - CD Sudeste
    - CD Sul
- Setores
    - Adm de vendas - conferência
    - Adm de vendas - financeiro
    - Adm de vendas - outros
    - Adm de vendas - pendência
    - Adm de vendas - triagem
    - Backoffice
    - CS
    - CX
    - Logística
    - Marketing
    - SDR
    - Suporte técnico
    - Transformação digital
    - Vendas
- Gestor das filas
    - Análise de desconto
    - Célula de financiamento
- Flags
    - Ativo
    - Cancela pedido
    - Pode alterar lider do time
    - Pode alterar vendedor do orçamento
    - Pode editar frete manual
    - Pode editar seguro
    - Pode editar serviço entrega
    - Pode gerar combinações automaticamente
    - Pode lançar desconto individual
    - Pode ver estoque
    - Pode ver totalizadores
    - Vendedor
    - Visualiza custos
    - Visualizar gestão avançada

### Permissões de acesso

A partir da listagem de telas e relatórios, são criados perfis de acesso aos usuários do sistema com o vínculo de cada
tela ou grupo de telas.

O cadastro de permissões possui os seguintes campos:

- Descrição
- Telas
    - Plataforma Distribuidor
        - Dashboard
        - Montar Kit
        - Kit fechado
        - Avulso
        - Orçamentos
            - Orçamento - Novo
            - Orçamento - Editar
        - Pedidos
            - Pedidos - Histórico
            - Pedidos - Novo
            - Pedidos - Editar
            - Pedidos - Pago
            - Pedidos - Pendente
            - Pedidos - Falha
        - Contatos
        - Integradores
            - Integradores - Novo
            - Integradores - Editar
        - Relatórios
        - Configurações
            - Etapas
            - Modelos de e-mail
                - Modelos de e-mail - Novo
                - Modelos de e-mail - Editar
            - Gestão de descontos
            - Usuários
                - Usuários - Novo
                - Usuários - Editar
            - Formas de pagamento
                - Formas de pagamento - Novo
                - Formas de pagamento - Editar
            - Condições de pagamento
                - Condições de pagamento - Novo
                - Condições de pagamento - Editar
            - Produtos
                - Produtos - Novo
                - Produtos - Editar
            - Times
            - Premissas
            - Combinação de kits
            - Tabela de fretes
            - Modelos de download
                - Modelos de download - Novo
                - Modelos de download - Editar
            - Status de orçamento
                - Status de orçamento - Novo
                - Status de orçamento - Editar
            - Motivos de perda
                - Motivos de perda - Novo
                - Motivos de perda - Editar
            - Promoções
                - Promoções - Novo
                - Promoções - Editar
            - Matérias
                - Matérias - Novo
                - Matérias - Editar
            - Tabelas classificação personalizada
            - Voucher geral
            - Voucher automático
            - Descarga
                - Descarga - Novo
                - Descarga - Editar
            - Permissões de acesso
                - Permissões de acesso - Novo
                - Permissões de acesso - Editar
            - Fornecedores
            - Anexos
                - Anexos - Novo
                - Anexos - Editar
            - Fornecedores de estruturas
            - Estruturas
            - Serviço de entrega
                - Serviço de entrega - Novo
                - Serviço de entrega - Editar
            - Seguro
                - Seguro - Novo
                - Seguro - Editar
            - Gestão de kits
            - Status de contrato
                - Status de contrato - Novo
                - Status de contrato - Editar
            - Setores
            - Lojas de integrações
            - Pendências
                - Pendências - Novo
                - Pendências - Editar
            - Fluxos de trabalho
                - Fluxos de trabalho - Novo
                - Fluxos de trabalho - Editar
            - Embalagem
                - Embalagem - Novo
                - Embalagem - Editar
            - Grupo motivo perda
                - Grupo motivo perda - Novo
                - Grupo motivo perda - Editar
            - Etapa da ocorrência
            - Precificação por UF
            - Transferência de itens de vendedor
            - Etapas do rastreio
            - Status do repasse
                - Status do repasse - Novo
                - Status do repasse - Editar
            - Tags
                - Tags - Novo
                - Tags - Editar
            - Tipos de ocorrência
            - Classificação integrador
            - Centros de distribuição
            - Financiamento
                - Geral
        - Monitor triagem
        - Monitor pendência
        - Análise desconto
        - Kit plus
        - Kit plus 2
        - Monitor vendas
        - Monitor integração
        - Monitor financeiro
        - Monitor financiamento
        - Monitor separação
        - Monitor fiscal
        - Monitor expedição
        - Monitor pedidos
        - Repasses
        - Controle ocorrências
            - Controle ocorrências - Novo
            - Controle ocorrências - Editar
            - Controle ocorrências - Lançamento
        - Monitor conferência
        - Monitor verificação
        - Monitor análise financeira
        - Monitor faturamento
        - Carteira integradores
        - Programa de fidelidade
        - Calendário atividade
        - Fechamento financeiro
            - Fechamento financeiro - Consulta
            - Fechamento financeiro - Novo
            - Fechamento financeiro - Editar
        - Central de simulação de financiamento
        - Financiamentos
        - Monitor de proposta
- Relatórios
    - Integradores
        - Integradores
        - Acessos
    - Orçamento/Pedidos
        - Orçamentos: sintético
        - Orçamentos: sintético - Painel / Inversor
        - Orçamentos: analítico
        - Pedidos: sintético
        - Pedidos: analítico
        - Pedidos pagos
        - Pedidos pendentes de pagamento
        - Pedidos faturados
        - Vendas: sintético
        - Vendas: analítico
        - Lucratividade vendas confirmadas
        - Lucratividade vendas aprovadas
        - Comissão vendas confirmadas
        - Comissão vendas aprovadas
        - Motivo de perda sintético
        - Motivo de perda analítico
        - Recebimentos
        - Comissão por time
        - Pagamentos aprovados
        - Produtos vendidos
        - Fretes
        - pedidos por time
        - Telemarketing
        - Pedidos integrados
        - Painel / Inversão integrados
        - Cupons de desconto
        - Orçamentos / Pedidos por colaborador
        - Lucratividade geral
        - Lucratividade por produto

## Mapeamento das demais telas do CRM

### Configurações

#### GESTÃO DE DESCONTOS

`TODO: (avaliar funcionalidade da página)`

No início da tela é exibido um quadro com o desconto máximo do usuário que está logado. Esse valor não interfere no
formulário logo abaixo.

A tela possui duas abas:

- Classificação dos integradores
    - Lista dos perfis de integrador com campo de limite de desconto
- Filtros avançados

  Permitem que descontos sejam aplicados em massa no resultado encontrado nos filtros abaixo:
    - Regras
        - Vendedor
        - Tags `(analisar necessidade)`
        - UF
        - Cidade
        - Desconto
        - Desconto máximo

#### ANEXOS

Registro dos anexos solicitados no cadastro de integrador, possuindo os seguintes campos:

- Título
- Descrição
- Obrigatório
    - Sim
    - Não

#### TIMES (de vendas)

Página para o cadastro dos times de vendas, com as seguintes informações:

- Nome
- Permissão para ver o mesmo nível
- Permissão para ver somente hierarquia
- Botão para adicionar um time abaixo
- Aplicação do funil comercial

A hierarquia de times permite que os mais altos na hierarquia enxerguem pedidos das pessoas abaixo, tendo permissões de
acordo com seu perfil.

Exemplo: Um coordenador consegue enxergar todos os pedidos dos seus líderes e vendedores abaixo deles.

Também, nos detalhes do pedido, os superiores do vendedor são exibidos no quadro das informações adicionais.

#### PRODUTOS

Página para cadastro dos produtos, com as seguintes informações:

- Foto
- Código de barras (GTINS)
- Referência
- Unidade
- Situação
    - Ativo
    - Bloqueado
- Atualiza estoque ERP
    - Sim
    - Não
- Descrição
- Descrição na proposta e contrato
- Descrição resumida
- Marca
    - [ lista de marcas ]
- Modelo
- Peso bruto (kg)
- Agrupamento
    - Kit (Kit gerador fotovoltaico)
    - Painel
    - Inversor
    - Stringbox
    - Cabo
    - Estrutura
    - Transformador
    - Bateria
    - Outros
- Tipo
    - Inteiro
    - Fracionado
    - Serviço
- Centros de distribuição
    - CD Sudeste
    - CD Nordeste
    - CD Norte
    - CD Sul
    - CD Centro-Oeste
- Link do datasheet
- Código no ERP
- Nacionalidade
    - Nacional
    - Importado
- Visibilidade
    - Todos
    - Vendedor
- [ ] Aparecer avulso
- [ ] Aparecer no HubB2B
- [ ] Exibir cálculo R$/Wp na descrição do monte seu kit

**Quando o agrupamento for Kit**:

- Potência
- Área
- Telhado
    - Sem estrutura
    - Cerâmico
    - Fibrocimento
    - Fibrometal
    - Metálico
    - Mini trilo
    - Laje
    - Solo
    - [ ] Mais vendido
    - [ ] Promocional
- Composição
    - Modal aberto com as abas para inserção dos produtos do kit
        - Painel
        - Inversor
        - Cabo
        - Stringbox
        - Estrutura
        - Bateria
        - Outro

**Quando o agrupamento for Painel**:

- Potência
- Área
- Largura
- Algura
- Comprimento
- Eficiência
- IMP
- ISC
- Tensão
- Conector específico (Código ERP)
- Descontos do produto
    - Abre-se uma tabela para a lista de descontos com as características:
        - Quantidade inicial
        - Quantidade final
        - [ ] Desconto
            - Desconto
            - Desconto custo
        - [ ] Desconto em lote
            - Desconto inicial
            - Desconto final
            - Desconto custo inicial
            - Desconto custo final

**Quando o agrupamento for Inversor**:

- Tipo de ligação
    - Monofásica
    - Trifásica
- Tensão
    - 220
    - 380
    - 440

**Quando o agrupamento for Stringbox**:

- Número de entradas
- Número de saídas

**Quando o agrupamento for Transformador**:

- Potência (va)
- Área (m2)

#### FORNECEDORES DE ESTRUTURA

Cadastro dos fornecedores de estrutura para instalação dos kits

- Upload da logo
- Nome
- [ ] Ativo

#### ESTRUTURAS

`TODO: (avaliar funcionalidade da página)`

Tipos de estrutura para montagem e instalação de kits. Na página é possível
configurar uma estrutura e atribuir os produtos para instalação.

#### GESTÃO DE KITS

`TODO: (avaliar funcionalidade da página)`

A página contém as abas "Criar novos kits" e "Editar kits criados". Aparentemente não usada no momento.

- Criar novos kits
    - Painel
        - [ lista de painéis ]
    - Marca do inversor
        - [ lista de marcas ]
    - Centro de distribuição
        - [ lista dos CDs ]
    - Fase
        - Monofásico
        - Trifásico
    - Tensão
        - 220 (se monofásico)
        - 220, 380 e 380+ (se trifásico)
    - Potênca válida
        - De (kWp)
        - Até (kWp)
    - Tipo de telhado
        - Cerâmico
        - Fibrocimento
        - Fibrometal
        - Metálico
        - Mini trilo
        - Laje
        - Solo
        - Sem estrutura
    - Fornecedor da estrutura
        - [ lista de fornecedores ]
    - Tipo de inversor
        - String
        - Micro
        - Híbrido
    - Descrição inicial
    - Quantidade mínima de inversores
    - Quantidade máxima de inversores
    - Menu de origem
        - Oferta Fotus
        - Fast Track
        - Kits Prontos
    - Radio: Desconto / Acréscimo
    - Porcentagem do desconto/acrésscimo

No final há um botão para gerar os kits e após gerada a lista, o botão para salvar os kits.

#### COMBINAÇÃO DE KITS

`TODO: (avaliar funcionalidade da página)`

*OBS*: Há um botão crítico nessa página, que é o "Gerar combinações automaticamente." O botão não possui uma confirmação
e, se clicado, inicia automaticamente a gerar os kits.

Há necessidade de validar se o processo acontece em background ou se, ao carregar a páginam o porocesso é interrompido.

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
      uma lista com os produtos e suas regras, além de um botão para adicionar um cabo.
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
            - Ao clicar noss botões, um novo modal é sobreposto sendo o conteúdo com as abas que exibem as listas de
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
    - É permitido selecionar um produto de cada aba e no final abre-se um novo modal com um campo de texto livre "
      Fórmula", que possui botões de ajuda para compor um texto com variáveis e funções, que definirão a fórmula gerada.

#### TABELA DE FRETES

Página para cadastro das tabelas de frete de acordo com a região e UF.

Para cadastrar uma nova tabela, deve-se preencher os campos:

- Região
- UF
- Filtro de cidade (ou deixar vazio para todas)
- Transportadora [lista com transportadoras cadastradas]
- Com a transportadora selecioanda, clicar no botão "Vincular cidades". Isso fará com que a transportadora seja
  vinculada àquela cidade.
- Com a lista de cidades, clicar no botão de edição, que abre o modal com os campos:
    - Prazo de entrega (dias)
    - Prazo de coleta (dias)
    - Prazo de despqcho (dias)
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

#### USUÁRIOS

[Ver detalhamento](#Usuários)

#### FORMAS DE PAGAMENTO

Cadastro das formas de pagamento disponíveis para os integradores. O formulário contém os seguintes campos:

- Descrição
- Código ERP
- Situação
    - Ativo
    - Bloqueado
- Tipo
    - Normal
    - Mercado pago
- [ ] Serviço / repasse
- [ ] Boleto
- [ ] Financiamento
- [ ] Financiamento próprio
- Centros de distribuição vinculados
    - Seleção múltiplas dos CDs
- Condições de pagamento vinculadas
    - Seleção múltipla das condições de pagamento

#### CONDIÇÕES DE PAGAMENTO

Cadastro das condições de pagamento disponíveis para os integradores. O formulário contém os seguintes campos:

- Descrição
- Código ERP
- Número de parcelas
- Dias entre parcelas
- Taxa
- Situação
    - Ativo
    - Bloqueado
- [ ] Possui entrada
- Limites
    - [ ] Valor mínimo do orçamento / pedido
        - Valor mínimo
    - [ ] Valor máximo do orçamento / pedido
        - Valor máximo

#### MODELOS DE E-MAIL

Modelos de e-mail utilizados na aplicação para comunicação com clientes.

O cadastro dos modelos contém os seguintes campos:

- Nome
- Tipo
    - Normal
    - Boas-vindas
    - Cancelamento
    - Contrato
    - Aviso de estoque mínimo
    - Aviso mudança para "Em andamento" da ocorrência
- Texto do e-mail
- Anexos
    - Botão de upload de arquivos que serão anexados ao e-mail

#### PROMOÇÕES

Página para o cadastro de promoções, contendo os seguintes campos:

- Imagem
- Descrição
- Classificações
    - [lista dos perfis dos integradores]
- Data de início
- Data de fim
- [ ] Ativo
- Botão "Selecioanr kit"
    - Modal com a lista dos kits disponíveis

#### MATÉRIAS E NOTÍCIAS

CRUD para cadastro de matérias e notícias exibidas na plataforma. Formulário simples que consiste em:

- Imagem
- Título
- Link
- [ ] Ativo

#### PREMISSAS DA EMPRESA

#### LOJA DE INTEGRAÇÕES

Tela para ativação de integrações com terceiros, aplicando as credenciais necessárias para as integrações.

A lista parece ser fixa do que é compatível com a Solaryum.

- Gateways de pagamento
    - Sicredi Boleto
    - Sicredi Pix
    - Getnet
    - Banco Itaú boleto/pix
    - Banco do Brasil Pix
- Cadastro
    - CNPJ Já
- Gateways de financiamento
    - Banco BV
    - Banco BTG
    - Banco fake (para testes)

Analisar a real necessidade para a Fotus, do que é aplicável para a situação atual.

#### LOJA DE PRODUTOS

`TODO: validar funcionamento da página`

#### FLUXOS DE TRABALHO

Página para gerenciar fluxos de mensagens da aplicação.

O formulário para registro do fluxo contém os seguintes campos:

- Nome
- Descrição
- Quando
    - Atividade
        - Concluir
            - Atividade
                - Email
                - Ligação
                - Orçamento
                - Retorno
                - Reunião
                - Visita
            - Efeito
                - Qualquer
                - Negativo
                - Positivo
                - Neutro
        - Criar
            - Atividade
                - Bate-papo
                - Email
                - Ligação
                - Orçamento
                - Retorno
                - Reunião
                - Visita
    - Integrador
        - Criar
        - Trocar de vendedor
    - Login
        - Integrador
    - Oportunidade
        - Encerrar com efeito negativo
        - Encerrar com efeito positivo
        - Entrar na etapa
            - Funil
                - [ lista de funis ]
            - Etapa
                - [ lista de etapas do funil selecionado ]
        - Entrar na etapa
            - Funil
                - [ lista de funis ]
            - Etapa
                - [ lista de etapas do funil selecionado ]
        - Sair da etapa
    - Orçamento
        - Criar
    - Pedido
        - Criar
    - Temporal
        - A cada hora
        - Diariamente
        - Semanalmente
        - Mensalmente
- E se (opcional)
    - Testa alguma condição correspondente
        - Condição
            - Oportunidade
                - Etapa
                - Situação
        - Status dos cards
            - Aberta
            - Perdida
            - Ganha
            - Congelada
            - Excluída
- Então faça
    - Atividade
        - Criar
            - Título
            - Atividade
                - Bate-papo
                - Email
                - Ligação
                - Orçamento
                - Retorno
                - Reunião
                - Visita
            - Responsável
                - [ lista de times com hierarquia ]
            - Inicia em (dias)
            - Hora
            - Duração
                - 5 min
                - 15 min
                - 30 min
                - 1h
                - 2h
                - 4h
                - 7h
                - 8h
            - Descrição
            - Anotação
            - [ ] Única do mesmo tipo
        - Enviar Convite
            - Para
                - Vendedor
                - Integrador
                - Ambos
            - Assunto
        - Enviar resumo
            - Funil atual
                - [ lista de funis ]
            - Etapa atual
                - [ lista de etapas do funil selecionado ]
            - Proprietário atual
                - Lista de times com hierarquia
            - Dias da semana para envio
                - Múltipla seleção de dias da semana
            - Assunto
    - Integrador
        - Alterar Vendedor
            - Dono
                - [ lista de times com hierarquia ]
    - Notificação
        - Enviar e-mail
            - Modelo
                - [ lista de modelos ]
            - De
                - [ lista de times com hierarquia ]
            - Para
                - [ lista de times com hierarquia ]
        - Enviar notificação
            - Para
                - [ lista de times com hierarquia ]
            - Mensagem
    - Oportunidade
        - Alterar etapa
            - Funil
                - [ lista de funis ]
            - Etapa
                - [ lista de etapas do funil selecionado ]
        - Buscar
            - Tipo de busca
                - Primeira
                - Última
                - Todos
            - Data
            - Tempo
            - Funil atual
                - [ lista de funis ]
            - Etapa atual
                - [ lista de etapas do funil selecionado ]
            - Proprietário atual
                - [ lista de times com hierarquia ]
        - Criar
            - Título
            - Dono
                - [ lista de times com hierarquia ]
            - Funil
                - [ lista de funis ]
            - Etapa
                - [ lista de etapas do funil selecionado ]
            - [ ] Única nesse funil
        - Duplicar
            - Dono
                - [ lista de times com hierarquia ]
            - Funil
                - [ lista de funis ]
            - Etapa
                - [ lista de etapas do funil selecionado ]
            - [ ] Única nesse funil
            - [ ] Copiar atividades
            - [ ] Zerar valor

#### PRECIFICAÇÃO POR UF

CRUD para configurar a % de precificação por UF com os seguintes campos

- UF
    - [ lista de UFs]
- Tipo
    - Desconto
    - Acréscimo
- Valor (%)

#### TRANSFERÊNCIA VENDEDOR

Formulário para transferência de todos os itens de um vendedor, alterando os status tanto do vendedor de origem quanto
do vendedor de destino.
O formulário contém os seguintes campos:

- Status
    - Todos
    - Ativo
    - Bloqueado
- De
    - [ lista de times com hierarquia ]
- Para
    - [ lista de times com hierarquia ]
- [ ] Clientes
- [ ] Orçamentos
- [ ] Pedidos

#### CENTROS DE DISTRIBUIÇÃO

CRUD dos centros de distribuição. O formulário contém os seguintes campos:

- Descrição
- Sigla
- Tags
    - [ múltipla seleção de tags pré-cadastradas ]
- [ ] Habilita integração distribuidor
- [ ] Pode ver rastreio

#### FINANCIAMENTO

Tela de configuração de financiamento, com formulário contendo:

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

#### VOUCHER GERAL

CRUD para criação de vouchers de promoção, contendo os campos:

- Código
- Descrição
- Prazo de validade (dias)
- Valor mínimo do pedido
- Tipo de desconto
    - % sobre o pedido
    - R$ sobre o pedido
- Valor do desconto
- Benefícios
- Condições

#### CRM

CRUD para cadastro dos funis de venda, separados pelos submenus abaixo:

FUNIS

- Descrição
- Tipo de funil
    - Normal
    - Carteira de integradores
    - Integradores sem vendedores
- [x] Habilitar positivo
    - Texto botão personalizado
- [x] Habilitar negativo
    - Texto botão personalizado
- Etapas do Funil
    - Descrição
    - [x] Exibir valor
        - Orçamentos
        - Pedidos
            - Etapa
                - [ múltipla seleção de etapas ]
            - Orçamentos
                - Todos
                - Ativos
                - Expirados

TIPOS DE ATIVIDADE

- Descrição
- Status
    - Ativo
    - Bloqueado
- Ícone
    - [ seleção de ícones pré-definidos ]
- Ações de conclusão
    - [x] Habilitar positivo
        - Texto botão personalizado
    - [x] Habilitar negativo
        - Texto botão personalizado
- Responsáveis
    - Adicionar responsáveis
        - [ modal com lista de usuários com checkboxes para seleção múltipla ]

TAGS
- Tag
- Status
  - Ativo
  - Bloqueado
- Ícone
    - [ seleção de ícones pré-definidos ]
- Cor
  - Color-picker para seleção de cor

CAMPOS PERSONALIZADOS
- Descrição
- Tipo
  - Texto
  - Número
  - Data
- [ ] Obrigatório
- Status
  - Ativo
  - Bloqueado

#### TABELAS ADICIONAIS

Diversas subpáginas com cruds 

---

# Dores atuais

- Dar permissão ao backoffice para:
    - cancelar um pedido em qualquer etapa
    - cancelar pedidos de consultores que já foram desligados
- Pedidos
    - No envio de mensagens por pedidos, as mensagens privadas podem ser enviadas para todo o setor e não somente a
      operadores específicos
- Relatórios
    - Revalidar os relatórios atuais, pois eles não geram doados coerentes
- Times
    - Usuários que não fazem parte do time de vendas, mas que precisam ter visão dos dados dos pedidos (ex: Backoffice),
      precisam ser vinculados a times especiais com poderes de visualização e edição como se fossem da raiz da
      hierarquia.
    - Tratar na gestão de times, os contextos:
        - Vendas (consegue enxergar somente o que está no seu nível e abaixo)
        - SDR / Backoffice (consegue enxergar todos os níveis)
- Integradores
    - A lista de integradores do menu sempre exibe todos os integradores. O ideal é que somente sejam exibidos
      integradores sem vínculo. Sugestão é criar um item do menu para vendedores encontrarem integradores órfãos.
    - Nos integradores órfãos listados, o vendedor tem a única opção de adicionar apontamentos, cabendo ao seu gestor a
      possibilidade de transferir esse integrador para sua carteira. 
  