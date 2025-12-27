# ShadcnViteReactTemplate

Um template otimizado para construção rápida de aplicações web modernas utilizando a biblioteca de componentes **shadcn/ui** com **Vite** e **React**. Disponibiliza um ambiente JavaScript pré-configurado, garantindo um fluxo de trabalho de desenvolvimento fluido e eficiente.

## 🚀 Funcionalidades

- **Stack Moderna**: Construído com Vite, React e Tailwind CSS.
- **Biblioteca de Componentes**: [shadcn/ui](https://ui.shadcn.com/) pré-instalado e configurado.
- **HMR Rápido**: Servidor de desenvolvimento extremamente veloz com Vite.
- **Estrutura Limpa**: Código mínimo para iniciar o desenvolvimento imediatamente.
- **ESLint & Prettier**: Configuração básica para consistência de código.

## 📦 Prerrequisitos

- Node.js (v18+ recomendado)
- npm ou yarn (usamos npm nos exemplos)

## ⚡ Início Rápido

1. **Clonar o repositório**
   bash
   git clone https://github.com/seu-usuario/shadcn-ui-vite-react.git
   cd shadcn-ui-vite-react
   

2. **Instalar dependências**
   bash
   npm install
   

3. **Iniciar o servidor de desenvolvimento**
   bash
   npm run dev
   

4. **Abrir o navegador**
   Visite `http://localhost:5173` para ver sua aplicação.

## 📂 Estrutura do Projeto

bash
├── public/
├── src/
│   ├── components/
│   │   └── ui/          # Componentes shadcn/ui
│   ├── App.jsx
│   └── main.jsx
├── .eslintrc.cjs
├── .prettierrc
├── tailwind.config.js
├── components.json       # Configuração shadcn/ui
└── vite.config.js


## 🛠️ Scripts Disponíveis

- `npm run dev`: Inicia o servidor de desenvolvimento.
- `npm run build`: Compila a aplicação para produção.
- `npm run preview`: Visualiza localmente a build de produção.
- `npm run lint`: Verifica erros de linting.

## 🧩 Adicionando Componentes

Este template usa `shadcn/ui`. Para adicionar novos componentes, execute o comando `init` (se não foi feito) e depois adicione os componentes específicos:

bash
# Inicializar (geralmente já feito neste template)
npx shadcn-ui@latest init

# Adicionar componente de botão
npx shadcn-ui@latest add button

Consulte a [documentação do shadcn/ui](https://ui.shadcn.com/docs/installation) para mais detalhes.

## 📄 Licença

Licença MIT. Sinta-se livre para usar este template em seus projetos.