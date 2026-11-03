# Bravos Pro Shop

Loja oficial do **Bravos Futebol Americano**, temporada 2026. O catálogo é exibido no site e o pedido é finalizado pelo WhatsApp (sem checkout/pagamento online).

## Rodar localmente

```bash
npm install
npm run dev
```

## Build de produção

```bash
npm run build   # gera a pasta dist/
```

## Onde editar

Tudo fica em `index.html`, no bloco `CONFIG` do script:

- `WHATSAPP`: número que recebe os pedidos (formato `55DDDNUMERO`)
- `PRODUCTS`: nome, preço, descrição, fotos e variações (tamanho, cor, modelo) de cada produto
- `LOOKS`: fotos do Game Day Lookbook
- `TICKER`: frases da faixa de notícias no topo
- `SIZE_TABLE`: tabela de medidas (Combine)

As imagens ficam em `public/img/` (WebP).
