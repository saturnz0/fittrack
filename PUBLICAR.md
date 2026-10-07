# FitTrack V1 — publicação

Projeto PWA mobile-first de acompanhamento de academia.

## Opção 1 — GitHub Pages
1. Crie um repositório público no GitHub.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Vá em **Settings → Pages**.
4. Em Source, selecione **Deploy from a branch**.
5. Selecione `main` e `/ (root)`.
6. Salve e aguarde o endereço do site.
7. Abra o endereço no Chrome do celular e escolha **Adicionar à tela inicial**.

## Opção 2 — Netlify
Crie um novo site e envie a pasta inteira. O arquivo `netlify.toml` já está incluído.

## Opção 3 — Vercel
Importe o repositório. O `vercel.json` já está incluído.

## Teste local
Na pasta do projeto:
`python -m http.server 8080`

Depois acesse:
`http://localhost:8080`

## Observação
A V1 usa dados de exemplo em memória. O próximo passo é adicionar persistência local e depois sincronização em nuvem.
