# Expert Doors (Astro)

Strona WWW firmy **Expert Doors** (montaż drzwi i bram garażowych w Szczecinie i okolicach).

## Start

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Struktura

- `src/components/OrbitGarageLogo.astro` – animowane logo
- `src/layouts/MainLayout.astro` – główny layout strony
- `src/styles/globals.css` – globalne style
- `src/pages/expert-doors.astro` – strona główna
- `src/pages/drzwi-wejsciowe.astro`
- `src/pages/drzwi-segmentowe.astro`
- `src/pages/drzwi-wewnetrzne.astro`
- `src/pages/automatyka-bram.astro`
- `src/pages/serwis-i-regulacje.astro`
- `src/pages/montaz-i-pomiar.astro`
- `src/pages/oferta-cenowa.astro`
- `src/pages/pobierz-aplikacje.astro`
- `src/pages/polityka-prywatnosci.astro`
- `src/pages/regulamin.astro`


## Edycja zdjęć i linków (szybka instrukcja)

### 1) Jak dodać własne zdjęcia realizacji na stronie głównej
Wgraj pliki JPG do folderu:

- `public/images/expert-doors/realizacje/`

Nazwy, które są już podpięte w kodzie:

- `realizacja-01.jpg`
- `realizacja-02.jpg`
- `realizacja-03.jpg`
- `realizacja-04.jpg`
- `realizacja-05.jpg`
- `realizacja-06.jpg`

Po podmianie plików odśwież stronę — zdjęcia zastąpią placeholdery automatycznie.

### 2) Jak zmienić linki inspiracji Castorama na podstronach
Linki są w plikach `src/pages/*.astro` przy sekcjach `service-gallery` (tagi `<a href="...">`).

Najczęściej edytowane pliki:
- `src/pages/drzwi-wejsciowe.astro`
- `src/pages/drzwi-segmentowe.astro`
- `src/pages/drzwi-wewnetrzne.astro`
- `src/pages/automatyka-bram.astro`
- `src/pages/serwis-i-regulacje.astro`
- `src/pages/montaz-i-pomiar.astro`

W każdym z nich podmień adres w `href` na docelowy URL, np. do wybranej kategorii lub konkretnej oferty.