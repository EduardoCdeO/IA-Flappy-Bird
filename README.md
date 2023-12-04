# IA + Flappy-Bird
[BR] Jogo do Flappy Bird feito em Python com a biblioteca PyGame, já adaptado para utilização de uma inteligência artificial que foi criada com o módulo NEAT, e configurada para aprender a jogar. A IA está configurada para criar gerações de 100 pássaros cada, e conforme novas gerações são criadas, ela vai se desenvolvendo, até se tornar invencível no jogo. <br>
##
[EN] Flappy Bird game made in Python with the PyGame library, already adapted to use an artificial intelligence that was created with the NEAT module, and configured to learn how to play. The AI ​​is configured to create generations of 100 birds each, and as new generations are created, it will develop, until it becomes invincible in the game.
<br>

## Imagem da IA jogando o Flappy Bird
<br>
<img src="/imgs/Exemplo.PNG">

# Clonando o Projeto
Requisitos: Python e Git instalados. <br><br>
Abra Git Bash.<br>
Altere o diretório de trabalho atual para o local em que deseja ter o diretório clonado.
```bash
git clone https://github.com/EduardoCdeO/IA-Flappy-Bird.git
```

# Configurando ambiente virtual(opcional, mas recomendado)
Abra seu terminal e entre na pasta (altere o caminho-do-diretório pelo caminho do local em que você clonou o repositório)<br>
```bash
cd caminho-do-diretório/IA-Flappy-Bird
```
## Criando o ambiente virtual:
```bash
python -m venv venv
```
## Ativando o ambiente virtual:

No Windows:
```bash
venv\Scripts\activate
```

No macOS/Linux:
```bash
source venv/bin/activate
```

# Instale as dependências
```bash
pip install -r requirements.txt
```

## Inicie a aplicação:
```bash
python FlappyBird.py
```
