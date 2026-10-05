# BBL TECH — site institucional

Site estático responsivo da BBL TECH, preparado para publicação no Cloudflare Pages.

A página `produtos.html` funciona como uma vitrine de desktops completos, notebooks, NVMEs, SSDs, pentes de memória, componentes, periféricos, energia, automação comercial, gamer/home office, rede, CFTV e serviços técnicos. Também apresenta kits prontos para Home Office, Empresa e Segurança. Os filtros são executados no navegador e os botões levam ao WhatsApp para consulta de estoque, preço ou atendimento.

Páginas adicionais: `servicos.html`, `sobre.html`, `projetos.html` e `contato.html`.

A página `produtos-digitais.html` reúne licenças, antivírus, produtividade, templates, configuração remota e backup em nuvem.

A página inicial também possui uma vitrine de produtos em destaque e um banner para os kits digitais.

Página dedicada ao Kit Outubro Rosa: `kit-outubro-rosa.html`, com apresentação ilustrativa em CSS e contato para consultar compra. O checkout poderá ser conectado quando o link específico estiver disponível.

## Cloudflare Pages

Este é um site Static HTML. No Cloudflare Pages, use `index.html` como arquivo principal, deixe o diretório de saída como a raiz do projeto e use `exit 0` como comando de build quando a publicação estiver conectada a um repositório Git. O arquivo `_headers` já está incluído para aplicar headers básicos de segurança.

## Visualizar localmente

Abra `index.html` diretamente no navegador. Como alternativa, use qualquer servidor local de arquivos estáticos.

## Publicar gratuitamente no Cloudflare Pages

1. Crie um novo projeto no Cloudflare Pages.
2. Conecte o repositório Git que contém estes arquivos (ou use o upload direto).
3. Para este site sem build, deixe o comando de build vazio e use a pasta raiz `/` como diretório de saída.
4. Publique. O Cloudflare fornecerá um endereço gratuito `*.pages.dev`.

Quando o domínio `bbltech.com.br` estiver disponível, ele poderá ser adicionado em **Custom domains** no projeto do Cloudflare Pages. Os links de WhatsApp já estão configurados para o número (92) 99158-7858.
