# 📚 GUIA COMPLETO: Como Publicar Seu Site Gratuitamente com Domínio Próprio

## 🎯 Resumo do Processo

1. Criar conta no GitHub (grátis)
2. Enviar seus arquivos para o GitHub
3. Escolher plataforma de hospedagem (Vercel ou Netlify)
4. Conectar seu domínio
5. Pronto! Site online

**Tempo total: ~30 minutos**

---

## 📋 PASSO 1: Preparar os Arquivos

Você tem 3 arquivos:
- `index.html` (seu site)
- `logo.png` (seu logo)
- `README.md` (informações)

✅ Já estão prontos! Você só precisa fazer upload deles.

---

## 🔐 PASSO 2: Criar Conta no GitHub (Grátis)

### O que é GitHub?
É um serviço gratuito que armazena seus arquivos na nuvem. Pense como um "Google Drive para código".

### Como criar:

1. Acesse: **https://github.com/signup**

2. Preencha o formulário:
   - **Username**: Seu nome de usuário (ex: ana-feitosa)
   - **Email**: Seu email
   - **Password**: Uma senha segura
   - **Verificação**: Confirme que você é humano

3. Clique em **"Create account"**

4. Verifique seu email (GitHub vai enviar um link de confirmação)

5. Pronto! Sua conta está criada ✅

---

## 📤 PASSO 3: Enviar Arquivos para o GitHub

### Opção A: Usando o Site (Mais Fácil - Recomendado)

1. Acesse: **https://github.com/new**

2. Preencha:
   - **Repository name**: `easyprotconsult-website`
   - **Description**: "Site institucional da EasyProt Consult"
   - Deixe marcado: **"Public"**

3. Clique em **"Create repository"**

4. Você verá uma página com instruções. Procure por:
   **"...or upload an existing file"**

5. Clique em **"uploading an existing file"**

6. Arraste os arquivos ou clique para selecionar:
   - `index.html`
   - `logo.png`
   - `README.md`

7. Clique em **"Commit changes"**

8. Pronto! Seus arquivos estão no GitHub ✅

### Opção B: Usando Git (Para Quem Quer Aprender)

Se quiser usar linha de comando:

```bash
# 1. Instale Git: https://git-scm.com/download

# 2. Abra o terminal/cmd na pasta do site

# 3. Execute estes comandos:
git init
git add .
git commit -m "Primeiro envio do site"
git branch -M main
git remote add origin https://github.com/seu-usuario/easyprotconsult-website.git
git push -u origin main
```

---

## 🚀 PASSO 4: Escolher Plataforma de Hospedagem

Você tem 2 opções gratuitas:

### Opção 1: VERCEL (Recomendado - Mais Rápido)

**Vantagens:**
- Muito rápido
- Deploy automático
- Suporte a domínio próprio

**Como fazer:**

1. Acesse: **https://vercel.com**

2. Clique em **"Sign Up"** → **"Continue with GitHub"**

3. Autorize o Vercel a acessar sua conta GitHub

4. Clique em **"New Project"**

5. Procure seu repositório: **"easyprotconsult-website"**

6. Clique em **"Import"**

7. Deixe as configurações padrão

8. Clique em **"Deploy"**

9. Aguarde ~1 minuto

10. Pronto! Seu site está online em uma URL tipo:
    `https://easyprotconsult-website.vercel.app`

### Opção 2: NETLIFY

**Vantagens:**
- Também muito bom
- Interface amigável
- Suporte a domínio próprio

**Como fazer:**

1. Acesse: **https://netlify.com**

2. Clique em **"Sign up"** → **"GitHub"**

3. Autorize o Netlify

4. Clique em **"New site from Git"**

5. Selecione **"GitHub"**

6. Procure seu repositório

7. Clique em **"Deploy site"**

8. Aguarde ~2 minutos

9. Seu site estará em uma URL tipo:
    `https://seu-site-aleatorio.netlify.app`

---

## 🌐 PASSO 5: Conectar Seu Domínio Próprio

Você tem um domínio? Ótimo! Vamos conectar.

### Se você já tem um domínio registrado:

#### No Vercel:

1. Vá para seu projeto no Vercel

2. Clique em **"Settings"** → **"Domains"**

3. Clique em **"Add Domain"**

4. Digite seu domínio (ex: `www.easyprotconsult.com.br`)

5. Clique em **"Add"**

6. Vercel vai mostrar as configurações de DNS

7. Vá para onde você registrou o domínio (GoDaddy, Registro.br, etc.)

8. Procure por **"DNS"** ou **"Nameservers"**

9. Copie os valores que o Vercel mostrou

10. Cole nos DNS do seu domínio

11. Aguarde 24 horas para propagar

12. Pronto! Seu domínio está conectado ✅

#### No Netlify:

1. Vá para seu site no Netlify

2. Clique em **"Site settings"** → **"Domain management"**

3. Clique em **"Add custom domain"**

4. Digite seu domínio

5. Siga as mesmas instruções do Vercel (passos 7-12)

### Se você NÃO tem um domínio ainda:

Você pode comprar em:
- **Registro.br** (domínios .com.br)
- **GoDaddy** (domínios internacionais)
- **Namecheap** (domínios internacionais)
- **Hostinger** (domínios internacionais)

**Custo:** ~R$ 40-100 por ano (dependendo da extensão)

---

## ✅ CHECKLIST FINAL

- [ ] Conta GitHub criada
- [ ] Arquivos enviados para GitHub
- [ ] Conta Vercel/Netlify criada
- [ ] Site publicado (URL temporária)
- [ ] Domínio registrado (se aplicável)
- [ ] Domínio conectado ao site
- [ ] Site acessível pelo seu domínio

---

## 🆘 TROUBLESHOOTING

### "Meu site não carrega"
- Aguarde 2-3 minutos após o deploy
- Limpe o cache do navegador (Ctrl+Shift+Delete)
- Recarregue a página (Ctrl+F5)

### "Domínio não funciona"
- Verifique se os DNS foram alterados corretamente
- Aguarde até 24 horas para propagação
- Teste em: https://dnschecker.org

### "Preciso fazer alterações no site"
1. Edite o arquivo `index.html` no GitHub
2. Ou baixe, edite localmente e faça upload novamente
3. O site será atualizado automaticamente em 1-2 minutos

### "Como editar o site depois?"
Você pode editar de 3 formas:

**Forma 1: Direto no GitHub (Mais Fácil)**
1. Vá para seu repositório
2. Clique no arquivo `index.html`
3. Clique no ícone de lápis
4. Faça as alterações
5. Clique em "Commit changes"

**Forma 2: Baixar, editar e reenviar**
1. Baixe o arquivo
2. Edite com um editor de texto
3. Faça upload novamente no GitHub

**Forma 3: Usar um editor online**
- CodePen, JSFiddle, Replit

---

## 📞 SUPORTE

Se tiver dúvidas:

- **GitHub Help**: https://docs.github.com
- **Vercel Docs**: https://vercel.com/docs
- **Netlify Docs**: https://docs.netlify.com

---

## 🎉 PARABÉNS!

Seu site está online e acessível para o mundo inteiro!

**Próximos passos (opcional):**
- Adicionar Google Analytics para rastrear visitantes
- Adicionar formulário de contato
- Otimizar para SEO
- Adicionar certificado SSL (geralmente automático)

---

**Dúvidas? Me avise! Estou aqui para ajudar! 😊**
