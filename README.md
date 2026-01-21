# 📁 Estrutura do Projeto

## 🚀 Tecnologias Utilizadas

HTML5 – Estrutura do site

SASS (SCSS/SASS) – Estilização modular e organizada

JavaScript (Vanilla) – Lógica e interações no front-end

## 📦 e-commerce-demo
├── index.html                  # Página principal da aplicação
├── assets
│   ├── css
│   │   └── app.css             # CSS final gerado pelo SASS (OUTPUT)
│   ├── sass
│   │   ├── app.sass             # Arquivo principal do SASS (INPUT)
│   │   ├── 0-plugins            # Bibliotecas, mixins e helpers externos
│   │   ├── 1-base               # Reset, variáveis, tipografia e estilos globais
│   │   ├── 2-layouts            # Estrutura do layout (header, footer, grid, etc.)
│   │   └── 3-modules            # Componentes reutilizáveis (cards, botões, etc.)
│   ├── js
│   │   └── index.js             # Script principal do projeto
│   └── img                      # Imagens do site
└── README.md


## 🎨 Organização do SASS

O projeto segue uma organização em camadas para facilitar manutenção e escalabilidade:

0-plugins → Dependências, mixins e funções

1-base → Estilos globais (reset, variáveis, tipografia)

2-layouts → Estrutura das páginas

3-modules → Componentes reutilizáveis

## ▶️ Como Clonar o Projeto
git clone https://github.com/seu-usuario/e-commerce-demo.git
cd e-commerce-demo

2️⃣ Instalar o SASS (caso não tenha)

Usando npm:

npm install -g sass


Verifique a instalação:

sass --version

### Compilação única:
sass sass/app.sass:css/app.css

### Modo automático (recomendado para desenvolvimento):
sass sass/app.sass:css/app.css --watch

## 📌 Observações
Projeto 100% front-end
Não possui backend ou integração com banco de dados
Ideal para estudos, demonstração e evolução futura

## 👨‍💻 Autor

Desenvolvido por Andrealezy
📧 Sugestões e melhorias são bem-vindas!