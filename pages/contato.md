---
layout: page
title: "Página de contato"
meta_title: "Falar conosco? Pra já! - Boas Obras"
subheadline: "É muito fácil falar com a gente 😉"
teaser: "Basta acessar alguma da páginas de nossas redes sociais (abaixo) ou entrar em contato pelo formulário."
header:
   image_fullwidth: "header_contato.jpg"
permalink: "/contato/"
---

<ul class="inline-list social-icons">
    {% for social_item in site.data.socialmedia %}
        <li><a href="{{ social_item.url }}" target="_blank" class="{{ social_item.class }}" title="{{ social_item.title }}"></a></li><br/>
    {% endfor %}
</ul>

## Faça a diferença conosco

Nos siga em nossas mídias sociais (que estão abaixo), dê uma conferida no nosso site **[Boas Obras ›][7]** ou ajude nosso código a melhorar no GitHub!

[![Acesse nosso Facebook!][1.1]][8]
[![Conecte com nosso GPlus][2.1]][9]
[![Melhore nosso código][3.1]][10]
[![Veja nosso insta][4.1]][11]
[![Conecte-se com nosso LinkedIn][5.1]][12]


## Sobre o site

Tema criado com &hearts; por [Phlow][6], editado por [Victor Neves][4] e com base em [Jekyll][5]. O site é open source e está sob licença [*MIT*][3].

<!-- Links utilizados nessa página -->

 [1]: http://www.prefeitura.sp.gov.br/cidade/secretarias/upload/assistencia_social/cecoas/AULA_2_SUAS_e_a_protecao_social_a_pessoa_com_deficiencia.pdf
 [2]: https://en.wikipedia.org/wiki/Think_globally,_act_locally
 [3]: https://github.com/BoasObras/boasobras.github.io/blob/master/LICENSE
 [4]: https://www.linkedin.com/in/nevesvictor/
 [5]: http://jekyllrb.com/
 [6]: http://phlow.de/
 [7]: http://boasobras.org/
 [8]: http://fb.com/grupoboasobras
 [9]: http://plus.google.com/
 [10]: https://github.com/BoasObras
 [11]: https://www.instagram.com/grupoboasobras/
 [12]: http://www.linkedin.com/

<!-- Imagens utilizados nessa página -->

 [1.1]: https://github.com/BoasObras/boasobras.github.io/blob/master/assets/socialmedia-icons/facebook.png (facebook icon with padding)
 [2.1]: https://github.com/BoasObras/boasobras.github.io/blob/master/assets/socialmedia-icons/google-plus.png (google plus icon with padding)
 [3.1]: https://github.com/BoasObras/boasobras.github.io/blob/master/assets/socialmedia-icons/github.png (github icon with padding)
 [4.1]: https://github.com/BoasObras/boasobras.github.io/blob/master/assets/socialmedia-icons/instagram.png (instagram icon with padding)
 [5.1]: https://github.com/BoasObras/boasobras.github.io/blob/master/assets/socialmedia-icons/linkedin.png (linkedin icon with padding)


<div class="container">  
  <form id="contact" action="https://docs.google.com/forms/d/e/1FAIpQLScDUWZ5_611hGMtf1PwYq3odKSosQMfv6IhU8ludpWfjNSnbA/formResponse" method="post">
    <fieldset>
      <input name="entry.292932745" placeholder="Seu nome" type="text" tabindex="1" required autofocus>
    </fieldset>
    <fieldset>
      <input name="entry.741816157" placeholder="Seu e-mail" type="email" tabindex="2" required>
    </fieldset>
    <fieldset>
      <textarea name="entry.1374242095" placeholder="Digite sua mensagem aqui..." tabindex="3" required></textarea>
    </fieldset>
    <fieldset>
      <button name="submit" type="submit" id="contact-submit" data-submit="...Enviando">Enviar</button>
    </fieldset>
  </form>
</div>

