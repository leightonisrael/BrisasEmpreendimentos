# Brisas Empreendimentos - Site Institucional

Website profissional da **Brisas Empreendimentos**, construtora com mais de 17 anos de atuação no mercado imobiliário de Natal/RN.

## 📁 Estrutura do Projeto

```
BrisasEmpreendimentos/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Estilos CSS
├── js/
│   └── main.js         # JavaScript
├── images/             # Imagens do site
│   └── README.md       # Instruções de imagens
└── README.md           # Este arquivo
```

## 🖼️ Imagens Necessárias

Para personalizar o site com suas imagens, adicione na pasta `images/`:

### Obrigatórias:
| Arquivo | Descrição | Tamanho Recomendado |
|---------|-----------|---------------------|
| `logo.png` | Logo da empresa | 200x80 px |
| `logo-white.png` | Logo branca (para footer) | 200x80 px |
| `hero-1.jpg` | Imagem principal do banner | 1920x1080 px |
| `hero-2.jpg` | Segunda imagem do banner | 1920x1080 px |
| `hero-3.jpg` | Terceira imagem do banner | 1920x1080 px |

### Seção Sobre:
| Arquivo | Descrição | Tamanho Recomendado |
|---------|-----------|---------------------|
| `sobre-1.jpg` | Imagem principal sobre | 800x600 px |
| `sobre-2.jpg` | Imagem secundária | 400x500 px |

### Sustentabilidade:
| Arquivo | Descrição | Tamanho Recomendado |
|---------|-----------|---------------------|
| `sustentabilidade.jpg` | Construção sustentável | 800x700 px |

### Empreendimentos:
| Arquivo | Descrição | Tamanho Recomendado |
|---------|-----------|---------------------|
| `empreendimento-1.jpg` | Residencial 1 | 600x400 px |
| `empreendimento-2.jpg` | Residencial 2 | 600x400 px |
| `empreendimento-3.jpg` | Residencial 3 | 600x400 px |
| `empreendimento-4.jpg` | Residencial 4 | 600x400 px |

### Galeria:
| Arquivo | Descrição | Tamanho Recomendado |
|---------|-----------|---------------------|
| `galeria-1.jpg` | Foto de obra 1 | 1200x800 px |
| `galeria-2.jpg` | Foto de obra 2 | 600x400 px |
| `galeria-3.jpg` | Foto de obra 3 | 600x400 px |
| `galeria-4.jpg` | Foto de obra 4 | 600x400 px |
| `galeria-5.jpg` | Foto de obra 5 | 600x400 px |
| `galeria-6.jpg` | Foto de obra 6 | 1200x800 px |

### CTA:
| Arquivo | Descrição | Tamanho Recomendado |
|---------|-----------|---------------------|
| `cta-bg.jpg` | Background do CTA | 1920x600 px |

> **Nota:** O site está configurado com imagens de fallback do Unsplash. Quando você adicionar suas próprias imagens, elas serão exibidas automaticamente.

## 🚀 Como Usar

1. **Abrir o site:**
   - Basta abrir o arquivo `index.html` no navegador
   - Ou usar um servidor local (recomendado)

2. **Usar servidor local (recomendado):**
   ```bash
   # Com Python 3
   python -m http.server 8000

   # Com Node.js (npx)
   npx serve
   
   # Com Live Server (VS Code)
   # Instalar extensão Live Server e clicar com botão direito em index.html
   ```

3. **Personalizar informações:**
   - Edite o arquivo `index.html` para alterar textos, endereços, telefones, etc.
   - Atualize o link do WhatsApp com seu número real

## 📱 Funcionalidades

- ✅ Design responsivo (mobile, tablet, desktop)
- ✅ Menu mobile hamburger
- ✅ Slider de imagens no hero
- ✅ Animações de scroll (AOS)
- ✅ Contagem animada de estatísticas
- ✅ Filtro de empreendimentos
- ✅ Galeria com lightbox
- ✅ Formulário de contato
- ✅ Máscara de telefone
- ✅ Botão flutuante do WhatsApp
- ✅ Botão "voltar ao topo"
- ✅ Imagens com fallback automático

## 🎨 Cores da Marca

```css
/* Cores principais */
--primary-color: #1a5f7a;     /* Azul corporativo */
--secondary-color: #2e7d32;   /* Verde sustentabilidade */
--accent-color: #f9a825;      /* Amarelo destaque */
```

## 📞 Personalizações Importantes

### WhatsApp
Altere o número do WhatsApp no arquivo `index.html`:
```html
<!-- Procure por estas linhas e altere o número -->
<a href="https://wa.me/5584XXXXXXXXX" ...
```

### Informações de Contato
Edite a seção de contato com os dados reais:
- Endereço completo
- Telefone
- E-mail
- Horário de funcionamento

### Empreendimentos
Personalize os cards de empreendimentos com informações reais dos seus projetos.

## 🔧 Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox, Grid, Variables)
- JavaScript (ES6+)
- [AOS - Animate On Scroll](https://michalsnik.github.io/aos/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/) (Montserrat, Open Sans)

## 📄 Licença

Este projeto foi desenvolvido para uso exclusivo da **Brisas Empreendimentos**.

---

Desenvolvido com ❤️ em Natal/RN
