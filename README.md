# Welcome to Remix and Storyblok!

- [Remix Docs](https://remix.run/docs)
- [Remix and Storyblok](https://www.storyblok.com/tp/headless-cms-remix)
- [Storyblok, how to structure the content](https://www.storyblok.com/docs/guide/essentials/content-structures)


## Development

From your terminal, clone the repo:

```sh
git clone https://github.com/roberto-butti/remix-storyblok.git
```

Install packages
```sh
cd remix-storyblok
npm install
```

Copy the .env:
```sh
cp .env.example .env
```
and then edit the .env, setting STORYBLOK_TOKEN with the right Storyblok token.

Now start the development web server

```sh
npm run dev
```



## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Enable HTTPS locally

```sh
local-ssl-proxy --source 3010 --target 3000 --cert localhost.pem --key localhost-key.pem
```


