---
title: LGBTQIA+
layout: base
header-image: /assets/images/backgrounds/betinho.jpg
header-height: 50vh
header-position: center
---
# Queer Activism during HIV and AIDS crises in Brasil, 1980s-1990s

{% include images/figure.html
  image-path="/assets/images/backgrounds/peste.jpg"
  caption="***Figure1:*** The worst and most terrible disease of the century. Two Brazilians dead. ‘Gay Plague’ already terrifies São Paulo. Newspaper *O popular*, 1983."
  alt-text="Hiking trail through a canyon in the Sandia foothills."
  class="right"
  width="40%"
  text="firstimage"
%}
## Introduction

This is a story about.[^anderson2019]

This page is the `index.md` file in your repository. You'll evenually replace everything here with your own introduction to your scrollstory.

You should be viewing this page at `https://[your-username].github.io/[repository-name]`

So that you can edit this homepage for your own site, all the instructions for editing your site are on the [instructions page](instructions).

The next section uses a basic scrollybox like you saw in Sapling. Keep scrolling to see text overlay a full-screen background image. [^telegrama]

{% include scrollybox/bg.html
  height="220vh"
  position="top"
  image-path="/assets/images/telegrama.png"
  above-box-space = "100vh"
  box-content=' One stated reason for building a men-only dorm is that Hokona Hall could be freed up to be used as a women-only dorm, where they would have supervision "of the best sort".'
%}

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

Brenda

















{% include images/figure.html
  image-path="/assets/images/backgrounds/lee.png"
  caption="***Figure3:*** Brenda Lee."
  alt-text="Hiking trail through a canyon in the Sandia foothills."
  class="left"
  width="40%"
  text="firstimage"
%}

Flight Attendance

{% include images/figure.html
  image-path="/assets/images/backgrounds/varig.png"
  caption="***Figure3:*** The worst and most terrible disease of the century. Two Brazilians dead. ‘Gay Plague’ already terrifies São Paulo. Newspaper *O popular*, 1983."
  alt-text="Hiking trail through a canyon in the Sandia foothills."
  class="right"
  width="40%"
  text="firstimage"
%}






{% include images/figure.html
  class="center"
  width="60%"
  caption="What a nice view"
  alt-text="Hiking trails winding through a canyon in the Sandia foothills."
  image-path="/assets/images/backgrounds/brenda.png"
%}

## Image Carousels (From Sapling)
All Sapling components work in Forest too. Here's a carousel for comparing multiple images:

{% assign images =
"/assets/images/brenda.png,
/assets/images/varig.png,
/assets/images/abia.png,
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
image1="images/estado.png"
image2="images/cartaz.png"
caption="From the TV room to the Chair room (actually, the History Department Common Room). With a less good view of the mountains."
%}


**Why use juxtapose?** When you want readers to actively explore the relationship between two images. The interactive slider invites engagement—readers control what they see and how much of each image.

**Use cases:**
- Historical photos showing change over time
- Different views of the same location
- Comparing historical documents or maps
- Revealing differences that might be subtle

Praesent sed vehicula velit, vel hendrerit neque. Vivamus scelerisque sed nunc nec congue. Curabitur sapien risus, finibus id tincidunt iaculis, porta et ipsum.




## Conclusion
In cunclusion...


## EXTRA

# Bibliography

 [^anderson2019]: Anderson, Mark J. ***Virtual Heritage: Designing Immersive Experiences for Public History***. Tucson: Sonoran Desert Press, 2019.
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