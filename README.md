## Project






Fullstack Trello Clone: Next.js 14, Server Actions, React, Prisma, Stripe, Tailwind, MySQL


![ttt](https://github.com/samik1234/trello-dev-clone/assets/82882143/26cc0efc-65c8-4cea-862b-97671bb680be)







This is a repository for Fullstack Trello Clone: Next.js 14, Server Actions, React, Prisma, Stripe, Tailwind, MySQL























## Tech Stack

**Client:** React, Nextjs 14, Stripe, TailwindCSS

**Server:** Node, MongoDB, Prisma













## Features

- Auth
- Organizations / Workspaces
- Board creation
- Unsplash API for random beautiful cover images
- Activity log for entire organization
- Board rename and delete
- List creation
- List rename, delete, drag & drop reorder and copy
- Card creation
- Card description, rename, delete, drag & drop reorder and copy
- Card activity log
- Board limit for every organization
- Stripe subscription for each organization to unlock unlimited boards
- Landing page
- MongoDB
- Prisma ORM
- shadcnUI & TailwindCSS 









## Prerequisites: 

Node version 18.x.x














## Setup .env file

- NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
- CLERK_SECRET_KEY=
- NEXT_PUBLIC_CLERK_SIGN_IN_URL=
- NEXT_PUBLIC_CLERK_SIGN_UP_URL=
- NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
- NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=
- DATABASE_URL=
- NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=
- STRIPE_API_KEY=
- NEXT_PUBLIC_APP_URL=
- STRIPE_WEBHOOK_SECRET=







## Setup Prisma

- Add MySQL Database (I used MongoDB)
-  npx prisma generate
-  npx prisma db push



## Start the app

 - npm run dev

