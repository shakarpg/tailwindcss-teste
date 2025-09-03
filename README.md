# TailwindCSS  Project

Este projeto tem como objetivo fornecer um ambiente simples para explorar e testar o framework **Tailwind CSS**. Ele contém uma configuração inicial básica para facilitar o aprendizado e a personalização da estilização usando Tailwind.

## 🚀 Tecnologias Utilizadas

- **Tailwind CSS**: Framework CSS utilitário para criar designs rápidos e responsivos.
- **PostCSS**: Ferramenta de transformação de CSS que ajuda a otimizar o código.
- **Autoprefixer**: Plugin para garantir que o código CSS seja compatível com diferentes navegadores.

## 📦 Instalação

Para configurar este projeto em sua máquina local, siga os passos abaixo:

### 1. Clone o Repositório

Clone este repositório usando o comando:

```bash
git clone https://github.com/shakarpg/tailwindcss-teste.git
````

### 2. Instale as Dependências

Instale as dependências necessárias para o projeto. Se você ainda não possui o **Node.js** instalado, faça o download e instalação através de [nodejs.org](https://nodejs.org/).

Execute os seguintes comandos no diretório do projeto:

```bash
npm install
```

### 3. Configuração do Tailwind CSS

Para configurar o **Tailwind CSS**, execute o seguinte comando para gerar os arquivos de configuração:

```bash
npx tailwindcss init -p
```

Isso criará os arquivos de configuração `tailwind.config.js` e `postcss.config.js` em seu projeto.

### 4. Configure o Arquivo CSS

Crie um arquivo CSS em `src/styles.css` com o conteúdo abaixo:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 5. Compile o CSS

Adicione um script no arquivo `package.json` para compilar o Tailwind CSS:

```json
"scripts": {
  "build": "tailwindcss -i ./src/styles.css -o ./dist/styles.css --watch"
}
```

### 6. Executando o Projeto

Para iniciar a compilação e assistir a alterações no arquivo CSS, execute:

```bash
npm run build
```

Isso criará um arquivo `dist/styles.css` que pode ser incluído no seu arquivo HTML.

### 7. Atualize o HTML

No arquivo `index.html`, adicione a referência ao CSS gerado:

```html
<link href="/dist/styles.css" rel="stylesheet">
```

## 💡 Como Contribuir

1. Fork este repositório.
2. Crie uma branch para sua nova feature ou correção: `git checkout -b feature-nome-da-feature`.
3. Realize suas alterações e faça commit delas: `git commit -m 'Adiciona nova feature'`.
4. Envie para sua branch: `git push origin feature-nome-da-feature`.
5. Abra um Pull Request no repositório principal.

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📌 Referências

* [Documentação do Tailwind CSS](https://tailwindcss.com/docs)
* [PostCSS](https://postcss.org/)
* [Autoprefixer](https://github.com/postcss/autoprefixer)

## 📬 Contato

Se você tiver alguma dúvida ou sugestão, fique à vontade para abrir uma **issue** ou enviar um **pull request**!
