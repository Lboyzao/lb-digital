# LB Digital — versão inicial atualizada

Painel demonstrativo em HTML, CSS e JavaScript. Não precisa instalar nada para testar: abra `index.html` no navegador.

## Publicar pelo GitHub + Cloudflare Pages

1. Crie um repositório no GitHub chamado `lb-digital`.
2. Extraia este ZIP no computador.
3. Abra o repositório e escolha **Add file → Upload files**.
4. Envie os arquivos que estão DENTRO da pasta extraída, mantendo `index.html` na raiz do repositório. Envie também `robots.txt`, `supabase/` e este README.
5. Clique em **Commit changes**.
6. No Cloudflare Pages, escolha **Create a project → Connect to Git**, conecte o GitHub e selecione `lb-digital`.
7. Para este site estático, deixe o comando de build vazio e o diretório de saída como `/` (raiz), se a tela pedir. Conclua o deploy.

## O que esta versão faz

- Painel LB Digital responsivo.
- Cadastro manual de estabelecimentos, filtros e exportação CSV.
- Atalhos para pesquisar empresas e abrir o Google Maps.
- Modelos demonstrativos para iniciar projetos de sites.
- Salva os cadastros no armazenamento local do navegador em que foram feitos.

## Limitações importantes

Esta é uma base inicial de interface, não a plataforma comercial completa. Ainda não tem login real, banco de dados conectado, pesquisa automática de empresas, verificação automática de sites, colaboração entre dispositivos ou publicação de sites de clientes. O arquivo `supabase/schema.sql` é apenas o esquema inicial do banco; não conecte credenciais secretas no HTML público.

“Sem site confirmado” deve ser usado somente depois de verificação humana. Não encontrar um endereço de site numa busca não prova que a empresa não tenha site.
