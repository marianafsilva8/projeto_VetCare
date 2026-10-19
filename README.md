# 🐾 VetCare - Clínica Veterinária e Centro Diagnóstico

## 📌 Visão Geral e Objetivo do Projeto
Este projeto foi desenvolvido como parte de uma simulação de prática profissional front-end. O objetivo principal é construir a landing page responsiva para o **VetCare Hospital Veterinário**, oferecendo uma interface semântica, acessível e intuitiva para tutores de animais de estimação que buscam atendimento médico especializado e pronto atendimento 24 horas[cite: 1, 3, 7].

O projeto aplica na prática conceitos fundamentais de arquitetura CSS, metodologia BEM, responsividade fluida, além da integração interativa via API do WhatsApp para atendimento rápido[cite: 1, 4].

---

## 🛠️ Tecnologias e Conceitos Aplicados

- **HTML5 Semântico**: Estruturação clara das seções (`<nav>`, `<header>`, `<main>`, `<section>`, `<details>`, `<summary>`, `<footer>`) focando em acessibilidade e SEO[cite: 1, 4].
- **CSS3 Puro**: Uso de CSS Variables (Tokens do Design System), Flexbox para layout e transições de microinteratividade (`:hover`, `box-shadow`)[cite: 3, 4, 5].
- **Metodologia BEM (Block Element Modifier)**: Padrão rigoroso de nomenclatura de classes HTML e seletores CSS para garantir modularidade e manutenibilidade do código[cite: 1].
- **Tipografia e Unidades Relativas**:
  - Escala base configurada na raiz via porcentagem e resgatada no elemento `body`.
  - Tipografia, espaçamentos e bordas gerenciados estritamente com a unidade relativa proporcional `rem`[cite: 2].
  - Uso de porcentagem (`%`) e unidades de viewport (`vh`/`vw`) para layouts flexíveis e de tela cheia, restringindo o uso de pixels apenas para detalhes pontuais como bordas[cite: 2].
- **Google Fonts**: Importação da família de fontes **Poppins** (pesos 400, 500, 600 e 700)[cite: 2, 6].
- **API do WhatsApp**: Redirecionamento flutuante configurado com a URL oficial e o contato telefônico do SENAI Henrique Lupo.

---

## 📂 Organização da Arquitetura de Arquivos

A estrutura do projeto foi organizada prezando pela estrita separação de responsabilidades (sem o uso de estilos inline ou blocos `<style>` embutidos no HTML)[cite: 1]:

```text
vetcare-hospital/
├── index.html                # Estrutura HTML semântica da aplicação
├── assets/
│   ├── css/
│   │   ├── variables.css     # Tokens de Design System (variáveis CSS)
│   │   ├── reset.css         # Reset de estilos globais e escala REM da raiz
│   │   ├── components.css    # Estilos de cards, botões, FAQ e menu lateral (BEM)
│   │   └── style.css         # Arquivo principal / importação e media queries
│   └── images/               # Imagens institucionais e de suporte
└── README.md                 # Documentação oficial do repositório

## 💻 Instruções de Visualização e Execução

Para visualizar, testar e rodar o projeto localmente ou em ambiente web, siga os passos abaixo:

### Opção 1: Execução Local
1. **Clonar o repositório do GitHub**:
   ```bash
   git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)