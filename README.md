# Jogo de Plataforma com Pygame

Este é um projeto de jogo de plataforma desenvolvido em Python utilizando a biblioteca Pygame. O jogo apresenta um ambiente de plataforma com um jogador interativo, obstáculos, animações e coliçoes.

## Dependências

- [Pygame](https://www.pygame.org/): Certifique-se de ter o Pygame instalado para executar este jogo.

## **Instalação e Execução do projeto**

### **1. Clonando o Repositório**:
Primeiro, clone o repositório para sua máquina local usando o Git:
```
git clone https://github.com/DemetriosCoutinho/task-sage.git
cd task-sage
```

### **2. Criando um Ambiente Virtual**:
O ambiente virtual é uma maneira de isolar as dependências do projeto para evitar conflitos com outros projetos. Aqui está como criar um:

**Para Linux/Mac**:
```
python3 -m venv venv
source venv/bin/activate
```

**Para Windows**:
```
python -m venv venv
.\venv\Scripts\activate
```

Após executar esses comandos, seu terminal ou prompt de comando deve indicar que o ambiente virtual está ativo, geralmente prefixando o prompt com `(venv)`.

### **3. Instalando as Dependências**:
Com o ambiente virtual ativado, instale as dependências necessárias usando o pip:
```
pip install -r requirements.txt
```


## Estrutura do Projeto

1. **assets**: Pasta que armazena recursos do jogo, como imagens de fundo, sprites e outros.
2. **soms**: Pasta que armazena efeitos sonoros no jogo.
3. **codigo**: Pasta que armazena codigo do jogo.
4. **soms**: Pasta que armazena efeitos sonoros no jogo.
5. **requirements.txt**: aquivo que armazena dependencias do projeo.

## Controles

- Setas direcionais esquerda/direita: Mover o jogador.
- Barra de espaço: Pular.

## Resumo do codigo

- **Player**: A classe representa o jogador no jogo. Ele pode se mover para a esquerda/direita, pular e interagir com o ambiente.
- **Objeto**: Uma classe base para objetos no jogo, como blocos. Pode ser estendida para criar outros elementos interativos.
- **Bloco**: Uma subclasse de Object representando blocos no ambiente.
- **Fogo**: Uma subclasse de Object representando uma chama no ambiente que interaje com o jogador.
- **Colicao**: A classe ressponsavel pelas funçoes de colicao ente o jogador e os objetos do cenaio.
- **Inimigo**: A classe ressponsavel por se movimenta no mapa e colidir com o jogador.
- **janela**: A classe ressponsavel por definir o tamano da tela e chma as outa classes poara serem instaciadas na tela.
- **jogador**: A classe ressponsavel pela movimentaçao do personagem e coliçoes do jogador nos outros objetos.
- **main**: Inicia o programa.
- **Soms**: Classe abstrata com afunção de emitir soms.
- **Sprite**: Classe responsabel pelos sprites dos objetos e sua movimentação.
- **Tela de Fundo**: Classe responsavel por gerar o backgroun do pograma.


