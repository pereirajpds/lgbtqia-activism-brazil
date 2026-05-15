---
title: LGBTQIA+
layout: base
header-image: /assets/images/backgrounds/betinho.jpg
header-height: 50vh
header-position: center
---
# From “Gay Plague” to Human Right: Activisms During the HIV/AIDS Crisis in Brazil, 1980s-1990s

{% include images/figure.html
  image-path="/assets/images/backgrounds/peste.jpg"
  caption="***Figure1:*** The worst and most terrible disease of the century. Two Brazilians dead. ‘Gay Plague’ already terrifies São Paulo. Newspaper *Notícias Populares*, 1983."
  alt-text="Hiking trail through a canyon in the Sandia foothills."
  class="right"
  width="45%"
  text="firstimage"
%}

In the 1980s, fear and misinformation spread across Brazilian society as the HIV/AIDS crisis began to reach the country. Newspapers O Povo (1983) described the first case of HIV/AIDS as the 'gay plague,' while other media claimed that AIDS was only a health issue in the United States.[^jornais] Initially, many Brazilians believed that HIV affected only gay men or foreigners.[ˆmarkito] Some politicians even defended banning HIV-positive people from entering the country.[^senado] Meanwhile, activists and people living with HIV pressured the Brazilian state to invest public money into the fight against HIV/AIDS in Brazil.[^ongbook]



{% include images/figure.html
  image-path="/assets/images/dinheiro.png"
  caption="***Figure2:*** 4th Meeting of People Living with HIV, Rio de Janeiro, 1991. The poster says Money is scarce, AIDS is not. Rio de Janeiro, 1991."
  alt-text="Hiking trail through a canyon in the Sandia foothills."
  class="left"
  width="45%"
  text="firstimage"
%}

The HIV/AIDS crisis of the 1980s and 1990s coincided with Brazil’s period of redemocratization (1979-1985). This period marked a transition from dictatorship to democracy. Brazil was ending more than twenty years of military dictatorship (1964–1985). Political exiles and human rights activists returned to Brazil after years abroad. Social movements such as Black, queer, and feminist ones emerged. Politicians and social movements debated a new constitution to include labor rights, non-discrimination policies, and free public health as a constitutional right. This political transition shaped Brazil’s response to HIV/AIDS from the 1980s to the 1990s.[^anderson2019]

Most of you are familiar with the United States' response to HIV/AIDS. Under President Ronald Reagan, the federal government responded slowly to the demands of non-governmental organizations (NGOs), while many people in the US depended on private insurance for treatment. Brazil followed a different path. The Brazilian state worked with NGOs and activists. Together, they created national campaigns to challenge the idea that HIV/AIDS only affected gay men. Activists and politicians also contributed to legal rights such as retirement benefits for people living with HIV. In 1988, Brazil’s new constitution recognized healthcare as a right rather than a private service, expanding the treatment for poor people with HIV/AIDS. [^anderson2019]

{% include scrollybox/bg.html
  height="220vh"
  position="top"
  image-path="/assets/images/telegrama.png"
  above-box-space = "100vh"
  box-content=' One stated reason for building a men-only dorm is that Hokona Hall could be freed up to be used as a women-only dorm, where they would have supervision "of the best sort".'
%}

This story is about how activism contributed to the Brazilian state's response to HIV/AIDS from the 1980s to the 1990s. In the first years of the epidemic, the state did not act fast enough. Groups such as ABIA, the Brazilian Interdisciplinary AIDS Association, pressured government officials to give people with HIV/AIDS access to treatment and produced public information via pamphlets and bulletins to show that everyone could be infected by HIV. In 1982, Brenda Lee created a shelter for trans people living with HIV/AIDS in São Paulo. Flight attendants brought medication from the United States to Brazil when many people could not access expensive medications like AZT. The 1996 law later made Brazil known for one of the most important public health responses to HIV/AIDS in the world.  However, the Brazilian state did not achieve this alone. Earlier, activists, queer communities, and people living with HIV helped each other survive the epidemic and pressured the state to take immediate action. [^anderson2019]

{% assign images =
"/assets/images/lee.png,
/assets/images/varig.png,
/assets/images/dinheiro.png," | split: ','
%}

{% assign headers =
"Brenda Lee,
Flight attendence, 
4th Meeting of People Living with HIV, Rio de Janeiro, 1991. The poster says Money is scarce, AIDS is not"
| split: ','
%}

{% assign captions =
" 4th Meeting of People Living with HIV, Rio de Janeiro, 1991. The poster says Money is scarce, AIDS is not. Rio de Janeiro, 1991.|
This image has a caption, but no title|
" | split: '|'
%}

{% include images/carousel.html
  width="100%"
  class="center"
  images=images
  headers=headers
  captions=captions
%}




This is a story about.[^anderson2019]

This page is the `index.md` file in your repository. You'll evenually replace everything here with your own introduction to your scrollstory.

You should be viewing this page at `https://[your-username].github.io/[repository-name]`

So that you can edit this homepage for your own site, all the instructions for editing your site are on the [instructions page](instructions).

The next section uses a basic scrollybox like you saw in Sapling. Keep scrolling to see text overlay a full-screen background image. [^telegrama]


## ABIA and State

{% include images/figure.html
  image-path="/assets/images/backgrounds/herbet.png"
  caption="***Figure2:*** Herbert José de Sousa, Betinho (1935-1997). Comitê Betinho 2023."
  alt-text="Hiking trail through a canyon in the Sandia foothills."
  class="right"
  width="40%"
  text="firstimage"
%}

Outras formas de ativismo...



{% include images/figure.html
  image-path="/assets/images/backgrounds/abia.png"
  caption="***Figure3:*** Abia."
  alt-text="Hiking trail through a canyon in the Sandia foothills."
  class="left"
  width="40%"
  text="firstimage"
%}

{% include scrollybox/bg.html
  height="220vh"
  position="top"
  image-path="/assets/images/brendalee.png"
  above-box-space = "100vh"
  box-content=' One stated reason for building a men-only dorm is that Hokona Hall could be freed up to be used as a women-only dorm, where they would have supervision "of the best sort".'
%}


## Image Carousels (From Sapling)
All Sapling components work in Forest too. Here's a carousel for comparing multiple images:

{% assign images =
"/assets/images/brenda.png,
/assets/images/varig.png,
/assets/images/dc.png,
/assets/images/encontro.png,
/assets/images/dinheiro.png," | split: ','
%}

{% assign headers =
"brenda,
flight attendence" | split: ','
%}

{% assign captions =
"abia|
This image has a caption, but no title|
" | split: '|'
%}

{% include images/carousel.html
  width="100%"
  class="center"
  images=images
  headers=headers
  captions=captions
%}

## Justapose

Below you'll see a **juxtapose component**—an interactive slider that lets readers compare two images by dragging a handle left and right. Perfect for before/after, then/now, or any two related images.

{% include images/juxtapose.html
  image1="/assets/images/lampiao.jpg"
  image2="/assets/images/quemvecara.png"
  caption="The TV room becomes the History Department Common Room."
%}

{% include images/figure.html
  image-path="/assets/images/backgrounds/encontro.png"
  caption="***Figure4:*** Abia."
  alt-text="Hiking trail through a canyon in the Sandia foothills."
  class="right"
  width="40%"
  text="firstimage"
%}

text.....

## Background Switching: The Advanced Feature
This is what makes Forest essays truly cinematic. You're about to scroll through a section where the background image **switches** as you read, creating a visual sequence that matches your narrative.

**Watch carefully:** The background will start with one image, then switch to another partway through. The text box stays visible throughout, but the background changes to match what you're reading about.

<!-- this is an unclosed div that needs to be closed with bg-multi-long-close-->
{% include scrollybox/bg-multi-long.html
  bg-id="bg1"
  image-path="/assets/images/lei1998.png"
  above-box-space="0"
  font-size = "90%"
  line-height = "100%"
%}

Now we have a text box scrolling up over the first image. At various points (clearly labeled below) **the background image will switch** while the text continues scrolling.

This is perfect for visual sequences: walking through a building room by room, showing historical change over time, or revealing evidence step by step.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec ante ligula. Nulla fringilla ligula sit amet nisl consectetur ultricies. Mauris ac tellus eu ante lobortis rhoncus non eu nisl.


### BACKGROUND IMAGE SWITCHES HERE

{% include scrollybox/bg-switch.html
  image-path="/assets/images/casacivil.png"
  switch-id="switch1"
  bg-id="bg1"
%}


### The New Background
Did you notice the background change? The floorplan switched to the TV room photo. Your text continued scrolling, but the visual context shifted.

**Why use background switching?**
- Narrative sequences (first this happened, then that)
- Spatial movement (from room to room, place to place)
- Evidence building (showing multiple sources for one argument)
- Visual comparisons while maintaining narrative flow

Duis ut dui dolor. Integer eu lectus at tellus accumsan euismod eget a ligula. Morbi venenatis, elit eu varius fermentum, ligula est dictum massa, sit amet ullamcorper augue nisl ut nunc.


#### The End of This Sequence
Watch as the text box scrolls out of view, followed by the background image fading away. Then normal scrolling resumes.

{% include scrollybox/bg-multi-long-close.html %}


## Conclusion
In cunclusion...

## EXTRA

# Bibliography

 [^jornais]: Fundação Oswaldo Cruz (Fiocruz), “A Epidemia da Aids Através do Tempo,” in O Vírus da Aids, 20 anos depois, accessed May 15, 2026,  https://www.ioc.fiocruz.br/en/aids20anos/linhadotempo.htmlThe timeline reproduces 1983 newspaper Notícias Populares’ language such as "gay plague” and “câncer gay” and references the stigmatizing discourse surrounding the early AIDS crisis in Brazil. This paper reports the first cases of HIV/AIDS in Brazil. 
 Biblioteca Nacional Digital, reproduced by Agência Senado, “O estilista Markito: segundo o jornal Última Hora, uma vítima do ‘câncer gay’,” early 1980s.https://www12.senado.leg.br/noticias/especiais/arquivo-s/aids-chegou-ao-brasil-ha-40-anos-e-trouxe-terror-preconceito-e-desinformacaoFashion According to the Newspaper Última Hora, a Victim of the ‘Gay Cancer.’ The newspaper reported that the famous Brazilian fashion designer Markito, who lived in New York, died from HIV/AIDS-related complications in the United States and that his body was being returned to Brazil. Markito's death was one of the first widely publicized cases of a Brazilian public figure.


 Anderson, Mark J. ***Virtual Heritage: Designing Immersive Experiences for Public History***. Tucson: Sonoran Desert Press, 2019.
 [^telegrama]: Pela Vidda Telegrama.

## Primary Sources

- Anderson, Mark J. ***Virtual Heritage: Designing Immersive Experiences for Public History***. Tucson: Sonoran Desert Press, 2019.

- Appler, Jane, and Robert L. DeLeon. “Community Archives and Borderlands Memory Work: Rethinking Participation in the Digital Age.” *Public History Quarterly* 47, no. 3 (2021): 233–259.

- Castillo, Elena. “Mapping Migration: GIS as a Tool for Storytelling in the U.S. Southwest.” *Journal of Digital Humanities Methods* 8, no. 1 (2020): 15–34.

- Gonzalez, Maria P. ***Digital Storytelling in Community Contexts: Practices from the U.S.–Mexico Border***. Albuquerque: High Mesa University Press, 2022.

- Hwang, Daniel, and Lisa Moreno. “Reconstructing Place: Photogrammetry and 3D Modeling for Local History Museums.” In *Digital Heritage and the Public*, edited by S. Karim and A. Velasquez, 112–134. Austin: Western Humanities Collaborative, 2023.

- Johnson, Lauren, and Emily Carter. “Metadata for the People: Participatory Cataloging in Community Archives.” *Archivaria* 92 (2021): 77–101.

- Kiser, Thomas W. ***Humanistic Computing: Ethical Design for the Digital Humanities***. Chicago: Lakeshore Academic Press, 2018.

- Moreno, Pilar. “Digitizing Memory: Oral Histories and the Politics of Representation in the Southwest.” *American Studies Review* 65, no. 4 (2020): 421–440.

- Rogers, Matthew, and Cynthia Lee. “Pedagogy in the Virtual Museum: Digital Literacy for History Students.” *Teaching History with Technology* 14, no. 2 (2022): 55–73.

- Tran, Michael, and Hannah Ruiz. ***Borderlands Data: Methods for Visualizing Regional History***. Santa Fe: Southwest Humanities Institute Publications, 2021.

## Secondary Sources