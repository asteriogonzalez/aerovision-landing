# AeroVision AR — Landing page

Static landing page for **AeroVision AR**, an Augmented Reality platform for aircraft maintenance (B2B SaaS for MROs, airlines, aircraft manufacturers and defence aviation).

> 🚀 **Live site:** (pendiente — se publica al activar GitHub Pages)
>
> 🌐 **Custom domain:** TBD — pendiente de M0-009

## Idiomas / Languages

| | | URL relativa |
|---|---|---|
| 🇪🇸 | Español | [`/`](./) |
| 🇬🇧 | English | [`/en/`](./en/) |
| 🇫🇷 | Français | [`/fr/`](./fr/) |
| 🇩🇪 | Deutsch | [`/de/`](./de/) |

Cada versión incluye un language switcher en el header. Sin auto-detect del navegador (decisión consciente: zero-JS).

## Stack

- HTML5 estático puro
- CSS embebido en cada página (mobile-first responsive)
- **Sin frameworks, sin tracking, sin JavaScript**
- Tipografía `system-ui` con fallbacks
- Paleta: navy `#0b2545` + acento `#f4b41a`

## Despliegue

Servido vía **GitHub Pages** (rama `main`, raíz `/`). Decisión de hosting documentada en `decision.records.md` del repo interno del proyecto (`D-004`).

Para probar localmente:

```bash
cd <ruta-del-repo>
python -m http.server 8000
# abrir http://localhost:8000
```

## Contexto del proyecto

Parte del **MBA Aeroespacial — EOI Promoción 2026**.

Equipo:
- Asterio González
- Javier Jiménez
- Emma Lope

Asignatura: MBA.08 — Business Design & Lean Startup.

## Roadmap del sitio

| Hito | Estado |
|------|--------|
| M0-007 — Landing ES baseline | ✅ |
| M0-013 — Multi-idioma (en/fr/de) | ✅ |
| M0-014 — Estudio comparativo hosting | ✅ |
| M0-015 — Deep dive Netlify/GH Pages | ✅ |
| M0-016 — Deploy GitHub Pages | 🟡 (este repo) |
| M0-009 — Custom domain | ⏳ (bloqueado, reserva de dominio pendiente) |

> Pendiente antes de envío B2B: revisión nativa profesional de FR / DE.

## License

(TBD)
