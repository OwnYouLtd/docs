# The OwnYou docs are used to update OwnYou web documentation

Site is managed by OwnYou Ltd but feedback and contributions are welcome.

## Vision

We are building the core architecture for individuals to harvest their personal data, make it available to third party machine learning entities, extract and monetize  intelligent personal profiles, in a privacy preserving manner.

These docs will help you better understand our vision and how the architecture works.

We want this to remain an open source project and your contributions will bring OwnYou to life.

Ultimately, OwnYou will form the base personal data layer for intelligent personal AI. But before we get to that, we need to figure out:

- how to efficiently harvest all our personal data in secure decentralized storage 
- how to make that data available to third party machine learning algorythms 

## Architecture

There are a couple of ways you can dicuss new ideas and contributions to the architecture. You can drop into the relevant Discord channel or you can submit a new issue on this discord repo:

- [Intelligence Stack](https://discord.com/channels/960473414978646036/986321483884294315)
- [Distributed Computing]
- [Decentralized Storage]
- [Digital Advertising using OwnYou's privacy preserving, equitable, personal data]
- [Other applications that leverage intelligent privacy presersing personal data] 


## Contributions
Add your site and author details in `_config.yml`:
```yaml
# Site title and description
title:              Docs
description:        Documentation Jekyll theme.
lang:               en

# Site subpath, e.g. /blog
baseurl:            ""

# Permalink URLs structure, for permalink style options see: https://jekyllrb.com/docs/permalinks/
permalink:          /:title/

# Site base hostname & protocol, e.g. http://example.com
url:                ""

# Site logo # e.g. logo.png, upload logo image file to /uploads/ folder
logo:               

navbar:
  search:           true;
  
# Default author settings
author:
    name:           Pete Seth
    title:          Lead Developer  
    avatar:         avatar-tom.png
```

## Customization

To modify the primary color, open `/_sass/theme/variables.scss` and replace the color values e.g.:

```scss
$global-primary-background:                   #05c896;
```

Further style customisation can be done in the following files:
```
/_sass/theme/mixins.scss
/_sass/theme/variables.scss
/assets/css/main.scss
```

## Development

Install [UIkit](https://getuikit.com/) font end framework dependency via Npm:
```bash
npm install
```
Enable live browser reload with the following:
```bash
bundle exec jekyll s --livereload
```

## Credits and Sources

- Google analytics https://www.google.com/analytics/
- Google maps https://www.google.com/maps
- UIkit front end framework https://getuikit.com/
- Jekyll CML https://jekyllrb.com/

## Support
Customer support is provided through our Envato item page [contact form](https://themeforest.net/item/docs-responsive-documentation-manual-jekyll-theme/21131076/support) for up to six months from the purchase date and is provided Monday to Friday during the business week. We aim to answer all support requests daily, most are handled within 24h.

## Documentation
Full documentation can be found here: [https://jekyll-theme-docs.netlify.com/docs/installation/](https://jekyll-theme-docs.netlify.com/docs/installation/).
