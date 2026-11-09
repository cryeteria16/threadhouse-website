# threadhousetrading.com

Website for Thread House Trading & Tailoring, Sharjah. Static HTML, hosted on GitHub Pages.

| Path | Page |
|---|---|
| `/` | Home |
| `/shop.html` | Laces & trims |
| `/product.html` | Product (guipure lace) |
| `/tailoring.html` | Tailoring services & booking |
| `/preview/` | Client preview with the four colour looks (not indexed by search engines) |

## Pointing the Namecheap domain at GitHub Pages

1. In Namecheap: **Domain List › Manage › Advanced DNS**.
2. Delete the default `CNAME www` and `URL Redirect` records Namecheap adds.
3. Add these records:

   | Type | Host | Value |
   |---|---|---|
   | A Record | `@` | `185.199.108.153` |
   | A Record | `@` | `185.199.109.153` |
   | A Record | `@` | `185.199.110.153` |
   | A Record | `@` | `185.199.111.153` |
   | CNAME Record | `www` | `<github-username>.github.io.` |

4. In the GitHub repository: **Settings › Pages**, check the custom domain shows `threadhousetrading.com`, wait for the DNS check to pass, then tick **Enforce HTTPS**.

DNS changes usually take 15 minutes to a few hours. The HTTPS certificate can take up to an hour after the DNS check passes.

## Before launch

The pages still contain placeholders in square brackets, such as `[Shop number, building, street]`, `[Opening days and hours]`, `[+971 phone number]` and some prices marked `[n]`. Search for `[` in the HTML files and replace them with the real details.
