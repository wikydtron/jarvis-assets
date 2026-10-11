# Jarvis assets

This repository hosts `jarvis.png`. The image is available directly from GitHub without a build step.

## Use the existing image

The current image URL follows the `main` branch:

```text
https://raw.githubusercontent.com/wikydtron/jarvis-assets/main/jarvis.png
```

For example, in Markdown:

```markdown
![Jarvis](https://raw.githubusercontent.com/wikydtron/jarvis-assets/main/jarvis.png)
```

Use a commit-specific URL when a document needs the exact image version checked on October 11, 2026:

```text
https://raw.githubusercontent.com/wikydtron/jarvis-assets/3df47456a67d87e71c8c13b5e3d62258dd707ee7/jarvis.png
```

The branch URL can serve a newer image if the asset is updated later; the commit-specific URL identifies this version.

## Asset reference

| Property | Verified value |
| --- | --- |
| Repository path | [`jarvis.png`](jarvis.png) |
| Format | PNG |
| File size | 839,150 bytes |
| Git blob SHA-1 | `934f51865fac834f0e466d997e50722b1a752305` |

The raw URL returned HTTP 200 with `Content-Type: image/png` during the [availability check](https://github.com/wikydtron/jarvis-assets/issues/1).

## Keeping existing integrations working

Keep `jarvis.png` at its existing path when adding other assets. Renaming or moving it changes the URL used by existing integrations. Add a separately named file when an integration needs to opt in to a different image.
