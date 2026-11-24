# RuneBones website

Static site for RuneBones, served by GitHub Pages at https://paulissta.github.io/runebones/.

| Page | URL | Used as |
| --- | --- | --- |
| `index.html` | https://paulissta.github.io/runebones/ | Website URL |
| `terms.html` | https://paulissta.github.io/runebones/terms.html | Terms of Service URL |
| `privacy.html` | https://paulissta.github.io/runebones/privacy.html | Privacy Policy URL |
| `callback.html` | https://paulissta.github.io/runebones/callback.html | Login Kit redirect URI (Web) |

`callback.html` forwards the sign-in result (`?code&state`, or `?error`) to RuneBones Studio running on the user's computer at `http://127.0.0.1:<port>/callback`. The port is the first part of `state` (`<port>.<random>`), and it defaults to 3455.

URL ownership: verify by URL prefix `https://paulissta.github.io/runebones/`. The verification file goes in the root of this repo.
