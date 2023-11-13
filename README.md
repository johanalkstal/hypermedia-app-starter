# hypermedia-app-starter

Template to get started building Hypermedia App Systems

- Deno runtime (https://deno.com/)
- Hono web server (https://hono.dev/)
- htmx (https://htmx.org/)
- alpine.js (https://alpinejs.dev/)
- tailwindcss (https://tailwindcss.com/)

Run `deno task tailwind` to watch for CSS changes.

Run `deno task dev` to run the server and watch for code changes.

A GitHub workflow is included to deploy the `main` branch to Deno Deploy. Change
the `"project-name"` in `deploy.yml` to the name of your Deno Deploy project.
