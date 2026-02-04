# Guia Rápido de Deploy - EasyProt Consult

Seu site está pronto para ser publicado! Escolha uma das opções abaixo:

## 🚀 Opção 1: Vercel (RECOMENDADO - Mais Rápido)

### Passo 1: Preparar o repositório Git
```bash
cd /home/ubuntu/easyprot-website
git init
git add .
git commit -m "Initial commit: EasyProt Consult website"
git branch -M main
git remote add origin https://github.com/seu-usuario/easyprotconsult-website.git
git push -u origin main
```

### Passo 2: Deploy no Vercel
1. Acesse [vercel.com](https://vercel.com)
2. Clique em "New Project"
3. Selecione "Import Git Repository"
4. Cole a URL do seu repositório GitHub
5. Clique em "Import"
6. Clique em "Deploy"
7. **Pronto!** Seu site estará online em ~30 segundos

**URL do site:** `https://seu-projeto.vercel.app`

---

## 🚀 Opção 2: Netlify

### Passo 1: Preparar o repositório Git
(Mesmo processo da Opção 1)

### Passo 2: Deploy no Netlify
1. Acesse [netlify.com](https://netlify.com)
2. Clique em "New site from Git"
3. Selecione seu repositório GitHub
4. Clique em "Deploy site"
5. **Pronto!** Seu site estará online

**URL do site:** `https://seu-site-aleatorio.netlify.app`

---

## 🚀 Opção 3: GitHub Pages (Mais Simples)

### Passo 1: Criar repositório no GitHub
1. Acesse [github.com/new](https://github.com/new)
2. Nome: `easyprotconsult-website`
3. Descrição: "Site institucional da EasyProt Consult"
4. Clique em "Create repository"

### Passo 2: Fazer push do código
```bash
cd /home/ubuntu/easyprot-website
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/seu-usuario/easyprotconsult-website.git
git push -u origin main
```

### Passo 3: Ativar GitHub Pages
1. Vá para Settings → Pages
2. Em "Source", selecione "Deploy from a branch"
3. Selecione "main" branch
4. Clique em "Save"
5. **Pronto!** Seu site estará em `https://seu-usuario.github.io/easyprotconsult-website`

---

## 📝 Personalizar Domínio Próprio

Após deploy em qualquer plataforma:

### Vercel
1. Vá para Project Settings → Domains
2. Clique em "Add Domain"
3. Digite seu domínio (ex: www.easyprotconsult.com.br)
4. Siga as instruções para apontar o DNS

### Netlify
1. Vá para Site Settings → Domain Management
2. Clique em "Add Custom Domain"
3. Digite seu domínio
4. Siga as instruções para apontar o DNS

### GitHub Pages
1. Vá para Settings → Pages
2. Em "Custom domain", digite seu domínio
3. Siga as instruções para apontar o DNS

---

## 🔧 Editar Informações de Contato

Antes de fazer deploy, edite o arquivo `index.html`:

### Email
Procure por:
```html
<a href="mailto:contato@easyprotconsult.com.br">
```
E altere para seu email.

### WhatsApp
Procure por:
```html
<a href="https://wa.me/5511999999999">
```
E altere o número (formato: 55 + DDD + número sem caracteres especiais)

---

## ✅ Checklist Pré-Deploy

- [ ] Email de contato atualizado
- [ ] Número de WhatsApp atualizado
- [ ] Repositório Git criado
- [ ] Código feito push para GitHub
- [ ] Plataforma de deploy escolhida
- [ ] Deploy realizado com sucesso
- [ ] Site acessível e funcionando
- [ ] Domínio personalizado configurado (opcional)

---

## 🆘 Troubleshooting

### Site não carrega
- Verifique se o arquivo `index.html` está na raiz do repositório
- Aguarde 2-3 minutos após o deploy

### Domínio personalizado não funciona
- Verifique as configurações de DNS
- Aguarde até 24 horas para propagação

### Preciso fazer alterações
1. Edite o arquivo `index.html` localmente
2. Faça commit: `git add . && git commit -m "Update"`
3. Faça push: `git push`
4. O site será atualizado automaticamente em 1-2 minutos

---

## 📊 Próximos Passos (Opcional)

### Adicionar Analytics
Adicione Google Analytics para rastrear visitantes:

1. Acesse [analytics.google.com](https://analytics.google.com)
2. Crie uma nova propriedade
3. Copie o código de rastreamento
4. Cole antes de `</head>` no arquivo `index.html`

### Adicionar Formulário de Contato
Para formulário funcional, use:
- [Formspree](https://formspree.io) - Gratuito
- [Basin](https://usebasin.com) - Gratuito
- [Getform](https://getform.io) - Gratuito

---

**Dúvidas? Consulte a documentação oficial:**
- [Vercel Docs](https://vercel.com/docs)
- [Netlify Docs](https://docs.netlify.com)
- [GitHub Pages Docs](https://pages.github.com)

**Seu site está pronto! 🎉**
