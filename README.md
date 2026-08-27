# projeto-github

Projeto HTML, CSS e JavaScript desenvolvido durante um workshop de GitHub na COTI Informática.

## Sobre

Este repositório contém um projeto front-end simples criado durante o workshop. O objetivo foi praticar controle de versão com Git/GitHub e construir páginas web usando as tecnologias básicas da web.

## Tecnologias

- HTML
- CSS
- JavaScript

> A composição de linguagens do repositório é principalmente HTML, com estilos em CSS e scripts em JavaScript.

## Estrutura do projeto (exemplo)

- index.html
- css/
  - styles.css
- js/
  - main.js
- assets/
  - imagens, ícones, etc.

(Os nomes de arquivos/pastas podem variar conforme a implementação do workshop.)

## Como abrir e rodar o projeto no VS Code

1. Abra o Visual Studio Code.
2. Vá em `File` > `Open Folder...` (ou `Arquivo` > `Abrir Pasta...`) e selecione a pasta do projeto (a raiz deste repositório).
3. Abra o arquivo `index.html` no editor.

Recomendado: usar a extensão Live Server

4. Instale a extensão Live Server (pesquise por "Live Server" na Marketplace do VS Code — extensão de Ritwick Dey).
5. Após instalada, clique em "Go Live" no canto inferior direito ou clique com o botão direito em `index.html` e selecione "Open with Live Server".
   - O Live Server irá abrir o projeto no navegador e fará reload automático quando você salvar alterações.

Alternativas sem extensões

- Abra o `index.html` diretamente no navegador (duplo clique no arquivo) — funciona na maioria dos casos.
- Ou rode um servidor HTTP simples via terminal:
  - Com Python 3: `python3 -m http.server 8000` e acesse `http://localhost:8000`.

## Boas práticas

- Use branches para novas funcionalidades: `git checkout -b minha-feature`.
- Faça commits pequenos e com mensagens descritivas: `git commit -m "Adiciona formulário de contato"`.
- Abra Pull Requests para revisar mudanças antes de mesclar.

## Contribuição

Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias, correções ou dúvidas. Descreva as mudanças e o objetivo no PR para facilitar a revisão.

## Licença

Sem licença especificada — adicione um arquivo `LICENSE` se desejar permitir usos específicos do código.
