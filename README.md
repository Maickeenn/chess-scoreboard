# Chess Score Overlay

Este projeto é uma sobreposição de pontuação de xadrez para ser usada em transmissões ao vivo, como no OBS. Ele exibe o placar de vitórias, empates, derrotas e a mudança de rating de um jogador de xadrez.

## Funcionalidades

- Exibe o número de vitórias, empates e derrotas.
- Mostra a mudança de rating do jogador.
- Filtra jogos por modo (Bullet, Blitz, Rapid, Classic).
- Atualiza automaticamente a cada segundo.

## Como Usar

1. Clone o repositório:
    ```sh
    git clone https://github.com/Maickeenn/chess-scoreboard.git
    ```

2. Abra o arquivo `teste.html` em um navegador.

3. Adicione os parâmetros na URL:
    - `username`: Nome de usuário do Chess.com.
    - `datetime`: Data e hora de início no formato `YYYY-MM-DD` ou `YYYY-MM-DD HH:MM`.
    - `mode`: Modo de jogo (B para Bullet, BL para Blitz, R para Rapid, C para Classic).

   Exemplo de URL:
    ```
    file:///caminho/para/teste.html?username=seu_usuario&datetime=2023-01-01%2012:00&mode=BL
    ```

## Estrutura do Projeto

- `teste.html`: Arquivo principal que contém o HTML, CSS e JavaScript para a sobreposição.

## Dependências

- Nenhuma dependência externa é necessária.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
