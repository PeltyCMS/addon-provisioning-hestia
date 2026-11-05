# HestiaCP

Auto-provision HestiaCP from PeltyCMS orders

Official provisioning module for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Providers who sell hosting, VPS, game panels or cloud and need auto-create on payment.

## Features

- Create services on **HestiaCP** when the customer pays
- Suspend, unsuspend and terminate follow the Pelty service lifecycle
- Map Pelty products to packages / plans on the remote panel
- API tokens stay in Pelty secrets
- MythicCloud panel linking for authenticated installs

## How it works

1. Install **HestiaCP** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/provisioning-hestia) inside Pelty Admin → Addons.
2. Open Pelty Admin → Products, map a product to the HestiaCP module, and save API credentials.
3. Customers hit checkout / login / order flow as usual — HestiaCP runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working HestiaCP credentials
- Outbound HTTPS from your panel

## Get it

**[HestiaCP on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/provisioning-hestia)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
