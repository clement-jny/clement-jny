# Hey everyone 👋, I'm Clément

### A passionate student full-stack developer from France.

### I've been learning to code for 5 years, after switching careers. I started with HTML, but have really found a passion for backend development...

* 🌍  I'm based in Lille
* 🖥️  See my portfolio [here](http://clement-jny.github.io/)
* 📫  You can contact me at [](mailto:)
* 🚀  I'm currently working on [emiliemphotographie](https://github.com/clement-jny/emiliemphotographie)
* 🧠  I'm currently learning NextJs, TypeScript
* 🤝  I'm open to collaborating on web projets, ...
* ⚡   I'd be delighted to talk to you

### Connect with me:

<p align="left">
	<a href="https://www.linkedin.com/in/clement-jaunay" target="_blank" rel="noreferrer">
		<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" />
	</a>

	<a href="https://discord.com/users/WlinT3rn_" target="_blank" rel="noreferrer">
		<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/discord.svg"
			width="36" height="36" alt="Discord" />
	</a>
</p>

### 🛠 Languages and tools













<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=clement-jny&show_icons=true&locale=en&layout=compact" alt="clement-jny" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=clement-jny&show_icons=true&locale=en" alt="clement-jny" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=clement-jny&" alt="clement-jny" /></p>








###

<h3 align="left">🔥 My Stats :</h3>

###

<div align="center">
  <img src="https://streak-stats.demolab.com?user=maurodesouza&locale=en&mode=daily&theme=dark&hide_border=false&border_radius=5&order=3" height="220" alt="streak graph"  />
</div>






### Badges

<b>My GitHub Stats</b>

<a href="http://www.github.com/clement-jny"><img src="https://github-readme-stats.vercel.app/api?username=clement-jny&show_icons=true&hide=&count_private=true&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&show_icons=true" alt="clement-jny's GitHub stats" /></a>

<a href="http://www.github.com/clement-jny"><img src="https://github-readme-streak-stats.herokuapp.com/?user=clement-jny&stroke=ffffff&background=1c1917&ring=0891b2&fire=0891b2&currStreakNum=ffffff&currStreakLabel=0891b2&sideNums=ffffff&sideLabels=ffffff&dates=ffffff&hide_border=true" /></a>

<a href="http://www.github.com/clement-jny"><img src="https://github-readme-activity-graph.cyclic.app/graph?username=clement-jny&bg_color=1c1917&color=ffffff&line=0891b2&point=ffffff&area_color=1c1917&area=true&hide_border=true&custom_title=GitHub%20Commits%20Graph" alt="GitHub Commits Graph" /></a>

<a href="https://github.com/clement-jny" align="left"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=clement-jny&langs_count=10&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&locale=en&custom_title=Top%20%Languages" alt="Top Languages" /></a>



<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=clement-jny" alt="clement-jny" /></a> </p>


<img src="https://raw.githubusercontent.com/clement-jny/clement-jny/output/snake.svg" alt="Snake animation" />

``` yml
name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
