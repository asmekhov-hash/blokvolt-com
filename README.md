# blokvolt.com

Regional English-language hub for BlokVolt — home EV charging for apartment-building
residents. Static site, no build step, served by GitHub Pages on the apex domain.

- The Serbian product site is separate and lives on Webflow at https://www.blokvolt.rs
- This site: brand presence outside Serbia, country routing, SEO, and the
  procurement page used in supplier outreach (`/partners/`).

## Structure

    index.html                     home + country picker
    serbia/                        service is live -> hands over to blokvolt.rs
    montenegro/ ...                markets not open yet, honest interest pages
    partners/                      wallbox manufacturers, distributors, installers
    assets/                        mark + favicon
    CNAME                          blokvolt.com

Editing is plain HTML; pages are generated from one template so the shell stays
identical across them.
