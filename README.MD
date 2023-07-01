<div align="center">

# Curriculum Vitae (CV)

<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/renatonunes74/curriculum_vitae.svg?style=for-the-badge">
<img alt="Repository size" src="https://img.shields.io/github/repo-size/renatonunes74/curriculum_vitae.svg?style=for-the-badge">
<a href="https://github.com/renatonunes74/curriculum_vitae/commits/master">
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/renatonunes74/curriculum_vitae.svg?style=for-the-badge">
<a href="https://github.com/renatonunes74/curriculum_vitae/issues">
<img alt="Repository issues" src="https://img.shields.io/github/issues/renatonunes74/curriculum_vitae.svg?style=for-the-badge">
</a>
<img alt="GitHub" src="https://img.shields.io/github/license/renatonunes74/curriculum_vitae.svg?style=for-the-badge">
<h4>Curriculum Vitae feito em Groff, com base no modelo do <a href="https://github.com/wlcsm/resume">wlcsm</a> e em boas práticas</h4>
<a href="#sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
<a href="#como-usar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
<a href="#funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
<a href="#organização-do-projeto">Organização do Projeto</a>

</p>
</div>

# Sobre
- Simples
- Legível
- Palavras-chaves

<div align="center"> 
<img src="./assets/CV_Renato_Nunes.png" width=60%>
</div>

# Dependências
- Groff

# Como usar
- Clone o repositório
    - `git clone https://github.com/renatonunes74`
- Entre na pasta
    - `cd curriculum-vitae`
- Compile o arquivo usando o Groff
    - `groff -ktesp curriculo.ms -Tpdf > curriculo.pdf`

# Funcionalidades
O arquivo utiliza de macros disponíveis no Troff
- Como:
  - `.ds NOME Seu nome`
  - `.ds EMAIL Seu@email.com`
  - etc...

# Organização do Projeto
- `curriculo.ms`
    - template do currículo
- `curriculo.pdf`
    - saída PDF do currículo
- `macro.tmac`
    - local de macros
- `assets/curriculo.png`
    - opcional (gerado via `imagemagick`)
