![Build AI Landing Page](https://img.shields.io/badge/Status-Active-success)
![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)

# 🚀 BuildAI - Professional Landing Page

Uma landing page profissional e moderna com design inspirado no visual do Copilot Plans. Desenvolvida com HTML5, CSS3 e JavaScript vanilla, apresentando gradientes roxo/azul, efeitos 3D e animações suaves.

## ✨ Características Principais

- 🎨 **Design Moderno**: Gradientes vibrantes em roxo, azul e rosa
- 📱 **Totalmente Responsivo**: Adaptável para todos os tamanhos de tela
- ⚡ **Performance Otimizada**: Animações suaves e rápidas
- 🎯 **Sections Completas**:
  - Hero Section com efeitos parallax
  - Features (6 cards com hover effects)
  - Capabilities (6 items numerados)
  - Pricing (3 planos com card destacado)
  - Plans Comparison (tabela detalhada)
  - Stats (4 estatísticas animadas)
  - CTA Final
  - Footer completo

## 🎨 Paleta de Cores

```
Primária: #7c3aed (Roxo)
Secundária: #0ea5e9 (Azul Ciano)
Accent: #ec4899 (Rosa)
Fundo Dark: #0f0a1a
Fundo Mais Escuro: #0a0612
```

## 📦 Estrutura do Projeto

```
landing-page-copilot/
├── index.html          # Estrutura HTML completa
├── styles.css          # Estilos e animações
├── script.js          # Interatividade e efeitos
└── README.md          # Este arquivo
```

## 🚀 Como Usar

### Instalação Local

1. Clone o repositório:
```bash
git clone https://github.com/Aibuilderz/landing-page-copilot.git
cd landing-page-copilot
```

2. Abra o arquivo `index.html` no navegador:
```bash
# Opção 1: Abrir diretamente
open index.html

# Opção 2: Usar um servidor local (Python)
python -m http.server 8000
# Então visite: http://localhost:8000
```

## 💻 Deployment

### GitHub Pages
1. Vá para Settings > Pages
2. Selecione `main` como source
3. Clique em Save
4. Seu site estará disponível em: `https://username.github.io/landing-page-copilot`

### Netlify
```bash
npm install -g netlify-cli
netlify deploy --prod
```

### Vercel
```bash
vercel --prod
```

## 🎯 Sections Detalhadas

### Hero Section
- Título com gradient animado
- Subtitle descritivo
- Dois botões de CTA (primário e secundário)
- Efeitos de orbs flutuantes
- Starfield animado de fundo

### Features (6 Cards)
- Ícones emojis customizáveis
- Hover effect com elevação
- Border gradient ao passar o mouse
- Descrições claras e concisas

### Capabilities (6 Items)
- Numeração elegante (01-06)
- Gradient backgrounds
- Hover effects interativos
- Layout responsivo

### Pricing
- 3 planos: Starter, Professional (destacado), Enterprise
- Preços em Real (R$)
- Listas de features com checkmarks
- Botões específicos para cada plano
- Badge "POPULAR" no plano destacado

### Plans Comparison
- Tabela detalhada e responsiva
- 8 features comparadas
- Hover effects nas linhas
- Scroll horizontal em mobile

### Stats
- 4 estatísticas principais
- Contadores animados ao scroll
- Cards com gradient backgrounds
- Efeitos hover suaves

### Footer
- 4 colunas de navegação
- Links sociais
- Copyright

## 🎬 Animações e Efeitos

- ✨ Fade-in ao carregar
- 🔄 Float dos orbs de gradiente
- 💫 Glow animado no texto gradiente
- 🎯 Parallax com mouse movement
- 📊 Contadores animados nas estatísticas
- 🎨 Hover effects em cards e botões
- 🌊 Ripple effect em cliques de botões

## 🔧 Customização

### Alterar Cores
Edite as variáveis CSS em `styles.css`:
```css
:root {
    --primary-color: #7c3aed;
    --secondary-color: #0ea5e9;
    --accent-color: #ec4899;
    /* ... */
}
```

### Ajustar Conteúdo
- Edite o `index.html` para mudar textos, preços e features
- Atualize o `logo-text` no navbar
- Modifique as URLs dos botões

### Adicionar Seções
Copie a estrutura de qualquer section existente e customizae a classe CSS correspondente.

## 📱 Responsividade

- **Desktop**: Experiência completa com todos os efeitos
- **Tablet (768px)**: Layout ajustado, navegação otimizada
- **Mobile (480px)**: Stack vertical, touch-friendly, sem excess effects

## ⚡ Performance

- Animações CSS for máxima performance
- Intersection Observer para lazy loading de animations
- Backdrop filters otimizados
- Minimal JavaScript para interatividade

## 🌐 Compatibilidade

- ✅ Chrome/Edge (Recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Licença

MIT License - Sinta-se livre para usar em seus projetos

## 👨‍💻 Autor

Desenvolvido por [Aibuilderz](https://github.com/Aibuilderz)

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se livre para:
1. Fork o projeto
2. Criar uma branch com sua feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/NovaFeature`)
5. Abrir um Pull Request

## 💡 Melhorias Futuras

- [ ] Dark/Light mode toggle
- [ ] Integração com CMS
- [ ] Multi-language support
- [ ] Blog section
- [ ] Testimonials carousel
- [ ] Contact form com validação
- [ ] Newsletter subscription
- [ ] Live chat integration

## 📞 Suporte

Tem dúvidas? Abra uma issue no repositório ou entre em contato!

---

**Divirta-se customizando! 🎉**