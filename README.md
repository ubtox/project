# ULTIMA WEB (GitHub Pages) — GPT‑5.2 / Gemini 3 Pro / Claude 4.5 / DeepSeek R1

Repo ultra-simple: **un seul fichier** `index.html` (GitHub Pages ready).

## Mise en ligne (3 minutes)
1. GitHub → New repository (ex: `ultima-web`)
2. Uploade `index.html` à la racine
3. Settings → Pages → Branch: `main` → Save
4. Ouvre le lien GitHub Pages

## Fonctionnalités
- Chat multi-LLM: OpenAI (GPT‑5.2), Gemini 3 Pro, Claude 4.5, DeepSeek R1
- `/img ...` → image via Pollinations (gratuit)
- TTS (lecture) + Dictée (si support navigateur)
- Upload d’image (Claude/Gemini) via base64
- Mode Agent (tools): `get_time`, `calc`, `http_get` (URL privées bloquées)

## Notes sécurité
- Les clés sont stockées dans **localStorage** (sur TON navigateur).
- Ne commit **jamais** tes clés dans GitHub.
- Certains providers peuvent être bloqués par CORS selon environnement; dans ce cas, utilise un proxy (Cloudflare Worker / Netlify Function).

## Raccourcis
- Entrée: envoyer
- Shift+Entrée: nouvelle ligne
