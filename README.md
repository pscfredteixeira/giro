# Giro da Psicaótica — Montador para Substack

Aplicativo web estático (V12) para transformar a exportação do grupo de WhatsApp do Giro da Psicaótica em um rascunho organizado para o Substack.

## Como usar

1. Abra `index.html` no navegador, ou acesse a página publicada com GitHub Pages.
2. Exporte a conversa do grupo no WhatsApp, de preferência **sem mídia**.
3. Importe o arquivo `.zip` ou `.txt`.
4. Revise as contribuições, os nomes, os @ do Instagram, os links da Amazon e as capas dos livros.
5. Confira a prévia e copie o texto formatado para o editor do Substack.
6. Revise novamente no Substack antes de publicar.

Os textos das conversas são processados no navegador e não são enviados a um servidor próprio. A busca de capas consulta serviços externos (Google Livros e Open Library); imagens também podem ser obtidas de fontes externas. O navegador pode guardar preferências locais de integrantes e capas.

## Publicar com GitHub Pages

No repositório, vá em **Settings → Pages → Build and deployment**. Em **Source**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/(root)`, e salve.

Quando o GitHub Pages terminar de publicar, o endereço esperado será: https://pscfredteixeira.github.io/giro/

> Este aplicativo **não publica automaticamente** no Substack. Links de afiliados e capas devem ser conferidos antes de enviar a newsletter.
