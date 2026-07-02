# DESIGN.md — Konoba Gušte v5 "Žar i krš" (Vodice)

register: brand
arhetip: PRESET 1 (konoba/steak house) s heritage tonom zaleđa — restraint set, tamni registar

## Koncept
Gušt (tal. *gusto*) = dalmatinska riječ za užitak. Steak house čiji jezik nije "USDA prime" nego šibensko zaleđe: krš, gromače, ognjište, gradele, dim. Konoba je u Vodicama — kuhinja i karakter su iz zaleđa. NE tvrditi da je objekt fizički u zaleđu.

## Paleta (izvedena iz komina i krša — NIJE v1 paleta)
- `--dim #1E1813` — topla dimna crna, zid uz komin (toplija od v1 #161210)
- `--dim-alt #282019` — karta/alt sekcija
- `--zar #C2571B` — žeravica pod gradelama (akcent; v1 je imao vinsko #9B3B2E — namjerno drugačije)
- `--krs #E8E0CF` — šibenski vapnenac (svijetli tekst na tamnom)
- `--trava #A08C5B` — suha trava i strnjika zaleđa (eyebrow/sekundarni)
- `--gradele #6E655A` — željezo gradela (linije, potpore)

## Fontovi (self-host woff2 — S3; različiti od Gušte v1–v4 i od Bare)
- Display: **Fraunces** (400/600 + italic 400) — topli "novi-stari" serif, mesnat, s karakterom
- Body: **Work Sans** (300/400/500)

## Hero (anti-kloniranje: SPLIT, ne fullbleed)
Split hero: lijevo tamni tekstni stupac (eyebrow VODICE · ŠIBENSKI KRAJ, H1, tagline, CTA), desno full-height fotografija plate s mesom (clip-path reveal + lagani parallax). Bare v7 = fullbleed svijetli; Gušte v1 = fullbleed tamni → v5 split = treći oblik.

## Potpisne interakcije (restraint, ≤2 scruba)
1. Clip-path reveal hero slike (ne-scrub, 1.2s)
2. Lagani parallax hero slike (1 scrub)
3. `.reveal` fade+24px po sekcijama (ne-scrub)
4. Ember-glow radial na tamnim sekcijama (statični CSS, diskretno)
5. Sensory hover na jelima ("/ dim / žar / sol")

## Dekorativni potpis (unikatan za Gušte)
SVG line-art SUHOZID divider (red kamenja) — izveden iz gromača zaleđa. Grain overlay 4%. Nikad ne koristiti na drugim klijentima (Bare ima barku/masline).

## Tvrda pravila
- Keyless mapa (S2) iza GDPR facade; self-host fontovi (S3); bez tajni (S1)
- ANTI-SLOP §1: cijene se NE prikazuju; jelovnik nosi vidljivu napomenu da je informativan; kontakt/satnica naslijeđeni iz v1/v4 + TODO[klijent]
- SEO/schema: Restaurant JSON-LD (Vodice)

## Stvarne činjenice (iz prijašnjih verzija — potvrditi s klijentom)
- Lokacija: Vodice (mapa: Konoba Gušte Vodice)
- Tel: +385 98 336 023 · Email: konoba@email.t-com.hr
- Radno vrijeme (iz v1): Pon–Pet 18–24, Sub 18–01, Ned 18–24

## Foto atribucija
- Suhozid: Mnalis, CC BY-SA 4.0, Wikimedia Commons (footer credit)
- Žar: CC0. Ostalo: Unsplash.
