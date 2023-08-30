About:

A clone of the very popular Threads social media app from Meta(formerly known as Facebook). Using the latest in web technologies with NextJS 13 server side rendering and MongoDB for backend database. Users can post a thread, reply to threads, create communities and see updates on their activities.

Prerequisites:
* You'will need a .env file
* A secret and framework key from Clerk at https://dashboard.clerk.com, account is free
* A webhook key from Clerk for the group/community component
* A mongo account with password for user for the database
* Sample .env should look like this:
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
MONGODB_URL=
NEXT_CLERK_WEBHOOK_SECRET=
```

How to start:
1. Go to root folder
2. Npm install
3. Npm run dev

Tech stacks used:

    React
    NextJS
    TypeScript
    Tailwindcss
    Clerk
    Mongoose
    Svix
    Shadcdn-ui
    Uploadthing

