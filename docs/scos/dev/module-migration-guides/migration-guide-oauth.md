---
title: Migration guide - Oauth
description: Use the guide to update versions to the newer ones of the Oauth module.
last_updated: May 20, 2022
template: module-migration-guide-template
---

## Upgrading from version 1.* to version 2.0.0

In this new version of the `Oauth` module, we have added the support of the new `league/oauth2-server` major version (`^8.0.0`).

*Estimated migration time: 5 minutes*

Upgrade the `Oauth` module to the new version:

```bash
composer require spryker/oauth: "^2.0.0" --update-with-dependencies
```
