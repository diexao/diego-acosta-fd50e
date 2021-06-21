---
title: Inicio
hide_title: true
sections:
  - section_id: hero
    type: section_hero
    title: 'Hola, soy Diego Acosta'
    content: |
      Acá estaré contándote un poco de mi y de lo que hago.
    actions:
      - label: Envíame un mensaje
        url: /contact
        style: button
  - section_id: latest-projects
    type: section_portfolio
    layout_style: mosaic
    title: Mis proyectos más recientes
    subtitle: Esto es lo último que he hecho
    projects_number: 6
    view_all_label: Ver todos
    view_all_url: portfolio
  - section_id: services
    type: section_grid
    title: Lo qué me gusta
    subtitle: Un poco de lo que sé y de lo que me gusta aprender
    col_number: two
    is_numbered: true
    grid_items:
      - title: Tecnología
        content: >
          Me encanta la tecnología y todo lo que se puede lograr con ella. Me
          gusta aprender y llegar a entender como podemos usarla en nuestro día
          a día.
      - title: Emprendimiento
        content: >
          Emprender es un acto de revolución y debemos entenderlos como tal,
          salir de la zona de confort y empezar por nuestra cuenta a resolver el
          problemas de los demás es una actitud que pocas personas pueden hacer.
      - title: Autoayuda
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam. Integer commodo sem at
          dui sollicitudin.
      - title: Autos y motos
        content: >
          Me encantan los autos y las motos, disfruto mucho de manejar y sentir
          la libertad de poder ir a cualquier parte y conocer nuevos lugares.
          Prefiero viajar en moto que en auto.
  - section_id: testimonials
    type: section_testimonials
    title: Testimonios
    subtitle: Lo que dicen de mi
    col_number: three
    testimonials:
      - author: Sean Salazar
        avatar: images/sean_salazar.jpg
        avatar_alt: Sean Salazar's photo
        content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla.
      - author: Aubrey Hoover
        avatar: images/aubrey_hoover.jpg
        avatar_alt: Aubrey Hoover's photo
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - author: Deegan Wallace
        avatar: images/deegan_wallace.jpg
        avatar_alt: Deegan Wallace's photo
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam.
  - section_id: latest-posts
    type: section_posts
    title: Lo último del Blog
    subtitle: Lo más reciente que he escrito
    posts_number: 3
    col_number: three
    actions:
      - label: Ir al Blog
        url: blog
        style: button
seo:
  title: diexao.com
  description: Me encanta la tecnología y el buen café.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: diexao.com
      keyName: property
    - name: 'og:description'
      value: Me encanta la tecnología y el buen café.
      keyName: property
    - name: 'og:image'
      value: /_static/app-assets/images/fotoperfilfeb2020.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: diexao.com
    - name: 'twitter:description'
      value: Me encanta la tecnología y el buen café.
    - name: 'twitter:image'
      value: /_static/app-assets/images/fotoperfilfeb2020.jpg
      relativeUrl: true
layout: advanced
---
