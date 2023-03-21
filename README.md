## Hello, World!
 <div>
    <img align="right" alt="Julia-pic" height="150" width="150" style="border-radius:50px;" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjxj1JWX_LLspuOkqePVIH7y0Qod2pQbewWe0yVKe3fxXbaTO8BoIhtNYt_nZ_4waKKKhgNF5Ya-1yicVS9L6Mgw8AMsSFgJJ61RmFZQEMvLg2VEI0fnEkh9MYUmCpL2sYhu-BlT7BompHDHtpqzFW0rkU3BpWD2H_uuEuL1pnFHIIQRXQNcX8I1H8fug/s320/Meu%20GIF.gif?width=676&height=676">
</div>
- 'm Julia!

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/juliasofreio/)](https://www.linkedin.com/in/juliasofreio/) 
 
  ##
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
      # Summary Cards
      - uses: actions/checkout@v2
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          USERNAME: ${{ github.repository_owner }}

      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
![Snake animation](https://github.com/juliasofreio/juliasofreio/blob/output/github-contribution-grid-snake.svg)
##

#### Languages and Tools:
<div style="display: inline_block"><br>
  <img align="center" alt="Julia-Python" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="Julia-Csharp" height="70" width="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain-wordmark.svg">
 </div>
 
##
<div>
    <a href="http://github.com/juliasofreio">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=juliasofreio&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
