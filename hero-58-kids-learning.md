# Hero elegido: Hero 58 - Kids Learning Hero (Shadcn Space)

Hero lúdico para niños: navbar limpio, titular con degradado de colores, vídeo en bucle de un personaje y CTAs primario/secundario. Encaja con el tema "sueños de niños".

- Bloque: `hero-58` (componente `Hero58`)
- Licencia: **PRO** (requiere email + license key en `components.json`)
- Incluye navbar propio: no añadir otro navbar encima.

## Instalación

Estilo base:

```bash
npx shadcn@latest add @shadcn-space/hero-58
```

Estilo radix:

```bash
npx shadcn@latest add @shadcn-space/radix/hero-58
```

Con pnpm (el proyecto `Webs/shadcnspace/next-app` usa pnpm):

```bash
pnpm dlx shadcn@latest add @shadcn-space/hero-58
```

## Licencia en components.json

```json
{
  "registries": {
    "@shadcn-space": {
      "url": "https://shadcnspace.com/r/{name}.json",
      "params": {
        "email": "${EMAIL}",
        "license_key": "${LICENSE_KEY}"
      }
    }
  }
}
```

## Uso

```tsx
import { Hero58 } from "@/components/shadcn-space/blocks/hero-58";

export default function Page() {
  return <Hero58 />;
}
```

## Textos sugeridos (cambiar solo texto visible)

- Titular: "Cada sueño empieza con un niño que se atreve a imaginar"
- Subtítulo: "Un mundo donde los más pequeños descubren quiénes quieren ser."
- CTA primario: "Empieza a soñar"
- CTA secundario: "Descubre más"

## Alternativa

`hero-34` (Category Spotlight Hero, PRO): personajes 3D flotantes con colección "kids", más de tienda que de sueños.
