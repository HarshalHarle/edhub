## EdHub - Learn Anytime, Anywhere.

Key Features:

- 🔍🎯 Browse & Filter Courses  
- 💳🛒 Purchase Courses using Stripe  
- ✅📌 Mark Chapters as Completed or Uncompleted  
- 📊📈 Progress Calculation of each Course  
- 🎓🏫 Student Dashboard  
- 👨‍🏫📚 Teacher Mode  
- ✏️📖 Create New Courses  
- 📄➕ Create New Chapters  
- 🔀📂 Easily Reorder Chapter Position with Drag n’ Drop  
- 🖼️📎📹 Upload Thumbnails, Attachments, and Videos using UploadThing  
- 🎞️⚙️🚀 Video Processing using Mux  
- 📺🎥 HLS Video Player using Mux  
- ✍️📝 Rich Text Editor for Chapter Description  
- 🔐🔑 Authentication using Clerk  
- 🔄🛠📦 ORM using Prisma  
- 🗄️🐬 MySQL Database  


### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone https://github.com/HarshalHarle/edhub.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

MUX_TOKEN_ID=
MUX_TOKEN_SECRET=

STRIPE_API_KEY=
NEXT_PUBLIC_APP_URL=http://localhost:3000
STRIPE_WEBHOOK_SECRET=

NEXT_PUBLIC_TEACHER_ID=
```

### Setup Prisma

Add MySQL Database

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
