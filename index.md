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
    caption: Black Death Spread in Europe (by Flappiefh on Ancient.eu)

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
    caption: <Strong>COVID-19 Spread by WHO region:</Strong> The above plot illustrates the reported infected individuals by each region of the world. The intermittent spikes are attributable to decreased testing on weekends. Currently, it seems as if the disease has passed its peak on a global scale, as evidenced by the gradual decrease in new cases for each region. 

  image_2: 
    image: "/uploads/plaguespread.jpg"
    caption: <Strong>Black Death Spread by Population:</Strong> This is an estimation of the number of individuals infected with the Bubonic Plague in England by year. Although data was reported less frequently compared to the new cases plot for COVID-19, the infection curve follows a similar trend; an initial exponential increase to the peak followed by gradual decrease. (graph from S. Broadberry, B. Campbell, and B. van Leeuwen 2010, English Medieval)

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/la_death.png"
    caption: <strong>Cumulative COVID-19 Deaths in Los Angeles:</strong> The above shows the cumulative deaths incurred by COVID-19 in Los Angeles since the first death. The plot shows a very linear trend; since April 2020, the total number of deaths has increased at a mostly linear rate through late-August. (From LA County Department of Public Health)
  image_2: 
    image: "/uploads/london_death.jpg"
    caption: <strong>Cumulative Bubonic Plague Deaths in London:</strong> This plot displays the cumulative deaths in the city of London on 4 separate epidemics of the bubonic plague (separate from the Black Death). Although deaths only rose around 50% per week, epidemics lasted 6 months. As a result, each of the four largest plague outbreaks killed about one fifth of Londoners. 

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/covidmortality.jpg"
    caption: <Strong>COVID-19 Hazard by Age:</Strong> This plot displays the risk (in percent) of developing serious symptoms from COVID-19  for different age groups. The mortality rate of COVID-19 increases as the infected individual’s age increases. This supports the CDC’s warning that the risk of severe illness increases with age. (from Williamson et. al., Nature, 7/8)
  image_2: 
    image: "/uploads/plaguemortality1.jpg"
    caption: <Strong>Black Death Mortality by Age:</Strong> This plot shows age distribution of the dead in England around the time of the Black Death. It can be seen that normal mortality rates report that over 25% of deaths are above the age of 70 whereas during the Black Death, the average age-at-death shifts to around 20-years-old. (DeWitte et al., 2017)

- template: detail-content
  block: one-column-1
  headline: Spread vs. Mortality Comparison Analysis
  content: With regards to the transmission of COVID-19 and the plague, several comparisons can be made between the two. In the modern age, disease spreads much differently than centuries ago; the development of air travel and ease of land travel has increased the ability for a contagious disease to spread rapidly. This is evidenced by the sporadic spread of cases across the United States in the figure <strong>COVID-19 Spread in the United States</strong>. Additionally, high population density in urban areas such as New York City and Los Angeles contribute to a greater rate of infections within populations. However, advances in modern medicine and hygiene hinders the spread since, comparatively, people wash their hands and wear masks at a much greater rate than in the 14th to 16th centuries. Meanwhile, as can be seen in the <strong>Black Death Spread in Europe</strong> figure, the bubonic plague spread through Europe along major trade routes and dispersed from major trading cities. Because the plague is transmitted by fleas that have bitten infected rodents, the low level of hygiene at the time was responsible for carrying infected rodents along trade routes.<br><br>Relating to the quantitative data surrounding the spread of both diseases, the graphs for cumulative infections and deaths follow somewhat similar trends. As shown in the <strong>Cumulative Bubonic Plague Deaths in London</strong> graph, the total deaths for all of the outbreaks of the plague followed a logarithmic curve where once the outbreak was controlled, the number of deaths tapered off. A comparable trend can be seen in the plot <strong>Black Death Spread by Population</strong>, although the trend is less pronounced due to the decreased data resolution. Similarly, the spread of COVID-19 also behaves logarithmically despite the use of masks and social distancing to contain the disease. As seen in the <strong>COVID-19 Spread by WHO Region</strong>, the number of new daily cases increases linearly until a peak and slowly decreases. If one were to plot this information in a cumulative manner where the graph shows the total number of reported cases, the graph would be logarithmic. This is because as the number of new daily cases increases, the cumulative plot would become steeper, and as the number of new daily cases slowly decreases, the cumulative plot would slowly begin to taper off. One feature of the WHO plot that is noteworthy is its ‘double spike’. The quarantine employed by state governments appeared to be showing success around April 1st when the number of new daily cases began to decrease. However, the reopening of several states’ economies around June caused a second wave of the disease to spread, as shown by the second surge of new daily cases. Comparatively, the plot of <strong>Cumulative COVID-19 Deaths in Los Angeles</strong> suggests that the total number of deaths increases in a linear fashion. Such behavior is attributable to modern medicine because drugs and intravenous treatments for diseases greatly increase the survivability of an infection such as COVID-19. This is a stark contrast to the treatments available at the time of the plague outbreaks, where medicine was not yet fully understood.

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/econ.png"
    caption: <Strong>Cumulative Global GDP Growth Since 2012 (%):</Strong> Covid-19 has caused the larget global recession in modern history since the Great Depression, as shown by the red dip in the graph above. Economic activity in advanced economies are projected to shrink up to 7% as well by the end of the year. 
  image_2: 
    image: "/uploads/death.png"
    caption: <Strong>England's Economic Impact and Population During the Plague:</Strong> As indicated in the graph, In the mid 15th Century, England's Population dipped to below 50% of what it was in 1270 (in red), and the GDP went down with it (in black). It's interesting to note that so many people died that it actually inflated their per capita GDP (in green). 

- template: detail-content
  block: one-column-1
  headline: Economic Impact Comparison
  content: The global economy has taken a turn for the worse in the past several months since the COVID-19 outbreak began in March.  Manufacturing supply chains being disrupted on top of decreasing demand for products due to a diminishing job market has created an economic crisis for many nations. The effects of quarantining and countries temporarily shutting down industries to curb the spread of the virus is another cause of the GDP trend shown in <strong>Cumulative Global GDP Growth Since 2012</strong>. The effects of COVID-19 on the economy have all been dependent on each other, akin to dominoes falling after one after another. Beginning with quarantine, the travel industry was the first casualty of the pandemic; valuable air freight capacity that accompanied passenger aircraft was lost, resulting in a building queue of shipments designated for shipment by air. Quarantine also caused several manufacturing plants in China to cease operation at the beginning of the outbreak, essentially halting the supply chain of products arriving in the US from China. In addition, quarantine also caused unemployment to skyrocket since companies could no longer afford to hire people as their overheads skyrocketed from the broken supply chains. Then, as unemployment increased, the demand for products dropped as more people had no source of income. Quarantine also created difficulty for consumers to shop, eliminating access to in-store shopping and dine-in all across the world; this further harmed the economy.<br><br>In contrast, the economic effect of the Black Plague on England did not cause as much economic damage. As shown in <strong>England’s Economic Impact and Population During the Plague</strong>, the overall GDP decreased by around 25% but the per capita GDP actually increased at the height of the Black Death. This is attributable to the high mortality rate of the plague during the Black Death and the lack of one key preventative measure that was employed during the COVID-19 pandemic — quarantine. As workers continued to work, industry was affected, but not stopped altogether like it has been in society as of late. In fact, the GDP loss caused by the Black Death and COVID-19 are very similar. In 14th century England, the GDP dropped about 25% over the span of 30 years. Meanwhile, COVID-19 has caused anywhere from a 15% to 25% GDP loss for many nations around the world since March. Although it took England almost 200 years to recover to its pre-Black-Death GDP, many believe that the economy of the world should recover rapidly once an effective vaccine has been developed and widely administered. 

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
    content: <ul style="text-align:left;"><li>Try to quarantine indoors, if going out is neccessary, maintain social distance (at least 6ft)<li>Wash your hands with soap and water or with 60%+ alcohol hand sanitizer<li>Clean and disinfect potentially contaminated surfaces<li>Wear a mask when going out<li>Avoid touching your face (eg. nose, eyes, mouth) </ul>
  col_2:
    content: <ul style="direction:rtl;text-align:right;"><li>Make your home and outbuildings rodent-proof<li>Wear gloves when handling potentially infected animals<li>Wear insect repellent to keep rodent fleas away, DEET + Permethrin containing products are effective repellents<li>Keep fleas off your pets<li>Because of lack of individuals infected with pneumonic plague, most don’t have to worry about measure to prevent  human to human transmission</ul>

- template: media-content
  block: media-2
  image_1: 
    image: "/uploads/prev_rona.png"
    caption: COVID-19 Protection Flyer
  image_2: 
    image: "/uploads/prev_plague.jpg"
    caption: Black Death Warning Flyer

- template: detail-content
  block: one-column-1
  headline: COVID-19 vs. The Black Death Prevention Effectiveness
  content: In the Middle Ages, medical science was yet to be developed so there was no prevention or treatment available for the Black Death. Because people were not active avoiding or taking measures to prevent the spread of the plague, they were more likely to come into contact with the plague and as a result, would most likely become infected and potentially die. The rich were able to isolate themselves and quarantine away from crowded cities or monasteries, which were the epicenters of disease. However, the poor had no means of protecting themselves besides praying to God and as a result, they died in much larger numbers than the wealthy.<br><br>In modern times, medical science is much better developed and there are treatments available to better prevent deaths and the ability to research for a cure has been greatly increased. With the addition of an increasingly connected world where the transfer of information is almost instant, knowledge about basic preventive actions has been disseminated to the masses leading to better prevention as seen by the <strong>COVID-19 Protection Flyer</strong> figure. The difficult issue with preventing COVID-19 is due to how contagious the virus is and how some people may be asymptomatic, but still able to unknowingly transfer disease which can be deadly to the eldery or those with preexisting conditions. However, this is not to say that the poor are now affected similarly to the rich. The wealthy still have access to better healthcare and can afford to isolate themselves or work from home, while the poor have a higher chance to work in essential jobs with customer-facing roles, leading to an increased chance of infection. 

- template: full-width-media-element
  block: media-1
  image: "/uploads/winewindow.jpg"
  caption: Medieval ‘wine windows’ are reopening, reviving Italian plague tradition.

- template: full-width-media-element
  block: media-1
  image: "/uploads/other_plague.png"
  caption: Covid Mortality Rate vs Past Epidemics. (from Goldstein and Lee, 2020)

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