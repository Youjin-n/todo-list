- [x] "npx create-next-app@latest {project-name}" to initialize nextjs
- [x] create github repo, and connect
- [x] change layout, change page.tsx, delete assets
- [x] create .env file, add .env to .gitignore
- [x] add .prettierrc

- [x] "npm i -D prisma"
- [x] "npm i @prisma/client"
- [x] "npx prisma init"
- [x] create lib/db.ts
- [x] add "postinstall": "prisma generate" to package.json's scripts
- [x] change datasource db provider to sqlite in schema.prisma
- [x] add DATABASE_URL="file:./dev.db" to .env
- [x] "npx prisma migrate dev --name init"
- [x] add dev.db* to .gitignore 
- [ ] note: "npx prisma generate" and "npx prisma db push" whenever schemas have changed
- [ ] note: "npx prisma studio" to manage content

---

- primary stack: nextjs13-app-nosrc, react, shadcn, tailwind, convex, clerk-withorg, liveblocks
- secondary stack: zustand, date-fns, use-hooks, react-contenteditable, perfect-freehand
- ui: font = poppins-inter-kalam, icons = lucide

---

-