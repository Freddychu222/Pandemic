---
layout: blocks
title: Homepage
date: 2020-11-22T23:00:00.000+00:00
page_sections:
- template: navigation-header #-w-button
  block: header-1
  logo: "/uploads/hist1blogo.jpg" #replace with hist 1b logo
  navigation:
  - link: "/"
    link_text: Home
  - link: "/covid.html" 
    link_text: COVID-19
  - link: "/plague.html"
    link_text: The Black Plague
  - link: "/other.html"
    link_text: Other Media
  - link: "/team.html"
    link_text: Team
- template: hero-banner-w-image
  block: hero-2
  headline: <strong>COVID-19</strong> vs <strong>The Black Plague</strong> 
  content: An analysis into the similarities and<br>differences of two widespread diseases. 
  cta:
    enabled: true
    url: https://github.com/Freddychu222/Pandemic
    button_text: 'Hosted on GitHub'
  image:
    image: "/uploads/faceplaguemask.jpg"
    alt_text: Product Shot
  background_image: "/uploads/2018/06/21/hero-2-bg.png"
- template: detail-content
  block: two-column-1
  col_1: 
    headline: Virus /ˈvīrəs/
    content: <p style="text-align:right;">(noun) an infective agent that typically consists of a nucleic acid molecule in a protein coat, is too small to be seen by light microscopy, and is able to multiply only within the living cells of a host.</p>
  col_2:
    headline: Plague /plāɡ/
    content: <p style="text-align:left;">(noun) a contagious bacterial disease characterized by fever and delirium, typically with the formation of buboes (bubonic plague) and sometimes infection of the lungs (pneumonic plague).</p>
- template: detail-content
  block: two-column-2
  headline: Causes
  col_1: 
    content: <p style="text-align:right;">Caused by the bacteria <strong>Yersinia pestis</strong></p>
  col_2:
    content: <p style="text-align:left;">Caused by the virus <strong>SARS-CoV-2</strong></p>
- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/covidspread.jpg"
    caption: COVID-19 Spread by WHO region 
  image_2: 
    image: "/uploads/plaguespread.jpg"
    caption: Black Death Spread by Population
- template: detail-content
  block: two-column-2
  headline: Spread
  col_1: 
    content: <p style="text-align:left;">Most commonly spread from contaminated/infected animals. People were bitten by infected fleas (fleas get it from infected rodents) and came into contact with contaminated animal tissue. In some cases, humans who have developed pneumonic plague can transmit the plague in an aerosol form through cough droplets, but this was much rarer.</p>
  col_2:
    content: <p style="text-align:right;">Most commonly spread from person-to-person by inhalation of respiratory droplets into the lungs. Based on current transmission rates, the virus is spreading easily and sustainably between people. Estimations place its infectivity between the flu and measles. Risk of animal to human transmission is considered to be very low.</p>
- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/covidmortality.jpg"
    caption: COVID-19 Hazard by Age
  image_2: 
    image: "/uploads/plaguemortality.jpg"
    caption: Black Death Mortality by Age 
- template: detail-content
  block: two-column-2
  headline: Effect
  col_1: 
    content: <ul style="text-align:left;"><li>Bubonic Plague<ul><li>Flu-like symptoms + swollen lymph nodes (buboes)<li>Results from being bitten by infected fleas</ul><li>Septicemic Plague<ul><li>Flu-like symptoms + abdominal pain + internal bleeding + tissue death.<li>Results from untreated bubonic plague or handling infected animals</ul><li>Pneumonic Plague<ul><li>Flu-like symptoms + severe pneumonia.<li>Results from inhaling infected droplets from infected individuals or when untreated plague spreads to lungs.<li>Only form of plague that can spread person-person</ul></ul>
  col_2:
    content: <ul style="direction:rtl;text-align:right;"><li>Flu-like symptoms<ul><li>Fever/Chills<li>Cough<li>Fatigue<li>Muscle/Body Aches<li>Headaches</ul><li>Sore Throat, Cough<li>Congestion/Runny Nose<li>Nausea/Vomiting<li>Diarrhea<li>Shortness of Breath/Difficulty Breathing<li>Loss of taste/smell</ul>
- template: detail-content
  block: two-column-2
  headline: Protection
  col_1: 
    content: <ul style="text-align:left;"><li>Make your home and outbuildings rodent-proof<li>Wear gloves when handling potentially infected animals<li>Wear insect repellent to keep rodent fleas away, DEET + Permethrin containing products are effective repellents.<li>Keep fleas off your pets<li>Because of lack of individuals infected with pneumonic plague, most don’t have to worry about measure to prevent  human to human transmission</ul>
  col_2:
    content: <ul style="direction:rtl;text-align:right;"><li>Maintain social distance (at least 6ft)<li>Wash your hands with soap and water or with 60%+ alcohol hand sanitizer<li>Clean and disinfect potentially contaminated surfaces<li>Wear a mask</ul>
- template: full-width-media-element
  block: media-1
  image: "/uploads/2018/06/21/theme.png"
  caption: All Available Blocks
- template: simple-footer
  block: footer-1
  content: Hello world! ❤︎

---
foo bar