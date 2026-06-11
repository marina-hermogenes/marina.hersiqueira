# Página Pessoal - Marina Hermógenes Siqueira

Repositório criado para o **Trabalho Prático 2** da disciplina de **Programação WEB (GAC116)** - 2026/1.

## Sobre o Projeto

Este projeto consiste em uma **Página Pessoal** desenvolvida com HTML, CSS e JavaScript, contemplando o uso de **dois frameworks CSS distintos** para permitir a comparação entre abordagens de estilização:

- **Versão Bootstrap** - Utiliza o framework [Bootstrap 5](https://getbootstrap.com/) com seu sistema de grid, componentes e utilitários.
- **Versão Bulma** - Utiliza o framework [Bulma CSS](https://bulma.io/) com sua abordagem modular baseada em Flexbox.

## Funcionalidades

-   Layout totalmente **responsivo** (mobile, tablet, desktop)
-   Alternância entre **tema claro e tema escuro** via botão toggle (JavaScript + localStorage)
-   Seções: Sobre, Formação, Habilidades, Projetos, Interesses e Contato
-   Animações de scroll (Intersection Observer API)
-   Formulário de contato com feedback visual
-   Botão "Voltar ao topo"
-   Navegação suave entre seções
-   Link para alternar entre as duas versões (Bootstrap ↔ Bulma)

## Estrutura do Projeto

```
marina.hersiqueira/
├── index.html                 # Página inicial (seleção de versão)
├── README.md                  # Documentação
├── bootstrap/                 # Versão com Bootstrap
│   ├── index.html             # Página principal
│   ├── style.css              # Estilos customizados
│   └── script.js              # JavaScript
└── bulma/                     # Versão com Bulma
    ├── index.html             # Página principal
    ├── style.css              # Estilos customizados
    └── script.js              # JavaScript
```

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/marina-hermogenes/marina.hersiqueira.git
   ```

2. Abra o arquivo `index.html` no navegador, ou inicie um servidor local:
   ```bash
   cd marina.hersiqueira
   python3 -m http.server 8080
   ```

3. Acesse `http://localhost:8080` no navegador.

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Uso |
|---|---|---|
| HTML5 | - | Estruturação das páginas |
| CSS3 | - | Estilização customizada |
| JavaScript | ES6+ | Interatividade e lógica |
| Bootstrap | 5.3.3 | Framework CSS (versão 1) |
| Bulma | 1.0.2 | Framework CSS (versão 2) |
| Bootstrap Icons | 1.11.3 | Ícones |
| Google Fonts (Inter) | - | Tipografia |

## Autora

**Marina Hermógenes Siqueira**  
Ciência da Computação - UFLA  
📧 marina.hersiqueira@gmail.com
🔗 [GitHub](https://github.com/marina-hermogenes)
