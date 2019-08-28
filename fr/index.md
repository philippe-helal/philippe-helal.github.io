---
layout: landing
title: Philippe Helal
excerpt: >
  Candidat à la maîtrise en informatique, Université de Montréal

permalink: /fr/index.html
lang: fr
fncontact-id: philippe-helal-fr

article_header:
  actions:
    - text: Projets
      type: outline-theme-dark
      url: "/fr/#projets"
    - text: Bio
      type: outline-theme-dark
      url: "/fr/#bio"
    - text: Blog
      type: outline-theme-dark
      url: "/fr/#blog"
    - text: Contact
      type: outline-theme-dark
      url: "/fr/#contact"
  
  height: 100vh
  theme: dark
  background_color: "#367a9a"
  background_image:
    gradient: "linear-gradient(rgba(0, 0, 0, .2), rgba(0, 0, 0, .6))"
    src: https://source.unsplash.com/daily?nature,dark  
    

data:  
  sections:
    - id: projets
      title: Projets en cours
      fade-in: down
      children:
        - title: PassTheTorch
          excerpt: Outils permettant des projets de<br>Machine Learning reproduisibles et mesurables
          actions:
            - text: '<i class="fab fa-github"></i> GitHub'
              url: https://github.com/ctrl-q/pass-the-torch
        
        - title: apify
          excerpt: Librarie client pour l'API apify.com
          actions:
            - text: '<i class="fab fa-github"></i> GitHub'
              url: https://github.com/ctrl-q/apify

        - title: jekyll-TeXt-theme
          excerpt: Ajouts au projet de Tian Qi.<br>Thème utilisé sur ce site
          actions:
            - text: '<i class="fab fa-github"></i> GitHub'
              url: https://github.com/ctrl-q/jekyll-TeXt-theme

        - title: ml
          excerpt: Divers modèles Machine Learning
          actions:
            - text: '<i class="fab fa-github"></i> GitHub'
              url: https://github.com/ctrl-q/ml


    - id: bio
      fade-in: down
      full_width: true
      title: Bio
      excerpt: <a href="https://pygy.co/phcvfr">Version complète</a>
      children:
        - title: Expérience
          excerpt: Modélisation prédictive, Intelligence d'affaire, Enseignement
        - title: Compétences développées
          excerpt: SQL, Python, Shell Linux, VBA
        - title: Éducation
          excerpt: Baccalauréat en Administration des affaires (2018) et M. Sc Informatique (prévu 2020)        
        - title:  Intérêts
          excerpt: Économique, Finance, Informatique
        
     
    - id: blog
      fade-in: down
      title: Blog
      children:
        - title: En construction  # TODO SHOULD HAVE HAVE LAST FOUR BLOG POSTS WITH IMAGE AND EXCERPT FOR EACH
          excerpt: Pour être averti au lancement, veuillez remplir le <a href="#contact">formulaire</a> avec '*blog*' pour message

    - id: contact
      fade-in: down
      title: Contact
      excerpt: <i class="fas fa-lock"></i> <a href="https://openpgpjs.org">Encrypté</a> avant l'envoi
      type: contact
      fields:
        - name: name
          label: name
          text: 'Nom '
          placeholder: Nom (facultatif)
        - name: email
          type: email
          label: email
          text: '<br>Adresse courriel '
          placeholder: Adresse courriel (obligatoire)
          required: true
        - name: message
          label: message
          tag: textarea
          style: "height:200px"
          encrypt: true
          required: true
          placeholder: Message (obligatoire)
        - name: url_success
          type: hidden
          value: "https://philippe-helal.github.io/fr/contact-success"
        - name: url_error
          type: hidden
          value: "https://philippe-helal.github.io/fr/contact-error"
        - name: submit
          type: submit
          value: Submit
---
