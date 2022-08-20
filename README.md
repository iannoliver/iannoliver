😜EAI, qual é a boa? me chamo iann, prazer!
🤣Apenas testando projetos no tempo livre ou trabalhos sérios!!
👌*No caminho da programação!*

✔ - "Viva com orgulho. Se sua fraqueza o dominar, aqueça seu coração, cerre os dentes e siga em frente. Mesmo que sua covardia o retarde, não impedirá a passagem do tempo. Envelhecer e morrer é o que dá sentido e beleza ao tempo fugaz de uma vida humana. É exatamente porque envelhecemos e morremos que nossas vidas têm valor e nobreza."

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
          github_user_name: iannoliver
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}




![ ](https://github.com/iannoliver/iannoliver/blob/main/steamuserimages-a.akamaihd.net.gif)   ![ ](https://github.com/iannoliver/iannoliver/blob/main/ora-jojo.gif)

