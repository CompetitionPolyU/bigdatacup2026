# IEEE BigData Cup 2026 — Suicide Risk Assessment on Social Media

Website for the IEEE BigData 2026 Cup Challenge: **Suicide Risk Assessment on Social Media (SRAM)**.

Live at: [www.bigdatacompetition.cn](https://www.bigdatacompetition.cn) and [competitionpolyu2026.github.io](https://competitionpolyu2026.github.io)

---

## Files

| File | Description |
|------|-------------|
| `index.html` | Main competition page |
| `guidelines.html` | Paper submission guidelines |

## Deployment (GitHub Pages)

1. Create a new GitHub repository named `<your-org>.github.io` (or any name, then enable Pages in Settings).
2. Push these files to the `main` branch.
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**.
4. The site will be live at `https://<your-org>.github.io`.

## Custom Domain (www.bigdatacompetition.cn)

1. Add a file named `CNAME` to the repo root containing:
   ```
   www.bigdatacompetition.cn
   ```
2. In your domain registrar's DNS settings, add a CNAME record:
   - **Host:** `www`
   - **Value:** `<your-org>.github.io`
3. In GitHub Pages settings, enter `www.bigdatacompetition.cn` under Custom Domain and enable HTTPS.

DNS propagation typically takes a few minutes to a few hours.

---

Organized by the **EventCube Research Group**, Department of Computing, The Hong Kong Polytechnic University.
