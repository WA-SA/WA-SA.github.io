---
title: CNAME
description: Emits a CNAME file for custom domain deployment.
tags:
  - plugin/emitter
image:
repository: "[quartz-community/cname](https://github.com/quartz-community/cname)"
enabled: true
required: false
ctime: 2026-06-08T09:06
updated: 2026-06-08T09:06
---

This plugin emits a `CNAME` record that points your subdomain to the default domain of your site.

If you want to use a custom domain name like `quartz.example.com` for the site, then this is needed.

See [[hosting|Hosting]] for more information.

> [!note]
> For information on how to add, remove or configure plugins, see the [[configuration#Plugins|Configuration]] page.

This plugin has no configuration options.

## API

- Category: Emitter
- Function name: `ExternalPlugin.CNAME()`.
- Source: [`quartz-community/cname`](https://github.com/quartz-community/cname)
- Install: `npx quartz plugin add github:quartz-community/cname`
