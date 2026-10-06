# iCosiSenpai Plugins per Jellyfin

Questa è la repository ufficiale (catalogo) dei plugin sviluppati da [iCosiSenpai](https://github.com/iCosiSenpai) per Jellyfin.

## Plugin Disponibili

1. **AnimeClick Metadata**: Provider di metadati anime in italiano basato su AnimeClick.it. **Richiede Jellyfin 12.0 o successivo**: le versioni 0.x per Jellyfin 10.x sono obsolete e non vengono più distribuite.
2. **KometaThemes**: Mette le sigle (OP/ED) degli anime da animethemes.moe sulle pagine di serie, stagioni e film. Richiede Jellyfin 12.

## Come installare la repository su Jellyfin

Per aggiungere questa repository al tuo server Jellyfin e poter installare i plugin direttamente dal pannello di controllo:

1. Vai nella **Dashboard** (Pannello di controllo) di Jellyfin.
2. Clicca su **Plugin** nel menu a sinistra.
3. Vai nella scheda **Repository**.
4. Clicca sul pulsante **+** per aggiungere una nuova repository.
5. Inserisci i seguenti dati:
   - **Nome repository:** `iCosiSenpai Plugins`
   - **URL repository:** `https://raw.githubusercontent.com/iCosiSenpai/iCosiSenpai-Plugins/main/manifest.json`
6. Salva e vai nella scheda **Catalogo**. Ora vedrai i plugin pronti per essere installati!

## Segnalazioni e Supporto

Se riscontri problemi o hai suggerimenti per uno dei plugin, apri una Issue nella repository specifica del plugin:
- [AnimeClick Plugin](https://github.com/iCosiSenpai/jellyfin-plugin-animeclick)
- [KometaThemes Plugin](https://github.com/iCosiSenpai/KometaThemes)
