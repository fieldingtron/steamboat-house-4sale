# Astro Website to promote steamboat house for sale by owners

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## Configuration

- Google Tag ID: Set `PUBLIC_GOOGLE_TAG_ID` to configure the Google tag (Analytics/Ads) ID. Defaults to `AW-16679746682` if not set.

### Local development

Create a `.env` file in the project root:

```
PUBLIC_GOOGLE_TAG_ID=AW-16679746682
```

Astro exposes `PUBLIC_` prefixed env vars to the client. The layout reads this value and injects it into the `gtag.js` loader and `gtag('config', ...)` call.
