# Shahab’s Aura

Offline-first study habits and Pomodoro PWA.

## Run locally

```bash
npm install
npm run dev
```

## Publish with GitHub Pages

1. Create a GitHub repository named **shahabs-aura**.
2. Upload these files or push them with Git.
3. In the project terminal, run:

```bash
npm install
npm run deploy
```

4. In GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: gh-pages → / (root) → Save**.
5. Your app will be at `https://shahabalamofficial-ship-it.github.io/shahabs-aura/`.

## iPhone install

Open the URL in Safari, tap Share, choose **Add to Home Screen**, then open it from the new icon.

## Important notification note

This app can request notification permission. Reliable scheduled notifications after the PWA is fully closed require a push-notification backend (server or service such as Firebase/OneSignal). Browser-only offline code cannot guarantee alarms at exact times on iPhone.
