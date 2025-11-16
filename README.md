<h1 align="center">🐦Flappy Bird – Projeto em Python (Pygame)</h1>

---

## 🎮 Sobre o Jogo
<br>

Este é um remake inspirado no clássico **Flappy Bird**, desenvolvido em **Python + Pygame**. O objetivo é simples: desviar dos canos e fazer a maior pontuação possível.

<br>

Funcionalidades:

- 🐦 Animação completa do pássaro

- 🌄 Movimento suave de fundo e solo

- 🧱 Canos gerados aleatoriamente

- ⌨️ Controle via barra de espaço

- 🔊 Sons de colisão

- 🧮 Sistema de pontuação

---
<br>

## 📂 Estrutura do Projeto

```
FlappyBird-Python/
│── .gitignore
│── README.md
│── FlappyBird.py
│── .venv/
│── .idea/
│   ├── inspectionProfiles/
│   │   └── profiles_settings.xml
│   ├── FlappyBird em Python.iml
│   ├── misc.xml
│   ├── modules.xml
│   └── workspace.xml
│
│── imgs/
│   ├── base.png
│   ├── bg1.png
│   ├── bg2.jpg
│   ├── bird1.png
│   ├── bird2.png
│   ├── bird3.png
│   ├── pipe.png
│   ├── pipe1.png
│   ├── pipe2.png
│
│── sons/
│   ├── colisao.mp3
│   ├── pulo.mp3
│   └── ponto.mp3
```

---
<br>

## 🛠️ Tecnologias utilizadas

- Python 3.12 (recomendado)

- Pygame 2.5+

⚠️ Compatibilidade importante (Python x Pygame) ⚠️

|    Pygame    | Suporte Python |     Sistemas suportados     |
|:------------:|:--------------:|:----------------------------:|
| **2.6.1**    |  3.8 → 3.12  | Windows, macOS, Linux        |
| **2.5.x**    |  3.8 → 3.11  | Windows, macOS, Linux        |
| **2.4.x**    |  3.7 → 3.10  | Windows, macOS, Linux        |
| **2.3.x ou anteriores** |  3.6 → 3.9 (obsoletos) | Compatibilidade parcial |

Atenção:

- Python 3.13 e 3.14 NÃO são suportados pelo Pygame (APIs mudaram).
- Se estiver usando essas versões, a instalação falhará.
- A versão 3.12 é a mais nova totalmente compatível.

---
<br>

## ▶️ Como Executar o Jogo

1) Obter o código
<p align="center">Opção A — clonar com Git:</p>

```bash
git clone https://github.com/Renan-Faganello/FlappyBird-Python.git
cd FlappyBird-Python

```
<p align="center">Opção B — baixar ZIP:</p>


- Clique em Code → Download ZIP no GitHub e extraia.

- Abra a pasta extraída no terminal.
<br>

2) Criar e ativar um ambiente virtual

```bash
# criar venv (usa o Python 3.12 se estiver instalado)
py -3.12 -m venv .venv

# ativar
.\.venv\Scripts\activate
```
Se py não existir, use:
```bash
python -m venv .venv
.\.venv\Scripts\activate
```
macOS / Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```
Ao ativar, o prompt mostrará (.venv) no começo da linha.

3) Conferir a versão do Python ativa
```bash
python --version
# Esperado: Python 3.12.x (ou 3.11.x)

```
4) Atualizar pip e instalar dependências
```bash
python -m pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
```
```bash
python -m pip install --upgrade pip setuptools wheel
pip install pygame
```
Se a instalação do pygame falhar por compilação (erro com distutils), rode:
```bash
pip install pygame==2.5.2 --only-binary :all:

```
(isto força a instalação do wheel pré-compilado compatível com Python 3.12/Windows)

5) Testar se o Pygame funciona
```bash
python -m pygame.examples.aliens
```
Se abrir uma janela de exemplo, o pygame está OK.

6) Rodar o jogo
Com o .venv ativo e estando na pasta do projeto:
```bash
python FlappyBird.py
```

7) Se algo der errado — quick fixes

Erro: pygame not found → pip install pygame

Erro: python não encontrado → marque “Add Python to PATH” na instalação do Python e reabra o terminal

PowerShell bloqueando ativação → rode (uma vez):
```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
```
<br>

## 🎮 Como Jogar

- Pressione barra de espaço para fazer o pássaro subir.

- Desvie dos canos.

- Tente fazer a maior pontuação possível!

---
<br>

## 📦 Download da Última Versão (ZIP)

Baixe a versão pronta para uso:

👉 **Releases**: disponível na aba **Releases** deste repositório.

---
<br>

## 🖼️ GIF / Screenshot

Inclua aqui o GIF ou imagem do jogo:

![Gameplay](./assets/gameplay.gif)

---
<br>

## 🌐 Release no GitHub

As versões empacotadas ficam na seção **Releases**, incluindo:

- Arquivo ZIP com código organizado
- Versão acompanhada de changelog

---
<br>

## 📜 Licença

Este projeto está sob a licença **MIT**.

Você pode utilizar, modificar e distribuir como quiser.

```
MIT License
Copyright (c) 2025
```

---
<br>

👨‍💻 Autor

Renan Faganello
Projeto desenvolvido com dedicação enquanto evolui em Python e desenvolvimento de jogos.

---
<br>

## 🙌 Contribuições

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir um pull request.

---

---


🧭 Como configurar corretamente (Python 3.12 + venv)

1. Verifique suas versões instaladas
   py -0

Você deve ver algo como:

-3.14-64
-3.12-64

Se o 3.12 não aparecer, instale por aqui:
https://www.python.org/downloads/release/python-31210/

Marque:
✔️ Add Python to PATH

2. Crie o ambiente virtual correto

Apague seu .venv antigo e recrie:

py -3.12 -m venv .venv

3. Ative
   .\.venv\Scripts\activate

4. Verifique
   python --version

Saída esperada:
Python 3.12.10

5. Instale o pygame
   pip install pygame

📦 Instalação do projeto
git clone https://github.com/Renan-Faganello/FlappyBird-Python.git
cd FlappyBird-Python
pip install -r requirements.txt
python FlappyBird.py

📷 Demonstração

(GIF será adicionado aqui posteriormente)

📜 Licença

Este projeto está licenciado sob MIT License.

1) Obter o código

Opção A — clonar com Git:

git clone https://github.com/Renan-Faganello/FlappyBird-Python.git
cd FlappyBird-Python


Opção B — baixar ZIP:

Clique em Code → Download ZIP no GitHub e extraia.

Abra a pasta extraída no terminal.
