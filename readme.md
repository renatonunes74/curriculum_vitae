<div align="center">

# Curriculum Vitae (CV)
![Groff](https://img.shields.io/badge/groff-%23ED8B00.svg?style=for-the-badge)
![Groff](https://img.shields.io/badge/troff-%23ED8B00.svg?style=for-the-badge)
![Acessos](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Frenatonunes74%2Fcurriculum_vitae&label=A%20C%20E%20S%20S%20O%20S&labelColor=%2320232a&countColor=%2320232a&labelStyle=upper)

[Sobre](#sobre) •
[Depedencias]($depedencias) •
[📑 Funcionalidades](#-funcionalidades) •
[📽 Como usar](#-execução) •
[📏 Organização do Projeto](#-organização-do-projeto)
</div>

# Sobre
Curriculum Vitae feito em Groff, com base no modelo do [wlcsm](https://github.com/wlcsm/resume) e modificado a gosto.

Criado com base nas boas práticas
- Simples
- Legível
- Palavras-Chaves

![Curriculo](https://github.com/renatonunes74/curriculum_vitae/curriculo_2.png)

# Depedencias
- Groff

# 📑 Funcionalidades
O arquivo utilza de macros disponíveis no Troff
- Como:
  - `.ds NOME Seu nome`
  - `.ds EMAIL Seu@email.com`
  - etc...

# 📽 Como usar
- Clone o repositório
    - `git clone https://github.com/renatonunes74`
- Entre na pasta
    - `cd curriculum-vitae`
- Compile o arquivo usando o Groff
    - `groff -ktesp curriculo.ms -Tpdf > curriculo.pdf`

# 📏 Organização do Projeto
- `curriculo.ms` -> template do curriculo
- `curriculo.pdf` -> saída PDF do curriculo
