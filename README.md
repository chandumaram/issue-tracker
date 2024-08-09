This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Process followed While Crating this Project

- Reference is [https://github.com/mosh-hamedani/issue-tracker/tree/main](https://github.com/mosh-hamedani/issue-tracker/tree/main) & [https://www.youtube.com/watch?v=J9sfR6HN6BY]

- Install react-icons using `npm install react-icons --save`

  - [https://react-icons.github.io/react-icons/]

- Install classnames using `npm i classnames`

- Install and setup MySql database

  1. Install MySql from `https://www.mysql.com/downloads/`
  2. Install DataGrip from `https://www.jetbrains.com/datagrip/`

- Using Prisma

  1. Install with `npm install prisma`
  2. Initializing with `npx prisma init`
  3. write Schema in `prisma/schema.prisma`
  4. Update DatabaseURL in `.evn`
  5. Migrate Schema using `npx prisma migrate dev`

- Setup database table in Mysql using DataGrip

- Install Zod using `npm i zod`

  - Zod is a TypeScript-first schema declaration and validation library

- [Radix UI](https://www.radix-ui.com/) - An open source component library

  - Install using `npm install @radix-ui/themes`
  - Import the CSS file in app/layout.tsx `import '@radix-ui/themes/styles.css';`
  - Add the **Theme** component in app/layout.tsx
    ```
    export default function () {
      return (
        <html>
          <body>
            <Theme>
              <MyApp />
            </Theme>
          </body>
        </html>
      );
    }
    ```

- Install react-simplemde-editor using `npm install --save react-simplemde-editor easymde`

  - [https://www.npmjs.com/package/react-simplemde-editor]

- Install react-hook-form using `npm install react-hook-form`

  - [https://react-hook-form.com/get-started]

- Install axios using `npm i axios`

  - Promise based HTTP client for the browser and node.js
  - [https://www.npmjs.com/package/axios]

- Install React Hook Form using `npm i @hookform/resolvers`

  - Performant, flexible and extensible forms with easy to use validation
  - [https://www.npmjs.com/package/@hookform/resolvers]

