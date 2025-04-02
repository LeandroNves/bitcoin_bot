# Bot de Trading para Bitstamp

Este é um bot de trading para a plataforma **Bitstamp** que utiliza **WebSocket** para obter os preços em tempo real do par de moedas **BTC/USD**. O bot realiza operações de compra e venda no mercado baseado em condições de preço específicas.

## Funcionalidades

- **Conexão WebSocket**: Conecta-se ao WebSocket da Bitstamp e assina o canal de transações ao vivo para o par **BTC/USD**.
- **Compra e Venda Automática**: Realiza compras e vendas automáticas de Bitcoin com base em condições de preço predefinidas.
- **Condições de Preço**: O bot compra quando o preço está abaixo de $8100 e vende quando está acima de $10000.
- **Logs em Tempo Real**: Exibe o preço atual do BTC e o status das operações no terminal.

## Requisitos

Para rodar este projeto, você precisa ter o Python instalado em sua máquina, além das dependências necessárias:

- **websocket-client**: Biblioteca para interagir com o WebSocket da Bitstamp.
- **bitstamp**: Biblioteca para realizar operações de trading na Bitstamp.
- **ssl**: Módulo nativo do Python para segurança nas conexões.

### Instalar Dependências

Execute o seguinte comando para instalar as dependências do projeto:

```bash
pip install websocket-client
pip install bitstamp
