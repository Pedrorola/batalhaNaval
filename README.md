# Batalha Naval - Oceanic Games

## Visão Geral
Este projeto implementa a base de um jogo de Batalha Naval em linguagem C para a empresa Oceanic Games. O programa atual representa o primeiro nível de desenvolvimento (Novato), que permite criar um tabuleiro e posicionar navios com validação de posicionamento.

## Funcionalidades
- **Criação de um tabuleiro 10x10**
- **Posicionamento de dois navios de tamanho 3**:
  - Um na horizontal
  - Um na vertical
- **Validação completa do posicionamento dos navios**:
  - Verificação de limites do tabuleiro
  - Prevenção de sobreposição de navios
- **Exibição visual do tabuleiro no console**

## Estrutura do Código
- **Definição de constantes**: Facilita a manutenção e legibilidade do código
- **Funções modularizadas**:
  - `inicializarTabuleiro()`: Preenche o tabuleiro com água (valor `0`)
  - `validarPosicaoNavio()`: Verifica se um navio pode ser posicionado em determinadas coordenadas
  - `posicionarNavio()`: Coloca um navio no tabuleiro após validação
  - `exibirTabuleiro()`: Mostra o estado atual do tabuleiro no console

## Legenda do Tabuleiro
- `0`: Água  
- `3`: Navio  

