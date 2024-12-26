# 🏜️ **Dune II** 🐪

Bem-vindo ao **Dune II**, um jogo inspirado no épico universo de Duna! Sua missão — sobreviver aos perigos do deserto de Arrakis enquanto coleta especiarias valiosas para prosperar sua casa. 🌵✨

<div align="center">
  <video src="https://github.com/user-attachments/assets/c1749e92-e1b6-4c50-9db6-64a134f48493" autoplay loop></video>
</div>


## 🌟 **Objetivo do Jogo**

- **⌛ Colete especiarias**: Espalhadas pelos mapas, elas são a chave para enriquecer sua casa e garantir sua prosperidade.
- **🛒 Venda especiarias**: Troque as especiarias por dinheiro e use os lucros para melhorar seu inventário e garantir sua sobrevivência.
- **💧 Gerencie sua água**: O deserto é implacável, e sem água você não sobreviverá. Sempre que possível, compre água para não morrer.
- **🗺️ Explore diferentes mapas**: Enfrente os vermes gigantes e colete mais ou menos especiarias de acordo com a dificuldade. 


## ⛰️ **Desafios**

- **⚖️ Equilibre recursos**: Colete especiarias, mas saiba conciliar com sua água, para acumular dinheiro sem morrer desidratado.
- **🚨 Evite os vermes gigantes**: Para não ser identificado por eles, não repita seus passos. Quanto mais especiarias no mapa, maior o risco de ataque.
- **🧠 Planeje cada movimento**: Errar pode significar a sua morte.


## 🎮 **Como Jogar**

### 🔗 Plataformas:
- PC
- Xbox
- Playstation (Em breve!)

### ⌨️ Controles no PC:
  - **WASD**: Movimente seu personagem.
  - **SPACE**: Pule as cutscenes.
  - **ENTER**: Confirme ações.
  - **P**: Interaja com portais.
  - **E**: Fique parado e prenda a respiração para evitar ser identificado pelos vermes que se rastejam sob a areia. 🐍


## 🪟 Instalação no Windows

1. Baixe o instalador clicando no link: 👉 [**Instalador para Windows**](https://github.com/Mateus-Ribeir0/DuneII/releases/download/DuneII/Instalar.Dune.II.exe)

2. Abra o instalador e siga as instruções para concluir a instalação.

3. Após a instalação, execute o jogo diretamente do atalho criado na área de trabalho ou no menu Iniciar.


## 💻 **Instalação em Linux**

1. Certifique-se de ter o GCC, make e git:
   ```
   sudo apt install build-essential git
   ```

2. Instale todas as bibliotecas necessárias:
   ```
   sudo apt install libasound2-dev libx11-dev libxrandr-dev libxi-dev libgl1-mesa-dev libglu1-mesa-dev libxcursor-dev libxinerama-dev libwayland-dev libxkbcommon-dev
   ```

3. Baixe o código-fonte do Raylib diretamente do GitHub e entre na pasta:
   ```
   git clone --depth 1 https://github.com/raysan5/raylib.git raylib
   cd raylib/src/
   ```

4. Compile a Raylib:
   ```
   make PLATFORM=PLATFORM_DESKTOP
   ```

5. Instale a Raylib:
   ```
   sudo make install
   cd ~
   ```

6. Clone o repositório do jogo:
   ```
   git clone https://github.com/Mateus-Ribeir0/DuneII.git
   cd DuneII
   ```

7. Compile e rode o jogo:
   ```
   make
   ./DuneII
   ```

8. Se não funcionar, tente esse comando alternativo:
   ```
   gcc -Wall -std=c99 -Iinclude -I../raylib/src src/*.c -o dune_game -L../raylib/src -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
   ```

Caso ocorra algum problema, consulte a documentação da Raylib para Linux: [Raylib para Linux](https://github.com/raysan5/raylib/wiki/Working-on-GNU-Linux).

## 🍎 **Instalação em Mac** (Observação: podem ocorrer problemas de compilação devido a diferenças entre sistemas Linux e macOS)

1. Configure o ambiente para suportar a compilação estática:
   ```
   export MACOSX_DEPLOYMENT_TARGET=10.9
   ```

2. Instale as ferramentas XCode (certifique-se de atualizar as ferramentas após a instalação):
   ```
   xcode-select --install
   ```

3. Se necessário, reinstale as ferramentas:
   ```
   sudo rm -rf /Library/Developer/CommandLineTools
   xcode-select --install
   ```

4. Baixe o código-fonte do Raylib diretamente do GitHub e entre na pasta:
   ```
   git clone https://github.com/raysan5/raylib.git
   cd raylib/src
   ```

5. Compile a Raylib:
   ```
   make
   ```

6. Clone o repositório do jogo:
   ```
   git clone https://github.com/Mateus-Ribeir0/DuneII.git
   cd DuneII
   ```

7. Compile e rode o jogo:
   ```
   make
   ./dune_game
   ```

Caso ocorra algum problema, consulte a documentação da Raylib para Mac: [Raylib para Mac](https://github.com/raysan5/raylib/wiki/Working-on-macOS).


\
 

