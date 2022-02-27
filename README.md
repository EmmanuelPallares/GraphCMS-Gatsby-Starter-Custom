# Gatsby-Starter-Custom-Vitoz

> A [Gatsby](httsp://gatsbyjs.com) starter for creating a basic blog with [GraphCMS](https://graphcms.com)

• [Demo](https://graph-cms-gatsby-starter-custom-9aray7341-emmanuelpallares.vercel.app) • [`gatsby-source-graphcms`](https://github.com/GraphCMS/gatsby-source-graphcms)

## Quick start

1. **Create a new Gatsby project via the [Gatsby CLI](https://www.npmjs.com/package/gatsby-cli)**

```shell
gatsby new graphcms-blog https://github.com/EmmanuelPallares/GraphCMS-Gatsby-Starter-Custom
```

2. **Provide your GraphCMS project keys**

> In order to use this starter, you'll need to have created a new GraphCMS project using our `Blog Template`.

Navigate into your new site’s directory and copy the `.env.sample` file.

```shell
cd graphcms-blog
cp .env.sample .env
```

Inside of your newly created `.env` file, provide values for each variable. These variables can be found in the [project settings UI](https://graphcms.com/docs/guides/concepts/apis#working-with-apis).

```env
GRAPHCMS_ENDPOINT=""
GRAPHCMS_TOKEN=""
```

3. **Start building!**

Install the dependencies and start the gatsby dev server:

```shell
yarn
yarn dev
```

## Features

- Use [`gatsby-image`](https://www.gatsbyjs.org/packages/gatsby-image) with your GraphCMS image assets.
- MDX support via [`gatsby-plugin-mdx`](https://www.gatsbyjs.org/packages/gatsby-plugin-mdx) on GraphCMS `RichText` fields.
- Built with [Tailwind CSS](https://tailwindcss.com/).
