Opa, tudo bem? Meu nome é Leandro Mendes.


- 🔭 Hoje trabalho com Back-end
- 🌱 Estudando .Net.
- 📫 Contata-me: llmendes133@gmail.com
- 😄 Ele/dele
  



  <img align="center" alt="Leo-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Leo-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="Leo-Csharp" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
>
</div>




    # Snake Animation
  - uses: Platane/snk@master
    id: snake-gif
    with:
      github_user_name: LLM3ndes
      svg_out_path: dist/github-contribution-grid-snake.svg
  - uses: crazy-max/ghaction-github-pages@v2.1.3
    with:
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
