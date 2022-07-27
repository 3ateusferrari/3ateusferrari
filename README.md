![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=3ateusferrari&theme=moltack&show_icons=true)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=3ateusferrari&layout=compact&theme=moltack&show_icons=true)](https://github.com/3ateusferrari/github-readme-stats)

</div>
<div style="display: inline_block"><br>
  <img align="center" alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Python" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
          
           
name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: 3ateusferrari
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
