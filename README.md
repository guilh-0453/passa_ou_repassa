Trabalho MK 2022 - Sistemas Embarcados

Eric Ryuta Nakao 10746922

Guilherme H. S. Rosa 10873299

Rayron Costa e Silva 10820741

# Passa-ou-Repassa

## Introdução

No presente trabalho, tem-se como objetivo o desenvolvimento de um jogo realizado em programas de palco, o qual consiste em apresentar perguntas para cada participante/equipe e passar o direito de resposta a quem apertar mais rápido seu respectivo botão.

## Envelope de trabalho

### Requisitos do sistema:
- Mais de um botão (um para cada participante/equipe)
- Indicações visuais tanto de início do jogo quanto para apontar qual botão foi apertado primeiro e por qual participante/equipe

### Funcionalidades do sistema:
- Indicação visual do início do jogo
- Indicação visual do primeiro botão pressionado
- Indicação visual do reset da partida
- Indicação visual da possibilidade de um dos botões serem apertados antes do botão de início ter sido pressionado
- Dispensa do uso de um computador "host"

### Descrição da arquitetura

![Image of Architecture](https://github.com/gcaurin/EmbeddedSystems-Aeronautics/blob/2021.2/projects-descriptions/Arquitetura.jpg)
  1. 3 Entradas - botões a serem pressionados (Início, participante/equipe 1 e participante/equipe 2)
  2. 4 Saídas  - LEDs (Início, participante/equipe 1, participante/equipe 2 e "queima de largada")
  3. 1 display para indicação do estado do jogo

### State Machine for the Software implementation of the Game
![MaquinadeEstado](https://user-images.githubusercontent.com/109768690/180353805-88a5c211-582f-4140-8271-7f50b2dc80a6.png)