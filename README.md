# Guest activities website

Four small web pages, one per activity on the Weekly Guest Activities poster.
Each QR code on the poster opens one of them.

| Activity | Folder |
|---|---|
| Mini Cooking Class | `cooking/` |
| Cultural Excursion: Wiang Kum Kam | `excursion/` |
| Thai Dessert Making | `dessert/` |
| Thai Herbal Drink Making | `herbal-drink/` |

**Never rename or move these folders:** the printed QR codes point to them,
and would stop working.

## Add the hotel's photos

Put up to three photos per activity in `photos/`, with exactly these names
(`.jpg` or `.webp`):

- `cooking-1.jpg`, `cooking-2.jpg`, `cooking-3.jpg`
- `excursion-1.jpg`, `excursion-2.jpg`, `excursion-3.jpg`
- `dessert-1.jpg`, `dessert-2.jpg`, `dessert-3.jpg`
- `herbal-drink-1.jpg`, `herbal-drink-2.jpg`, `herbal-drink-3.jpg`

Photo 1 comes first. Any shape is fine (tall recipe cards too): the page
shows each photo whole, and a tap opens it full size. A missing photo is
simply left out; with none at all, the page says "Photos coming soon".

- JPG, about 1000 to 1600 px wide and under 500 KB each, so pages open fast
  on mobile data.
- No guest's face unless that guest agreed: these pages are public.

## Fill in the blanks

Words in [BRACKETS] on a yellow mark are blanks: time, price, meeting
point. Open each folder's `index.html` and replace them with the real facts.
