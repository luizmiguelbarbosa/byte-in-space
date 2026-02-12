# Byte in Space 🐶🚀💫

## Team 🧑‍💻
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/gustavocharamba">
        <img src="https://avatars.githubusercontent.com/gustavocharamba" width="100px;" alt="Gustavo Charamba"/><br />
        <sub><b>Gustavo Charamba</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/lgss0">
        <img src="https://avatars.githubusercontent.com/lgss0" width="100px;" alt="lgss0"/><br />
        <sub><b>Luiz Gabriel</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/rafael-smoura">
        <img src="https://avatars.githubusercontent.com/rafael-smoura" width="100px;" alt="rafael-smoura"/><br />
        <sub><b>Rafael</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/lebb8">
        <img src="https://avatars.githubusercontent.com/lebb8" width="100px;" alt="lebb8"/><br />
        <sub><b>Eduardo</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/luizmiguelbarbosa">
        <img src="https://avatars.githubusercontent.com/luizmiguelbarbosa" width="100px;" alt="Luiz Miguel Barbosa"/><br />
        <sub><b>Luiz Miguel Barbosa</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/miqueias-santos">
        <img src="https://avatars.githubusercontent.com/miqueias-santos" width="100px;" alt="Luiz Miguel Barbosa"/><br />
        <sub><b>Miqueias Santos</b></sub>
  </tr>
</table>

## Installing the Game ⚙️🛠️

Clone the repository:
```bash
git clone https://github.com/luizmiguelbarbosa/byte_in_space.git
```
In PowerShell, run:
```bash
Set-ExecutionPolicy RemoteSigned -Scope Process
& byte_in_space/venv/Scripts/Activate.ps1
```
```bash
cd byte_in_space
```
```bash
pip install -r requirements.txt
```
## Folder Structure 📂
Project Folder Architecture
### entites
Game entity classes. Example: `Player`, `Enemies` e `Collectibles`
```bash
├── entities
│   ├── coletavel.py
│   ├── eventos.py
│   ├── inimigo.py
│   ├── nave.py
│   ├── render.py
│   └── update.py
```
### assets
Game asset files. Example: `Images`, `Music` e `Videos`
```bash
├── assets
│   ├── imagens
│   │   ├── cenario1.png
│   │   ├── circuito.png
│   │   ├── computador.png
│   │   ├── dados.png
│   │   ├── icone_janela.png
│   │   ├── imagem_menu.png
│   │   ├── sprite_inimigo.png
│   │   └── sprite_nave.png
│   ├── musicas
│   │   ├── musica_jogo.mp3
│   │   ├── musica_start.mp3
│   │   └── tiro.mp3
│   └── videos
│       └── cutscene1.mp4
```
## Libraries Used 📚
```bash
pygame 2.6.1
openCV2 4.12.0
random
sys
```
## Project Task Distribution 🌌

<p align="center">
<table align="center">
  <tr>
    <th>Time</th>
    <th>Tarefas</th>
  </tr>
  <tr>
    <td><a href="https://github.com/gustavocharamba?tab=overview&from=2025-08-01&to=2025-08-11">Gustavo Charamba</a></td>
    <td>Developed the game control states and logic involving items</td>
  </tr>
  <tr>
    <td><a href="https://github.com/lgss0">Luiz Gabriel</a></td>
    <td>Developed all game responsiveness features</td>
  </tr>
  <tr>
    <td><a href="https://github.com/SmouraCodeX">Rafael</a></td>
    <td>Developed initial screens, credits, game over screen, and shooting mechanics using the space baro</td>
  </tr>
  <tr>
    <td><a href="https://github.com/lebb8">Eduardo</a></td>
    <td>Developed collision handling between all project objects</td>
  </tr>
  <tr>
    <td><a href="https://github.com/luizmiguelbarbosa">Luiz Miguel</a></td>
    <td>Main code reviewer, developed the base entity class and player movement</td>
  </tr>
  <tr>
    <td><a href="https://github.com/miqueias-santos">Miqueias</a></td>
    <td>Assisted with design and contributed to performance optimizations</td>
  </tr>
</table>

## Concepts Used
We applied everything from fundamental concepts such as lists and loop structures to more advanced topics, including the foundational principles of Object-Oriented Programming (OOP).

The use of functions, loops, and conditionals was crucial for the development of the game, as they significantly contributed to the scalability and organization of the code.

Additionally, Object-Oriented Programming allowed us to structure and build the code around organized classes and their associated methods. The ability to manage each object independently simplified the development process and significantly improved code readability.

## Challenges and Issues
We faced several challenges during the project, especially related to planning and task prioritization within the team. The main issue was the lack of prioritization of fundamental tasks, which led us to spend considerable time rewriting part of the codebase along with implementations that had already been completed. As a result, we encountered multiple merge conflicts and integration issues between different branches.

Everyone on the team certainly learned that good planning and proper prioritization are just as crucial as strong technical knowledge.
