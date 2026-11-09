# app-policies

Public repo that hosts the privacy policies of my apps through GitHub Pages: `https://jadevelopr.github.io/app-policies/<app>/`.

## Layout
```
index.md             list of apps
setlist-live/        one folder per app, named after the app's final name
  index.md           that app's privacy policy
_config.yml          Pages theme
```

## Rules
- **Everything here is public.** Only policies, nothing else.
- **URLs are permanent.** They are pasted into Play Console, so never rename or move an app folder.
- One folder per app with its own policy, because each policy must match that app's real data practices.
- To add an app: create `<app>/index.md`, add a row to `index.md`.
- Source for the Setlist Live policy is `docs/PRIVACY_POLICY.md` in the private SetlistApp repo; copy changes here and update the "Last updated" date.
