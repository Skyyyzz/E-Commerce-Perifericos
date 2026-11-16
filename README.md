# PC Store | E-Commerce de Periféricos

<div align="center">

<img src="https://img.shields.io/badge/Status-Em_desenvolvimento-243447?style=for-the-badge" alt="Em desenvolvimento" />
<img src="https://img.shields.io/badge/React-161b22?style=for-the-badge&logo=react&logoColor=61dafb" alt="React" />
<img src="https://img.shields.io/badge/Vite-161b22?style=for-the-badge&logo=vite&logoColor=a78bfa" alt="Vite" />

**Projeto de estudo de desenvolvimento front-end para uma loja de periféricos e acessórios.**

</div>

## Sobre o projeto

A PC Store é um projeto em React para praticar a construção de interfaces, a organização de componentes e a navegação entre páginas de um e-commerce. O código utiliza JavaScript, CSS e React Router, com Vite no ambiente de desenvolvimento.

O projeto está em uma etapa inicial. As telas de carrinho e conta possuem conteúdo introdutório; os fluxos de compra e autenticação ainda precisam ser desenvolvidos.

## Estrutura atual

- Rotas para início, categorias, produtos, carrinho e minha conta.
- Rota de página não encontrada.
- Cabeçalho e rodapé compartilhados na aplicação.
- Organização de páginas, componentes, dados, estilos e imagens em diretórios próprios.

## Tecnologias

| Tecnologia | Uso no projeto |
| --- | --- |
| React | Construção da interface com componentes |
| JavaScript | Código da aplicação |
| React Router | Navegação entre páginas |
| CSS | Estilização da interface |
| Vite | Servidor de desenvolvimento e build |
| Oxlint | Análise estática do código |

## Como executar

Tenha Node.js e npm instalados, em versões compatíveis com as dependências do projeto.

```bash
git clone https://github.com/Skyyyzz/E-Commerce-Perifericos.git
cd E-Commerce-Perifericos
npm ci
npm run dev
```

Abra no navegador o endereço exibido pelo Vite no terminal.

### Comandos disponíveis

| Comando | Finalidade |
| --- | --- |
| `npm run dev` | Inicia o servidor de desenvolvimento |
| `npm run build` | Gera a versão de produção |
| `npm run preview` | Serve o build localmente, após gerar a versão de produção |
| `npm run lint` | Executa o Oxlint |

## Organização do código

| Diretório ou arquivo | Conteúdo |
| --- | --- |
| `src/pages/` | Páginas da aplicação |
| `src/components/` | Componentes compartilhados |
| `src/data/` | Dados utilizados no projeto |
| `src/styles/` | Estilos da interface |
| `src/assets/` | Imagens e recursos visuais |
| `src/App.jsx` | Estrutura principal e configuração das rotas |
| `src/main.jsx` | Ponto de entrada da aplicação |

## Próximas melhorias

- Evoluir a exibição e a navegação dos produtos.
- Implementar adição, remoção e atualização de itens no carrinho.
- Desenvolver o fluxo de conta e autenticação.
- Revisar responsividade e acessibilidade.
- Adicionar testes, capturas da interface e uma demonstração publicada.

## Autor

**Rodrigo Souza** — estudante de Ciência da Computação na UNIP e do curso Técnico em Desenvolvimento de Sistemas no Senac.

[GitHub](https://github.com/Skyyyzz) · [LinkedIn](https://www.linkedin.com/in/rodrigo-souza-5303b9339)
