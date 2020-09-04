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
    link_text: The Black Death
  - link: "/podcast.html"
    link_text: Podcast
  - link: "/team.html"
    link_text: Team

- template: hero-banner-w-image
  block: hero-2
  headline: <a href="/Pandemic/covid.html"><strong>COVID-19</strong></a> vs <a href="/Pandemic/plague.html"><strong>The Black Death</strong></a>
  content: An analysis into the similarities and<br>differences of two widespread diseases. 
  cta:
    enabled: true
    url: https://github.com/Freddychu222/Pandemic
    button_text: 'Hosted on GitHub'
  image:
    image: "/uploads/faceplaguemask.jpg"
    alt_text: Product Shot
  background_image: "/uploads/2018/06/21/hero-2-bg.png"

- template: 1-column-text
  block: one-column-1
  headline: Welcome! 
  content: There are interesting parallels to be drawn between the present day pandemic of COVID-19 and the medieval plague of the Black Death. Using a side-by-side comparison, this website hopes to offer a better insight into the spread of diseases and their effects. 

- template: full-width-media-element
  block: media-1
  image: "/uploads/intro.png"
  caption: <strong>COVID-19 Mural by Will Phillips (left), Triumph of Death by Pieter Bruegel (right)</strong>

- template: detail-content
  block: two-column-1
  col_1: 
    headline: Virus /ˈvīrəs/
    content: <p style="text-align:left;">(noun) an infective agent that typically consists of a nucleic acid molecule in a protein coat, is too small to be seen by light microscopy, and is able to multiply only within the living cells of a host.</p>
  col_2:
    headline: Plague /plāɡ/
    content: <p style="text-align:right;">(noun) a contagious bacterial disease characterized by fever and delirium, typically with the formation of buboes (bubonic plague) and sometimes infection of the lungs (pneumonic plague).</p>

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/cov_img.jpg"
    caption: Caused by the virus <strong>SARS-CoV-2</strong></p>
  image_2: 
    image: "/uploads/plague_img.jpg"
    caption: Caused by the bacteria <strong>Yersinia pestis</strong></p>
    
- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/covidspread.gif"
    caption: COVID-19 Spread in the United States
  image_2: 
    image: "/uploads/plaguespread.png"
    caption: Black Death Spread in Europe

- template: detail-content
  block: two-column-2
  headline: Spread
  col_1: 
    content: <p style="text-align:left;">Most commonly spread from person-to-person by inhalation of respiratory droplets into the lungs. Based on current transmission rates, the virus is spreading easily and sustainably between people. Estimations place its infectivity between the flu and measles. Risk of animal to human transmission is considered to be very low.</p>
  col_2:
    content: <p style="text-align:right;">Most commonly spread from contaminated/infected animals. People were bitten by infected fleas (fleas get it from infected rodents) and came into contact with contaminated animal tissue. In some cases, humans who have developed pneumonic plague can transmit the plague in an aerosol form through cough droplets, but this was much rarer.</p>

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/covidspread.jpg"
    caption: COVID-19 Spread by WHO region 
  image_2: 
    image: "/uploads/plaguespread.jpg"
    caption: Black Death Spread by Population

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/la_death.png"
    caption: Cumulative deaths in the county of Los Angeles since the start of COVID-19
  image_2: 
    image: "/uploads/london_death.jpg"
    caption: Cumulative deaths in the city of London on 4 separate epidemics of the Black Death

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/covidmortality.jpg"
    caption: COVID-19 Hazard by Age
  image_2: 
    image: "/uploads/plaguemortality1.jpg"
    caption: Black Death Mortality by Age 

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/econ.png"
    caption: <Strong>Consensus Forecasts of Global GDP(%)- </Strong>Covid-19 has caused the larget global recession in modern history since the Great Depression, as shown by the red dip in the graph above. Economic activity in advanced economies are projected to shrink up tp 7% as well by the end of the year. 
  image_2: 
    image: "/uploads/death.png"
    caption: <Strong>England's Economic Impact and Population During the Plague- </Strong>As indicated in the graph, In the mid 15th Century, England's Population dipped to below 50% of what it was in 1270 (in red), and the GDP went down with it (in black). It's interesting to note that so many people died that it actually inflated their per capita GDP (in green). 

- template: detail-content
  block: two-column-2
  headline: Effect
  col_1: 
    content: <ul style="text-align:left;"><li>Flu-like symptoms<ul><li>Fever/Chills<li>Cough<li>Fatigue<li>Muscle/Body Aches<li>Headaches</ul><li>Sore Throat, Cough<li>Congestion/Runny Nose<li>Nausea/Vomiting<li>Diarrhea<li>Shortness of Breath/Difficulty Breathing<li>Loss of taste/smell</ul>
  col_2:
    content: <ul style="direction:rtl;text-align:right;"><li>Bubonic Plague<ul><li>Flu-like symptoms + swollen lymph nodes (buboes)<li>Results from being bitten by infected fleas</ul><li>Septicemic Plague<ul><li>Flu-like symptoms + abdominal pain + internal bleeding + tissue death<li>Results from untreated bubonic plague or handling infected animals</ul><li>Pneumonic Plague<ul><li>Flu-like symptoms + severe pneumonia<li>Results from inhaling infected droplets from infected individuals or when untreated plague spreads to lungs<li>Only form of plague that can spread person-person</ul></ul>

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/covidprotection.jpg"
    caption: COVID-19 Protective Gear
  image_2: 
    image: "/uploads/plagueprotection.jpg"
    caption: Black Death Protective Gear

- template: detail-content
  block: two-column-2
  headline: Protection
  col_1: 
    content: <ul style="text-align:left;"><li>Maintain social distance (at least 6ft)<li>Wash your hands with soap and water or with 60%+ alcohol hand sanitizer<li>Clean and disinfect potentially contaminated surfaces<li>Wear a mask</ul>
  col_2:
    content: <ul style="direction:rtl;text-align:right;"><li>Make your home and outbuildings rodent-proof<li>Wear gloves when handling potentially infected animals<li>Wear insect repellent to keep rodent fleas away, DEET + Permethrin containing products are effective repellents<li>Keep fleas off your pets<li>Because of lack of individuals infected with pneumonic plague, most don’t have to worry about measure to prevent  human to human transmission</ul>

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/prev_rona.png"
    caption: COVID-19 Protective Gear
  image_2: 
    image: "/uploads/prev_plague.jpg"
    caption: Black Death Protective Gear

- template: full-width-media-element
  block: media-1
  image: "/uploads/winewindow.jpg"
  caption: Medieval ‘wine windows’ are reopening, reviving Italian plague tradition.

- template: full-width-media-element
  block: media-1
  image: "/uploads/other_plague.png"
  caption: Covid Mortality Rate vs Past Epidemics. 

- template: full-width-media-element
  block: media-1
  image: "/uploads/final_compare.jpg"
  caption: <strong>More on plagues throughout history!</strong>

# - template: full-width-media-element
#   block: media-1
#   image: "/uploads/2018/06/21/theme.png"
#   caption: All Available Blocks
---
foo bar