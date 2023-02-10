<p align="center">
<img src="public/logo.png" width="60%" title="La Crypta Tickets">
</p>

## Instructions

Just fork it.

Copy **.env.sample** into **.env** file and set your destination URL.

```bash
VITE_TITLE="La Crypta - Redirecting..."
VITE_DESTINATION="http://lacrypta.com.ar"
VITE_GOOGLE_ANALYTICS="G-0000000000"
```

Deploy it and assign a subdomain.

### Features

- [x] Vite
- [x] Custom Title
- [x] Analytics
- [x] Netlify Button
- [x] Vercel Button
- [ ] Multiple links

## Auto Deploy on Netlify or Vercel

[![Deploy on Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/lacrypta/redirect)

or

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Flacrypta%2Fredirect&env=VITE_TITLE,VITE_DESTINATION,VITE_GOOGLE_ANALYTICS&envDescription=HTML%20Title%20while%20loading%20and%20Destination%20URL&project-name=redirect&repository-name=redirect)
