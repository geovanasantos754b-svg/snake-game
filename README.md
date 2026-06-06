# snake-game
Jogo criado no curso do SENAI utilizado ChatGPT 
🐍 Snake Game Web

Um jogo clássico da cobrinha desenvolvido para navegador utilizando HTML, CSS e JavaScript. O objetivo é controlar a cobra, coletar alimentos e alcançar a maior pontuação possível sem colidir com as paredes ou com o próprio corpo.

🎮 Demonstração

O Snake Game apresenta uma interface simples e intuitiva, permitindo que o jogador inicie rapidamente uma partida e acompanhe sua evolução através do sistema de pontuação e recorde.

Recursos disponíveis
🐍 Movimentação da cobra em tempo real
🍎 Sistema de geração de alimentos
🎯 Controle de pontuação
🏆 Sistema de recorde (High Score)
⌨️ Controle por teclado
🔄 Reinício de partida
🎨 Interface amigável
⚡ Atualização dinâmica do jogo
📖 Sobre o Projeto

O Snake Game é uma recriação digital de um dos jogos mais populares da história dos videogames.

O projeto foi desenvolvido com o objetivo de praticar conceitos fundamentais de desenvolvimento web, incluindo:

Manipulação do DOM
Programação orientada a eventos
Estruturas de dados
Controle de estados
Desenvolvimento de jogos 2D
Lógica de programação
🎯 Objetivo do Jogo

O jogador deve controlar a cobra pelo cenário coletando alimentos para aumentar sua pontuação.

A cada alimento consumido:

A cobra cresce de tamanho;
A pontuação aumenta;
O nível de dificuldade aumenta gradativamente.

O jogo termina quando ocorre uma colisão.

⌨️ Controles
Tecla	Ação
⬆️	Mover para cima
⬇️	Mover para baixo
⬅️	Mover para esquerda
➡️	Mover para direita
🏗️ Arquitetura do Projeto

O sistema é dividido em componentes responsáveis por diferentes partes da aplicação:

🎮 Game Engine

Responsável pelo gerenciamento geral do jogo.

Funções:

Inicializar partida;
Controlar o loop principal;
Atualizar estados;
Gerenciar reinício do jogo.
🐍 Snake Controller

Responsável por:

Controlar a movimentação;
Atualizar posições;
Crescimento da cobra;
Verificação de colisões.
🍎 Food Generator

Responsável por:

Gerar novos alimentos;
Posicionar alimentos aleatoriamente;
Detectar consumo.
📊 Score Manager

Responsável por:

Atualizar pontuação;
Registrar recordes;
Exibir informações na interface.
