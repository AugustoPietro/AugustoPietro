uses: AugustoPietro/AugustoPietro
with:
  AugustoPietro: ${{ github.AugustoPietro }}

  #  supported options:
  #  - palette:     A preset of color, one of [github, github-dark, github-light]
  #  - color_snake: Color of the snake
  #  - color_dots:  Coma separated list of dots color.
  #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
  #                 Exactly 5 colors are expected.
  outputs: |
    dist/github-snake.svg
    dist/github-snake-dark.svg?palette=github-dark
    dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
