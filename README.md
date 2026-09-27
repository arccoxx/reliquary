# Reliquary / CORTEX-IR

Word ≠ Term. ConceptNet is a witness log, not a merge dictionary.
Play: `webgame/index.html` (PWA). Store: Python v0, `pytest` offline.

Canon: `docs/REQUIREMENTS_CANON.md` — last update sticks; older gates stay.

## iPhone
1. Enable Pages: Settings → Pages → Deploy from branch `main` / `webgame`.
2. Open the Pages URL in Safari.
3. Share → Add to Home Screen.
4. Export log from the game; iOS may evict localStorage.

## Windows (core, optional)
```powershell
cd C:\src\reliquary
py -3 -m pip install -e ".[dev]"
py -3 -m pytest
py -3 -m reliquary.cli load --store .\store
start webgame\index.html
```

Grok Build is a **terminal** CLI (`grok` after `grok login`), not a Grok chat side tab.
