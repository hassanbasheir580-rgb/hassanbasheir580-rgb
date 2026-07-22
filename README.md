<h1 align="center">Hi, I'm Simon Lecoq 👋</h1>

<p align="center">
  <a href="https://simon.lecoq.io"><img src="https://img.shields.io/badge/website-simon.lecoq.io-blue?style=flat-square"></a>
  <a href="https://metrics.lecoq.io"><img src="https://img.shields.io/badge/metrics-metrics.lecoq.io-brightgreen?style=flat-square"></a>
  <img src="https://img.shields.io/badge/Developer%20Program-Member-purple?style=flat-square">
</p>

<p align="center"><i>Weird or wired?</i></p>

---

### 🚀 About me

- 🔭 Maintainer of **[lowlighter/metrics](https://github.com/lowlighter/metrics)**
- 📈 GitHub metrics rendered live below — powered by my own tool
- 🌐 Portfolio: [simon.lecoq.io](https://simon.lecoq.io)
- 🛠️ Metrics playground: [metrics.lecoq.io](https://metrics.lecoq.io)

---

### 📊 GitHub Metrics

<!--START_SECTION:metrics-->
<p align="center">
  <img src="https://raw.githubusercontent.com/lowlighter/metrics/master/examples/6-showcase.classic.svg" alt="GitHub metrics" width="100%">
</p>
<!--END_SECTION:metrics-->

> Generated automatically with [`lowlighter/metrics`](https://github.com/lowlighter/metrics) — see the workflow setup below to render your own.

---

### 🧩 Mastered technologies & topics

<p align="left">
  <img src="https://skillicons.dev/icons?i=js,ts,html,css,vue,react,nodejs,python,cpp,rust,go,docker,git,github,linux,raspberrypi,firefox,figma,notion,powershell,bash,ios,androidstudio" />
</p>

---

### 🎧 Currently vibing to

- Bipolar Nightmare — Keigo Hoashi
- Mutter — Rammstein

---

### ⚙️ How this README works

This profile README is powered by the **[Metrics](https://github.com/lowlighter/metrics)** GitHub Action, which generates an SVG (or PDF/JSON) card with:

- Profile stats (repos, followers, stars, forks, watchers)
- Contribution calendar & streaks
- Commit activity by hour/day
- Most used languages
- Suggested music tracks, PageSpeed Insights, and more via plugins

#### Quick setup

1. Create a workflow file at `.github/workflows/metrics.yml` in your `<username>/<username>` repository:

```yaml
name: metrics
on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches:
      - master

jobs:
  github-metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          filename: metrics.svg
          token: ${{ secrets.METRICS_TOKEN }}
          plugin_languages: yes
          plugin_habits: yes
          plugin_calendar: yes
          plugin_music: yes
          plugin_pagespeed: yes
          plugin_pagespeed_url: https://your-site.example
          plugin_stars: yes
          plugin_topics: yes
          plugin_projects: yes
```

2. Add a `METRICS_TOKEN` secret (a personal access token with `repo` and `read:user` scopes).
3. Embed the generated `metrics.svg` in this README between the `START_SECTION:metrics` / `END_SECTION:metrics` markers.
4. Commit — the Action will keep the image refreshed on the schedule you set.

---

<p align="center"><sub>Made with ❤️ and a bit of automation.</sub></p>
