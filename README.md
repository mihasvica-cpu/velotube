# VELOTUBE Android projekt

To je pripravljen Android projekt za aplikacijo **VELOTUBE**.

## Kaj dela
- odpre `https://velotube.kolesar.ski/`
- omogoča prijavo in shranjevanje seje v WebView
- podpira nazaj gumb
- zunanje povezave (`mailto:`, `tel:` in druge zunanje domene) odpre izven aplikacije
- podpira osnovni file chooser iz WebView
- ima preprost splash / launcher izgled

## Pomembno
V ZIP-u, ki si ga poslal, je bil viden predvsem backend (`index.js`) in prazen `public`, zato je ta Android app nastavljen tako, da odpira **živo spletno stran**.

## GitHub Actions build APK
1. Na GitHubu odpri zavihek **Actions**.
2. Izberi workflow **Build VELOTUBE APK**.
3. Klikni **Run workflow**.
4. Po koncu odpri workflow run in prenesi artifact **VELOTUBE-debug-apk**.

## Ime paketa
- `ski.kolesar.velotube`

## Kje spremeniš URL
Datoteka:
- `app/src/main/res/values/strings.xml`

Vrednost:
- `base_url`
