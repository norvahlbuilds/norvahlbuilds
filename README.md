## Haseeb

Designer and engineer. I run [Norvahl](https://github.com/norvahl), a one-person studio that builds custom software, websites and online stores for small businesses.

One person does both trades here. I draw it, I build it, and I am the one who answers when it breaks.

### What I work on

Lead routing that scores every crew on distance, tier and load, then hands an unclaimed lead to the next one after fifteen minutes. Quoting engines that price a job from the customer's own inputs and lock the number for a day. One inbox that reads email, forms, WhatsApp, SMS, chat and social as a single queue, drafting replies from the client's own pages. Client portals and the small internal tools that replace a shared spreadsheet.

Then the storefront side: WordPress, WooCommerce and Shopify, built or rescued, and kept fast afterwards.

### Things I have measured

I rebuilt a WooCommerce store for a sealer manufacturer and took it from 59 to a steady 94 to 95 on mobile PageSpeed, with the server's first byte cut from 1,870 ms to 337 ms and the plugin list from 63 to 32. Halfway through, the old site's database died and the job became a migration as well. [The whole story](https://norvahl.com/learn/seal-n-lock-woocommerce-speed).

I spent four working days on a live Shopify store carrying 29 apps and took it from about 60 to 91 to 95 on mobile, with no design change and every ad pixel and lead pipeline intact. [What came off, and why](https://norvahl.com/learn/resin-rock-shopify-speed).

That second job turned up a measurement defect in Google's PageSpeed test fleet that affects Shopify storefronts. It is reproduced on a two-page test, 0 of 5 runs held without Shopify's head code and 9 of 27 with it, and reported as [Lighthouse issue 17230](https://github.com/GoogleChrome/lighthouse/issues/17230) and on the [Shopify Community](https://community.shopify.com/t/storefront-head-code-delays-chromes-first-frame-by-1-2-s-on-googles-pagespeed-machines-reproducible-two-page-test/679801).

### Tools

Astro, Cloudflare Workers, D1, KV, R2, Durable Objects, Stripe, React Native with Expo, and the WordPress and Shopify stacks where a client already lives.

My own site carries 24 KB of JavaScript, no third-party requests and no cookies, and every page works with JavaScript switched off. It seemed a poor argument to sell speed from a slow site.

### Reach me

[norvahl.com](https://norvahl.com) · [hello@norvahl.com](mailto:hello@norvahl.com) · [LinkedIn](https://www.linkedin.com/in/chhaseebdotcom)
