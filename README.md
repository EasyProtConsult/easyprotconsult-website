# EasyProt Consult - Website Institucional

Site institucional elegante para apresentação de serviços de consultoria em comércio exterior.

## Características

- ✨ Design elegante e profissional
- 📱 Totalmente responsivo (mobile, tablet, desktop)
- ⚡ Carregamento rápido (site estático puro)
- 🎨 Paleta de cores baseada na identidade da marca
- 🔍 Otimizado para SEO
- 📊 Seções: Hero, Sobre, Serviços, Metodologia, Benefícios, Contato

## Estrutura

```
easyprotconsult-website/
├── index.html          # Página principal (HTML + CSS inline)
├── README.md           # Este arquivo
└── .gitignore         # Arquivo Git
```

## Como Usar Localmente

1. Abra o arquivo `index.html` diretamente no navegador
2. Ou use um servidor local:
   ```bash
   python -m http.server 8000
   # Acesse http://localhost:8000
   ```

## Deploy em Plataformas Gratuitas

### Vercel (Recomendado)

1. Acesse [vercel.com](https://vercel.com)
2. Clique em "New Project"
3. Selecione seu repositório Git
4. Clique em "Deploy"
5. Seu site estará online em poucos segundos

### Netlify

1. Acesse [netlify.com](https://netlify.com)
2. Clique em "New site from Git"
3. Selecione seu repositório
4. Clique em "Deploy site"
5. Seu site estará disponível em um URL Netlify

### GitHub Pages

1. Faça push do código para um repositório GitHub
2. Vá para Settings → Pages
3. Selecione "Deploy from a branch"
4. Escolha a branch `main`
5. Seu site estará em `https://seu-usuario.github.io/seu-repositorio`

## Personalização

### Alterar Cores

Edite as variáveis CSS no início do arquivo `index.html`:

```css
:root {
    --primary-dark: #003D7A;
    --primary-light: #005988;
    --accent: #21B2C9;
    --accent-light: #3b8ba5;
    --white: #FFFFFF;
    --text-light: #F0F4F8;
    --bg-dark: #0A1628;
}
```

### Alterar Informações de Contato

Procure pela seção "Contact Section" e atualize:
- Email: `contato@easyprotconsult.com.br`
- WhatsApp: `https://wa.me/5511999999999`

### Adicionar Mais Conteúdo

O site é um arquivo HTML único. Você pode:
1. Duplicar cards de serviço
2. Adicionar novas seções
3. Modificar textos conforme necessário

## Performance

- Tamanho: ~15KB (HTML + CSS inline)
- Tempo de carregamento: < 1 segundo
- Sem dependências externas
- Sem JavaScript necessário

## Compatibilidade

- Chrome, Firefox, Safari, Edge (versões recentes)
- Mobile: iOS 12+, Android 5+
- Sem suporte para IE11

## Próximos Passos

1. Personalizar emails e telefone de contato
2. Adicionar logo em SVG (se desejar)
3. Configurar domínio personalizado
4. Adicionar Google Analytics para rastrear visitantes
5. Implementar formulário de contato (opcional)

## Suporte

Para dúvidas sobre deploy ou personalização, consulte a documentação das plataformas:
- [Vercel Docs](https://vercel.com/docs)
- [Netlify Docs](https://docs.netlify.com)
- [GitHub Pages Docs](https://pages.github.com)

---

**Desenvolvido com ❤️ para EasyProt Consult**
