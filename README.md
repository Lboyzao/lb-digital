# LB Digital — SEO para Google

Esta atualização acrescenta metadados SEO, endereço canônico, Open Graph, robots.txt e sitemap.xml.

## Instalar
Envie `index.html`, `robots.txt` e `sitemap.xml` diretamente na raiz do repositório GitHub `lb-digital`, substituindo os dois arquivos existentes. O Cloudflare Pages fará uma nova implantação automaticamente.

## Google Search Console
1. Entre em https://search.google.com/search-console/
2. Adicione uma propriedade do tipo **Prefixo do URL** com `https://lb-digital.pages.dev/`.
3. Escolha verificação por **Arquivo HTML**. Baixe o arquivo de verificação fornecido pelo Google e envie-o à raiz do repositório GitHub, mantendo o nome exato. Aguarde a implantação do Cloudflare.
4. Volte ao Search Console e clique em **Verificar**.
5. Inspecione `https://lb-digital.pages.dev/` e clique em **Solicitar indexação**.
6. Na seção Sitemaps, envie `https://lb-digital.pages.dev/sitemap.xml`.

**Observações:** a indexação não é garantida e pode demorar. Esta versão continua sendo um painel demonstrativo, não um serviço com busca de empresas, banco de dados e login reais. Uma página institucional pública, com conteúdo original sobre serviços, contato e portfólio, tende a ser mais adequada para atrair clientes do que um painel demonstrativo. Não envie credenciais ou chaves privadas para o GitHub público.
