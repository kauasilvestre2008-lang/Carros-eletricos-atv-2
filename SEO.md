# SEO.md – Atividade 2 (Meu Site Encontrável)

**Aluno:** Kauã Silvestre Vilas Boas  
Site: https://kauasilvestre2008-lang.github.io/Carros-eletricos-atv-2/

Repositório: https://github.com/kauasilvestre2008-lang/Carros-eletricos-atv-2

## 1. Palavras-chave planejadas

| # | Palavra-chave | Onde é trabalhada |
|---|---------------|-------------------|
| 1 | carros elétricos | `index.html` (title, h1, description, texto) |
| 2 | como funciona um carro elétrico | `index.html` (title, description, h3 "Como funciona um carro elétrico") |
| 3 | recarga de carro elétrico | `recarga-de-carro-eletrico.html` (title, h1, description, URL) e card da home |

## 2. Decisões tomadas

**title e description únicos**
- Home: *"Carros elétricos: como funciona e como recarregar"* 
- Página 2: *"Recarga de carro elétrico: wallbox, eletroposto e AC x DC"* 
- Cada página trabalha palavras-chave diferentes para não competirem entre si.

**canonical, Open Graph e favicon**
- `<link rel="canonical">` com URL absoluta em cada página.
- Open Graph completo (type, site_name, locale, title, description, url, image, largura, altura e texto alternativo), mais Twitter Card.
- Imagem `images/og-image.jpg` com **1200×630**.
- Favicon em `.ico`, `.svg` e `apple-touch-icon`.

**JSON-LD**
- Tipo `Article` (conteúdo explicativo), com `WebSite` na home e `BreadcrumbList` na página 2.
- Campos: headline, description, image, datePublished, dateModified, author, publisher, keywords e about.

**robots.txt e sitemap.xml**
- `robots.txt` libera todo o site e aponta para o sitemap.
- `sitemap.xml` lista as 2 páginas com `lastmod`.

**URLs e links internos**
- URL amigável: `recarga-de-carro-eletrico.html` 
- Links descritivos entre as páginas 


## 3. Lighthouse (celular): antes e depois


| Categoria | Antes | Depois |
|-----------|-------|--------|
| Performance | __ | __ |
| Accessibility | __ | __ (meta ≥ 90) |
| Best Practices | __ | __ |
| SEO | __ | __ (meta ≥ 95) |

Prints: `prints/lighthouse-antes.png` e `prints/lighthouse-depois.png`.

## 4. Validação do JSON-LD

Validado em https://validator.schema.org 
