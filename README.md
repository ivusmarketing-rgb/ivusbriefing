# Briefing — Romeo Pizza Bar & Torúm

One-page de briefing de redes sociais, produzido pela Ivus Studio de marca e conteúdo.

## Deploy

Site estático (sem build). No Cloudflare Pages:
- Comando de build: vazio
- Diretório de saída: `/`

## Envio das respostas

O formulário envia as respostas por e-mail via [Formspree](https://formspree.io).
Antes de publicar, configure o endpoint no `index.html`:

```js
var FORMSPREE_ENDPOINT = 'https://formspree.io/f/SEU_ID_AQUI';
```

Troque `SEU_ID_AQUI` pelo ID gerado na sua conta Formspree.
