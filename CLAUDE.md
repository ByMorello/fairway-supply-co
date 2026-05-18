# Fairway Supply Co. — Regler for Claude Code

## Designsystem
- Bakgrunn: #F5F4EF (aldri ren hvit #FFFFFF)
- Primærgrønn: #0F3B2E
- Sekundærgrønn: #184D3B
- Sort: #111111
- Heading-font: Cormorant Garamond (Google Fonts)
- Body-font: Jost (Google Fonts)
- Border-radius: maks 3–4px
- Ingen box-shadows
- Ingen drop-shadows
- Aldri ren svart #000000 som tekstfarge

## Responsivt design — ALLTID
Hver eneste endring i style.css skal inkludere 
responsive regler for disse tre breakpoints:
- Desktop: 1440px (standard)
- Nettbrett: 768px (@media max-width: 1024px)
- Mobil: 375px (@media max-width: 480px)

Dette er ikke valgfritt. Alle nye seksjoner, 
endringer i layout, padding, font-størrelse og 
grid skal ha tilsvarende regler for alle tre 
skjermstørrelser.

## Tone og språk
- Alt innhold skrives på norsk
- Tone: rolig, selvsikker, underspilt
- Ingen hype, ingen overdrivelse

## Generelle regler
- Aldri bruk inline styles — alt går i style.css
- Aldri bruk !important
- Kommenter seksjoner tydelig i CSS
- Behold eksisterende klassenavn med mindre du 
  har god grunn til å endre dem

## Typografi — orddeling
Aldri bruk automatisk orddeling (hyphens) noe sted på siden.
Alle elementer skal ha:
hyphens: none;
-webkit-hyphens: none;
word-break: normal;
Overskrifter (h1-h6) skal alltid ha word-break: keep-all;
Dette gjelder alle fremtidige endringer uten unntak.
