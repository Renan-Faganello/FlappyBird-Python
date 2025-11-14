# 🐦Flappy Bird – Projeto em Python (Pygame)

---

## 🎮 Sobre o Jogo

Este é um remake inspirado no clássico **Flappy Bird**, desenvolvido em **Python + Pygame**. O objetivo é simples: desviar dos canos e fazer a maior pontuação possível.

Funcionalidades:

🐦 Animação completa do pássaro

🌄 Movimento suave de fundo e solo

🧱 Canos gerados aleatoriamente

⌨️ Controle via barra de espaço

🔊 Sons de pulo, colisão e pontuação

🧮 Sistema de pontuação

---

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

## 🛠️ Tecnologias utilizadas

- Python 3.12 (recomendado)

- Pygame 2.5+

⚠️ Compatibilidade importante (Python x Pygame)

2.6.1 ✅ 3.8 → 3.12 Windows, macOS, Linux

2.5.x ✅ 3.8 → 3.11 Windows, macOS, Linux

2.4.x ✅ 3.7 → 3.10 Windows, macOS, Linux

2.3.x ou anteriores ⚠️ 3.6 → 3.9 (obsoletos) Compatibilidade parcial

⚠️ Atenção

Python 3.13 e 3.14 NÃO são suportados pelo Pygame (APIs mudaram).

Se estiver usando essas versões, a instalação falhará.
✔️ A versão 3.12 é a mais nova totalmente compatível.

---

## ▶️ Como Executar o Jogo

```bash
# Instalar dependências
pip install -r requirements.txt

# Rodar o jogo
python src/main.py
```

## 🎮 Como Jogar

- Pressione barra de espaço para fazer o pássaro subir.

- Desvie dos canos.

- Tente fazer a maior pontuação possível!

---

## 📦 Download da Última Versão (ZIP)

Baixe a versão pronta para uso:

👉 **Releases**: disponível na aba **Releases** deste repositório.

---

## 🖼️ GIF / Screenshot

Inclua aqui o GIF ou imagem do jogo:

![Gameplay](./assets/gameplay.gif)

---

## 🌐 Release no GitHub

As versões empacotadas ficam na seção **Releases**, incluindo:

- Arquivo ZIP com código organizado
- Versão acompanhada de changelog

---

## 📜 Licença

Este projeto está sob a licença **MIT**.

Você pode utilizar, modificar e distribuir como quiser.

```
MIT License
Copyright (c) 2025
```

---

## ✨ Melhorias Futuras

- Implementar sons
- Criar menu inicial
- Adicionar sistema de dificuldade crescente
- Colocar placar global com API

---

👨‍💻 Autor

Renan Faganello
Projeto desenvolvido com dedicação enquanto evolui em Python e desenvolvimento de jogos.

---

## 🙌 Contribuições

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir um pull request.

---

---

🛠️ Tecnologias utilizadas

Python 3.12 (recomendado)

Pygame 2.5+

⚠️ Compatibilidade importante (Python x Pygame)
Pygame Suporte Python Sistemas suportados
2.6.1 ✅ 3.8 → 3.12 Windows, macOS, Linux
2.5.x ✅ 3.8 → 3.11 Windows, macOS, Linux
2.4.x ✅ 3.7 → 3.10 Windows, macOS, Linux
2.3.x ou anteriores ⚠️ 3.6 → 3.9 (obsoletos) Compatibilidade parcial

⚠️ Atenção

Python 3.13 e 3.14 NÃO são suportados pelo Pygame (APIs mudaram).

Se estiver usando essas versões, a instalação falhará.
✔️ A versão 3.12 é a mais nova totalmente compatível.

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
