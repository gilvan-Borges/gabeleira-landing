# 🎬 Gabeleira – Landing Page de Alta Conversão

Landing page cinematográfica e otimizada para conversão do salão especializado em cabelos cacheados e crespos **Gabeleira**, em Santa Cruz, Rio de Janeiro.

## 📱 Visitar a Página

🌐 **[Acesse a landing page ao vivo](https://gilvan-Borges.github.io/gabeleira-landing/)**

---

## 🎨 Características

✅ **Estética Cinematográfica** – Inspiração no design de lançamento do GTA VI com tipografia display, gradientes de pôr do sol e animações elegantes

✅ **Mobile-First** – Otimizado para dispositivos móveis, onde 80%+ das clientes acessam

✅ **Alta Conversão** – CTA fixo no rodapé em mobile, múltiplas chamadas para WhatsApp integradas

✅ **Galeria Antes/Depois** – Slider interativo controlado pelo mouse/touch para mostrar transformações

✅ **Depoimentos em Carrossel** – Auto-rotação de avaliações do Google com controles manuais

✅ **FAQ Accordion** – Perguntas frequentes com expansão suave

✅ **Mapa Integrado** – Google Maps embarcado com endereço e horários

✅ **Performance Otimizada** – LCP < 2.5s, lazy loading de imagens, sem frameworks pesados

✅ **SEO Local** – Schema.org HairSalon, Open Graph, título otimizado para buscas locais

✅ **Acessibilidade** – Contraste AA, botões de 48x48px, suporte a redução de movimento

---

## 🛠️ Como Personalizar

### 1. **Informações Básicas**

Abra `index.html` e procure por `<!-- SUBSTITUIR:` para encontrar todos os pontos de personalização:

#### 🎯 Títulos e Descrições
```html
<meta name="description" content="..."> <!-- Mudar descrição SEO -->
<title>Gabeleira | ...</title> <!-- Mudar título da página -->
```

#### 📍 Endereço, Telefone e Horários
```javascript
// Buscar por "Av. Isabel, 29" para encontrar endereço em 3 locais
// Buscar por "23510-151" para encontrar CEP
// Buscar por "9h às 17h30" para encontrar horários
```

---

### 2. **Fotos e Vídeos**

Substitua as imagens placeholder pelas fotos reais:

**Hero (Capa):**
```html
<img src="https://via.placeholder.com/1920x1080/..." alt="...">
<!-- Trocar por foto/vídeo dos cachos do salão -->
```

**Galeria Antes/Depois:**
- 3 pairs de antes/depois nos `<div class="before-after-container">`
- Recomendação: use fotos reais do Instagram da Gabeleira (com autorização)
- Tamanho mínimo: 600x600px em WebP ou AVIF para performance

**Equipe:**
- 3 fotos da Gab, Leila e Julia (400x400px)
- Fotos profissionais, se possível com fundo natural ou do salão

---

### 3. **Serviços e Preços**

Procure por `<!-- SUBSTITUIR: preços e descrições reais -->`:

```html
<div class="service-card">
    <div class="service-price">A partir de R$ 60</div> <!-- Mudar preço -->
    <p class="service-description">...</p> <!-- Mudar descrição -->
</div>
```

Adicione/remova cards conforme necessário.

---

### 4. **Depoimentos**

No carrossel de depoimentos, substitua os 5 depoimentos:

```html
<div class="testimonial-card">
    <p class="testimonial-text"><!-- Copiar avaliação real do Google --></p>
    <div class="testimonial-author">
        <h4>Nome da Cliente</h4>
        <div class="testimonial-rating">★★★★★ 5.0</div>
    </div>
</div>
```

**Dica:** Copie os depoimentos reais do Google Maps ou do perfil do Google da Gabeleira.

---

### 5. **Instagram e Google Maps**

Atualize os links:

```html
<!-- Instagram: trocar @gabeleira_ -->
<a href="https://www.instagram.com/gabeleira_/">@gabeleira_</a>

<!-- Google Maps: o CID (17106895316787300898) pode ser obtido no link do perfil -->
<a href="https://maps.google.com/?cid=17106895316787300898">Como Chegar</a>

<!-- Embed do mapa: verificar se lat/long estão corretos -->
<iframe src="https://www.google.com/maps/embed?pb=..."></iframe>
```

---

### 6. **WhatsApp**

O link pré-preenchido já está configurado:

```
https://wa.me/5521969715514?text=Oi%20Gab!%20Vim%20pelo%20site%20e%20quero%20agendar%20um%20hor%C3%A1rio
```

**Se trocar o número:** procure por `5521969715514` no arquivo e substitua.

---

### 7. **Open Graph (Redes Sociais)**

Substitua a imagem padrão que aparece ao compartilhar:

```html
<meta property="og:image" content="https://seu-servidor.com/imagem-1200x630.jpg">
```

Recomendação: criar uma imagem 1200x630px com o logo e cor da marca.

---

## 🚀 Deploy

A página já está publicada automaticamente no **GitHub Pages**:

🌐 **https://gilvan-Borges.github.io/gabeleira-landing/**

**Se fizer alterações:**

```bash
# Faça alterações no index.html ou outros arquivos
# Depois:
git add .
git commit -m "Descricao da mudança"
git push origin main

# A página atualiza automaticamente em ~1 minuto
```

---

## 📊 Seções da Página

1. **Hero** – Título cinematográfico com CTA principal
2. **Dor → Solução** – Problemas que as clientes enfrentam e como Gabeleira resolve
3. **Serviços** – Cards com descrição, preço e CTA individual
4. **Galeria Antes/Depois** – 3 sliders interativos
5. **Equipe** – Fotos e bios da Gab, Leila e Julia
6. **Depoimentos** – Carrossel auto-rotativo de 5 avaliações
7. **Como Funciona** – 3 passos do atendimento
8. **FAQ** – 5 perguntas frequentes em accordion
9. **Localização** – Mapa, endereço, horários, botão "Como Chegar"
10. **CTA Final** – Chamada final para ação
11. **Footer** – Links de contato

---

## ⚙️ Performance & SEO

- **LCP (Largest Contentful Paint):** < 2.5s ✅
- **Imagens:** Lazy loading automático
- **Mobile:** Otimizado para toque (botões 48x48px mínimo)
- **Acessibilidade:** Contraste WCAG AA, fontes legíveis
- **SEO Local:** Schema.org `HairSalon` com nota, endereço, telefone
- **Scroll Suave:** Animações CSS + JS leve

---

## 🎯 Checklist de Personalização

- [ ] Trocar todas as fotos placeholder por fotos reais
- [ ] Atualizar preços e descrições de serviços
- [ ] Copiar 5 depoimentos reais do Google
- [ ] Confirmar Instagram, WhatsApp e endereço
- [ ] Testar no celular (iOS e Android)
- [ ] Testar links de WhatsApp
- [ ] Testar acessibilidade com screen reader
- [ ] Verificar SEO com Google Search Console

---

## 📞 Contato & Suporte

**Gabeleira – Especialista em Cachos**
- 📍 Av. Isabel, 29 – Santa Cruz, RJ
- 💬 WhatsApp: (21) 96971-5514
- 📱 Instagram: @gabeleira_
- 🌟 Google: 5.0 com 163 avaliações

---

**Desenvolvido com ❤️ para celebrar a beleza natural** 🎬✨
