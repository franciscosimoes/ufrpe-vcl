---
title: Home
---

# UFRPE Visual Computing Laboratory

O UFRPE Visual Computing Lab é um laboratório de pesquisa situado no Departamento de Computação da Universidade Federal Rural de Pernambuco. Focado principalmente nas áreas de Visão Computacional e Computação Visual, o UFRPE-VCL atua em pesquisas de base e aplicadas em áreas como Sensoriamento Inteligente para a Indústria e o Agronegócio, Análises de Imagens Médicas, Cidades Inteligentes (Complementar Aqui).

{%
  include link.html
  type="home-page"
  icon=""
  text="Site do DC-UFRPE"
  link="http://www.dc.ufrpe.br/"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include figure.html image="images/ufrpe-vcl-logo-ai.png"%}

{% include section.html %}

# Highlights

{% capture text %}
As pesquisas do UFRPE-VCL geram resultados de alto impacto científico, sendo publicados em periódicos e eventos de alta relevância como Pattern Recognition Letters, Computers and Graphics, CVPRW, WACV, IJRS, CAG (COMPLETAR).

{%
  include link.html
  link="research"
  text="Veja nossas publicações"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research_ai.jfif"
  link="research"
  title="Nossa Pesquisa"
  text=text
%}

{% capture text %}
Nossas tecnologias estão disponíveis bla bla bla.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/tools_ai.jfif"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
Nosso time é composto por professores, pesquisadores e estudantes da UFRPE, com parcerias nacionais e internacionais para o desenvolvimento de pesquisas de ponta.

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/team_ai.jfif.jpg"
  link="team"
  title="Our Team"
  text=text
%}

*As imagens deste site foram criadas com a plataforma Dall-e3, acessada através do Bing Image Creator em 12/2023: link="https://www.bing.com/images/create/".
