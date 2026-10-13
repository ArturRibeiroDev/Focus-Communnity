# Focus Academy — Landing Page

Landing page estática, responsiva, em português. Sem build, frameworks ou dependências.

## Publicar

**Netlify:** envie esta pasta em *Add new project > Deploy manually* ou conecte um repositório. Publish directory: `.`; build command: vazio.

**Vercel:** importe o repositório, selecione framework **Other**, sem build command; output directory `.`. O `vercel.json` já inclui cabeçalhos básicos.

**GitHub Pages:** publique o conteúdo da pasta a partir da raiz de sua branch de publicação. Para funcionar também em uma subpasta, o favicon usa caminho absoluto e pode precisar mudar para `./favicon.svg`.

**Prévia local:** execute `python3 -m http.server 8080` na pasta e visite `http://localhost:8080`.

## Antes da publicação oficial

- Definir domínio e, se desejar, configurar `canonical`, `og:url`, imagem de compartilhamento e sitemap com o domínio definitivo.
- Vincular botões e chamadas para a aplicação real, se quiser direcionar usuários para cadastro ou catálogo: a versão atual mantém links internos, como na v3.
- Revisar textos do roadmap e das funcionalidades para refletirem o estado real do produto.

## Arquivos

- `index.html`: site com CSS e JS embutidos.
- `favicon.svg`: favicon vetorial.
- `robots.txt`: permite indexação.
- `netlify.toml`, `vercel.json`: configurações opcionais para cada hospedagem.

A preferência por tema claro/escuro é salva no navegador, com compatibilidade com a preferência anterior de FocusEdu.
# Focus-Communnity
