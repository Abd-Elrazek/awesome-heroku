
![](https://d3k90kvix375hb.cloudfront.net/assets/home/hero/startup@2x-7d19c0222639db59ac497178719016583e1c886ac83eff67670d2c7584513620.png)

# Awesome Heroku [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of helpful Heroku resources.


## Table of Contents

- [Analytics](#analytics)
- [Deployment](#deployment)
- [Domains](#domains)
- [Meta](#meta)
- [Security](#security)
- [Toolbelt](#toolbelt)
- [Goodbye...](#goodbye)


## Analytics

- `tool` [Metabase](http://www.metabase.com/docs/v0.13.3/operations-guide/running-metabase-on-heroku.html) — a beta of Metadata as an app that can be deployed directly to Heroku.


## Architecture

- `article` [Heroku and SOA](https://www.rdegges.com/2014/heroku-and-soa/) — discusses why Heroku is perfectly suited to building a service-oriented architecture for your projects.


## Deployment

- `article` [Automating our Heroku deployments from Jenkins](https://www.paulfurley.com/automating-heroku-deployments-from-jenkins/) — explains how you'd go about automating certain parts of deployment like enabling maintenance mode, copying your database from production to staging, running migrations against staging, etc.
- `question` [How do you ignore files when deploying to Heroku?](http://stackoverflow.com/questions/12523435/how-do-i-ignore-folders-and-files-when-pushing-to-heroku-with-a-rails-app) — the answer to a common question about `.gitignore` like functionality.


## Domains

- `article` [Hosting multiple Heroku apps on a single domain](https://pilot.co/blog/hosting-multiple-heroku-apps-on-a-single-domain/) — an article on how to share the same domain between multiple Heroku applications.
- `question` [How do you host multiple Heroku apps on a single domain?](http://stackoverflow.com/questions/19119164/multiple-heroku-apps-on-a-single-domain) — a StackOverflow question with a few responses to a the common question of how to serve multiple Heroku apps from different paths instead of subdomains.


## Meta

- `official` [The big kickoff](https://blog.heroku.com/archives/2007/10/30/the_big_kickoff) — the first ever Heroku blog article.
- `article` [Heroku isn't for idiots](https://www.rdegges.com/2012/heroku-isnt-for-idiots/) — explains Heroku's advantages and why it's not just for side projects.
- `article` [My Heroku values](https://brandur.org/heroku-values) — a great series of takeaways from [Brandur Leach](https://twitter.com/brandur) when he left Heroku.
- `book` [The Heroku Hacker's Guide](http://www.theherokuhackersguide.com/) — an ebook that covers a lot of the basics in maintaining and scaling a project on Heroku.


## Postgres

- `official` [Importing and Exporting Databases](https://devcenter.heroku.com/articles/heroku-postgres-import-export) — the official way to 


## Scaling

- `tool` [HireFire](https://www.hirefire.io/) — a SaaS tool that automatically scales your Heroku dynos up and down as load requires.


## Security

- `article` [Set up CloudFlare's free SSL on Heroku](https://robots.thoughtbot.com/set-up-cloudflare-free-ssl-on-heroku) — walks you through the exact steps to setting up free SSL via Cloudflare.


## Toolbelt

- `official` [Toolbelt Download](https://toolbelt.heroku.com/) — where to download the Heroku toolbelt.
- `plugin` [heroku-accounts](https://github.com/ddollar/heroku-accounts) — makes it easy to work with multiple accounts at once from the command line.
- `plugin` [heroku-pg-extras](https://github.com/heroku/heroku-pg-extras) — a toolbelt plugin that adds extra useful plugins for working with Postgres. Things like analyzing cache hit rates, outlier queries, unused indexes, table sizes, etc.


## Goodbye...

- `tool` [dokku](http://dokku.viewdocs.io/dokku/) — a self-hosted, docker-based, Heroku-compliant platform.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ian Storm Taylor](http://ianstormtaylor.com) has waived all copyright and related or neighboring rights to this work.
