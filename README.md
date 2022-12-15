This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, install the following plug ins:

-   [Prettier](https://prettier.io/docs/en/index.html) 
-   [ESLint](https://eslint.org/docs/latest/)

When combined, these two extensions ensure that all code conforms to the style being used in other files while also making debugging and error catching easier.

## Running Prettier

The following is the general command used to format with Prettier.

`npx prettier --write`

When ran, rearrangements to code according to the format preferences that Prettier has been told to use will take place.
If entered without specifiying a file or directory, the entire project will undergo a reformation.
Although there are no immediate issues with this, it can take a while to complete.
Instead, if directory or specific file formatting are all that is required, the following commands can be entered to do just that.

For directory formatting:

`npx prettier --write DirectoryEx/`

For file formatting:

`npx prettier --write DirectoryEx/FolderEx/File.js/`

To check if a file has already been formatted, enter the following command:

`npx prettier --check`

## Running ESLint



## Running localhost

When working on the website, it is often helpful to be able to see the changes you've made as you're making them.
This can be achieved by running localhost and creating a temporary server for the website.
Begin by entering either of the following commands into the terminal.

```bash
npm run dev
# or
yarn dev
```

Once entered, open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

When you being making changes to the file you're working on, you'll see that the page updates automatically each time you save.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Next Build

Run the following command in the terminal to build

## Static Export

Because the website is hosted on UCR servers, we have to use static html files.

## Learn More

To learn more about Next.js, take a look at the following resources:

-   [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
-   [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.