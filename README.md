# NOP – Sistema de Oportunidades (Projeto Acadêmico)

Projeto desenvolvido em equipe como parte da disciplina INF1039 – PUC-Rio, com o objetivo de criar uma aplicação web para centralizar oportunidades acadêmicas e profissionais para alunos da universidade.

A plataforma permite que professores cadastrem oportunidades e que estudantes visualizem conteúdos compatíveis com seus interesses.

# Tecnologias utilizadas

- Python
- Django
- HTML / CSS
- SQLite
- Figma (prototipação)
- Git / GitHub

# Funcionalidades

- Cadastro e visualização de oportunidades
- Sistema básico de autenticação
- Organização de rotas e views
- Renderização de templates Django
- Estrutura CRUD
- Planejamento do projeto com Kanban

# Minha participação no projeto

Atuei principalmente nas áreas de:

- Desenvolvimento backend em Django
- Criação e organização de views, rotas e templates
- Apoio na modelagem da aplicação
- Prototipação de telas no Figma
- Organização do fluxo de trabalho usando Kanban
- Distribuição de tarefas e acompanhamento do progresso do grupo

Além do desenvolvimento técnico, participei ativamente da organização do projeto e da comunicação entre os membros da equipe.

# Como executar o projeto
``` bash 
git clone https://github.com/udagla5/INF1039---25.2---Time-1
cd INF1039---25.2---Time-1
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
pip install -r requirements.txt
python manage.py makemigrations
python manage.py popular_interesses
python manage.py popular_cursos
python manage.py migrate
python manage.py runserver
```
Acesse no navegador:

http://127.0.0.1:8000

# Aprendizados

Durante este projeto tive contato prático com:

- Estrutura de aplicações Django
- Organização de projetos em equipe
- Metodologias ágeis (Kanban)
- Integração entre backend e frontend
- Versionamento com Git

# Observações

Este é um projeto acadêmico desenvolvido em grupo.
Repositório original da equipe:

https://github.com/udagla5/INF1039---25.2---Time-1

# Apresentação do projeto

Slides desenvolvidos em equipe no Canva, contendo visão geral do sistema, protótipos, fluxo da aplicação e organização do projeto:

Link da apresentação: https://www.canva.com/design/DAG0MfFg8gY/_dxfdoX0eeVsja8mdDEKpw/edit?utm_content=DAG0MfFg8gY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
