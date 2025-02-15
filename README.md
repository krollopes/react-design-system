# React Design System

Este repositório contém um Design System desenvolvido com React, TypeScript e Styled Components. Ele oferece uma coleção de componentes reutilizáveis, estilizados e acessíveis para acelerar o desenvolvimento de interfaces consistentes.

## 📌 Tecnologias Utilizadas

- ⚛️ **React** – Biblioteca para construção de interfaces
- 🟦 **TypeScript** – Tipagem estática para maior segurança no código
- 💅 **Styled Components** – Estilização dinâmica e modular
- 📖 **Storybook** – Documentação e visualização interativa de componentes
- 🧪 **Jest & React Testing Library** – Testes unitários e de integração
- 🚀 **Vite** – Ferramenta para build e desenvolvimento rápido

## 📁 Estrutura do Projeto

```
react-design-system/
├── .storybook/            # Configurações do Storybook
├── src/
│   ├── components/        # Componentes reutilizáveis
│   ├── styles/            # Estilos globais
│   ├── utils/             # Utilitários e helpers
│   ├── index.ts           # Ponto de entrada
├── .gitignore
├── package.json
├── tsconfig.json
├── README.md
└── vite.config.ts
```

## 🚀 Instalação e Uso

1. Clone o repositório:
   ```sh
   git clone https://github.com/krollopes/react-design-system.git
   cd react-design-system
   ```
2. Instale as dependências com **pnpm**:
   ```sh
   pnpm install
   ```
3. Inicie o ambiente de desenvolvimento:
   ```sh
   pnpm dev
   ```
4. Para visualizar os componentes no Storybook:
   ```sh
   pnpm storybook
   ```
5. Execute os testes:
   ```sh
   pnpm test
   ```

## 📌 Principais Componentes

- **Button** – Botão estilizado com variantes (primary, secondary, etc.)
- **Typography** – Elementos de texto padronizados
- **Input** – Campos de entrada com estados e validação
- **Modal** – Componente de modal acessível
- **ThemeProvider** – Suporte para temas customizáveis

## 🧪 Testes

O projeto utiliza **Jest** e **React Testing Library** para garantir qualidade e confiabilidade dos componentes.

- Rodar todos os testes:
  ```sh
  pnpm test
  ```
- Rodar testes em modo watch:
  ```sh
  pnpm test:watch
  ```

## 📜 Licença

Este projeto está sob a licença **MIT**. Sinta-se à vontade para contribuir e utilizar!

---

✨ Criado por [Caroline Lopes](https://github.com/krollopes). Contribuições são bem-vindas! 🚀

