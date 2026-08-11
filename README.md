# Guia prático de Angular — Minicurso

Site de página única (apostila digital) para um minicurso de Angular de ~3 horas,
com foco em CRUD. Conteúdo alinhado ao **Angular 17 / Node.js 18**.

Recursos: menu lateral navegável, modo claro/escuro, botão "copiar" em cada bloco
de código, barra de progresso de leitura e navegação entre capítulos.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `minicurso-angular`).
2. Envie o arquivo **`index.html`** para a raiz do repositório.
   - Pelo site: botão **Add file → Upload files**, arraste o `index.html`, **Commit**.
3. No repositório, vá em **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch**.
5. Em **Branch**, selecione **main** e a pasta **/ (root)**. Clique em **Save**.
6. Aguarde ~1 minuto. O site fica disponível em:
   `https://SEU-USUARIO.github.io/minicurso-angular/`

Pronto. É só um arquivo, sem build e sem dependências — funciona offline também
(basta abrir o `index.html` no navegador).
