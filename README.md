# Ecco Visuals

Biblioteca visual compartilhada dos produtos Ecco.

## Estrutura
- `gifs/` — visuais gerais
- `gifs/rp/` — Ecco RP
- `gifs/admin/` — Ecco Admin
- `gifs/constructor/` — Ecco Constructor

## Integração
A biblioteca **não troca emojis automaticamente**. Cada bot precisa ser configurado uma vez para apontar os eventos desejados para os GIFs.

Depois de publicar este repositório no GitHub como público, as URLs terão este formato:

`https://raw.githubusercontent.com/SEU-USUARIO/Ecco-Visuals/main/gifs/verified.gif`

Em Discord.js, por exemplo:

```js
const visuals = {
  verified: 'https://raw.githubusercontent.com/SEU-USUARIO/Ecco-Visuals/main/gifs/verified.gif'
};

embed.setImage(visuals.verified);
```

A ideia é deixar todas as URLs em um único `visuals.js` dentro de cada bot.
