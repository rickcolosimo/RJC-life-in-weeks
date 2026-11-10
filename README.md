# Life in Weeks

This is an interactive map of my life, where each week I've been alive is a little box. The box's border color represents where I was living, the fill color what I was doing. Tap a box to see what I was doing where that week.

I adapted this from the Gina Trapani code on Github to remind myself of some things in my past and to help my boys see ahead of them..

Read more about Gina Trapani's mindset at [Life in Weeks at Wait But Why](https://waitbutwhy.com/2014/05/life-weeks.html).

Her code was copied and adapted from [Buster Benson](https://busterbenson.com/life-in-weeks). It is a single webpage statically-rendered with [Hugo](https://gohugo.io/) hosted on Netlify. It consists of two [data](data/events.yml) [files](data/colors.yml), [an introduction](content/index.md), and a [template](layouts/_default/index.html).

[I used Github Copilot to port from using Hugo to Github pages for simplicity on my end.]

## ✨ Customize

- `content/` → Page content
- `layouts/` → Templates
- `assets/scss/` → Styles
- `assets/imgs/` → Site-wide images
- `static/` → Unprocessed assets
- `hugo.toml` → Site settings

## Colophon - notes from Gina

This page uses [Bootstrap](https://getbootstrap.com/) for layout and interaction, and a smidge of [jQuery](https://jquery.com/) to reflect the current week on the map.

The font is [Red Hat Display](https://fonts.google.com/specimen/Red+Hat+Display). Colors chosen via [Color Hunt](https://colorhunt.co/). Edited in [Zed](https://zed.dev).
