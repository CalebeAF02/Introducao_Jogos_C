# Introdução Jogos C 🎮

Um projeto de jogo em **C/C++** utilizando a biblioteca [Raylib](https://www.raylib.com/).  
Este repositório acompanha meus primeiros passos com gráficos, texturas e lógica de jogo.

---

## 🎆 Primeira Janela

![Primeira Janela](asset/linha_do_tempo/primeira_janela.png)

---

## 🚀 Funcionalidades já implementadas

- Criação de janela com Raylib (`InitWindow`).
- Exibição de texto na tela (`DrawText`).
- Carregamento e renderização de imagens (`LoadTexture` e `DrawTexture`).
- Estrutura organizada com `src/`, `include/`, `libs/` e `docs/`.

---

## 📂 Estrutura do projeto

- **Introducao_Jogos_C/**
    - **src/** → Código-fonte (`main.cpp`, `sistema.cpp`)
    - **include/** → Headers (`raylib.h`, `sistema.hpp`)
    - **libs/** → Bibliotecas (`libraylib.a`, `raylib.dll`)
    - **docs/** → Imagens e documentação
    - **CMakeLists.txt** → Configuração do build
    - **README.md** → Este arquivo

---

## ⚙️ Como compilar

### Pré-requisitos

- [CMake](https://cmake.org/)
- [MinGW/TDM-GCC](http://tdm-gcc.tdragon.net/) ou outro compilador compatível
- [Raylib](https://github.com/raysan5/raylib) compilado (já incluído em `libs/` e `include/`)

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/CalebeAF02/Introducao_Jogos_C.git
   cd Introducao_Jogos_C

#### Compile com CMake:

bash
cmake -B build
cmake --build build
Execute:

#### bash

./build/Introducao_Jogos_C.exe
🖼️ Assets
As imagens utilizadas estão na pasta docs/imagens/. Exemplo de carregamento no código:

#### cpp

Texture2D baome = LoadTexture("docs/imagens/baome/baome_verde_de_frente.png");
DrawTexture(baome, 50, 720 - baome.height, WHITE);

---

## 📌 Próximos passos

Criar sistema de cenas/estados (menu, jogo, pausa).

Adicionar movimentação de personagem com teclado.

Implementar sons e música.

Estruturar melhor a pasta assets/ para imagens, sons e fontes.

## 👨‍💻 Autor

Github : [CalebeAF02](https://github.com/CalebeAF02?tab=repositories).
