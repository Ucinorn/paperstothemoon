*Looking for a shareable component template? Go here --> [sveltejs/component-template](https://github.com/sveltejs/component-template)*

---

## From this Reddit comment

You buy seeds. Then you plant them and water them and the trees grow. You chop them down. You transfer to the factory and it turns them into paper, which then is placed on what looks like a rocket platform and your first goal is to stack enough paper to get to the moon. I've had this damn idea for freaking years now and I have no idea how I'd ever be able to make it so here it is. Someone please make it.

Currency is made by selling paper then you buy more seeds, more land to plant trees, workers to automate, so on. World events would happen like another company decides they're going to try and beat you to the moon with their own paper stack. They try and sabotage your stack. You eventually have to build walls around it and put up defenses, which becomes its own tower defense mini game. Workers can become warriors to fend off attacks from competing companies that join up. I thought it would be cool to also have like a newspaper marquee at the top tracking your progress and whatnot like city builder games do. There'd also be a research facility to learn new strains of tree that produce more paper or seeds that grow faster and stuff like that.

Eventually you will get to the moon and I really want that to take a bit. Which then turns out to be only step one. Now you get the galactic map. It's time to keep that paper stack growing. You now have to fight aliens and fend off alien attacks so you have to sell paper to build a new ship factory and build defenses with battle ships and stuff like that. The stack eventually needs to grow too fast so you need to send out scout ships to find other planets to plant trees on. But you also need more money so you start more paper stacks on those planets to sell more paper and it'll be worth more with upgrades and whatnot. Man... I really just want to play this damn game.

---

# svelte app

This is a project template for [Svelte](https://svelte.dev) apps. It lives at https://github.com/sveltejs/template.

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit sveltejs/template svelte-app
cd svelte-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.

If you're using [Visual Studio Code](https://code.visualstudio.com/) we recommend installing the official extension [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode). If you are using other editors you may need to install a plugin in order to get syntax highlighting and intellisense.

## Building and running in production mode

To create an optimised version of the app:

```bash
npm run build
```

You can run the newly built app with `npm run start`. This uses [sirv](https://github.com/lukeed/sirv), which is included in your package.json's `dependencies` so that the app will work when you deploy to platforms like [Heroku](https://heroku.com).


## Single-page app mode

By default, sirv will only respond to requests that match files in `public`. This is to maximise compatibility with static fileservers, allowing you to deploy your app anywhere.

If you're building a single-page app (SPA) with multiple routes, sirv needs to be able to respond to requests for *any* path. You can make it so by editing the `"start"` command in package.json:

```js
"start": "sirv public --single"
```

## Using TypeScript

This template comes with a script to set up a TypeScript development environment, you can run it immediately after cloning the template with:

```bash
node scripts/setupTypeScript.js
```

Or remove the script via:

```bash
rm scripts/setupTypeScript.js
```

## Deploying to the web

### With [Vercel](https://vercel.com)

Install `vercel` if you haven't already:

```bash
npm install -g vercel
```

Then, from within your project folder:

```bash
cd public
vercel deploy --name my-project
```

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public my-project.surge.sh
```
