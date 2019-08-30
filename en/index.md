---
layout: landing
title: Philippe Helal
excerpt: >
  Computer Science Graduate Student at Université de Montréal

permalink: /en/index.html
fncontact-id: philippe-helal-en
lang: en

article_header:
  actions:
    - text: Projects
      type: outline-theme-dark
      url: "#projects"
    - text: Resume
      type: outline-theme-dark
      url: "#resume"
    - text: Blog
      type: outline-theme-dark
      url: "#blog"
    - text: Contact
      type: outline-theme-dark
      url: "#contact"
  
  height: 100vh
  theme: dark
  background_color: "#367a9a"
  background_image:
    gradient: "linear-gradient(rgba(0, 0, 0, .2), rgba(0, 0, 0, .6))"
    src: https://source.unsplash.com/daily?nature,dark  
    

data:  
  sections:
    - id: projects
      title: Ongoing Projects
      fade-in: down
      children:
        - title: PassTheTorch
          excerpt: Framework for reproducible and trackable<br>Machine-Learning projects
          actions:
            - text: '<i class="fab fa-github"></i> GitHub'
              url: https://github.com/ctrl-q/pass-the-torch
        
        - title: apify
          excerpt: Unofficial client for the apify.com API
          actions:
            - text: '<i class="fab fa-github"></i> GitHub'
              url: https://github.com/ctrl-q/apify

        - title: jekyll-TeXt-theme
          excerpt: Tweaks to Tian Qi's work.<br>Theme used on this site
          actions:
            - text: '<i class="fab fa-github"></i> GitHub'
              url: https://github.com/ctrl-q/jekyll-TeXt-theme

        - title: ml
          excerpt: Collection of Machine-Learning<br>models & experiments
          actions:
            - text: '<i class="fab fa-github"></i> GitHub'
              url: https://github.com/ctrl-q/ml


    - id: resume
      fade-in: down
      full_width: true
      title: Resume
      excerpt: <a href="https://pygy.co/phcven">Full Version</a>
      children:
        - title: Experience
          excerpt: Predictive Modeling, Business Intelligence, and Teaching
        - title: Main skills
          excerpt: SQL, Python, Shell and VBA
        - title: Education
          excerpt: Bachelor's of Business Administration (2018) and M. Sc Computer Science (expected 2020)        
        - title:  Main Interests
          excerpt: Economics, Finance and Computer Science
        
     
    - id: blog
      fade-in: down
      title: Blog
      children:
        - title: Under construction  # TODO SHOULD HAVE HAVE LAST FOUR BLOG POSTS WITH IMAGE AND EXCERPT FOR EACH
          excerpt: To be notified when it launches, fill the <a href="#contact">contact form</a> with '*blog*' as the message

    - id: contact
      fade-in: down
      title: Contact
      excerpt: <i class="fas fa-lock"></i> Will be <a href="https://openpgpjs.org">encrypted</a> before leaving your network
      type: contact
      fields:
        - name: name
          label: name
          text: 'Name '
          placeholder: Name (optional)
        - name: email
          type: email
          label: email
          text: '<br>E-mail '
          placeholder: E-mail (required)
          required: true
        - name: message
          label: message
          tag: textarea
          style: "height:200px"
          encrypt: true
          required: true
          placeholder: Message (required)
        - name: url_success
          type: hidden
          value: "https://philippe-helal.github.io/en/contact-success"
        - name: url_error
          type: hidden
          value: "https://philippe-helal.github.io/en/contact-error"
        - name: submit
          type: submit
          value: Submit
---
