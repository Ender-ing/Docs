# Website

> [!NOTE]
> This repository is excluded from the typical subdomain building process!
>
> It has its own building script!

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

> [!NOTE]
> You may use the following command to swizzle elements:
>
> ```bash
> npx docusaurus swizzle @docusaurus/theme-classic ELEMENT
> ```

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
