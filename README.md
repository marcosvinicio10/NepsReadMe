# Marcos Vinicio - Site Pessoal

Este é o meu site pessoal, onde apresento meus projetos, portfólio, experiências e formas de contato. O objetivo é fornecer uma vitrine profissional e atualizada para meu trabalho como desenvolvedor de software.

---

## Demonstração

![Screenshot do site](docs/images/demo.png)

*Acesse online:* [www.marcosvinicio.site](https://www.marcosvinicio.site)

---

## Índice

- [Sobre o Projeto](#sobre-o-projeto)  
- [Tecnologias Utilizadas](#tecnologias-utilizadas)  
- [Funcionalidades](#funcionalidades)  
- [Pré-requisitos](#pré-requisitos)  
- [Instalação](#instalação)  
- [Uso](#uso)  
- [Estrutura de Pastas](#estrutura-de-pastas)  
- [Como Contribuir](#como-contribuir)  
- [Licença](#licença)  
- [Contato](#contato)  

---

## Sobre o Projeto

O site **marcosvinicio.site** é uma plataforma pessoal construída para reunir meu portfólio, blog e informações profissionais em um único lugar. Ele visa facilitar o contato com recrutadores, parceiros e clientes, além de mostrar minhas habilidades técnicas e projetos recentes.

---

## Tecnologias Utilizadas

- **HTML5** — Estrutura das páginas.  
- **CSS3** — Estilização e responsividade.  
- **JavaScript (Vanilla)** — Funcionalidades dinâmicas.  
- **Vercel** — Hospedagem e deploy.  

---

## Funcionalidades

- Página inicial com resumo profissional.  
- Seção de projetos com descrição e links.  
- Blog com artigos técnicos e insights.  
- Formulário de contato integrado.  
- Layout responsivo para dispositivos móveis e desktop.  

---

## Pré-requisitos

Antes de começar, você precisa ter instalado em sua máquina:

- **Git** ([download aqui](https://git-scm.com/downloads))  
- Um navegador moderno (Chrome, Firefox, Edge...)  
- (Opcional) Um editor de código como [VS Code](https://code.visualstudio.com/)  

---

## Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/marcosvinicio10/meu-website.git
   ```
2. **Acesse a pasta do projeto**
   ```bash
   cd meu-website
   ```

---

## Uso

Existem duas formas de visualizar o site localmente:

**1. Abrindo diretamente no navegador**  
- Navegue até a pasta `src` e abra o arquivo `index.html` no navegador.

**2. Usando um servidor local (opcional, recomendado para testes)**  
- Com Python 3:
  ```bash
  python -m http.server 8000
  ```
  Acesse [http://localhost:8000/src](http://localhost:8000/src)

- Com Node.js:
  ```bash
  npx serve src
  ```
  Acesse [http://localhost:3000](http://localhost:3000)

---

## Estrutura de Pastas

```text
meu-website/
├── docs/               # Arquivos de documentação (imagens, GIFs, etc.)
│   └── images/
│       └── demo.png
├── src/                # Código-fonte do site
│   ├── index.html       # Página principal
│   ├── css/             # Estilos
│   │   └── style.css
│   ├── js/              # Scripts
│   │   └── main.js
│   └── assets/          # Imagens e outros arquivos
│       └── images/
├── README.md            # Documentação do projeto
└── LICENSE              # Arquivo de licença
```

---

## Como Contribuir

1. Faça um fork do projeto  
2. Crie uma branch para sua feature (`git checkout -b minha-feature`)  
3. Commit suas alterações (`git commit -m 'Minha nova feature'`)  
4. Envie para o seu fork (`git push origin minha-feature`)  
5. Abra um Pull Request  

---

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
