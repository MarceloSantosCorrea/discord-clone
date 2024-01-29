// Dart theme
bun i next-themes

npx shadcn-ui@latest add dropdown-menu
npx shadcn-ui@latest add button

// Instalação Prisma
npm i -D prisma
npx prisma init

npx prisma generate
npx prisma db push
npm i @prisma/client

// Modal
npx shadcn-ui@latest add dialog
npx shadcn-ui@latest add input
npx shadcn-ui@latest add form