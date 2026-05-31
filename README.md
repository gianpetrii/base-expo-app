# base-expo-app

## Descripción del proyecto

Plantilla móvil en **Expo ~52** con Expo Router, NativeWind, Zustand, React Hook Form + Zod y cliente **Supabase** para persistencia y auth según la configuración del proyecto.

## Problema que resuelve

Acelera el arranque de apps React Native con navegación por archivos, estilos utilitarios y cliente backend ya alineados, en lugar de configurar a mano router, tema, validación y Supabase en cada nuevo repositorio.

## Stack

- Expo, Expo Router, React Native
- Supabase, NativeWind / Tailwind

## Requisitos

- Node.js LTS

## Instalación

```bash
pnpm install
pnpm start
```

Scripts: `pnpm android`, `pnpm ios`, `pnpm web`.

## Variables de entorno

Copiá [`.env.local.example`](.env.local.example) a `.env.local` y configurá las claves `EXPO_PUBLIC_*` según el archivo.

## Personalizar

Si clonás esta plantilla para otro producto, actualizá en [`app.config.ts`](app.config.ts) `name`, `slug`, `scheme` y los identificadores nativos (`bundleIdentifier`, `package`).
