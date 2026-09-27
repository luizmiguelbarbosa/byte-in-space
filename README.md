<h1 align="center">Byte in Space 🐶🚀💫</h1>

<h2>Equipe 🧑‍💻</h2>

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
        <img src="https://avatars.githubusercontent.com/lgss0" width="100px;" alt="Luiz Gabriel"/><br />
        <sub><b>Luiz Gabriel</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/rafael-smoura">
        <img src="https://avatars.githubusercontent.com/rafael-smoura" width="100px;" alt="Rafael"/><br />
        <sub><b>Rafael</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/lebb8">
        <img src="https://avatars.githubusercontent.com/lebb8" width="100px;" alt="Eduardo"/><br />
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
        <img src="https://avatars.githubusercontent.com/miqueias-santos" width="100px;" alt="Miqueias Santos"/><br />
        <sub><b>Miqueias Santos</b></sub>
      </a>
    </td>
  </tr>
</table>

<hr>

<h2>⚙️🛠️ Instalação do Jogo</h2>

<p><strong>Clone o repositório:</strong></p>

<pre>
git clone https://github.com/luizmiguelbarbosa/byte_in_space.git
</pre>

<p><strong>No PowerShell, execute:</strong></p>

<pre>
Set-ExecutionPolicy RemoteSigned -Scope Process
&amp; byte_in_space/venv/Scripts/Activate.ps1
</pre>

<pre>
cd byte_in_space
</pre>

<pre>
pip install -r requirements.txt
</pre>

<hr>

<h2>📂 Estrutura de Pastas</h2>

<h3>Arquitetura das Pastas do Projeto</h3>

<h3>entities</h3>

<p>Classes responsáveis pelas entidades do jogo, como <code>Player</code>, <code>Enemies</code> e <code>Collectibles</code>.</p>

<pre>
├── entities
│   ├── coletavel.py
│   ├── eventos.py
│   ├── inimigo.py
│   ├── nave.py
│   ├── render.py
│   └── update.py
</pre>

<h3>assets</h3>

<p>Arquivos de recursos utilizados pelo jogo, como imagens, músicas e vídeos.</p>

<pre>
├── assets
│   ├── imagens
│   │   ├── cenario1.png
│   │   ├── circuito.png
│   │   ├── computador.png
│   │   ├── dados.png
│   │   ├── icone_janela.png
│   │   ├── imagem_menu.png
│   │   ├── sprite_inimigo.png
│   │   └── sprite_nave.png
│   ├── musicas
│   │   ├── musica_jogo.mp3
│   │   ├── musica_start.mp3
│   │   └── tiro.mp3
│   └── videos
│       └── cutscene1.mp4
</pre>

<hr>

<h2>📚 Bibliotecas Utilizadas</h2>

<pre>
Pygame 2.6.1
OpenCV 4.12.0
random
sys
</pre>

<hr>

<h2>🌌 Distribuição das Tarefas do Projeto</h2>

<p align="center">
<table align="center">
  <tr>
    <th>Equipe</th>
    <th>Tarefas</th>
  </tr>
  <tr>
    <td><a href="https://github.com/gustavocharamba?tab=overview&from=2025-08-01&to=2025-08-11">Gustavo Charamba</a></td>
    <td>Desenvolvimento dos estados de controle do jogo e da lógica relacionada aos itens.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/lgss0">Luiz Gabriel</a></td>
    <td>Desenvolvimento de todos os recursos relacionados à responsividade do jogo.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/SmouraCodeX">Rafael</a></td>
    <td>Desenvolvimento das telas iniciais, créditos, tela de Game Over e mecânica de disparos utilizando a barra de espaço.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/lebb8">Eduardo</a></td>
    <td>Desenvolvimento do sistema de tratamento de colisões entre os objetos do projeto.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/luizmiguelbarbosa">Luiz Miguel</a></td>
    <td>Principal responsável pela revisão do código, desenvolvimento da classe base das entidades e implementação da movimentação do jogador.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/miqueias-santos">Miqueias</a></td>
    <td>Auxílio no design e contribuição para otimizações de desempenho.</td>
  </tr>
</table>
</p>

<hr>

<h2>🧠 Conceitos Utilizados</h2>

<p>
Durante o desenvolvimento, aplicamos conceitos fundamentais, como listas e estruturas de repetição, além de conceitos mais avançados relacionados aos princípios fundamentais da <strong>Programação Orientada a Objetos (POO)</strong>.
</p>

<p>
O uso de funções, loops e estruturas condicionais foi fundamental para o desenvolvimento do jogo, contribuindo diretamente para a escalabilidade e organização do código.
</p>

<p>
Além disso, a Programação Orientada a Objetos permitiu estruturar o projeto utilizando classes organizadas e seus respectivos métodos. A capacidade de gerenciar cada objeto de forma independente simplificou o processo de desenvolvimento e melhorou significativamente a legibilidade e a manutenção do código.
</p>

<hr>

<h2>⚠️ Desafios e Problemas</h2>

<p>
Enfrentamos diversos desafios durante o desenvolvimento do projeto, especialmente relacionados ao planejamento e à priorização das tarefas dentro da equipe. O principal problema foi a falta de priorização das tarefas fundamentais, o que nos levou a gastar um tempo considerável reescrevendo partes da base de código e refazendo implementações que já haviam sido concluídas.
</p>

<p>
Como consequência, enfrentamos diversos conflitos de merge e problemas de integração entre diferentes branches. Essas dificuldades evidenciaram a importância de uma organização adequada do fluxo de desenvolvimento em equipe.
</p>

<p>
Todos os integrantes da equipe certamente aprenderam que um bom planejamento e uma priorização adequada são tão importantes quanto o conhecimento técnico para o desenvolvimento de um projeto de software.
</p>
