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
  # cta:
  #   url: https://history.ucla.edu/
  #   button_text: UCLA History
- template: hero-banner-w-image
  block: hero-2
  headline: <strong>COVID-19</strong> vs <strong>The Black Plague</strong> # <br><strong>design blocks</strong>
  content: An analysis into the similarities and<br>differences of two widespread diseases. #The tool that allows you to build beautiful sites<br>all inside Forestry's content manager.
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
    content: (noun) an infective agent that typically consists of a nucleic acid molecule in a protein coat, is too small to be seen by light microscopy, and is able to multiply only within the living cells of a host.
  col_2:
    headline: Plague /plāɡ/
    content: (noun) a contagious bacterial disease characterized by fever and delirium, typically with the formation of buboes (bubonic plague) and sometimes infection of the lungs (pneumonic plague).
- template: detail-content
  block: two-column-2
  headline: Causes
  col_1: 
    content: Caused by the bacteria <strong>Yersinia pestis</strong>
  col_2:
    content: Caused by the virus <strong>SARS-CoV-2</strong>
- template: detail-content
  block: two-column-2
  headline: Spread
  col_1: 
    content: <p style="text-align:left;">Most commonly spread from contaminated/infected animals. People were bitten by infected fleas (fleas get it from infected rodents) and came into contact with contaminated animal tissue. In some cases, humans who have developed pneumonic plague can transmit the plague in an aerosol form through cough droplets, but this was much rarer.</p>
  col_2:
    content: <p style="text-align:left;">Most commonly spread from person-to-person by inhalation of respiratory droplets into the lungs. Based on current transmission rates, the virus is spreading easily and sustainably between people. Estimations place its infectivity between the flu and measles. Risk of animal to human transmission is considered to be very low.</p>
- template: detail-content
  block: two-column-2
  headline: Effect
  col_1: 
    content: <p style="text-align:left;"> - Bubonic Plague - Flu-like symptoms + swollen lymph nodes (buboes)<br>&emsp; - Results from being bitten by infected fleas<br> - Septicemic Plague - Flu-like symptoms + abdominal pain + internal bleeding + tissue death. <br>&emsp; - Results from untreated bubonic plague or handling infected animals<br> - Pneumonic Plague - flu -like symptoms + severe pneumonia. <br>&emsp; - Results from inhaling infected droplets from infected individuals or when untreated plague spreads to lungs. <br>&emsp; - Only form of plague that can spread person-person</p>
  col_2:
    content: <p style="text-align:left;"> - Flu-like symptoms (Fever/Chills, Cough, Fatigue, Muscle/Body Aches, Headaches)<br> - Sore Throat, Cough<br> - Congestion/Runny Nose<br> - Nausea/Vomiting<br>- Diarrhea<br> - Shortness of Breath/Difficulty Breathing<br> - Loss of taste/smell</p>
- template: detail-content
  block: two-column-2
  headline: Protection
  col_1: 
    content: <p style="text-align:left;"> - Make your home and outbuildings rodent-proof.<br> - Wear gloves when handling potentially infected animals.<br> - Wear insect repellent to keep rodent fleas away.<br> - DEET + Permethrin containing products are effective repellents.<br> - Keep fleas off your pets.<br> - Because of lack of individuals infected with pneumonic plague, most don’t have to worry about measure to prevent  human to human transmission</p>
  col_2:
    content: <p style="text-align:left;"> - Maintain social distance (at least 6ft).<br> - Wash your hands with soap and water or with 60%+ alcohol hand sanitizer.<br> - Clean and disinfect potentially contaminated surfaces.<br> - Wear a mask!</p>
# - template: content-feature
#   block: feature-1
#   media_alignment: Left
#   headline: <strong>Swap &amp; Switch<span class="light">&nbsp;</span></strong><span
#     class="light">the Blocks to create sites quickly</span>
#   content: Quickly assemble and create custom sites with 16 design blocks for seven
#     different sections.
#   media:
#     image: "/uploads/2018/06/21/blocks-split.png"
#     alt_text: uBuild Blocks Mock-Up  
# - template: content-feature
#   block: feature-1
#   media_alignment: Right
#   headline: <strong>Customize Blocks</strong><span class="light">&nbsp;to make quick
#     edits throughout your new site</span>
#   content: Each block comes with custom Front Matter that can easily be edited in
#     Forestry's UI.
#   media:
#     image: "/uploads/2018/06/21/edit.gif"
#     alt_text: Customize Blocks
# - template: 1-column-text
#   block: one-column-1
#   headline: 16 Fully Responsive Design Blocks
#   content: "The Design Blocks can be used without Forestry but to harness the power
#     of Blocks we recommend using Forestry. Once the site is imported you can immediately
#     create new sites and make them fully customizable. \U0001F447"
- template: full-width-media-element
  block: media-1
  image: "/uploads/2018/06/21/theme.png"
  caption: All Available Blocks
# - template: detail-content
#   block: text-1
#   headline: Steps to Build a Site!
#   content: <p>uBuild is an open-source Jekyll based theme that doubles as a builder
#     tool inside the Forestry content manager. It's easy to get started!</p><ol><li><p>Fork
#     the <a href="https://github.com/forestryio/ubuild-jekyll">repo</a> and import
#     the site into <a href="https://forestry.io/">Forestry</a> (or use <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks#even-quicker-start">our
#     magic button</a>).</p></li><li><p>Click on 'Add New' in Forestry and select the
#     Page-Builder template.</p></li><li><p>Add and customize the available Blocks and
#     preview them as you go along.</p></li><li><p>Read <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks/">our
#     article</a> and create your own Blocks.</p></li></ol>
- template: simple-footer
  block: footer-1
  content: Hello world! ❤︎

---
foo bar