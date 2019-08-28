---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_BoasObras.jpg
widget1:
  title: "Conheça sobre nós"
  url: /sobre/quem-somos/
  image: quem-somos.jpg
  text: 'Ajudar o próximo é o que nos motiva e nossa missão é distribuir subsídios e amor para a comunidade de Campinas. Venha conhecer mais sobre a gente 😃'
widget2:
  title: "Atividades e Campanhas"
  url: /atividades/
  image: atividades.jpg
  text: 'Durante o ano inteiro, nós do <em>Boas Obras</em> realizamos atividades e campanhas de arrecadação. Quer conhecê-las ou nos sugerir novas ideas?'
widget3:
  title: "Torne-se voluntário(a)!"
  url: /inscricao/
  image: inscricao.jpg
  text: 'Não nascemos voluntários, nos tornamos! Descubra como fazer parte do nosso grupo e faça <em>Boas Obras</em> conosco 💛💚💙💜💕'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /como-ajudar/
  text: Quero ajudar o Boas Obras com o que puder ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
