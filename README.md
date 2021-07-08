<p align="center">
<a href="#"><img title="WHATSAPP DEV" src="https://img.shields.io/badge/Whatsapp Bot-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/Akkinori"><img title="Author" src="https://img.shields.io/badge/Author-Akinori-red.svg?style=for-the-badge&logo=github"></a>
</p>

## Instalar o bot

```bash
> termux-setup-storage
> apt update && apt upgrade
> pkg install git
> pkg install nodejs-lts
> git clone https://github.com/Akkinori/teddy-wabot
> cd teddy-wabot
> bash install.sh
```

<summary>Para gerar o qr code

```bash
> npm start
```

<summary>Para o bot não cair

```bash
> npm i -g pm2
> pm2 start index.js
> pm2 momit
```