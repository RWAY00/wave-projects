# WAVE Projects — YouTube-style Static Template

## Quick start
1. Fork this repo.
2. Replace `images/header.jpg` और `images/thumb-sample.jpg` अपनी images से बदल दें।
3. Edit `projects.json` में अपने प्रोजेक्ट्स डालें (GitHub UI से भी कर सकते हैं)।
4. GitHub → Settings → Pages → Branch: `main` (or gh-pages) select करके Pages enable करें।
5. Open yourpages.github.io/your-repo/ — site दिखना चाहिए।

## Admin settings (simple)
- Settings बटन देखने के लिए page URL में `?admin=1` जोड़ें (example: `https://<username>.github.io/<repo>/?admin=1`).
- Settings modal सिर्फ static JSON दिखाता है; persist करने के लिए `projects.json` edit कर के commit करें (GitHub UI से आसान)।

## आगे के steps (optional)
- Add a simple admin UI to edit `projects.json` and push commits via GitHub API (requires auth & server).
- Add serverless "play" proxy to host private playback or to run on-demand builds.
- Add search/indexing or categories.
