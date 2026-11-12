# ParkPaws

Amenity-first static directory of US dog parks and official off-leash areas.

ParkPaws pages emphasize **fencing, water, small-dog areas, hours, and local rules** over bare name+pin listings. Unknown amenities are labeled rather than invented.

## Live URLs

- **Primary:** https://parkpaws.vercel.app
- **Mirror:** https://spacemonkey-x.github.io/parkpaws/
- **Repo:** https://github.com/Spacemonkey-X/parkpaws

## Tree

```
parkpaws/
├── README.md
├── index.html              # Homepage (search placeholder, city hubs)
├── styles.css              # Shared styles
└── dog-parks/
    ├── texas/
    │   ├── austin/
    │   │   ├── index.html
    │   │   └── sources.md
    │   ├── san-antonio/
    │   │   ├── index.html
    │   │   └── sources.md
    │   ├── houston/
    │   │   ├── index.html
    │   │   └── sources.md
    │   ├── dallas/
    │   │   ├── index.html
    │   │   └── sources.md
    │   └── fort-worth/
    │       ├── index.html
    │       └── sources.md
    ├── california/
    │   ├── los-angeles/
    │   ├── san-diego/
    │   ├── long-beach/
    │   ├── irvine/
    │   ├── huntington-beach/
    │   ├── anaheim/
    │   ├── santa-ana/
    │   ├── riverside/
    │   ├── rancho-cucamonga/
    │   ├── corona/
    │   ├── san-francisco/
    │   ├── oakland/
    │   ├── san-jose/
    │   └── sacramento/
    │       (each: index.html + sources.md)
    └── colorado/
        ├── denver/
        ├── colorado-springs/
        ├── aurora/
        ├── fort-collins/
        ├── boulder/
        └── lakewood/
            (each: index.html + sources.md)
```

## Publishing

**Vercel** ([parkpaws.vercel.app](https://parkpaws.vercel.app)) is the primary host; **GitHub Pages** ([spacemonkey-x.github.io/parkpaws](https://spacemonkey-x.github.io/parkpaws/)) is the secondary mirror.

Nightly publishing adds and refreshes city/park pages under `dog-parks/{state}/{city}/`.  
Hand-built hubs so far: **Austin**, **San Antonio**, **Houston**, **Dallas**, **Fort Worth**, **Los Angeles**, **San Diego**, **Long Beach**, Orange County (**Irvine**, **Huntington Beach**, **Anaheim**, **Santa Ana**), Inland Empire (**Riverside**, **Rancho Cucamonga**, **Corona**), **San Francisco**, **Oakland**, **San Jose**, **Sacramento**, and Colorado (**Denver**, **Colorado Springs**, **Aurora**, **Fort Collins**, **Boulder**, **Lakewood**), and Arizona (**Phoenix**, **Mesa**, **Chandler**, **Scottsdale**). Subsequent cities follow the same pattern:

- SEO title + H1 aimed at “best dog parks in {city}”
- Intro with park count / permit notes from official sources
- Amenity cards or table (fenced / water / small-dog / hours / notes)
- Map placeholder → official or embedded map later
- FAQ grounded in public park-department rules
- “What to bring” affiliate-ready gear section (placeholder Amazon search URLs + FTC disclosure; **real affiliate IDs still TODO**)

## Local preview

Open in a browser:

- `/workspace/parkpaws/index.html`
- `/workspace/parkpaws/dog-parks/texas/austin/index.html`
- `/workspace/parkpaws/dog-parks/texas/san-antonio/index.html`
- `/workspace/parkpaws/dog-parks/texas/houston/index.html`
- `/workspace/parkpaws/dog-parks/texas/dallas/index.html`
- `/workspace/parkpaws/dog-parks/texas/fort-worth/index.html`
- `/workspace/parkpaws/dog-parks/california/los-angeles/index.html`
- `/workspace/parkpaws/dog-parks/california/san-diego/index.html`
- `/workspace/parkpaws/dog-parks/california/long-beach/index.html`
- `/workspace/parkpaws/dog-parks/california/irvine/index.html`
- `/workspace/parkpaws/dog-parks/california/huntington-beach/index.html`
- `/workspace/parkpaws/dog-parks/california/anaheim/index.html`
- `/workspace/parkpaws/dog-parks/california/santa-ana/index.html`
- `/workspace/parkpaws/dog-parks/california/riverside/index.html`
- `/workspace/parkpaws/dog-parks/california/rancho-cucamonga/index.html`
- `/workspace/parkpaws/dog-parks/california/corona/index.html`
- `/workspace/parkpaws/dog-parks/california/san-francisco/index.html`
- `/workspace/parkpaws/dog-parks/california/oakland/index.html`
- `/workspace/parkpaws/dog-parks/california/san-jose/index.html`
- `/workspace/parkpaws/dog-parks/california/sacramento/index.html`
- `/workspace/parkpaws/dog-parks/arizona/phoenix/index.html`
- `/workspace/parkpaws/dog-parks/arizona/mesa/index.html`
- `/workspace/parkpaws/dog-parks/arizona/chandler/index.html`
- `/workspace/parkpaws/dog-parks/arizona/scottsdale/index.html`
- `/workspace/parkpaws/dog-parks/colorado/denver/index.html`
- `/workspace/parkpaws/dog-parks/colorado/colorado-springs/index.html`
- `/workspace/parkpaws/dog-parks/colorado/aurora/index.html`
- `/workspace/parkpaws/dog-parks/colorado/fort-collins/index.html`
- `/workspace/parkpaws/dog-parks/colorado/boulder/index.html`
- `/workspace/parkpaws/dog-parks/colorado/lakewood/index.html`

Or serve the folder with any static file server.

## Data rules

1. Prefer City / Parks Department pages, then reputable local lists.
2. Do not invent addresses or amenity flags.
3. Cite sources in `sources.md` and/or an HTML comment on the city page.

## Affiliates

City hubs include a **What to bring to [City] dog parks** section with category cards
(waste bags, collapsible bowl, 6 ft leash, tick/flea prevention). Links currently point at
generic Amazon search URLs with `#affiliate-placeholder` — **do not treat them as live
Associates tags**. Replace with tagged product URLs (or another network) before relying on
revenue.

The homepage `#gear` section is a separate set of category search cards (waste bags,
collapsible water bowl, portable dog water bottle, standard leash, harness, treat pouch,
dog towel, and pet first aid kit) plus its own nav to each city’s gear section. Those
homepage links are plain Amazon searches — **real affiliate tags are not configured**.
