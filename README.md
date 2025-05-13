# Tela de Login Material Design (Tema Escuro)

![Versão](https://img.shields.io/badge/versão-1.0.0-blue.svg)
![Licença](https://img.shields.io/badge/licença-MIT-green.svg)

Um componente de tela de login minimalista e elegante, desenvolvido com HTML semântico e CSS, seguindo os princípios do Material Design do Google em tema escuro. Este projeto prioriza acessibilidade, SEO e experiência do usuário.

![Preview da Tela de Login](./assets/preview.png)

## 📋 Índice

- [Características](#características)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Como Usar](#como-usar)
- [Acessibilidade](#acessibilidade)
- [SEO](#seo)
- [Personalização](#personalização)
- [Boas Práticas](#boas-práticas)
- [Melhorias Futuras](#melhorias-futuras)
- [Licença](#licença)

## ✨ Características

- **Design Minimalista**: Interface limpa e focada na experiência do usuário
- **Tema Escuro**: Reduz a fadiga visual e proporciona uma experiência moderna
- **Material Design**: Segue as diretrizes de design do Google
- **Responsivo**: Adaptável a diferentes tamanhos de tela
- **Acessível**: Implementa práticas de acessibilidade para todos os usuários
- **Otimizado para SEO**: Utiliza HTML semântico e metadados apropriados
- **Phosphor Icons**: Integração com a biblioteca de ícones Phosphor

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com variáveis CSS
- **Phosphor Icons**: Biblioteca de ícones
- **Google Fonts**: Fonte Roboto (padrão do Material Design)

## 📁 Estrutura do Projeto

```
tela-login-material-design/
│
├── index.html          # Arquivo HTML principal
├── style.css           # Arquivo CSS principal
└── README.md           # Documentação do projeto
```

O CSS está incorporado diretamente no arquivo HTML para facilitar a implementação, mas pode ser extraído para um arquivo separado conforme necessário.

## 🚀 Como Usar

### Instalação

1. Clone este repositório ou baixe os arquivos
2. Abra o arquivo `index.html` em seu navegador

### Implementação em Projeto Existente

Para integrar esta tela de login em um projeto existente:

1. Copie o conteúdo HTML da seção `<main>` para seu projeto
2. Copie as regras CSS para seu arquivo de estilos
3. Certifique-se de incluir as dependências:
   - Fonte Roboto do Google Fonts
   - Biblioteca Phosphor Icons

### Personalização Básica

Para alterar as cores principais:

```css
:root {
    --primary-color: #seu-codigo-de-cor; /* Cor principal para botões e links */
    --background: #seu-codigo-de-cor;    /* Cor de fundo da página */
    --surface: #seu-codigo-de-cor;       /* Cor de fundo do card */
}
