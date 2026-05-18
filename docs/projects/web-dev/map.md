---
tags:
  - Svelte
  - CSS
  - JavaScript
  - HTML
  - Cloudflare
  - Cloudflare Pages
---

<div style="display: flex;">

<img align="left" height="120" width="120" src="../../../assets/map/map_map-logo.svg" />

<div>
USTP-CDO Campus Interactive Map is an interactive map of my alumni university University of Science and Technology of Southern Philippines inspired by <a href="https://campus-map.stanford.edu/">Stanford</a>. It features accessible, searchable, and shareable links to landmarks, event centers, buildings, utilities and more. These locations are accompanied with on site pictures as visual aid. All types of locations have their own identifiable pins on the map.
</div>
</div>

[Website :material-web:](https://map.ustp.party/){ .md-button }
[GitHub :simple-github:](https://github.com/ustp-party/map){ .md-button }

=== "Landing Page"

    <img src="../../../assets/map/map_map.png">

=== "Points of Interests (POIs)"

    <video autoplay muted loop playsinlinesrc controls>
        <source src="../../../assets/map/map_POIs.mp4">
    </video>

=== "Finding POIs"

    <video autoplay muted loop playsinlinesrc controls>
        <source src="../../../assets/map/map_Finding%20POIs.mp4">
    </video>

=== "Switching Themes"

    <video autoplay muted loop playsinlinesrc controls>
        <source src="../../../assets/map/map_Switching%20Themes.mp4">
    </video>

## Features

- Desktop/Mobile friendly
- Searchable Points of Interests
- UI Theme switching
- GPS Enabled
- Enabling/disabling POIs
- Location sharing
- Descriptive locations

## Methodology

- Open-source data augmented with gathered data

### Frameworks
  - [Svelte](https://svelte.dev/) for the frontend framework
  - [Leaflet](https://leafletjs.com/) for the mapping engine
### Cloud
  - Static page hosted on [Cloudflare Pages](https://pages.cloudflare.com/)
  - Images hosted on [Cloudinary](https://cloudinary.com/)

## Metrics

### Lighthouse

| Metric         | Mobile Score | Desktop Score |
| -------------- | ------------ | ------------- |
| Performance    | 82           | 92            |
| Accessibility  | --           | --            |
| Best Practices | 96           | 96            |
| SEO            | 100          | 100           |
