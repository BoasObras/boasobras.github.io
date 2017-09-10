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

<style>
.container {
  width: 600px;
  margin: 2em auto;
  overflow: hidden;
  background: rgba(255,255,255,1);
  border-radius: 5px;
}

.message, .contact, .name, .footer, header, textarea  {
 display: block;
 padding: 0;
 margin: 0;
 border: 0;
 clear: both;
 overflow: hidden;
}

.first, .last {
  float: left;
  width: 278px;
  margin: 0;
  padding: 0 0 0 20px;
  border: 1px solid rgba(0,0,0,.1);
  height: 50px;
}

.last {
  width: 279px;
  border-left: 0;  
}

.email {
  height: 50px;
  width: 578px;
  line-height: 50px;
  padding: 0 0 0 20px;
  border-top: 0;
  border-left: 1px solid rgba(0,0,0,.1);
  border-right: 1px solid rgba(0,0,0,.1);
  border-bottom: 1px solid rgba(0,0,0,.1);
}

textarea {
  @extend .email;
  height: 200px;
}

footer {
  @extend header;
  height: 49px;
  border-top: 1px dashed rgba(0,0,0,.3);
  border-radius: 0 0 5px 5px;
  padding-left: 0;
  padding-right: 20px;
  
  button {
    height: 32px;
    background: rgba(231, 76, 60,1.0);
    border-radius: 5px;
    border: 0;
    margin: 7px 0;
    color: rgba(255,255,255,1);
    float: right;
    padding: 0 20px 0 20px;
    border-bottom: 3px solid rgba(192, 57, 43,1.0);
    transition: all linear .2s;
    
    &:hover {
      background: rgba(192, 57, 43,1.0);  
    }
    
    &:focus {
       outline: none; 
    }
  }
}

.first:focus, .last:focus, .email:focus, textarea:focus {
  outline: none;
  background: rgba(52, 152, 219,.1);
  color: rgba(51,51,51,.7);
}
</style>

.container
  %header
    %h1 Send us a suggestion! 
  .name
    %input.first{ :type => 'text', :placeholder => 'First Name'}
    %input.last{ :type => 'text', :placeholder => 'Last Name'}
  .contact
    %input.email{ :type => 'text', :placeholder => 'E-mail Address'}
  .message
    %textarea{ :placeholder => 'Your Suggestions Here!'}
  %footer 
    %button Send Suggestion
