# ParkPaws

Amenity-first static directory of US dog parks and official off-leash areas.

ParkPaws pages emphasize **fencing, water, small-dog areas, hours, and local rules** over bare name+pin listings. Unknown amenities are labeled rather than invented.

## Tree

```
parkpaws/
├── README.md
├── index.html              # Homepage (search placeholder, city hubs)
├── styles.css              # Shared styles
└── dog-parks/
    └── texas/
        ├── austin/
        │   ├── index.html  # Best Dog Parks in Austin, TX
        │   └── sources.md
        ├── san-antonio/
        │   ├── index.html  # Best Dog Parks in San Antonio, TX
        │   └── sources.md
        └── houston/
            ├── index.html  # Best Dog Parks in Houston, TX
            └── sources.md
```

## Publishing

Nightly publishing adds and refreshes city/park pages under `dog-parks/{state}/{city}/`.  
Hand-built hubs so far: **Austin**, **San Antonio**, and **Houston**. Subsequent cities follow the same pattern:

- SEO title + H1 aimed at “best dog parks in {city}”
- Intro with park count / permit notes from official sources
- Amenity cards or table (fenced / water / small-dog / hours / notes)
- Map placeholder → official or embedded map later
- FAQ grounded in public park-department rules
- Soft affiliate section (no fake links)

## Local preview

Open in a browser:

- `/workspace/parkpaws/index.html`
- `/workspace/parkpaws/dog-parks/texas/austin/index.html`
- `/workspace/parkpaws/dog-parks/texas/san-antonio/index.html`
- `/workspace/parkpaws/dog-parks/texas/houston/index.html`

Or serve the folder with any static file server.

## Data rules

1. Prefer City / Parks Department pages, then reputable local lists.
2. Do not invent addresses or amenity flags.
3. Cite sources in `sources.md` and/or an HTML comment on the city page.
