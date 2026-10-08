KALKULÁTOR 3D TISKU – PWA (aplikace pro Android)

Obsah složky: index.html (aplikace), manifest.webmanifest, sw.js (offline režim), icons/ (ikony).
Složku nasaďte celou, soubory musí zůstat vedle sebe.

1) NASAZENÍ (jednou, zdarma)
   - Otevřete https://app.netlify.com/drop a přetáhněte celou rozbalenou složku.
   - Dostanete adresu https://něco.netlify.app. Alternativy: GitHub Pages, Cloudflare Pages.
   - Aplikace musí běžet na adrese https:// (offline režim jinak nefunguje).

2) INSTALACE V TELEFONU
   - V Chrome na Androidu otevřete adresu.
   - Menu ⋮ -> Instalovat aplikaci (nebo Přidat na plochu).
   - Ikona „Kalkulace 3D“ se objeví mezi aplikacemi a otevírá se na celou obrazovku.
   - Po prvním otevření funguje i bez internetu.

3) DŮLEŽITÉ
   - Katalog a zadané hodnoty se ukládají v telefonu pro danou adresu. Při změně adresy
     (jiný hosting) se nepřenesou.
   - Aktualizace: nahrajte nové soubory na stejnou adresu. Telefon si novou verzi stáhne
     na pozadí a použije ji při dalším otevření aplikace.
   - Při větší úpravě změňte v sw.js číslo verze (kalk3d-v1 -> kalk3d-v2).

