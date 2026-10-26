# EditaHTML 1.2

Editor leve para editar HTML e outros arquivos de código, com realce de sintaxe, numeração de linhas, busca e substituição, histórico local, desfazer/refazer e pré-visualização em modo automático, smartphone ou PC.

## Recursos
- Editor com realce de sintaxe e numeração de linhas.
- Abrir arquivos locais e exportar escolhendo a extensão.
- Histórico local de versões e pontos de recuperação.
- Desfazer/refazer e atalhos de teclado.
- Painéis de ações recolhíveis e ajuda por título/toque longo.
- Testar código em prévia isolada ou em outra aba.
- PWA instalável, com cache para uso offline após a primeira visita.

## Publicação
Os arquivos desta pasta compõem o site. Publique a pasta mantendo a estrutura de `index.html`, `manifest.webmanifest`, `sw.js` e `icons/`. A instalação PWA requer HTTPS (GitHub Pages fornece HTTPS). A abertura direta do HTML como arquivo local funciona como editor, mas instalação PWA e service worker só funcionam em um site servido por HTTPS ou localhost.

## Dados e segurança
Rascunhos e histórico são armazenados no armazenamento local do navegador. O modo de teste executa o código dentro de um iframe isolado; ainda assim, execute apenas código em que confia.
