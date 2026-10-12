# 🛼 Snitap Patins

Landing page fictícia de uma marca de patins, focada em **animações feitas só com HTML e CSS**, sem nenhuma linha de JavaScript.

## ✨ Animações

- **Hero com texto rotativo:** as palavras *Saudável*, *Radical* e *Divertida* se alternam com um efeito de "pulo" (`@keyframes` + `translateY`).
- **Entrada da imagem principal:** o patins e as estrelas entram deslizando pela direita, cada um com um pequeno atraso (`animation-delay`).
- **Banner infinito:** faixa com gradiente animado que rola sem parar.
- **Galeria com scroll animation:** as fotos aparecem conforme a página é rolada, uma depois da outra (`animation-timeline: view()`).
- **Hover na galeria:** a foto dá zoom e a legenda com o autor sobe de baixo para cima.
- **Microinterações:** o logo gira, o ícone da sacola balança e os links do rodapé ganham um sublinhado animado.

## 🛠️ Tecnologias

- HTML5 semântico
- CSS3 com **CSS Nesting**, **Grid**, **Flexbox**, **custom properties** e **scroll-driven animations**
- Fontes do Google Fonts: Montserrat, Syne e Inter

## 📁 Estrutura

```
├── index.html
├── assets/        # imagens, ícones e logo
└── styles/
    ├── index.css  # importa todos os outros
    ├── global.css # reset, variáveis e tipografia
    ├── header.css
    ├── hero.css
    ├── banner.css
    ├── gallery.css
    └── footer.css
```

## 🚀 Como rodar

Não precisa instalar nada:

```bash
git clone https://github.com/Carlosamaro37/Patins-Animation.git
```

Depois é só abrir o `index.html` no navegador.

> **Atenção:** as animações da galeria que dependem do scroll (`animation-timeline`) só funcionam em navegadores baseados em Chromium (Chrome, Edge). Nos outros navegadores as fotos aparecem normalmente, mas sem a animação.
