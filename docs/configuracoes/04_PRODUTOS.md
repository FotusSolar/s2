#### PRODUTOS

Sistema de cadastro dos produtos no Solaryum, com as seguintes informações:

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
- Altura
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
