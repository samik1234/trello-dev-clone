


Fullstack Trello Clone: Next.js 14, Server Actions, React, Prisma, Stripe, Tailwind, MongoDB







![ttt](https://github.com/samik1234/trello-dev-clone/assets/82882143/eeced529-2a40-4683-973b-13cd32f7be49)

























## Tech Stack

**Client:** React, Redux, TailwindCSS

**Server:** Node, Express












Key Features:

> Auth

> Organizations / Workspaces

> Board creation

> Unsplash API for random beautiful cover images

> Activity log for entire organization

> Board rename and delete

> List creation

> List rename, delete, drag & drop reorder and copy

> Card creation

> Card description, rename, delete, drag & drop reorder and copy

> Card activity log

> Board limit for every organization

> Stripe subscription for each organization to unlock unlimited boards

> Landing page

> MongoDB

> Prisma ORM

>shadcnUI & TailwindCSS









Prerequisites: 

Node version 18.x.x















Install packages
npm i














Setup .env file

1.NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=


2.CLERK_SECRET_KEY=


3.NEXT_PUBLIC_CLERK_SIGN_IN_URL=


4.NEXT_PUBLIC_CLERK_SIGN_UP_URL=


5.NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=


6.NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=


7.DATABASE_URL=


8.NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=


9.STRIPE_API_KEY=


10.NEXT_PUBLIC_APP_URL=


11.STRIPE_WEBHOOK_SECRET=







Setup Prisma

 Add MySQL Database (I used MongoDB)

  npx prisma generate

  npx prisma db push



Start the app

 npm run dev

