# Partência

> O Partência é um ecossistema web colaborativo focado no mapeamento e na conexão direta de monitorias estudantis, projetado para transformar o compartilhamento de conhecimento no ambiente universitário.
<div align="left">
  <img src="https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow" alt="Status">
  <img src="https://img.shields.io/badge/Estrutura-HTML5-orange" alt="HTML">
  <img src="https://img.shields.io/badge/Estilo-CSS3-blue" alt="CSS">
  <img src="https://img.shields.io/badge/Funcional-JavaScript-yellow" alt="JS">
</div>

## 📑 Sumário
- [Sobre o Projeto](#-sobre-o-projeto)
- [Objetivo](#-objetivo)
- [Público-Alvo](#-público-alvo)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Integrantes](#-integrantes)

---

## 💜 Sobre o Projeto
Grandes jornadas não são trilhadas individualmente, e o verdadeiro aprendizado nasce quando decidimos dar o primeiro passo juntos. O **Partência** foi desenvolvido como o projeto prático para a disciplina de Programação Web Front-End, atuando como o ponto de partida para a partilha de experiências dentro do campus.

O sistema funciona como uma plataforma livre e descentralizada onde o conhecimento é uma via de mão dupla. Qualquer estudante logado pode encontrar suporte imediato nas matérias mais desafiadoras ou, com um clique, oferecer-se como monitor daquela disciplina que já domina. 

A dinâmica elimina intermediários burocráticos: através de uma interface moderna de *Split Layout* (Duas Colunas), o aluno filtra a área desejada e analisa a disponibilidade do monitor por meio de um **Mini Calendário Semanal Visual** integrado diretamente ao card, permitindo o contato direto entre as partes e auxiliando na conquista de horas complementares pelo ensino voluntário.

## 🎯 Objetivo
- Centralizar e mapear a oferta de monitorias voluntárias no campus.
- Disponibilizar um mural dinâmico com filtros rápidos por Grandes Áreas do Conhecimento (Exatas, Tecnológicas, Humanas/Linguagens).
- Facilitar a identificação de horários compatíveis por meio de um cronograma visual (Grade de Turnos).
- Permitir a conversão rápida de alunos ouvintes em monitores de forma autônoma.
- Garantir a integridade do ecossistema por meio de telas de autenticação (Login e Cadastro com e-mail institucional).
- Auxiliar os estudantes na consolidação do aprendizado e no acúmulo de horas complementares de extensão.
  
## 👥 Público-Alvo
- Alunos que enfrentam dificuldades em disciplinas específicas e buscam apoio.
- Estudantes veteranos ou proficientes dispostos a ensinar e validar horas complementares.
- Comunidade acadêmica do campus interessada em reduzir os índices de retenção em matérias de exatas e tecnologias.
  
## 📂 Estrutura do Projeto
O repositório está organizado de forma modular para o desenvolvimento front-end com 3 páginas principais:
```bash
├── index.html        # Página Principal (Mural de Monitores, Banner Sobre e Filtros)
├── login.html        # Página de Autenticação do Usuário
├── cadastro.html     # Página de Registro de Novos Alunos e Perfis de Monitoria
├── css/
│   └── estilos.css   # Arquivo centralizador de estilos (Design System, Cores ODS 4 e Grid)
└── js/
    └── main.js       # Scripts de validação de formulários e dinamismo dos filtros
