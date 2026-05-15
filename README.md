# Arquitectura Page

Galería personal de mis plantillas de arquitectura, hecha con Astro.

## Estructura

```
/
├── src/
│   ├── components/    # Componentes reutilizables
│   ├── layouts/       # Layouts base
│   ├── sections/      # Secciones de página
│   ├── styles/        # CSS global
│   └── pages/         # Páginas del sitio
├── templates/         # Plantillas individuales
│   └── 01/           # Template 01 (despliegue independiente)
└── public/           # Assets estáticos
```

## Comandos

| Comando | Acción |
|---------|--------|
| `bun install` | Instala dependencias |
| `bun dev` | Inicia servidor en desarrollo |
| `bun build` | Genera build de producción |
| `bun preview` | Previsualiza el build |

## Cómo agregar una plantilla

1. Agregar la plantilla en `templates/`
2. Agregar la URL de despliegue en `src/pages/index.astro`
3. Desplegar la plantilla en Vercel (u otro provider)

## Despliegues

Cada plantilla en `templates/` se despliega de forma independiente.