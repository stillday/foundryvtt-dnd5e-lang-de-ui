
# foundryvtt-dnd5e-lang-de-ui

Web translation UI for https://github.com/League-of-Foundry-Developers/foundryvtt-dnd5e-lang-de-ui

This is the Alpha version for the UI.

This Project is createt with SvelteKit. 

When you have interesst to help to Translate, write me on Discord. You find me under crash#7509

You have interesst to help to Develop this Project, than fork please this Project and after you work, create Merge Request.

### ToDo:
- [ ] use NeDB to load the Origin Datastore
- [ ] include search Function
- [ ] only login user can write translation, with log
- [ ] rework design. Color, Responsive, ...
- [ ] include new interface
- [ ] include international lang function, [example from git project](https://github.com/dreitzner/kit-i18n/blob/master/src/hooks.ts)



WORK IN PROGRESS

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Before creating a production version of your app, install an [adapter](https://kit.svelte.dev/docs#adapters) for your target environment. Then:

```bash
npm run build
```

> You can preview the built app with `npm run preview`, regardless of whether you installed an adapter. This should _not_ be used to serve your app in production.