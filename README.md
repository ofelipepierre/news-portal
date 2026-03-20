# 🌐 TechNews - Portal de Notícias Moderno

![Status do Projeto](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![Linguagem](https://img.shields.io/badge/Stack-HTML5%20%2F%20CSS3-blue)

O **TechNews** é um portal de notícias responsivo focado no ecossistema de tecnologia, cobrindo tópicos como Inteligência Artificial, Blockchain e Robótica. Este projeto foi desenvolvido como um **estudo de caso** para aplicar conceitos avançados de arquitetura CSS e layouts complexos com Grid e Flexbox.

---

## 🎯 Objetivos do Projeto
* **Semântica de Dados**: Utilização de tags HTML5 como `header`, `main`, `section`, `article`, `figure` e `aside` para melhor acessibilidade e SEO.
* **Arquitetura de Layout**: Implementação de um sistema de grid robusto para organizar múltiplas seções de notícias.
* **Manutenibilidade**: Separação de responsabilidades em arquivos CSS distintos, facilitando a organização do código.

---

## 🛠️ Tecnologias e Conceitos Aplicados

### 🏗️ Arquitetura de Layout
* **CSS Grid Areas**: Gerenciamento do layout principal através de áreas nomeadas (`featured`, `weekly`, `ai`, `aside`).
* **Subgrids e Flexbox**: Uso de `grid-template-columns` para os cards e `flexbox` para o alinhamento de itens nos menus.

### 🎨 Estilização e Design
* **Variáveis CSS**: Centralização da paleta de cores (Dark Mode), tipografia e escalas de espaçamento no `:root`.
* **Utility-First**: Classes utilitárias para controle de espaçamento (`gap-16`, `gap-32`) e tamanhos de fonte (`text-2xl`, `text-lg`).
* **Modern CSS Nesting**: Organização de seletores aninhados para um código mais limpo.

---

## 🧩 Estrutura do Portal

O projeto é composto por quatro blocos principais:
1. **Destaques (Featured)**: Notícia principal em evidência com cards secundários em grid.
2. **Mais Lidas (Weekly)**: Seção horizontal com as notícias de maior impacto da semana.
3. **Destaques de IA**: Feed vertical detalhado focado em Inteligência Artificial.
4. **Sidebar (Viu isso aqui?)**: Barra lateral com notícias rápidas e variadas.

---

## 📂 Organização dos Arquivos
```text
├── index.html          # Estrutura semântica do portal
├── styles/
│   ├── index.css       # Ponto de entrada (Imports)
│   ├── global.css      # Variáveis e Grid principal
│   ├── utilities.css   # Classes de utilidade
│   ├── header.css      # Estilos de navegação
│   └── sections.css    # Estilos de cada bloco de notícias
└── assets/             # Imagens e ícones do projeto
