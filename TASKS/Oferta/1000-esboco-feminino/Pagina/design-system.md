# Design System - Pagina de Vendas: 1000 Esbocos Feminino

**Routed by:** Design Chief
**Specialist:** @brad-frost (Design Systems)
**Visual Direction:** Women Ministry / Elegant Empowerment
**Date:** 2026-02-25

---

## 1. Paleta de Cores

### Cores Primarias

| Token | Hex | Uso | Justificativa |
|-------|-----|-----|---------------|
| `--color-gold` | `#C9A96E` | Acento principal, badges, destaques | Espiritualidade, valor, nobreza. Remete a uncao e ao sagrado sem ser religioso demais |
| `--color-mauve` | `#B87D82` | Acento secundario, bordas, detalhes | Feminino maduro, nao infantil. Rosa envelhecido que transmite sofisticacao |
| `--color-charcoal` | `#2C2C2C` | Texto principal, titulos | Seriedade, legibilidade, contraste forte. Evita preto puro que e agressivo |

### Cores de CTA

| Token | Hex | Uso | Justificativa |
|-------|-----|-----|---------------|
| `--cta-bg` | `#D4A017` | Fundo do botao CTA | Dourado vibrante que chama atencao sem ser agressivo. Remete a "valor" e "oportunidade" |
| `--cta-text` | `#1A1A1A` | Texto do botao CTA | Texto escuro sobre dourado para maximo contraste e legibilidade |
| `--cta-hover` | `#E0B432` | Hover do botao CTA | Versao mais clara/luminosa do dourado para feedback visual |

### Cores de Fundo

| Token | Hex | Uso | Justificativa |
|-------|-----|-----|---------------|
| `--bg-white` | `#FAF8F5` | Fundo principal da pagina | Off-white quente. Pureza e clareza sem o esterilizado do branco puro |
| `--bg-warm` | `#F5F0EA` | Secoes alternadas (depoimentos, FAQ) | Bege rosado sutil para criar ritmo visual entre secoes |
| `--bg-dark` | `#2C2C2C` | Secoes de destaque (CTA, preco) | Inversao dramatica para chamar atencao nas secoes criticas |
| `--bg-gold-soft` | `#FBF6ED` | Secao hero, secao de garantia | Dourado diluido que cria aura de "especial" sem pesar |

### Cores de Texto

| Token | Hex | Uso |
|-------|-----|-----|
| `--text-primary` | `#2C2C2C` | Corpo de texto, paragrafos |
| `--text-secondary` | `#5A5A5A` | Texto de apoio, legendas, meta |
| `--text-muted` | `#8A8A8A` | Placeholders, texto terciario |
| `--text-on-dark` | `#FAF8F5` | Texto sobre fundos escuros |
| `--text-gold` | `#C9A96E` | Destaques sobre fundo escuro |
| `--text-accent` | `#B87D82` | Citacoes, destaques femininos |

### Cores de Estado

| Token | Hex | Uso |
|-------|-----|-----|
| `--color-success` | `#6B8F71` | Checkmarks, confirmacoes |
| `--color-strikethrough` | `#CC4444` | Preco original riscado |

---

## 2. Tipografia

### Font Families

| Nivel | Font | Fallback | Uso |
|-------|------|----------|-----|
| Display/Headlines | `Playfair Display` | `Georgia, 'Times New Roman', serif` | H1, H2, H3, citacoes em destaque |
| Body | `Lato` | `'Helvetica Neue', Arial, sans-serif` | Paragrafos, listas, botoes, UI |
| Depoimentos | `Playfair Display Italic` | `Georgia, serif` | Textos de depoimento (autenticidade) |

### Escala Tipografica - Desktop (1280px+)

| Elemento | Font | Size | Weight | Line-Height | Letter-Spacing |
|----------|------|------|--------|-------------|----------------|
| H1 (Hero) | Playfair Display | 48px / 3rem | 700 | 1.2 | -0.02em |
| H2 (Secao) | Playfair Display | 36px / 2.25rem | 700 | 1.25 | -0.01em |
| H3 (Sub-secao) | Playfair Display | 28px / 1.75rem | 600 | 1.3 | 0 |
| H4 (Card title) | Lato | 22px / 1.375rem | 700 | 1.35 | 0 |
| Body Large | Lato | 20px / 1.25rem | 400 | 1.7 | 0.01em |
| Body | Lato | 18px / 1.125rem | 400 | 1.7 | 0.01em |
| Body Small | Lato | 16px / 1rem | 400 | 1.6 | 0 |
| Caption | Lato | 14px / 0.875rem | 400 | 1.5 | 0.02em |
| CTA Button | Lato | 18px / 1.125rem | 700 | 1 | 0.05em |
| Price Large | Playfair Display | 64px / 4rem | 700 | 1.1 | -0.02em |
| Price Strike | Lato | 24px / 1.5rem | 400 | 1 | 0 |

### Escala Tipografica - Mobile (375px)

| Elemento | Size | Line-Height |
|----------|------|-------------|
| H1 (Hero) | 32px / 2rem | 1.2 |
| H2 (Secao) | 26px / 1.625rem | 1.25 |
| H3 (Sub-secao) | 22px / 1.375rem | 1.3 |
| H4 (Card title) | 18px / 1.125rem | 1.35 |
| Body Large | 18px / 1.125rem | 1.7 |
| Body | 16px / 1rem | 1.7 |
| Body Small | 14px / 0.875rem | 1.6 |
| CTA Button | 16px / 1rem | 1 |
| Price Large | 48px / 3rem | 1.1 |

---

## 3. Espacamentos

### Grid System

| Propriedade | Desktop | Tablet (768px) | Mobile (375px) |
|-------------|---------|----------------|----------------|
| Max-width | 1080px | 100% | 100% |
| Colunas | 12 | 8 | 4 |
| Gutter | 24px | 20px | 16px |
| Margem lateral | auto (centrado) | 32px | 20px |

### Spacing Scale (base 8px)

| Token | Valor | Uso Tipico |
|-------|-------|-----------|
| `--space-1` | 4px | Micro-espacos (entre icone e label) |
| `--space-2` | 8px | Padding interno minimo, gap entre badges |
| `--space-3` | 16px | Padding interno padrao de cards |
| `--space-4` | 24px | Gap entre items de lista, padding de secao mobile |
| `--space-5` | 32px | Margem entre blocos de conteudo |
| `--space-6` | 48px | Padding vertical de secoes (mobile) |
| `--space-7` | 64px | Padding vertical de secoes (desktop) |
| `--space-8` | 96px | Separacao entre secoes principais (desktop) |
| `--space-9` | 128px | Espacamento hero / secoes de destaque |

### Secoes - Padding Vertical

| Tipo de Secao | Desktop | Mobile |
|---------------|---------|--------|
| Hero | 96px top / 80px bottom | 64px top / 48px bottom |
| Secao padrao | 80px | 48px |
| Secao destaque (escura) | 96px | 64px |
| Secao compacta (FAQ item) | 24px | 16px |

---

## 4. Componentes

### 4.1 Botao CTA

**Estado Normal:**
```
Background: #D4A017 (--cta-bg)
Color: #1A1A1A (--cta-text)
Font: Lato 18px/700, uppercase
Letter-spacing: 0.05em
Padding: 20px 48px
Border-radius: 10px
Border: none
Box-shadow: 0 4px 15px rgba(212, 160, 23, 0.3)
Cursor: pointer
Transition: all 0.3s ease
Max-width: 100% (mobile)
```

**Estado Hover:**
```
Background: #E0B432 (--cta-hover)
Box-shadow: 0 6px 20px rgba(212, 160, 23, 0.45)
Transform: translateY(-2px)
```

**Estado Active:**
```
Background: #BF9215
Transform: translateY(0)
Box-shadow: 0 2px 8px rgba(212, 160, 23, 0.3)
```

**Variante Secundaria (sobre fundo escuro):**
```
Background: #FAF8F5
Color: #2C2C2C
Box-shadow: 0 4px 15px rgba(250, 248, 245, 0.2)
```

### 4.2 Card de Depoimento

```
Background: #FFFFFF
Border-radius: 12px
Padding: 32px
Border-left: 4px solid #C9A96E
Box-shadow: 0 2px 12px rgba(0, 0, 0, 0.06)
Margin-bottom: 24px

Avatar:
  Width/Height: 56px
  Border-radius: 50%
  Border: 3px solid #C9A96E
  Object-fit: cover

Quote Icon:
  Font: Playfair Display
  Size: 48px
  Color: #C9A96E
  Opacity: 0.3
  Position: absolute, top -10px, left 24px

Name:
  Font: Lato 16px/700
  Color: #2C2C2C

Meta (idade, cidade):
  Font: Lato 14px/400
  Color: #8A8A8A

Text:
  Font: Playfair Display Italic 17px/400
  Color: #5A5A5A
  Line-height: 1.7
```

### 4.3 Card de Bonus

```
Background: #FFFFFF
Border-radius: 12px
Padding: 28px
Border: 1px solid rgba(201, 169, 110, 0.2)
Box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04)
Transition: transform 0.3s, box-shadow 0.3s

Hover:
  Transform: translateY(-4px)
  Box-shadow: 0 8px 24px rgba(0, 0, 0, 0.08)
  Border-color: #C9A96E

Numero Badge:
  Background: #C9A96E
  Color: #FFFFFF
  Font: Lato 14px/700
  Width/Height: 32px
  Border-radius: 50%
  Display: flex, center

Title:
  Font: Lato 20px/700
  Color: #2C2C2C
  Margin-top: 12px

Valor:
  Font: Lato 14px/400
  Color: #B87D82
  Style: "Valor: R$XX"

Description:
  Font: Lato 16px/400
  Color: #5A5A5A
  Line-height: 1.6
```

### 4.4 Badges/Selos

**Selo de Garantia:**
```
Width: 120px (desktop) / 96px (mobile)
Shape: Circular com borda dourada
Border: 3px solid #C9A96E
Background: #FAF8F5
Text center: "7 DIAS"
Sub-text: "GARANTIA"
Font: Lato Bold
Shadow: 0 4px 12px rgba(201, 169, 110, 0.2)
```

**Selos de Seguranca (inline, horizontal):**
```
Display: flex, gap 16px, center
Each:
  Font: Lato 13px/600
  Color: #5A5A5A
  Icon: 16px, color #6B8F71
  Items: "Compra Segura" | "Acesso Imediato" | "7 Dias Garantia" | "Hotmart"
```

**Badge de Destaque (ex: "2000+ Esbocos"):**
```
Background: #C9A96E
Color: #FFFFFF
Font: Lato 13px/700, uppercase
Padding: 6px 16px
Border-radius: 20px
Letter-spacing: 0.05em
```

### 4.5 Separadores de Secao

**Separador Ornamental:**
```
Width: 80px
Height: 2px
Background: linear-gradient(to right, transparent, #C9A96E, transparent)
Margin: 0 auto
```

**Separador de Secao Completo:**
```
Transicao de cor de fundo entre secoes (sem linha visivel)
Ou: border-top 1px solid rgba(201, 169, 110, 0.15)
```

### 4.6 Value Stack Table

```
Width: 100%, max-width 680px
Border-collapse: separate
Border-spacing: 0

Row:
  Padding: 16px 20px
  Border-bottom: 1px solid rgba(201, 169, 110, 0.1)
  Font: Lato 16px

Row (alternado):
  Background: rgba(201, 169, 110, 0.04)

Item name:
  Color: #2C2C2C
  Font-weight: 400

Valor column:
  Color: #B87D82
  Font-weight: 600
  Text-align: right

Total row:
  Background: #2C2C2C
  Color: #FAF8F5
  Font: Lato 18px/700
  Border-radius: 0 0 8px 8px
```

### 4.7 FAQ Accordion Item

```
Border-bottom: 1px solid rgba(201, 169, 110, 0.15)
Padding: 24px 0

Question:
  Font: Lato 18px/700
  Color: #2C2C2C
  Cursor: pointer
  Padding-right: 32px (espaco para icone)

Answer:
  Font: Lato 16px/400
  Color: #5A5A5A
  Line-height: 1.7
  Margin-top: 12px
  Padding-left: 0

Toggle icon:
  Right-aligned, color #C9A96E
  Transition: transform 0.3s
```

### 4.8 Pain Point Item

```
Padding: 20px 0
Border-left: 3px solid #B87D82 (ou transparente com icone)

Texto negrito (abertura):
  Font: Lato 18px/700
  Color: #2C2C2C

Texto corpo:
  Font: Lato 16px/400
  Color: #5A5A5A
  Line-height: 1.7

Alternativa: icone de X vermelho ou checkmark ao lado
```

---

## 5. Imagery Direction

### Estilo Fotografico

**Abordagem:** Fotografia real de mulheres reais (nao stock generico). Se stock for necessario, priorizar:
- Mulheres negras e pardas (publico brasileiro evangelico)
- Idades 30-55 anos
- Expressoes de confianca, alegria, serenidade
- Contextos: leitura da Biblia, ministracaob, oracao, estudo
- Iluminacao quente, natural
- EVITAR: fotos muito "americanas", loiras, ambientes frios/corporativos

### Imagens Necessarias

| Imagem | Descricao | Localizacao |
|--------|-----------|-------------|
| Hero Background | Mulher com Biblia aberta, luz quente lateral, expressao confiante. Overlay escuro sutil para legibilidade | Secao 1 |
| Mockup do Produto | Telas de celular + tablet mostrando interface dos esbocos. Estilo "flat lay" digital | Secao 6 |
| Foto da Autora | Elena Martin, foto profissional, sorriso acolhedor, fundo neutro ou estudio. Iluminacao quente | Secao 7 |
| Avatares Depoimentos | 5 fotos de mulheres diversas (placeholder circular, 56px) | Secao 11 |
| Icone Garantia | Selo/shield com numero 7 | Secao 13 |
| Fundo CTA Final | Textura sutil dourada ou imagem com overlay | Secao 16 |

### Icones

**Biblioteca sugerida:** Font Awesome 6 (CDN gratuito) ou Phosphor Icons

**Estilo:** Line icons (outline), peso regular, cor `#C9A96E` ou `#5A5A5A`

**Icones necessarios:**
- Checkmark (beneficios, listas)
- Livro/Biblia (produto)
- Coracao (empatia, depoimentos)
- Escudo (garantia, seguranca)
- Relogio (tempo/acesso imediato)
- Estrela (bonus)
- Usuarios/Grupo (comunidade)
- Cadeado (compra segura)
- Seta para baixo (scroll cue)
- Aspas (depoimentos)
- WhatsApp (bonus grupo)
- Celular (acesso mobile)

---

## 6. Efeitos e Animacoes (CSS puro)

### Fade-in on Scroll

```css
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  transition: opacity 0.6s ease, transform 0.6s ease;
}
.fade-in.visible {
  opacity: 1;
  transform: translateY(0);
}
```

### Hover Effects

- Botoes: `translateY(-2px)` + shadow increase
- Cards de bonus: `translateY(-4px)` + shadow increase
- Cards de depoimento: sutil `scale(1.01)`

### Pulse no CTA (sutil)

```css
@keyframes subtle-pulse {
  0%, 100% { box-shadow: 0 4px 15px rgba(212, 160, 23, 0.3); }
  50% { box-shadow: 0 4px 25px rgba(212, 160, 23, 0.5); }
}
```

Aplicar apenas no CTA principal do hero, periodo de 3s.

---

## 7. Responsive Breakpoints

| Breakpoint | Nome | Comportamento |
|------------|------|---------------|
| >= 1280px | Desktop Large | Max-width 1080px centrado |
| 1024-1279px | Desktop | Max-width 960px |
| 768-1023px | Tablet | Grid 8 colunas, padding lateral 32px |
| 376-767px | Mobile Large | Grid 4 colunas, padding lateral 20px |
| <= 375px | Mobile | Grid 4 colunas, padding lateral 16px |

### Decisoes Responsivas Chave

- **Hero:** Desktop = texto lado esquerdo, imagem direita. Mobile = texto full-width, imagem background
- **Bonus Grid:** Desktop = 2 colunas. Mobile = 1 coluna stack
- **Value Stack Table:** Mantido como tabela em todos os tamanhos (scroll horizontal se necessario nao)
- **Depoimentos:** Desktop = 2 colunas. Mobile = 1 coluna
- **CTA Buttons:** Mobile = full-width com padding 16px 24px
- **FAQ:** Mesmo layout em todos os tamanhos (texto-only)

---

## 8. Acessibilidade

- Contraste minimo WCAG AA (4.5:1 para texto, 3:1 para elementos grandes)
- `#2C2C2C` sobre `#FAF8F5` = ratio 13.5:1 (passa AAA)
- `#D4A017` com `#1A1A1A` texto = ratio 5.8:1 (passa AA)
- Focus states visiveis em todos os interativos
- Alt text descritivo em todas as imagens
- Semantica HTML5 (header, main, section, footer)
- Landmark roles para navegacao por screen reader

---

*Design System v1.0 - Routed by Design Chief, executed by @brad-frost methodology*
*Atomic Design: Atoms (cores, tipos) -> Molecules (cards, botoes) -> Organisms (secoes) -> Template (pagina)*
