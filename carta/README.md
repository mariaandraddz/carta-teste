# Carta para você

Site de declaração romântica em um único arquivo (`index.html`).

## Personalizar

Abra o `index.html` e escreva o nome dele em `var NOME = "";` perto do final do arquivo.
O texto da carta e os motivos também estão no próprio `index.html`.

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub.
2. Na pasta do projeto:
   ```bash
   git init
   git add -A
   git commit -m "Carta de amor"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
   git push -u origin main
   ```
3. No repositório, vá em Settings > Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)`.
4. Deixe o campo "Custom domain" vazio.
5. Depois de cerca de um minuto o site abre em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.
