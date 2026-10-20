# Moulshree for Trupeer

A one-page pitch for Trupeer, written for the Product Manager role.

**Live:** https://moulshree-trupeer.vercel.app

## What is in here

A single static page with no build step and no dependencies.

- `index.html`: the whole page (HTML, CSS and a little JavaScript)

## Run it locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Deployment

Hosted on Vercel and connected to this repository. Every push to `main` deploys automatically.
No framework or build command is needed.

## Analytics

Visitor counts use Vercel Web Analytics. The two-line snippet right after the `</style>` tag in `index.html` loads `/_vercel/insights/script.js`, which Vercel serves once Analytics is enabled for the project (Project → Analytics → Enable). Results appear in the Analytics tab of the Vercel project. The `@vercel/analytics` npm package is not used because this site has no build step.
