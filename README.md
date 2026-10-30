# HRO Housing — hro housing ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `hrohousingltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/hrohousingltd.mjs`).
> To change the content, edit that file and run `node build.mjs hrohousingltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@hrohousingltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per room / $Per property / $Clarified) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
HRO Housing Ltd provides shared and other accommodation in Birmingham, trading since 2020. We let rooms and shared homes, manage them to the standards that apply to houses in multiple occupation, and keep the fire safety and condition requirements current. The rule that governs this work carries the heaviest penalty in private renting. A house in multiple occupation needs a licence, mandatory where five or more people in two or more households share, and often under additional or selective schemes a council has designated. Operating without one is an offence carrying an unlimited fine or a civil penalty, it can trigger a rent repayment order of up to twelve months' rent, and no section 21 notice can be served while the property is unlicensed. So we licence before we let. Site: hrohousingltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
