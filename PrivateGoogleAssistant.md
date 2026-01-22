# Private Google Assistant

Want to use Google Assistant without making your Home Assistant Instance public or paying for Home Assistant Cloud? Here is how!

According to the official [Home Assistant documentation](https://www.home-assistant.io/integrations/google_assistant/), if you don't want to pay for Home Assistant Cloud "your Home Assistant configuration has to be externally accessible with a hostname and SSL certificate". However you can use Cloudflare Tunnels to only allow Google to communicate with your Home Assistant Instance but you will need to own a domain.

## Prerequisites
- Domain Ownership
- Cloudflare Account

## How To

### Cloudflare Domain Setup
First off you need to setup your domain on Cloudflare. Follow the instructions on the Cloudflare Overview page and setup the Cloudflare Nameservers on your Domain's DNS.

### Cloudflare
You will need to setup Cloudflare One in order to setup a Tunnel.

**PLEASE NOTE: Cloudflare One will ask for Credit Card / Billing Details. This will NOT charge you anything on the free tier and it's just for verification reasons.**

Go to **Networks -> Connectors** and click **Create New Tunnel**
