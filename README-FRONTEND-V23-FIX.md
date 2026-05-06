# Shule AI Frontend v23 - New Backend Fix

This frontend-only package fixes the GitHub Pages frontend connection.

## Fixed
- Replaced old backend URL:
  `https://shuleaibackend-32h1.onrender.com`
- New backend URL:
  `https://shule-ai-backend.onrender.com`
- Forces stale `SHULE_API_BASE_URL` localStorage values to the new backend.
- WebSocket now uses the same backend base URL.
- Fixed `currentUser().role` null crash in `rollout-fixes-v17.js`.

## Upload to GitHub Pages
Upload/commit everything in this folder to your frontend repository, then hard refresh the browser with Ctrl+Shift+R.
