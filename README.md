# Calculadora de Partidas Rankeadas
Este projeto é uma simples calculadora de partidas rankeadas desenvolvida em JavaScript. A aplicação calcula o saldo de vitórias e derrotas de um jogador e determina seu nível com base nesse saldo. O objetivo é fornecer uma forma rápida e intuitiva de classificar jogadores em diferentes níveis de acordo com seu desempenho.

## Funcionalidades
Cálculo de Saldo: A aplicação subtrai o número de derrotas do número de vitórias para calcular o saldo do jogador.
Classificação de Nível: Com base no saldo calculado, o jogador é classificado em um dos seguintes níveis:
Ferro
Bronze
Prata
Ouro
Diamante
Lendário
Imortal
### Saída de Dados:
O saldo e o nível do jogador são exibidos no console, permitindo uma fácil visualização dos resultados.
## Como Usar:
Clone o repositório para o seu ambiente local.
Abra o arquivo index.js e ajuste os valores das variáveis vitorias e derrotas conforme necessário.
Execute o código para ver o saldo e o nível do jogador no console.
O nível do jogador também é retornado pela função resultado e pode ser usado em outras partes do seu projeto.

## Exemplo 
let vitorias = 100;
let derrotas = 3;

let nivelDoHeroi = resultado(vitorias, derrotas);

Exemplo
