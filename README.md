# React App with Vite, Pnpm, Tailwindcss, Typescript
1. Install node 
2. Instal pnpm (package management)
3. Use vite instead of create-react-app
- Not use: `npx create-react-app my-app`
- Use: `pnpm create vite my-app --template type-of-app`
- `type-of-app` = vue, react, react-ts, lit, lit,...
4. We use react with typescript (typescript = javascript with type)
-> create app: `pnpm create vite my-app --template react-ts`
5. After cloning run `pnpm install-all`
6. Run `pnpm dev` to start frontend, backend server
7. Use css library: TailwindCSS
(docs)[https://tailwindcss.com/docs/guides/vite]
- `pnpm install -D tailwindcss postcss autoprefixer`
- `npx tailwindcss init -p`
- config in tailwindcss.config.js
- config in file index.css 
- modify in App.tsx
8. Install extension Tailwind CSS IntelliSense to help recognize syntax
9. Delete App.css