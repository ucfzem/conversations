# Session du 31 mai 2026 — Partie 2 (soir)

**Sujet :** Fix final — image & drawing fonctionnent  
**Corrections :**
- `inline_data` → `inlineData` (camelCase Gemini) — débloque l'onglet Image
- `system_instruction` séparé dans le proxy — l'IA respecte mieux les consignes
- Fallback Groq `llama-3.2-11b-vision-preview` → décommissionné → switch vers `meta-llama/llama-4-scout-17b-16e-instruct` (vision OK)
- `system_draw` amélioré : "Analyse précisément ce dessin (traits, formes, composition, éléments)"
- `system_img` amélioré : "Décris précisément cette image (couleurs, formes...)"
- System prompt principal : "Base-toi STRICTEMENT sur le texte ou l'image fourni(e)"
- Texte utilisateur préservé : `{ contents }` au lieu de `{ prompt }`

**Résultat final :** Les 3 modes (Texte, Image, Dessin) fonctionnent ✅  
**URL :** https://promptgenius.azer-tyu199p.workers.dev/

**Projet suivant évoqué :** Flash/ActionScript (reporté)
