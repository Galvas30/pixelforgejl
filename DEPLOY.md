# Pixelforge JL — Deploy Guide

## Arquivos para subir no Vercel

Sobe os seguintes arquivos juntos numa pasta:

```
📁 pixelforge/
├── pixelforge.html   ← site principal
├── favicon.ico       ← ícone da aba do navegador
├── og-image.png      ← imagem de preview (WhatsApp, redes)
└── vercel.json       ← configuração do Vercel
```

---

## Como subir no Vercel (passo a passo)

1. Acesse [vercel.com](https://vercel.com) e crie uma conta gratuita
2. Clique em **"Add New Project"**
3. Escolha **"Deploy from your local files"** (arrasta a pasta)
4. Clique em **Deploy** — pronto! ✅

Seu site vai estar no ar em menos de 1 minuto com HTTPS automático.

---

## Conectar domínio próprio (ex: pixelforge.com.br)

1. No painel do Vercel, vá em **Settings → Domains**
2. Digite seu domínio (ex: `pixelforge.com.br`)
3. O Vercel vai te dar um código DNS para configurar no Registro.br
4. Acesse [registro.br](https://registro.br), vá em **DNS** do seu domínio
5. Adicione o registro que o Vercel indicou
6. Aguarde até 24h para propagar (geralmente bem mais rápido)

---

## Atualizar o site depois

Basta arrastar os arquivos novamente no painel do Vercel — ele publica a nova versão automaticamente.

---

Feito com ❤️ por João & Luigi — Pixelforge JL
