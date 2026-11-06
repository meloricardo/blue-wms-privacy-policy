# Política de privacidade do Blue-WMS

Página pública da política de privacidade do aplicativo Blue-WMS (pacote `ascblue.bluewms`), exigida pelo Google Play.

- Conteúdo: [`index.html`](index.html), servido pelo GitHub Pages a partir da raiz da branch `main`.
- Endereço publicado: `https://meloricardo.github.io/blue-wms-privacy-policy/`, que é a URL informada no Play Console em **Conteúdo do app → Política de privacidade**.
- Página de demonstração: [`demo/index.html`](demo/index.html), em `https://meloricardo.github.io/blue-wms-privacy-policy/demo/`, com as etiquetas de local e os códigos de barras dos produtos fictícios do servidor de demonstração. O revisor do Google só consegue separar um pedido lendo esses códigos com a câmera; o endereço vai em **Detalhes do login** no Play Console.

## Ao alterar

- A política precisa bater com o formulário de **Segurança dos dados** do app no Play Console. Mudou um, revise o outro.
- Atualize a data de "Última atualização" no topo da página.
- A estrutura segue as políticas do Blue Delivery e do Blue Commerce, para as três dizerem o mesmo sobre controladora, operadora, base legal e transmissão.
- As imagens de `demo/` vêm de `backend/src/BlueMobile.MockApi/docs/codigos-de-barras/wms/` do repositório `blue-mobile`. Mudou um dado do mock, regere as imagens lá e copie para cá.
- O código do aplicativo fica no repositório privado `blue-mobile`; este repositório é público e não deve receber nada além da política e da página de demonstração.
