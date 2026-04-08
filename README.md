# coffee-app-legal

Legal documents for **Sipfolk** (privacy policy, terms of service, data deletion), published via [GitHub Pages](https://stephsung.github.io/coffee-app-legal/).

## Languages

| Language | Index | Documents |
|----------|-------|-----------|
| 繁體中文 | [index.html](index.html) | `privacy_policy.html`, `terms_of_service.html`, `data_deletion.html` |
| English | [index_en.html](index_en.html) | `privacy_policy_en.html`, `terms_of_service_en.html`, `data_deletion_en.html` |

The mobile app opens the correct file based on the user’s in-app language (see `EXPO_PUBLIC_LEGAL_BASE_URL` / default `https://stephsung.github.io/coffee-app-legal` in the Sipfolk app).

## Update workflow

1. Edit HTML in this repo (or sync from the main app repo’s `legal/` folder).
2. Fill in the “最後更新” / “Last updated” dates before release.
3. Commit and push `main`; GitHub Pages will refresh shortly.

## App repository

Source copies of these pages also live under `legal/` in the Sipfolk application project.
