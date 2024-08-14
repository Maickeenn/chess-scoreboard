# Chess Score Overlay

Este projeto é uma sobreposição de pontuação de xadrez para ser usada em transmissões ao vivo, como no OBS. Ele exibe o placar de vitórias, empates, derrotas e a mudança de rating de um jogador de xadrez.

## Funcionalidades

- Exibe o número de vitórias, empates e derrotas.
- Mostra a mudança de rating do jogador.
- Filtra jogos por modo (Bullet, Blitz, Rapid, Classic).
- Atualiza automaticamente a cada segundo.

## Como Usar

1. Acesse a URL:
    ```
    https://maickeenn.github.io/chess-scoreboard?username=seu_usuario&datetime=2024-08-01&mode=B
    ```

2. Adicione os parâmetros na URL:
   - `username`: Nome de usuário do Chess.com.
   - `datetime`: Data e hora de início no formato `YYYY-MM-DD` ou `YYYY-MM-DD HH:MM`.
   - `mode`: Modo de jogo (B para Bullet, BL para Blitz, R para Rapid, C para Classic).

## Modos de Jogo

- **B (Bullet)**: Partidas rápidas com tempo de jogo muito curto.
- **BL (Blitz)**: Partidas com tempo de jogo curto, mas mais longo que Bullet.
- **R (Rapid)**: Partidas com tempo de jogo moderado.
- **C (Classic)**: Partidas com tempo de jogo longo, geralmente diárias.

## Estrutura do Projeto

- `index.html`: Arquivo principal que contém o HTML, CSS e JavaScript para a sobreposição.

## Dependências

- Nenhuma dependência externa é necessária.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
