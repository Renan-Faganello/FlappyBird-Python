necessario py
| Pygame | Compatível com Python | Sistema operacional suportado |
| :---------------------- | :----------------------- | :---------------------------- |
| **2.6.1** | ✅ 3.8 → 3.12 | Windows, macOS, Linux |
| **2.5.x** | ✅ 3.8 → 3.11 | Windows, macOS, Linux |
| **2.4.x** | ✅ 3.7 → 3.10 | Windows, macOS, Linux |
| **2.3.x ou anteriores** | ⚠️ 3.6 → 3.9 (obsoletos) | Alguns sistemas podem falhar |

⚠️ Importante

Python 3.13 e 3.14 ainda não são suportados oficialmente (novas APIs quebraram compatibilidade).
➜ É por isso que o pygame falhou antes quando você estava com o Python 3.14.

A versão 3.12 é atualmente a mais nova suportada 100% estável.

🧭 Passo a passo para forçar o VS Code e o venv a usar o Python 3.12.10
🔹 1. Confirme que o Python 3.12.10 está instalado

No PowerShell:

py -0

Isso vai listar todos os Pythons instalados.
Você deve ver algo assim:

-3.14-64
-3.12-64

Se não aparecer o 3.12, baixe e instale ele aqui:
👉 https://www.python.org/downloads/release/python-31210/

Durante a instalação, marque:
✅ “Add Python 3.12 to PATH”

🔹 2. Delete o ambiente virtual atual

No seu projeto, delete a pasta .venv:

C:\Users\Renan Faganello\Desktop\Projetos Renan Dev\FlappyBird em Python\.venv

🔹 3. Crie um novo ambiente virtual com o Python 3.12

No terminal do VS Code (PowerShell), dentro da pasta do projeto:

py -3.12 -m venv .venv

Isso cria uma nova virtualenv baseada explicitamente no Python 3.12.10.

🔹 4. Ative o novo ambiente
.\.venv\Scripts\activate

Você deve ver algo como:

(.venv) PS C:\Users\Renan Faganello\Desktop\Projetos Renan Dev\FlappyBird em Python>

🔹 5. Verifique a versão ativa
python --version

Saída esperada:

Python 3.12.10

🔹 6. Reinstale o Pygame

Agora sim, o comando deve funcionar:

pip install pygame

🔹 7. Configure o VS Code para usar o novo interpretador

No VS Code:

Pressione Ctrl + Shift + P

Digite “Python: Select Interpreter”

Escolha o caminho:

.venv\Scripts\python.exe (Python 3.12.10)

Após isso, rode:

python -m pygame.examples.aliens

🎉 Se abrir uma janelinha com o jogo, está tudo certo!
