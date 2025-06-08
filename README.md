# rest-express

A GitHub clone project built with modern web technologies.

## 📦 Project Setup

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

## 📁 Project Structure

- `components.json` - Project components configuration
- `drizzle.config.ts` - Drizzle ORM configuration
- `tailwind.config.ts` - Tailwind CSS configuration
- `tsconfig.json` - TypeScript configuration
- `.replit` - Replit configuration for cloud-based IDE setup

## 📜 Available Scripts

```json
{
  "dev": "NODE_ENV=development tsx server/index.ts",
  "build": "vite build && esbuild server/index.ts --platform=node --packages=external --bundle --format=esm --outdir=dist",
  "start": "NODE_ENV=production node dist/index.js",
  "check": "tsc",
  "db:push": "drizzle-kit push"
}
```

## 📚 Dependencies

- **Main Dependencies**:
  @hookform/resolvers, @jridgewell/trace-mapping, @neondatabase/serverless, @radix-ui/react-accordion, @radix-ui/react-alert-dialog, @radix-ui/react-aspect-ratio, @radix-ui/react-avatar, @radix-ui/react-checkbox, @radix-ui/react-collapsible, @radix-ui/react-context-menu, @radix-ui/react-dialog, @radix-ui/react-dropdown-menu, @radix-ui/react-hover-card, @radix-ui/react-label, @radix-ui/react-menubar, @radix-ui/react-navigation-menu, @radix-ui/react-popover, @radix-ui/react-progress, @radix-ui/react-radio-group, @radix-ui/react-scroll-area, @radix-ui/react-select, @radix-ui/react-separator, @radix-ui/react-slider, @radix-ui/react-slot, @radix-ui/react-switch, @radix-ui/react-tabs, @radix-ui/react-toast, @radix-ui/react-toggle, @radix-ui/react-toggle-group, @radix-ui/react-tooltip, @tailwindcss/vite, @tanstack/react-query, adm-zip, class-variance-authority, clsx, cmdk, connect-pg-simple, date-fns, drizzle-orm, drizzle-zod, embla-carousel-react, express, express-session, framer-motion, input-otp, lucide-react, memorystore, next-themes, passport, passport-local, react, react-day-picker, react-dom, react-hook-form, react-icons, react-resizable-panels, recharts, tailwind-merge, tailwindcss-animate, tw-animate-css, vaul, wouter, ws, zod, zod-validation-error

- **Dev Dependencies**:
  @replit/vite-plugin-cartographer, @replit/vite-plugin-runtime-error-modal, @tailwindcss/typography, @types/connect-pg-simple, @types/express, @types/express-session, @types/node, @types/passport, @types/passport-local, @types/react, @types/react-dom, @types/ws, @vitejs/plugin-react, autoprefixer, drizzle-kit, esbuild, postcss, tailwindcss, tsx, typescript, vite

---

This project is intended as a GitHub clone example using technologies like TypeScript, TailwindCSS, and potentially Drizzle ORM.
