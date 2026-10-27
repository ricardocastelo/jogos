# Jogos da Família — arquivos de ícone

## Arquivos incluídos
- `manifest.webmanifest`: identidade do aplicativo para o Chrome/Android.
- `icon-192.png` e `icon-512.png`: tamanhos padrão do ícone de aplicativo.
- `icon-maskable-512.png`: ícone preparado para recorte adaptativo do Android.
- `apple-touch-icon.png`: ícone de atalho para iPhone/iPad.
- `favicon-32.png`: ícone de aba/favorito.
- `head-links.html`: trechos a inserir dentro da seção `<head>` do HTML existente.

## Instalação no GitHub Pages
1. Envie estes arquivos para a **raiz do repositório** que publica esta aplicação (não crie uma subpasta).
2. No `index.html` existente, abra a seção `<head>` e copie de `head-links.html` as linhas de metadados e links. Não substitua o HTML inteiro da aplicação por esse trecho.
3. Mantenha os caminhos relativos `./...`, que funcionam quando os arquivos estão na mesma raiz do `index.html`.
4. Faça Commit na branch publicada pelo GitHub Pages e aguarde a publicação em Actions.
5. No Android, remova o atalho antigo da tela inicial. Abra a página atualizada no Chrome e use ⋮ → **Adicionar à tela inicial** ou **Instalar app**, se essa opção aparecer.

Os navegadores podem guardar o ícone antigo em cache. Remover e criar novamente o atalho é importante para forçar a atualização. O conteúdo do Apps Script/iframe não muda; este ajuste modifica o ícone da página externa publicada pelo GitHub Pages.
