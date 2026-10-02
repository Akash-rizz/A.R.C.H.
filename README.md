# A.R.C.H. — Complete Fixed Build

This build fixes the mobile failure where the 3D scene was blank and SEND did nothing.

Fixes:
- UI/command handler is protected from 3D startup failures.
- Three.js loads from jsDelivr, then falls back to unpkg.
- If both CDNs fail, local commands still work and the page reports a 3D fallback state.
- No API key or server is required.

Upload this `index.html` over the current GitHub Pages `index.html`, then hard-refresh the page.
