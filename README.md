````markdown
# ⚡ React Router + TailwindCSS + shadcn/ui (canary) Starter Template

A modern React starter template powered by **React Router v7 (Framework Mode)**,
**TailwindCSS v4**, and the bleeding-edge **shadcn/ui@canary** components. Ideal
for quickly bootstrapping full-featured, aesthetically pleasing, and accessible
web apps.

---

## ✨ Features

- ⚛️ **React Router Framework Mode** – built-in file-based routing
- 🎨 **TailwindCSS** – utility-first styling with full customization
- 🧩 **shadcn/ui (canary)** – prebuilt, accessible, and customizable UI
  components
- ⚡ **Vite** – blazing fast dev experience
- 🧱 **Project Structure** – opinionated layout with scalability in mind

---

## 📦 Tech Stack

- [React Router](https://reactrouter.com/en/main/start/tutorial) (Framework
  Mode)
- [TailwindCSS](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/docs/installation/canary)
- [Vite](https://vitejs.dev/)

---

## 🚀 Getting Started

```bash
npx degit yourusername/react-router-tailwind-shadcn-template my-app
cd my-app
npm install
npm run dev
```
````

---

## 🧱 Folder Structure

```
.
├── app/                   # React Router pages, layouts, and routes
│   ├── routes/            # Route modules (file-based routing)
│   └── layout.tsx         # Root layout
├── components/            # Reusable UI components (shadcn-based)
├── lib/                   # Utility functions, custom hooks, etc.
├── styles/                # Tailwind config and global styles
├── tailwind.config.ts     # TailwindCSS configuration
├── postcss.config.js
├── vite.config.ts
└── README.md
```

---

## 🛠️ Setup Notes

### 1. Install shadcn/ui (canary)

```bash
npx shadcn-ui@canary init
```

Choose:

- Framework: `react`
- TypeScript: `yes`
- Tailwind: `yes`
- Directory: `components`
- Alias: `@/`

Then, start adding components using:

```bash
npx shadcn-ui@canary add button
```

### 2. Tailwind Configuration

Ensure `tailwind.config.ts` is properly configured to scan your `app`,
`components`, and `lib` directories.

```ts
content: [
  "./app/**/*.{ts,tsx}",
  "./components/**/*.{ts,tsx}",
  "./lib/**/*.{ts,tsx}"
],
```

---

## 🧪 Scripts

| Command           | Description          |
| ----------------- | -------------------- |
| `npm run dev`     | Start dev server     |
| `npm run build`   | Build for production |
| `npm run preview` | Preview prod build   |

---

## 📄 License

MIT — free to use and modify.

---

## 🙌 Acknowledgments

- [shadcn/ui](https://github.com/shadcn/ui)
- [Tailwind Labs](https://github.com/tailwindlabs)
- [React Router Team](https://github.com/remix-run/react-router)
- [Vite](https://vitejs.dev/)

---

Happy hacking! 💻✨

```

---

Let me know if you want to include a badge section (e.g. Netlify deploy, GitHub Actions), an example page screenshot, or a live demo link!
```
