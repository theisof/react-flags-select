# Add Flag

1. Add flag SVG to `/flags`, source: https://flagicons.lipis.dev/
2. Update `/src/data/countries.ts` with country/language code and label.
3. Run `npm run build`
4. Copy generated `build` folder to project `vendors`

Country codes must match SVG name (case insensitive). No underscore or special characters in country code. Must be two characters.
