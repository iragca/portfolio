---
tags:
  - React
  - CSS
  - JavaScript
  - HTML
  - Docker
  - Python
  - FastAPI
---

<div style="display: flex;">

<img align="left" height="120" width="120" src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/docuisine/docuisine-no-base.png" />

<div>
Docuisine is a self-managed/hosted application for saving and documenting food recipes. Inspired by my hobby of cooking, I aimed to document favorites recipes I encounter and wish to cook myself. These recipes are rich in metadata and can be easily shared with friends over the internet.
</div>
</div>

[Demo :material-play-circle:](https://docuisine.iragca.dev/){ .md-button }
[Website :material-web:](https://docuisine.github.io/documentation/){ .md-button }
[GitHub :simple-github:](https://github.com/docuisine/docuisine){ .md-button }

!!! info "Work in progress"

=== "Homepage"

    <img src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/docuisine/homepage.png">

=== "Signing up"

    <img src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/docuisine/signup_page.png">

=== "Creating a recipe"

    <img src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/docuisine/create_recipe.png">

=== "Account settings"

    <img src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/docuisine/account_page.png">

## Features

- Create, browse, and share recipes
- Save and organize cookbooks
- Manage a variety of ingredients, and kitchen tool information
- Rich metadata for recipes, ingredients, and supermarket/stores
- Can be self-hosted on a single machine or deployed using free offerings from Cloudflare, Vercel and Supabase

## Methodology

### Frameworks

- [React](https://react.dev/) for the frontend framework
- [Shadcn](https://ui.shadcn.com/) for the UI components

### Cloud

- Frontend hosted on [Vercel](https://vercel.com/)
- Serverless FastAPI backend hosted on [Vercel](https://vercel.com/)
- S3-bucket image hosting service on [Cloudlfare R2](https://www.cloudflare.com/developer-platform/products/r2/)
- Can be hosted on your own machine with [Docker](https://www.docker.com/) using a single docker compose

## Metrics

### Lighthouse

| Metric         | Mobile Score | Desktop Score |
| -------------- | ------------ | ------------- |
| Performance    | 86           | 96            |
| Accessibility  | 99           | 99            |
| Best Practices | 100          | 100           |
| SEO            | 83           | 83            |
