<div align="center">

# Hi, I'm Kamlesh aka Kyren Marunate 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code\&pause=1000\&color=00BFFF\&center=true\&vCenter=true\&width=600\&lines=AI+Madness;Creative+Mess;Lifelong+Gamer;Digital+Art+Lover;Building+Ideas+Into+Reality)](https://git.io/typing-svg)

AI enthusiast, creative thinker, and lifelong gamer.
Building projects, exploring new tech, and blending code with creativity. 🚀🤖🎮🎨


</div>

---

## ✨ About Me

* 🤖 Exploring Artificial Intelligence
* 🚀 Building side projects and experimenting
* 🎮 Gamer at heart
* 🎨 Digital art and creative design enthusiast
* 📚 Always learning new technologies
* 💡 Turning "What if?" into "Why not?"

---

## ⚡ Tech Stack

### Frontend

[![My Skills](https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind,vite)](https://skillicons.dev)

### Backend & Database

[![My Skills](https://skillicons.dev/icons?i=nodejs,express,python,mpngodb,supabase,postgres)](https://skillicons.dev)

### Tools & Platforms

[![My Skills](https://skillicons.dev/icons?i=git,github,vscode,figma,vercel)](https://skillicons.dev)

### Creative Tools

[![My Skills](https://skillicons.dev/icons?i=ps,ae,unrealengine)](https://skillicons.dev)

---

## 📊 GitHub Stats

name: Update GitHub Stats

on:
  schedule:
    # Every 6 hours
    - cron: "0 */6 * * *"

  workflow_dispatch:

  push:
    paths:
      - ".github/workflows/profile-stats.yml"

permissions:
  contents: write

jobs:
  stats:
    runs-on: ubuntu-latest

    steps:

      - name: Checkout profile repository
        uses: actions/checkout@v6

      - name: Generate GitHub Stats
        uses: stats-organization/github-readme-stats-action@v2
        with:
          card: stats
          options: username=${{ github.repository_owner }}&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF
          path: profile/stats.svg
          token: ${{ secrets.GITHUB_TOKEN }}

      - name: Generate Top Languages
        uses: stats-organization/github-readme-stats-action@v2
        with:
          card: top-langs
          options: username=${{ github.repository_owner }}&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9
          path: profile/top-langs.svg
          token: ${{ secrets.GITHUB_TOKEN }}

      - name: Commit updated cards
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"

          git add profile/*.svg

          git commit -m "📊 Update GitHub stats" || exit 0

          git push

---

## 🔥 GitHub Streak

<p align="center">
<img src="https://streak-stats.demolab.com?user=KyrenMarunate&theme=tokyonight"/>
</p>

---

## 📈 Contribution Graph

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=KyrenMarunate&theme=tokyo-night"/>
</p>

---

## 🏆 GitHub Trophies

<p align="center">
<img src="https://github-profile-trophy.vercel.app/?username=KyrenMarunate&theme=tokyonight&row=1&column=7"/>
</p>

---

## 🌐 Connect With Me

* 💼 LinkedIn: [KamleshLink](https://www.linkedin.com/in/kamlesh20mishra)
* 📧 Email: YOUR_EMAIL
* 🌍 Portfolio: [LordKyren](https://www.lordkyren.me/)

---

<div align="center">

### 🚀 Building cool things, one commit at a time.

![](https://komarev.com/ghpvc/?username=KyrenMarunate\&color=blue)

</div>
