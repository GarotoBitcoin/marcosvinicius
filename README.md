# Portfólio — Marcos Vinícius

Portfólio pessoal de **Marcos Vinícius**, Desenvolvedor Full-Stack & Arquiteto de Software.
Single-page com seções de projetos, projetos pessoais (Garoto Bitcoin), especialidades, stack e contato.

## Estrutura

```
.
├── index.html                          # Site principal (entry point)
├── demos/
│   ├── projeto1-dashboard.html         # Demo: Dashboard de Apuração
│   └── projeto2-restaurantguru.html    # Demo: Réplica Restaurant Guru
└── README.md
```

## Stack

- HTML5 semântico
- Tailwind CSS (via CDN)
- JavaScript vanilla
- Iconify para ícones
- Chart.js (no demo do dashboard)

## Deploy

Site 100% estático. Basta servir o diretório raiz por qualquer host:

- **GitHub Pages**: habilite Pages apontando para a branch `main` (root).
- **Vercel / Netlify**: import do repositório, sem build step.
- **Local**: abra `index.html` no navegador ou use `python -m http.server`.

## Demos

Os projetos 1 e 2 abrem em modal de visualização (sem interação) carregando os arquivos da pasta `demos/` via iframe. O projeto 3 (LLM Survey Reader) é interno e não possui demo pública.

---

© 2026 Marcos Vinícius
