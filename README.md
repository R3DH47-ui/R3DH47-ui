<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:0e4429,100:00ff41&height=220&section=header&text=R3dh47&fontSize=70&fontColor=00ff41&fontAlignY=38&desc=Frontend%20Dev%20%7C%20Cybersecurity%20%26%20Networking%20Explorer&descAlignY=58&descSize=18&descColor=39ff14&animation=fadeIn" alt="header banner"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=39FF14&center=true&vCenter=true&width=700&lines=%3E+Turning+packets+into+pixels+by+day...;%3E+Exploring+cybersecurity+vulnerabilities+by+night...;%3E+Wake+up%2C+Neo...+the+matrix+has+you+%F0%9F%92%8A;%3E+Always+learning+something+new+%F0%9F%8C%B1" alt="Typing SVG" />

<img src="https://komarev.com/ghpvc/?username=r3dh47-ui&label=Profile%20Views&color=00ff41&style=for-the-badge" alt="profile views" />
<img src="https://img.shields.io/github/followers/r3dh47-ui?label=Followers&style=for-the-badge&color=00ff41&logo=github" alt="followers" />

</div>

<br/>

<!-- 🐍 Matrix-style contribution snake — dynamic, regenerates on every push via GitHub Actions -->
<div align="center">
<img src="https://raw.githubusercontent.com/r3dh47-ui/r3dh47-ui/output/github-contribution-grid-snake-dark.svg" alt="contribution snake animation" width="100%"/>
</div>

> ⚙️ **Setup note:** the snake animation above needs a one-time GitHub Action (it's what makes it move/regenerate automatically). See the **"Make it live"** section at the bottom — it's copy-paste, ~2 minutes.

<br/>

## 🧑‍💻 About Me

```yaml
whoami:     R3dh47
role:       Frontend Developer | Cybersecurity & Networking Explorer
learning:   [C, JavaScript, Networking, Website & APK Development]
ask_me:     Networking
contact:    r3dhat404@gmail.com
fun_fact:   "Turning packets into pixels by day, hunting vulnerabilities by night 🛡️💻"
```

<div align="center">

<a href="https://instagram.com/ogpain00" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
<a href="mailto:r3dhat404@gmail.com"><img src="https://img.shields.io/badge/Email-00ff41?style=for-the-badge&logo=gmail&logoColor=black" alt="Email"/></a>

</div>

<br/>

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=android,c,css,html,linux,python,unity,js,git&theme=dark" alt="tech stack icons"/>

</div>

<br/>

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=r3dh47-ui&show_icons=true&count_private=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=39ff14&text_color=c9d1d9&border_radius=12" alt="GitHub Stats" height="180"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=r3dh47-ui&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9&border_radius=12" alt="Top Languages" height="180"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=r3dh47-ui&theme=highcontrast&hide_border=true&background=0d1117&ring=00ff41&fire=39ff14&currStreakLabel=00ff41&border_radius=12" alt="Streak Stats"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=r3dh47-ui&theme=react-dark&hide_border=true&bg_color=0d1117&color=39ff14&line=00ff41&point=ffffff&area=true&area_color=00ff41" alt="Contribution Activity Graph" width="100%"/>

</div>

<br/>

## 🏅 Achievements

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=r3dh47-ui&theme=matrix&no-frame=true&no-bg=true&row=2&column=4&margin-w=15&margin-h=15" alt="trophies"/>

</div>

<br/>

## 🚀 Featured Projects

<div align="center">

<table>
<tr>
<td width="50%">

<a href="https://github.com/r3dh47-ui/repo-one">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=r3dh47-ui&repo=repo-one&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=39ff14&text_color=c9d1d9&border_radius=12" alt="Featured Project 1"/>
</a>

</td>
<td width="50%">

<a href="https://github.com/r3dh47-ui/repo-two">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=r3dh47-ui&repo=repo-two&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=39ff14&text_color=c9d1d9&border_radius=12" alt="Featured Project 2"/>
</a>

</td>
</tr>
</table>

</div>

> ✏️ Replace `repo-one` / `repo-two` with your real, case-sensitive repo names. Add more `<td>` cells (2 per `<tr>`) for extra projects — 4–6 total keeps the grid clean.

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff41,100:0f2027&height=120&section=footer" alt="footer wave"/>

<i>Thanks for stopping by — feel free to explore my pinned repos and reach out! 🚀</i>

</div>

---

<details>
<summary>⚡ Make the snake animation live (one-time, ~2 min)</summary>

<br/>

1. In your **profile repo** (`r3dh47-ui/r3dh47-ui`), go to **Settings → Actions → General** and make sure Actions are enabled.
2. Create `.github/workflows/snake.yml` with:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch: {}
  push:
    branches: [ main ]

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: r3dh47-ui
          outputs: |
            dist/github-contribution-grid-snake-dark.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Push it — the Action creates an `output` branch with the SVG, which is exactly what the `<img>` at the top of this README points to. It'll regenerate every 6 hours automatically.

</details>
