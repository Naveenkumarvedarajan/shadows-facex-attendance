# FaceX browser demo — GitHub Pages upload

This package contains the upstream FaceX `docs/demo` static demo and its local assets, placed at the repository root so relative asset paths work on GitHub Pages.

## Publish
1. Upload all files in this ZIP to the root of your `shadows-facex-attendance` repository.
2. Commit to `main`.
3. In Settings → Pages, choose Deploy from a branch, branch `main`, folder `/(root)`.
4. Open `https://naveenkumarvedarajan.github.io/shadows-facex-attendance/`.

## Important
This is the FaceX demo only. It does not connect to Google Apps Script attendance or payroll. Do not use face verification for payroll until a real adapter has been implemented and tested. The demo loads ONNX Runtime Web from jsDelivr, so that external CDN must be reachable. Keep your attendance app's `Code.gs`, spreadsheet IDs, admin PINs, and secrets out of this repository.
