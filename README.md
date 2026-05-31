# Potenciální energie

Interaktivní simulace volného pádu pro výuku fyziky. Porovnáváte energii dopadu (potenciální → kinetická) při různé gravitaci, hmotnosti a tvaru tělesa.

## Funkce

- **Prostředí:** Země (10 N/kg), Měsíc (1,6 N/kg), stav beztíže
- **Typ tělesa:** předměty (meloun, zlatá cihla, láhev, míč, kámen) nebo koule různého objemu a hmotnosti
- **Výška:** 0–2 m (slider nebo tažení ve scéně)
- **Přístroj:** zobrazení energie dopadu; vizuální elipsa „gravitace“ ve scéně
- **Přepnutí prostředí** zachová aktuální výšku předmětu

## Spuštění

Projekt načítá SVG přes `fetch`, proto ho otevírejte přes lokální server (ne `file://`).

```bash
npm install
npm run dev
```

Aplikace běží na [http://127.0.0.1:8766/index.html](http://127.0.0.1:8766/index.html).

## Online verze

Po pushi na `main` se aplikace automaticky nasadí na GitHub Pages:

[https://frantisekvvb.github.io/potencialni_energie/](https://frantisekvvb.github.io/potencialni_energie/)

## Struktura

```
potencialni_energie/
├── index.html      # aplikace (HTML, CSS, JS)
├── assets/         # grafika scény a předmětů
├── package.json
└── README.md
```

## Technologie

- Čisté HTML, CSS a JavaScript (bez buildu)
- [live-server](https://www.npmjs.com/package/live-server) pro vývoj

## Licence

Soukromý vzdělávací projekt — upravte licenci podle potřeby před zveřejněním.
