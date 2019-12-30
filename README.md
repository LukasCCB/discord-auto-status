# Discord Alterar Status Automáticamente

Anime seu status com este BOT

**Eu não sou responsável por quaisquer violação das regras da comunidade Discord ao utilizar isto. Use por sua conta e risco.**

---

# Requisitos
- [NodeJS](https://nodejs.org/en/)
- [Conhecimento básico em JSON](https://www.json.org/)

# Instalação
1. Baixar/Clonar este repo
2. Extrair
3. Abrir seu terminal na pasta da repo
4. Escrever no terminal `npm install`
5. Renomear `config.json.example` para `config.json` e ajustar conforme seu uso - [Tutorial aqui](#Configuração)
6. Enter `node index.js`

# Configuração
- token `String`: Entre na conta do Discord que deseja obter o token **NÃO COMPARTILHE COM NINGUÉM, ESTE TOKEN CONTÉM DADOS ACESSIVEIS DE SUA CONTA** - [Como obter seu Token](#como-obter-seu-token)
- animation `Array`:
	- text `String`: Text to display as custom status
	- emojiID `String|null`: Emoji ID of the emoji you want to display or `null` for nothing - [How to get your emojiID](#how-to-get-your-emojiid)
	- emojiName `String|null`: Emoji name of the emoji you want to display or `null` for nothing
	- timeout `Number`: Amount in **milliseconds** how long to wait before continuing to the next one

# Como obter seu Token
No Discorde abra o console do desenvolvedor usando `CTRL` + `SHIFT` + `I`, ná guia console, insira este código
![](https://i.imgur.com/byd76Xh.png)

```JS
var req=webpackJsonp.push([[],{extra_id:(e,r,t)=>e.exports=t},[["extra_id"]]]);for(let e in req.c)if(req.c.hasOwnProperty(e)){let r=req.c[e].exports;if(r&&r.__esModule&&r.default)for(let e in r.default)"getToken"===e&&console.log(r.default.getToken())}
```

Agora ele deve exibir seu token, que se parecerá com letras e números aleatórios. Esse é o seu token, copie seu **token**.

# Como obter o ID de um Emoji (Isto vale também para emoji customizados ou animados desde que tenha Discord Nitro)
![](https://media.giphy.com/media/j5bbEYtka86PmVYf8s/giphy.gif)
