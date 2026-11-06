# Polymetrický Metronom (PWA)

Kompletní Progressive Web App metronomu optimalizovaná pro displeje mobilních telefonů.

## Obsah balíčku
- `index.html`: Samostatná aplikace s Web Audio syntézou, lookahead plánovačem a responzivním UI.
- `manifest.json`: Web App Manifest definující ikony, barvy tématu a samostatný (standalone) režim zobrazení.
- `sw.js`: Service Worker pro kompletní offline provoz a ukládání do mezipaměti.
- `icon-192.png` & `icon-512.png`: PWA ikony optimalizované pro Android launchery.

## Jak zprovoznit a nainstalovat na Pixel
1. **GitHub Pages (nejjednodušší):**
   - Vytvořte nový GitHub repozitář a nahrajte do něj všechny soubory z tohoto archivu.
   - V `Settings -> Pages` zapněte publikování z větve `main`.
   - Otevřete vygenerovanou URL v Chrome na Pixelu a klepněte na „Instalovat“.

2. **Lokální server přes USB:**
   - Spusťte ve složce lokální HTTP server: `python3 -m http.server 8000`
   - Přes Chrome DevTools (`chrome://inspect/#devices`) nastavte port forwarding portu `8000`.
   - V mobilu otevřete `http://localhost:8000` a zvolte Instalovat.
