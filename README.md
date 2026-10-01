# Vivano Steak — site estático

Site mobile first, sem framework, pronto para GitHub Pages. A página principal está em `index.html` e a central de links em `tree/index.html`.

## Publicar no GitHub Pages

1. Crie um repositório e envie o conteúdo desta pasta para a raiz da branch principal.
2. Em **Settings → Pages**, selecione **Deploy from a branch**, a branch principal e a pasta **/(root)**.
3. Aguarde a URL pública. O site usa caminhos relativos, então funciona tanto em domínio próprio quanto em `usuario.github.io/repositorio/`.
4. Se configurar um domínio próprio, ajuste o DNS e crie um arquivo `CNAME` com o domínio escolhido. Depois de ativo, defina a URL canônica e `og:url` nas duas páginas.
5. Rode o PageSpeed Insights na URL pública, em mobile e desktop. A medição pública depende da URL final e da rede do visitante.

## Conteúdo e ativos

- Identidade visual e logo vetorial: `G:\Meu Drive\Design Multiuma\Vivano\IDV\assets` e kit `Vivano-Artes-Vetor`.
- Fotos: extraídas das peças da Vivano em `01_Instagram_Posts`; fachada do arquivo de identidade.
- Fontes: Newsreader e Jost, com licenças OFL em `assets/`.
- Cardápio e delivery: site atual da Vivano no Google Sites.
- Telefone, email e endereço: fontes públicas atuais da Vivano; confirme esses dados antes de publicar se houver alterações operacionais.

O site não inclui scripts externos, cookies, analytics, vídeo automático ou fontes carregadas de terceiros. Não há dependências de build.
