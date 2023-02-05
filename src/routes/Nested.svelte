<div>
<p>Wassup?</p>

<pre>
# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

</pre>

<p>package.json</p>
<pre><code>
{`
{
	"name": "myapp",
	"version": "0.0.1",
	"private": true,
	"scripts": {
		"dev": "vite dev",
		"build": "vite build",
		"preview": "vite preview",
		"test": "playwright test",
		"check": "svelte-kit sync && svelte-check --tsconfig ./tsconfig.json",
		"check:watch": "svelte-kit sync && svelte-check --tsconfig ./tsconfig.json --watch",
		"test:unit": "vitest",
		"lint": "prettier --plugin-search-dir . --check . && eslint .",
		"format": "prettier --plugin-search-dir . --write ."
	},
	"devDependencies": {
		"@playwright/test": "^1.28.1",
		"@sveltejs/adapter-auto": "^1.0.0",
		"@sveltejs/kit": "^1.0.0",
		"@typescript-eslint/eslint-plugin": "^5.45.0",
		"@typescript-eslint/parser": "^5.45.0",
		"eslint": "^8.28.0",
		"eslint-config-prettier": "^8.5.0",
		"eslint-plugin-svelte3": "^4.0.0",
		"prettier": "^2.8.0",
		"prettier-plugin-svelte": "^2.8.1",
		"svelte": "^3.54.0",
		"svelte-check": "^3.0.1",
		"tslib": "^2.4.1",
		"typescript": "^4.9.3",
		"vite": "^4.0.0",
		"vitest": "^0.25.3"
	},
	"type": "module"
}
`
}
</code></pre>

</div>