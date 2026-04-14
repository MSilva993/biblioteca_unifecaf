# Projeto Biblioteca

## Introdução

Este projeto foi desenvolvido como parte da disciplina de **Design Web** no curso de **Análise e Desenvolvimento de Sistemas** da UNIFecaf.  
O objetivo é aplicar conceitos de HTML, CSS e responsividade na construção de uma página web acadêmica.

## Objetivos

- Criar uma página web funcional e responsiva.
- Utilizar boas práticas de organização de arquivos (HTML, SCSS, CSS, imagens).
- Documentar o projeto de forma clara e acadêmica.
- Publicar a página utilizando **GitHub Pages**.

## Tecnologias Utilizadas

- **HTML5** para estruturação da página.
- **CSS3/SCSS** para estilização e responsividade.
- **Git & GitHub** para versionamento e hospedagem.

## Página Publicada

Acesse a versão online do projeto através do GitHub Pages:  
[Projeto Biblioteca - GitHub Pages](https://msilva993.github.io/biblioteca_unifecaf/)

## Estrutura de Diretórios

```
Projeto Biblioteca/
├── index.html              # Página principal
├── README.md               # Documentação do projeto
├── css/                    # Estilos (SCSS modular e CSS compilado)
│   ├── style.scss          # SCSS principal (importa todos os módulos)
│   ├── style.css           # CSS compilado
│   ├── style.css.map       # Mapa de origem do CSS
│   ├── responsivo.scss     # SCSS de responsividade
│   ├── responsivo.css      # CSS compilado da responsividade
│   ├── responsivo.css.map  # Mapa de origem da responsividade
│   ├── _variaveis.scss     # Paleta de cores e tipografia
│   ├── _global.scss        # Reset e estilos globais
│   ├── _header.scss        # Estilos do cabeçalho
│   ├── _sobre.scss         # Estilos da seção "Sobre"
│   ├── _livros.scss        # Estilos da seção "Livros"
│   ├── _unidades.scss      # Estilos da seção "Unidades"
│   ├── _contatos.scss      # Estilos da seção "Contatos"
│   └── _footer.scss        # Estilos do rodapé
└── image/                  # Pasta com todas as imagens utilizadas
```

---

## Responsividade

O projeto foi desenvolvido com **media queries** para adaptação em diferentes dispositivos:

- **Mobile:** até 768px
- **Tablet:** entre 769px e 1024px
- **Desktop:** acima de 1024px

---

## 🚀 Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/MSilva993/biblioteca_unifecaf.git
   ```

---

## Autor

Desenvolvido por **Marcos André**  
Disciplina: **Design Web**  
Curso: **Análise e Desenvolvimento de Sistemas - UniFECAF**
