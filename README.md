# 🎨 AI Skills — Creative Marketing Pro

Paquete de skills profesionales de marketing digital para agentes de IA (GitHub Copilot, Claude, Gemma y compatibles con el estándar SKILL.md).

Diseñado para **TiendaTuti** y marcas argentinas de moda, calzado y lifestyle. Incluye cobertura completa del **Mundial 2026**, sorteos, campañas estacionales y generación de contenido con IA.

---

## 📦 Skills Incluidas

| Skill | Descripción | Casos de Uso |
|-------|-------------|-------------|
| `creative-director` | Director Creativo — orquesta todas las skills | Campañas completas, estrategia, briefings |
| `flyer-generator` | Generador de flyers publicitarios | Ofertas, sorteos, eventos, fútbol |
| `instagram-reels` | Contenido para Instagram | Posts, stories, reels, captions, hashtags |
| `tiktok-creator` | Creador de TikToks con guion | Videos virales, trends, scripts completos |
| `video-prompt-engineer` | Prompts para IA generativa de video | Sora, Runway, Kling, Pika, Luma |
| `image-prompt-engineer` | Prompts para IA generativa de imagen | Midjourney, DALL-E 3, Flux, Stable Diffusion |
| `social-media-manager` | Estrategia y calendario editorial | Planificación, métricas, sorteos, comunidad |
| `copywriter-es-ar` | Copywriter en español rioplatense | Headlines, captions, email, descripciones |
| `tiendatuti-brand` | Brand Identity TiendaTuti completo | Paleta, tipografías, plantillas, campañas |
| `football-campaigns` | Campañas de fútbol y Mundial 2026 | Pre/durante/post partido, sorteos futboleros |
| `viral-content-generator` | Generador de contenido viral | Hooks, trends, UGC, psicología viral |

---

## 🚀 Instalación

### Opción 1 — Proyecto (`.github/skills/`)
```bash
# Clonar o copiar las carpetas dentro de tu proyecto
cp -r ai-skills/* .github/skills/
```

### Opción 2 — Personal (`~/.copilot/skills/`)
```bash
# Para uso personal en todos los proyectos
cp -r ai-skills/* ~/.copilot/skills/
```

### Opción 3 — Alternativa (`.agents/skills/`)
```bash
cp -r ai-skills/* .agents/skills/
```

### Opción 4 — Importar desde GitHub (URL)
Si subís este repo a GitHub, podés cargar las skills directamente desde la URL del archivo raw.

---

## 💬 Cómo Usar

Una vez instaladas, las skills se activan automáticamente cuando el agente detecta que son relevantes para tu solicitud, o podés invocarlas manualmente con `/`:

```
# Invocar manualmente en el chat del agente:
/creative-director Quiero una campaña para la liquidación de invierno de TiendaTuti
/flyer-generator Flyer para sorteo de zapatillas Nike con el Mundial de fondo
/instagram-reels Guion para reel de 30 segundos sobre nueva colección de camperas
/tiktok-creator TikTok viral sobre el look del hincha argentino
/football-campaigns Campaña completa para Argentina vs Brasil en el Mundial 2026
/viral-content-generator Ideas virales para el Black Friday de TiendaTuti
```

---

## 📁 Estructura del Repositorio

```
ai-skills/
│
├── creative-director/
│   └── SKILL.md          # Orquestador principal — Director Creativo
│
├── flyer-generator/
│   └── SKILL.md          # Flyers: ofertas, sorteos, eventos, fútbol
│
├── instagram-reels/
│   └── SKILL.md          # Posts, stories, reels, captions
│
├── tiktok-creator/
│   └── SKILL.md          # TikToks con guion completo
│
├── video-prompt-engineer/
│   └── SKILL.md          # Prompts IA para generación de video
│
├── image-prompt-engineer/
│   └── SKILL.md          # Prompts IA para generación de imágenes
│
├── social-media-manager/
│   └── SKILL.md          # Estrategia, calendarios, métricas
│
├── copywriter-es-ar/
│   └── SKILL.md          # Copy en español rioplatense
│
├── tiendatuti-brand/
│   └── SKILL.md          # Brand identity y sistema visual TiendaTuti
│
├── football-campaigns/
│   └── SKILL.md          # Campañas fútbol y Mundial 2026
│
└── viral-content-generator/
    └── SKILL.md          # Contenido viral, hooks, psicología
```

---

## 🎯 Casos de Uso Rápidos

### "Quiero un flyer para el Black Friday"
→ Activa: `flyer-generator` + `copywriter-es-ar` + `tiendatuti-brand`

### "Necesito contenido para el partido de Argentina"
→ Activa: `football-campaigns` + `instagram-reels` + `tiktok-creator`

### "Armame una estrategia de sorteo"
→ Activa: `social-media-manager` + `viral-content-generator` + `copywriter-es-ar`

### "Generame un prompt para hacer una imagen de producto con IA"
→ Activa: `image-prompt-engineer` + `tiendatuti-brand`

### "Quiero un reel viral de TikTok sobre la nueva colección"
→ Activa: `tiktok-creator` + `viral-content-generator` + `copywriter-es-ar`

---

## 🔮 Skills en Desarrollo (Próximamente)

```
ai-skills/ (futuras)
├── email-marketing/          # Campañas de email y newsletters
├── influencer-outreach/      # Scripts de contacto a influencers
├── seo-descriptions/         # Descripciones SEO para e-commerce
├── whatsapp-campaigns/       # Marketing por WhatsApp y difusiones
├── reels-editor-notes/       # Notas de edición para editores de video
└── brand-partnerships/       # Propuestas de colaboración entre marcas
```

---

## 🤝 Compatibilidad

| Agente | Soporte | Ruta |
|--------|---------|------|
| GitHub Copilot | ✅ Completo | `.github/skills/` |
| Claude (Anthropic) | ✅ Completo | `.claude/skills/` |
| Gemma / Google | ✅ Compatible | `.agents/skills/` |
| Cursor | ✅ Compatible | `.cursor/skills/` |
| Windsurf | ✅ Compatible | `.agents/skills/` |

---

## 📝 Licencia

Libre para uso personal y comercial. Si lo adaptás o mejorás, compartilo.

---

*Creado para TiendaTuti y marcas argentinas que quieren una agencia de publicidad completa dentro de su agente de IA.*
