# RGZ — Site Institucional (Documentação Técnica)

Documentação técnica do site institucional da **RGZ Growth & Performance**, desenvolvido em **HTML5 e CSS3 puro**, com foco em performance, controle de layout e facilidade de manutenção.

---

## Objetivo do projeto

Criar uma landing page institucional moderna, performática e escalável, sem dependência de frameworks, utilizando boas práticas de HTML semântico e CSS organizado por seções.

---

## Tecnologias utilizadas

- HTML5
- CSS3
- Google Fonts
  - Hanken Grotesk
  - Plus Jakarta Sans

> Não foram utilizados frameworks (Bootstrap, Tailwind, etc.) nem bibliotecas JS externas.

---

## Estrutura de pastas

    /
    ├─ README.md
    ├─ index.html
    └─ src/
    ├─ css/
    │ ├─ style.css → estilos globais e por seção
    │ └─ variables.css → paleta de cores e variáveis
    ├─ img/
    │ ├─ Background-Img.png
    │ ├─ FavIcon.svg
    │ ├─ Logo.svg
    │ ├─ hero-img.png
    │ └─ google-icon.svg
    └─ js/
    └─ script.js → reservado para interações futuras


---

## Estrutura de seções (HTML)

1. `#home` — Hero / proposta de valor
2. `#stagnation` — Problema de mercado
3. `#ascend` — Metodologia / sistema
4. `#manifest` — Manifesto de marca
5. `#reviews` — Prova social (Google)
6. `#ideal-client` — Qualificação de público
7. `#final-cta` — CTA final
8. `footer`

---

## Layout e responsividade

- Largura máxima: **1440px**
- Container centralizado (`.container`)
- Breakpoints principais:
  - 1280px
  - 1024px
  - 900px
  - 768px
  - 640px
  - 480px

---

## Boas práticas aplicadas

- HTML semântico (`header`, `main`, `section`, `footer`)
- Separação clara de responsabilidades no CSS
- Uso de `aria-hidden="true"` em elementos decorativos
- Uso de `alt=""` em imagens não informativas
- Efeitos visuais (blur, glow, gradientes) feitos apenas com CSS
- Código organizado por comentários de seção

---

## Como executar

### Abrir diretamente
Abra o arquivo `index.html` em qualquer navegador moderno.

### Servidor local (recomendado)
No VS Code:
1. Instale a extensão **Live Server**
2. Clique com o botão direito em `index.html`
3. Selecione **Open with Live Server**

---

## Pontos de atenção para manutenção

- Ajustes de cores devem ser feitos apenas em `variables.css`
- Novas seções devem seguir o padrão:
  - comentário
  - container
  - grid/flex interno
- Evitar adicionar dependências externas sem necessidade

---

## Possíveis evoluções técnicas

- Integração com Google Analytics (GA4)
- Implementação de formulário de diagnóstico
- Otimização de imagens (WebP)
- Internacionalização (i18n)
- Adição de microinterações com JS puro
- Inclusão de avaliações reais
- Links reais para o botões, levando para o WhatsApp/Formulário

---

## Autor

Rafael de Morais Rodrigues

Projeto desenvolvido para **RGZ Growth & Performance**.

© 2025 RGZ Growth & Performance
