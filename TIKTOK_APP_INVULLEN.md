# TikTok-app "Brotrading": wat je waar invult

De site staat op `https://brotradingnl.github.io/` (GitHub-gebruiker brotradingnl).

| Veld | Invullen |
|---|---|
| App icon | `icon.png` uit deze map (1024x1024) |
| App name | Brotrading |
| Category | Tools (of "Lifestyle" als Tools er niet staat) |
| Description | Brotrading publishes my own daily NQ/ES futures trading session recaps (post, carousel and story images) to my own TikTok account after manual approval. Educational content only, not financial advice. |
| Terms of Service URL | `https://brotradingnl.github.io/terms.html` |
| Privacy Policy URL | `https://brotradingnl.github.io/privacy.html` |
| Platforms | Web en Desktop aanvinken; Website URL: `https://brotradingnl.github.io/` |
| Products | Login Kit + Content Posting API (Direct Post aan) |
| Scopes | `user.info.basic`, `video.upload`, `video.publish` |
| Login Kit Redirect URI | `https://brotradingnl.github.io/callback.html` |
| URL properties (domain verification) | URL-prefix `https://brotradingnl.github.io/` (TikTok geeft een bestand om te uploaden) |

## Sandbox
Zet de schakelaar op **Sandbox**, maak een sandbox aan en voeg onder **Target users** je echte TikTok-account toe.

## Client key / secret
Komt op de app-pagina te staan. Zet zelf in `C:\ATAS_Claude\notifier_config.json`:
```
"tiktok_client_key": "...",
"tiktok_client_secret": "..."
```
Niet in de chat plakken.
